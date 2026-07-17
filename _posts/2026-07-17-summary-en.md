---
layout: default
title: "Horizon Summary: 2026-07-17 (EN)"
date: 2026-07-17
lang: en
---

> From 205 items, 29 important content pieces were selected

---

1. [xAI open-sources Grok Build after data upload backlash](#item-1) ⭐️ 9.0/10
2. [Google OAuth Device Flow Hijacking Allows Universal Account Takeover](#item-2) ⭐️ 9.0/10
3. [New Unauthenticated RCE Vulnerability in ServiceNow](#item-3) ⭐️ 9.0/10
4. [Kimi K3: Open Frontier Model with 2.8T Parameters and 1M Context](#item-4) ⭐️ 8.0/10
5. [OTA Update Breaks Android Auto, Sparks Software Quality Debate](#item-5) ⭐️ 8.0/10
6. [Firefox Compiled to WebAssembly Runs Inside Another Browser](#item-6) ⭐️ 8.0/10
7. [GPT-5.6 Codex Bug Can Delete $HOME Directory](#item-7) ⭐️ 8.0/10
8. [Thinking Machines Lab Releases Inkling, a 975B Open-Weights MoE Model](#item-8) ⭐️ 8.0/10
9. [Linus Torvalds Declares Linux Not Anti-AI](#item-9) ⭐️ 8.0/10
10. [Claude web_fetch tool bypass enables data exfiltration](#item-10) ⭐️ 8.0/10
11. [Shift Privacy Focus to Company Accountability](#item-11) ⭐️ 8.0/10
12. [Fourier Pixel Turns Screens into Cameras](#item-12) ⭐️ 8.0/10
13. [Morocco whistleblower reveals widespread Pegasus spyware use](#item-13) ⭐️ 8.0/10
14. [Millions of Shark Vacuums Vulnerable to RCE Attack](#item-14) ⭐️ 8.0/10
15. [ASUS bsitf.sys Driver Vulnerability Allows Arbitrary Physical Memory Mapping](#item-15) ⭐️ 8.0/10
16. [Microsoft open-sources Comic Chat, a 1990s IRC client](#item-16) ⭐️ 7.0/10
17. [LM Studio Bionic: AI Agent for Open Models](#item-17) ⭐️ 7.0/10
18. [Decoy Font: Dual Text Layers Fool AI Vision Models](#item-18) ⭐️ 7.0/10
19. [Classical ML for LLM Text Detection](#item-19) ⭐️ 7.0/10
20. [OnePlus Halts New Product Launches in US and Europe](#item-20) ⭐️ 7.0/10
21. [Interactive Linear Algebra Book Wins Community Praise](#item-21) ⭐️ 7.0/10
22. [Rust-to-Zig Rewrite: A Compiler Engineer's Perspective](#item-22) ⭐️ 7.0/10
23. [TSMC pledges additional $100bn for US expansion](#item-23) ⭐️ 7.0/10
24. [Telstra Outage Caused by Missing Software Update and Undocumented Change](#item-24) ⭐️ 7.0/10
25. [Trump Media to sell priority access to Truth Social posts](#item-25) ⭐️ 7.0/10
26. [Updated Semgrep C/C++ Ruleset Released for Production Use](#item-26) ⭐️ 7.0/10
27. [Google Rebrands NotebookLM to Gemini Notebook](#item-27) ⭐️ 6.0/10
28. [GOES-19 Weather Satellite Enters Safe Hold Mode](#item-28) ⭐️ 6.0/10
29. [Global heating supercharged West Africa floods, displacing thousands](#item-29) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [xAI open-sources Grok Build after data upload backlash](https://simonwillison.net/2026/Jul/15/grok-build/#atom-everything) ⭐️ 9.0/10

xAI released the entire Grok Build codebase under Apache 2.0 license after its grok CLI tool was found to upload entire directories to the cloud, including sensitive user files. The company also deleted all retained user data and disabled default data retention. This incident highlights serious privacy risks in AI-powered CLI tools and forced xAI to take unprecedented transparency measures. Open-sourcing the codebase allows the community to audit the software and restore trust. The Grok Build repository contains 844,530 lines of Rust code with only about 3% vendored, and includes a self-contained Mermaid diagram renderer. The code was released in a single commit, so no development history is visible.

rss · Simon Willison · Jul 15, 23:59

**Background**: The grok CLI tool is a conversational AI terminal interface that connects to xAI's Grok API. Users discovered that running the command in a directory would upload the entire directory to xAI's cloud storage, leading to severe privacy concerns. xAI initially disabled the feature and later open-sourced the codebase to regain trust.

<details><summary>References</summary>
<ul>
<li><a href="https://x.ai/cli">Grok Build | SpaceXAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apache_License">Apache License</a></li>

</ul>
</details>

**Discussion**: The community expressed outrage over the data upload behavior, with one user reporting that their SSH keys and password manager database were uploaded. The open-sourcing move was generally welcomed as a step toward transparency, though some questioned whether it was sufficient to restore trust.

**Tags**: `#security`, `#open source`, `#AI`, `#privacy`, `#xAI`

---

<a id="item-2"></a>
## [Google OAuth Device Flow Hijacking Allows Universal Account Takeover](https://www.reddit.com/r/netsec/comments/1uy44c4/13337_confused_deputy_google_idp_universal/) ⭐️ 9.0/10

A critical vulnerability in Google's OAuth device authorization flow (RFC 8628) allows universal account takeover by exploiting missing client_id/scope validation and the prompt=none parameter, making the attack invisible and one-click. This vulnerability affects all Google Identity Platform users, potentially allowing attackers to hijack any account without user interaction, undermining trust in Google's authentication infrastructure. The attack exploits the device authorization grant where the authorization server fails to verify that the client_id and scope in the consent URL match those issued for the device_code, and prompt=none bypasses user consent, enabling silent account takeover.

reddit · r/netsec · /u/swinglr · Jul 16, 14:15

**Background**: OAuth 2.0 Device Authorization Grant (RFC 8628) allows devices with limited input (e.g., TVs, CLI) to authenticate by polling for login on a second device. The prompt=none parameter in OpenID Connect skips user interaction if a valid session exists. Proper validation of client_id and scope is critical to prevent confused deputy attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://datatracker.ietf.org/doc/html/rfc8628">RFC 8628 - OAuth 2.0 Device Authorization Grant - Datatracker</a></li>
<li><a href="https://oauth.net/2/device-flow/">RFC 8628: OAuth 2.0 Device Authorization Grant</a></li>
<li><a href="https://www.descope.com/learn/post/device-authorization-flow">What Is the OAuth 2.0 Device Authorization Flow?</a></li>

</ul>
</details>

**Discussion**: The netsec community praised the technical depth of the disclosure and discussed the severity of the attack, with some noting that Google's prompt=none behavior combined with missing validation creates a dangerous confused deputy scenario.

**Tags**: `#security`, `#OAuth`, `#vulnerability`, `#Google`, `#account takeover`

---

<a id="item-3"></a>
## [New Unauthenticated RCE Vulnerability in ServiceNow](https://www.reddit.com/r/netsec/comments/1uwzsix/more_unauthenticated_arbitrary_code_execution_in/) ⭐️ 9.0/10

A new unauthenticated arbitrary code execution vulnerability in ServiceNow has been disclosed, tracked as CVE-2026-6875, which allows attackers to execute arbitrary code without authentication. This vulnerability is critical because ServiceNow is widely used by enterprises, and unauthenticated RCE could lead to full compromise of affected instances and connected systems. The flaw is a sandbox escape in the ServiceNow AI Platform, with a CVSS score of 9.5, and patches have been released by ServiceNow.

reddit · r/netsec · /u/ahhhpipipi · Jul 15, 08:25

**Background**: ServiceNow is a leading enterprise platform for IT service management and workflow automation. The AI Platform component extends its capabilities with AI-driven features. A sandbox escape vulnerability allows code execution outside the intended restricted environment, often leading to full system compromise.

<details><summary>References</summary>
<ul>
<li><a href="https://cyberpress.org/critical-servicenow-ai-platform-flaw/">Critical ServiceNow AI Platform Flaw Enables Unauthenticated Remote Code Execution</a></li>
<li><a href="https://dailysecurityreview.com/cyber-security/servicenow-patches-cve-2026-6875-unauthenticated-rce-in-ai-platform/">ServiceNow Patches CVE-2026-6875 Unauthenticated RCE in AI...</a></li>
<li><a href="https://slcyber.io/research-center/smashing-the-servicenow-sandbox-pre-authentication-rce/">Smashing the ServiceNow Sandbox – Pre Authentication RCE ...</a></li>

</ul>
</details>

**Tags**: `#security`, `#vulnerability`, `#ServiceNow`, `#RCE`, `#enterprise`

---

<a id="item-4"></a>
## [Kimi K3: Open Frontier Model with 2.8T Parameters and 1M Context](https://www.kimi.com/blog/kimi-k3) ⭐️ 8.0/10

Kimi released K3, an open-weight frontier AI model with 2.8 trillion parameters and a 1 million token context window, achieving competitive performance against leading models like Anthropic's Sonnet series. K3 demonstrates that Chinese AI labs can produce frontier-level open models, potentially commoditizing AI intelligence and pressuring proprietary models to lower prices. K3 uses a hybrid linear attention mechanism called Kimi Delta Attention and Attention Residuals, and its pricing ($3/$15 per million tokens) matches Anthropic's Sonnet series.

hackernews · vincent_s · Jul 16, 14:46 · [Discussion](https://news.ycombinator.com/item?id=48935342)

**Background**: Open-weight models make trained parameters publicly available for download, fine-tuning, and local deployment. Kimi K3 is the first open model to reach 2.8 trillion parameters, setting a new record for open-model size.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kimi.com/blog/kimi-k3">Kimi K 3 Tech Blog: Open Frontier Intelligence</a></li>
<li><a href="https://artificialanalysis.ai/models/kimi-k3">Kimi K 3 - Intelligence, Performance & Price Analysis</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K 3 - Kimi API Platform</a></li>

</ul>
</details>

**Discussion**: The community noted K3's high pricing for a Chinese open model but acknowledged its frontier-level performance. Some debated whether Chinese labs are commoditizing intelligence or still investing heavily in training.

**Tags**: `#AI`, `#LLM`, `#open-source`, `#pricing`, `#Chinese AI`

---

<a id="item-5"></a>
## [OTA Update Breaks Android Auto, Sparks Software Quality Debate](https://imdanielkendall.com/the-great-software-regress-how-move-fast-and-break-things-broke-our-lives/) ⭐️ 8.0/10

A car owner reports that an over-the-air (OTA) update broke Android Auto functionality, highlighting how software defects are increasingly pushed to users as QA testers. This incident underscores the growing problem of software quality in automotive systems, where OTA updates can disrupt critical features and erode consumer trust, potentially impacting car sales and brand reputation. The author's car received an OTA update that disabled Android Auto, and the issue was not acknowledged or explained by the manufacturer. Similar cases, like Kia's EV9 update breaking CarPlay, show this is a recurring problem.

hackernews · Expletive4138 · Jul 16, 22:29 · [Discussion](https://news.ycombinator.com/item?id=48941129)

**Background**: OTA updates allow car manufacturers to remotely update vehicle software, similar to smartphone updates. However, in automotive contexts, software failures can affect safety and usability, and the lack of physical media means companies bear less cost for shipping broken software, shifting the burden to users.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Over-the-air_update">Over-the-air update - Wikipedia</a></li>
<li><a href="https://support.google.com/androidauto/answer/6348190?hl=en">My Android Auto app isn't working - Android Auto Help</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration with OTA updates breaking features, with one noting that Kia's EV9 update broke CarPlay. Others criticized the misuse of agile methodologies and the outsourcing of QA to users, while some argued that software should not control essential hardware functions.

**Tags**: `#automotive software`, `#OTA updates`, `#software quality`, `#agile development`, `#user experience`

---

<a id="item-6"></a>
## [Firefox Compiled to WebAssembly Runs Inside Another Browser](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 8.0/10

Puter has compiled the full Firefox browser (Gecko engine) to WebAssembly, enabling it to run inside another browser as a demo. The project used AI assistance (Claude Opus and Fable) to help with the compilation, costing an estimated $25,000 in tokens but much less due to a subscription plan. This is a significant demonstration of WebAssembly's potential for porting large, complex native applications to the web. It shows that even a full browser engine can run inside another browser, opening possibilities for sandboxed browsing, legacy app compatibility, and new cross-platform use cases. The demo uses the Wisp protocol to proxy all network traffic through Puter's server, as browser code cannot open arbitrary network connections. The Gecko engine was chosen for its strong single-process support, and the project claims end-to-end encryption for HTTPS traffic.

rss · Simon Willison · Jul 16, 23:34

**Background**: WebAssembly (WASM) is a low-level binary instruction format that runs in modern web browsers at near-native speed. It allows code written in languages like C, C++, and Rust to be compiled and executed on the web. Compiling a full browser like Firefox to WASM is a major engineering feat because browsers are large, complex applications with many dependencies.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.puter.com/labs/firefox-wasm/">Firefox in WebAssembly</a></li>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/ wisp - protocol : Wisp is a low-overhead...</a></li>
<li><a href="https://news.ycombinator.com/item?id=48926939">Show HN: Firefox in WebAssembly | Hacker News</a></li>

</ul>
</details>

**Tags**: `#WebAssembly`, `#Firefox`, `#Browser`, `#Portability`, `#Demo`

---

<a id="item-7"></a>
## [GPT-5.6 Codex Bug Can Delete $HOME Directory](https://simonwillison.net/2026/Jul/16/bad-codex-bug/#atom-everything) ⭐️ 8.0/10

Thibault Sottiaux reported that GPT-5.6 Codex, when running with full access mode and no sandboxing, can accidentally delete the $HOME directory while attempting to override the $HOME environment variable. This bug highlights critical safety risks in AI coding agents, especially for developers who rely on full-access mode without sandboxing, potentially leading to irreversible data loss. The bug occurs when the model attempts to set a temporary directory by overriding $HOME but mistakenly deletes the original $HOME instead. It requires full access mode, no sandboxing, and no auto-review enabled.

rss · Simon Willison · Jul 16, 17:45

**Background**: Codex is an AI coding agent from OpenAI that can execute commands on the user's system. Full access mode grants the agent unrestricted system access, while sandboxing provides a safety layer to contain actions. Without sandboxing, a mistake in environment variable handling can lead to catastrophic file deletions.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/openai/codex/issues/18509">Codex Desktop deleted workspace roots + installed apps on failed...</a></li>
<li><a href="https://explainx.ai/blog/chatgpt-codex-5-hour-limit-removed-weekly-reset-july-2026">ChatGPT 5-Hour Limit Removed — July 2026 | explainx.ai... | explainx.ai</a></li>

</ul>
</details>

**Tags**: `#codex`, `#coding-agents`, `#generative-ai`, `#ai-safety`, `#bug`

---

<a id="item-8"></a>
## [Thinking Machines Lab Releases Inkling, a 975B Open-Weights MoE Model](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Mira Murati's Thinking Machines Lab released Inkling, a 975B total parameter (41B active) Mixture-of-Experts multimodal model under the Apache-2.0 license, trained on 45 trillion tokens of text, images, audio, and video. This release strengthens the US open-weights ecosystem, offering a competitive alternative to Chinese open models and providing a strong base for fine-tuning via the Tinker platform. The model card and training data documentation are notably sparse, lacking detailed information about data sources. Thinking Machines also plans to release Inkling-Small (276B total, 12B active) once testing is complete.

rss · Simon Willison · Jul 16, 15:35

**Background**: Mixture-of-Experts (MoE) models use multiple specialized sub-networks (experts) and a gating mechanism to activate only a subset of parameters per input, achieving high capacity with lower computational cost. Open-weights models make trained parameters publicly available, allowing modification and fine-tuning, often under permissive licenses like Apache-2.0.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@apoorvajain1111/inside-the-sparse-brain-how-mixture-of-experts-moe-makes-llms-smarter-faster-and-greener-205b0fea1416">Inside the Sparse Brain: How Mixture - of - Experts ( MoE )... | Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apache_License">Apache License</a></li>
<li><a href="https://promptmetheus.com/resources/llm-knowledge-base/open-weights-model">Open - weights Model | LLM Knowledge Base</a></li>

</ul>
</details>

**Tags**: `#AI`, `#open-weights`, `#MoE`, `#multimodal`

---

<a id="item-9"></a>
## [Linus Torvalds Declares Linux Not Anti-AI](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds, the creator and top maintainer of Linux, publicly stated that Linux is not an anti-AI project and that AI is clearly a useful tool, inviting dissenters to fork or leave. This strong endorsement from a key figure in open source signals that AI integration is becoming mainstream in the Linux ecosystem, potentially influencing other projects and developers to adopt AI tools. Torvalds made the statement on the Linux Media Mailing List, emphasizing that while questions about AI's economy remain, its usefulness is no longer in doubt.

rss · Simon Willison · Jul 16, 13:26

**Background**: The Linux kernel is the core of many operating systems, and Linus Torvalds has the final say on what is accepted. AI tools, such as large language models, have been controversial in some open-source communities due to concerns about licensing and ethics.

**Tags**: `#Linux`, `#AI`, `#Open Source`, `#Linus Torvalds`

---

<a id="item-10"></a>
## [Claude web_fetch tool bypass enables data exfiltration](https://simonwillison.net/2026/Jul/15/claude-web-fetch-exfiltration/#atom-everything) ⭐️ 8.0/10

Researcher Ayush Paul discovered a bypass in Anthropic's Claude web_fetch tool that allowed data exfiltration by tricking the model into following nested links from a honeypot page, extracting user memories such as name, city, and employer. This attack demonstrates a practical bypass of Anthropic's data exfiltration protections, highlighting the ongoing challenge of securing AI agents that combine private data, tool access, and untrusted content—the 'lethal trifecta'. The bypass exploited a loophole where web_fetch could navigate to URLs embedded in previously fetched pages, allowing a multi-step exfiltration chain. Anthropic had already internally identified the issue and closed the hole by removing the ability to follow links from fetched content.

rss · Simon Willison · Jul 15, 14:21

**Background**: The 'lethal trifecta' refers to AI agents that have access to private data, can communicate externally (e.g., via web fetch), and are exposed to untrusted content (e.g., from websites or emails). Prompt injection attacks can trick the model into combining these capabilities to exfiltrate data. Anthropic's web_fetch tool was designed to prevent URL construction from sensitive data, but the nested link bypass circumvented that protection.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2025/Sep/10/claude-web-fetch-tool/">Claude API: Web fetch tool | Simon Willison’s Weblog</a></li>
<li><a href="https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/">The lethal trifecta for AI agents: private data, untrusted content, and...</a></li>
<li><a href="https://github.com/anthropics/claude-code/issues/18729">[DOCS] Logical Inconsistency in Web Fetch Tool Security and URL...</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#security`, `#Claude`, `#data exfiltration`, `#prompt injection`

---

<a id="item-11"></a>
## [Shift Privacy Focus to Company Accountability](https://www.schneier.com/blog/archives/2026/07/protecting-privacy-in-an-ai-era.html) ⭐️ 8.0/10

Bruce Schneier highlights Daniel Solove's argument that privacy regulation should shift from individual data control to holding companies accountable, similar to food and drug safety. Solove proposes measures like data minimization, fiduciary duties, and algorithmic liability. This paradigm shift could make privacy regulation more effective in the AI era by focusing on preventing harm rather than burdening individuals. It aligns with broader trends in AI governance that emphasize corporate responsibility. Solove's proposals include rigorous data minimization, fiduciary duties for data handlers, liability for negligent or reckless technological design, liability for harmful algorithms, and multi-stakeholder review of technologies. The argument is detailed in a Wall Street Journal article and an academic paper.

rss · Schneier on Security · Jul 16, 14:34

**Background**: Current privacy laws often rely on individual consent and control, but this approach has proven ineffective as people cannot meaningfully manage complex data practices. Solove's approach draws parallels to food and drug regulation, where companies are held responsible for safety rather than consumers. Key concepts include data minimization (collecting only necessary data), fiduciary duties (legal obligation to act in users' best interest), and algorithmic liability (holding companies accountable for harms caused by algorithms).

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Data_minimization">Data minimization</a></li>
<li><a href="https://teachprivacy.com/ai-companies-should-have-information-fiduciary-duties/">AI Companies Should Have Information Fiduciary Duties</a></li>
<li><a href="https://www.webbb.ai/blog/algorithmic-liability-how-businesses-can-protect-consumer-rights-and-avoid-ai-driven-legal-risks">Algorithmic Liability : How Businesses Can Protect Consumer Rights...</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#AI regulation`, `#data governance`, `#accountability`

---

<a id="item-12"></a>
## [Fourier Pixel Turns Screens into Cameras](https://www.schneier.com/blog/archives/2026/07/a-video-screen-that-is-also-a-camera.html) ⭐️ 8.0/10

Researchers at ETH Zurich have developed a Fourier pixel that can both emit and detect light, enabling a video screen to function as a camera. The findings were published in Nature in July 2026. This breakthrough could lead to displays that see without needing separate cameras, raising significant privacy concerns reminiscent of Orwell's telescreen. It also opens new possibilities for interactive displays and imaging technology. The Fourier pixel manipulates light's intensity, phase, and polarization using surface waves, allowing simultaneous emission and sensing. This is a fundamental advance in pixel design, though not yet a commercial product.

rss · Schneier on Security · Jul 15, 11:04

**Background**: Traditional pixels only emit light (displays) or detect light (cameras), but not both. The Fourier pixel combines these functions in a single element by using guided waves that scatter and interfere. This reciprocal design treats the display as an active imaging device rather than an obstacle.

<details><summary>References</summary>
<ul>
<li><a href="https://petapixel.com/2026/06/26/researchers-develop-all-new-pixel-type-that-can-both-record-and-display-light/">Researchers Develop All-New Pixel Type That Can Both... | PetaPixel</a></li>

</ul>
</details>

**Tags**: `#display technology`, `#privacy`, `#computer vision`, `#hardware`, `#research`

---

<a id="item-13"></a>
## [Morocco whistleblower reveals widespread Pegasus spyware use](https://www.theguardian.com/news/2026/jul/16/morocco-intelligence-insider-reveals-widespread-use-hacking-software-pegasus) ⭐️ 8.0/10

A former Moroccan intelligence officer has revealed that the country's security services deployed Pegasus spyware from 2017 against journalists, activists, French politicians, and Spanish officials. This unprecedented insider account exposes the scale of state-sponsored surveillance, threatening press freedom and diplomatic relations, and highlights the ongoing global controversy over NSO Group's spyware. Pegasus, developed by Israel's NSO Group, can remotely access a phone's emails, messages, photos, and activate its microphone and camera. The whistleblower's testimony provides rare direct evidence of its use by Moroccan intelligence.

rss · The Guardian World · Jul 16, 04:30

**Background**: Pegasus is a commercial spyware that governments license for counterterrorism, but it has been repeatedly used to target journalists and dissidents. NSO Group claims it only sells to authorized governments, but investigations have documented widespread abuse. The Israeli government must approve all Pegasus exports.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus (spyware)</a></li>
<li><a href="https://en.wikipedia.org/wiki/NSO_Group">NSO Group</a></li>

</ul>
</details>

**Tags**: `#Pegasus`, `#spyware`, `#surveillance`, `#privacy`, `#Morocco`

---

<a id="item-14"></a>
## [Millions of Shark Vacuums Vulnerable to RCE Attack](https://www.reddit.com/r/netsec/comments/1uy4iyq/no_shark_is_safe_millions_of_shark_vacuums_are/) ⭐️ 8.0/10

A critical remote code execution (RCE) vulnerability has been disclosed affecting millions of Shark robot vacuum cleaners, allowing attackers to gain root shell access and remotely control the devices. This vulnerability exposes a vast number of IoT devices in homes to potential hijacking, surveillance, and use in botnets, highlighting systemic security weaknesses in consumer IoT products. The vulnerability was discovered by researcher Tokay0, who accessed exposed UART pins on the RV2320EDUS motherboard and interrupted the U-Boot sequence with Ctrl-C to bypass password authentication and obtain a root shell.

reddit · r/netsec · /u/an0n9021O · Jul 16, 14:30

**Background**: IoT devices like smart vacuums often run embedded Linux and expose hardware debug interfaces (e.g., UART) for manufacturing, but these interfaces are sometimes left accessible in production units. RCE vulnerabilities allow attackers to execute arbitrary code on a device remotely, potentially taking full control.

<details><summary>References</summary>
<ul>
<li><a href="https://cyberpress.org/shark-vacuum-rce-flaw/">Shark Vacuum RCE Flaw Lets Attackers Remotely Control Cameras...</a></li>
<li><a href="https://1275.ru/vulnerability/obnovlenie-bezopasnosti-dlya-pylesosov-shark-otsutstvuet-kriticheskaya-uyazvimost-rce-ugrozhaet-millionam-ustroystv_32272">Обновление безопасности для пылесосов Shark отсутствует...</a></li>

</ul>
</details>

**Discussion**: The r/netsec discussion likely includes technical analysis of the UART attack vector and mitigation strategies, with some users criticizing Shark for not providing security updates.

**Tags**: `#IoT security`, `#RCE`, `#vulnerability disclosure`, `#embedded systems`

---

<a id="item-15"></a>
## [ASUS bsitf.sys Driver Vulnerability Allows Arbitrary Physical Memory Mapping](https://www.reddit.com/r/netsec/comments/1uxuqyg/asus_bsitfsys_cve202613585_arbitrary_physical/) ⭐️ 8.0/10

A critical vulnerability (CVE-2026-13585) has been disclosed in ASUS's bsitf.sys kernel driver, which allows arbitrary physical memory mapping via an unvalidated IOCTL (0x222808). This vulnerability can be exploited by attackers to gain arbitrary physical memory read/write access, potentially leading to privilege escalation, data theft, or system compromise. It affects ASUS Business Manager and Software Manager users, and highlights the risks of vulnerable kernel drivers from major hardware vendors. The IOCTL 0x222808 accepts a size from the user input buffer, allocates physically contiguous kernel memory, maps it into the user process, and returns both the virtual pointer and physical address. ASUS has published a vendor advisory with countermeasures.

reddit · r/netsec · /u/watchdogsrox · Jul 16, 06:26

**Background**: The bsitf.sys driver is a kernel driver bundled with ASUS WinFlash and ASUS Business Manager/Software Manager, used for flashing UEFI BIOS images. Kernel drivers that expose IOCTLs without proper validation can allow user-mode applications to perform privileged operations, such as mapping physical memory, which is a dangerous primitive for attackers.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.ahmadz.ai/asus_bsitf_0_day_poc/">ASUS bsitf.sys (CVE-2026-13585): Arbitrary Physical Memory ...</a></li>
<li><a href="https://www.loldrivers.io/drivers/9905c737-83ad-4801-a573-8267f3aea924/">9905c737-83ad-4801-a573-8267 f 3aea924 | LOLDrivers</a></li>
<li><a href="https://www.veraproject.xyz/field-guide/drivers/bsitf-sys">bsitf . sys — Vera Field Guide | Vera</a></li>

</ul>
</details>

**Tags**: `#CVE`, `#ASUS`, `#kernel driver`, `#memory corruption`, `#security`

---

<a id="item-16"></a>
## [Microsoft open-sources Comic Chat, a 1990s IRC client](https://opensource.microsoft.com/blog/2026/07/16/microsoft-comic-chat-is-now-open-source/) ⭐️ 7.0/10

On July 16, 2026, Microsoft released Comic Chat (later renamed Microsoft Chat) as open-source software. The code is now available on GitHub under an MIT license. Comic Chat is a historically significant piece of Internet software that pioneered graphical chat with comic-style avatars, bundled with Windows 98. Its open-sourcing preserves digital history and allows developers to study and experiment with a unique IRC client. Comic Chat was developed by Microsoft researcher David Kurlander and first released with Internet Explorer 3.0 in 1996. The open-source release was facilitated by Robert Standefer and Scott Hanselman after a six-year effort.

hackernews · jervant · Jul 16, 16:06 · [Discussion](https://news.ycombinator.com/item?id=48936426)

**Background**: Internet Relay Chat (IRC) is a text-based chat protocol that was popular in the 1990s and early 2000s. Comic Chat was a graphical IRC client that automatically rendered conversations as comic strips with characters expressing emotions, making chat more visual and playful.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Microsoft_Comic_Chat">Microsoft Comic Chat</a></li>
<li><a href="https://en.wikipedia.org/wiki/IRC_client">IRC client</a></li>

</ul>
</details>

**Discussion**: Community members expressed nostalgia and appreciation, with Robert Standefer sharing the backstory of the open-sourcing effort. Some noted that Comic Chat was controversial in its time for extending the IRC protocol with proprietary features, but overall the sentiment is positive.

**Tags**: `#open source`, `#microsoft`, `#irc`, `#retro computing`, `#history`

---

<a id="item-17"></a>
## [LM Studio Bionic: AI Agent for Open Models](https://lmstudio.ai/blog/introducing-lm-studio-bionic) ⭐️ 7.0/10

LM Studio has launched Bionic, a new AI agent app that enables local agentic workflows using open models, with features like automatic checkpointing for document manipulation. Bionic brings advanced agent capabilities to local models, offering enterprises and privacy-conscious users a secure, cost-effective alternative to cloud-based frontier models. Bionic is available in initial preview and supports coding (Code projects) and document creation/manipulation (Work projects) with automatic checkpointing for every change.

hackernews · minimaxir · Jul 16, 20:18 · [Discussion](https://news.ycombinator.com/item?id=48939662)

**Background**: LM Studio is a popular desktop app for running open-source language models locally. Bionic extends this by providing an agentic harness that can autonomously perform tasks like coding and document editing using local models, similar to tools like Codex but fully local.

<details><summary>References</summary>
<ul>
<li><a href="https://9to5mac.com/2026/07/16/lm-studio-expands-beyond-chat-with-bionic-a-new-ai-agent-app-for-open-models/">LM Studio launches Bionic , a new AI agent app for open... - 9to5Mac</a></li>
<li><a href="https://modernorange.io/item/48939662">LM Studio Bionic : the AI agent for open models | Modern Orange</a></li>

</ul>
</details>

**Discussion**: Community feedback is positive, with users noting it works well with existing models like Qwen3.6 35B. Founder Yagil offered free credits for testing with specific models. Some users expressed concerns about the shift in business model toward cloud services.

**Tags**: `#AI agents`, `#local models`, `#LM Studio`, `#open source`, `#developer tools`

---

<a id="item-18"></a>
## [Decoy Font: Dual Text Layers Fool AI Vision Models](https://www.mixfont.com/experiments/decoy-font) ⭐️ 7.0/10

Decoy Font is a typographic technique that embeds two different messages in a single image: one visible at high resolution and another revealed when the image is scaled down or blurred, effectively confusing AI vision models while remaining readable to humans. This technique highlights a vulnerability in current AI vision systems, which can be exploited to hide text from automated analysis, with potential applications in adversarial attacks, data poisoning, or privacy protection. The effect relies on the difference in spatial frequency between the two text layers: the high-frequency layer (sharp text) disappears when downsampled, while the low-frequency layer (blurred text) becomes dominant. Tests show that GPT-4o, Gemini, and Claude exhibit varying abilities to detect the hidden text.

hackernews · ray__ · Jul 16, 16:18 · [Discussion](https://news.ycombinator.com/item?id=48936584)

**Background**: Adversarial examples in computer vision are inputs designed to cause models to misclassify, often through subtle perturbations imperceptible to humans. This font is a novel form of adversarial typography that exploits multi-scale image processing, similar to how adversarial patches fool object detectors.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cs.princeton.edu/courses/archive/spring20/cos598C/lectures/lec19-adversarial-examples.pdf">Pres_COS598C_AdversarialExamples</a></li>
<li><a href="https://arxiv.org/pdf/1802.08195">Adversarial Examples that Fool both Computer</a></li>

</ul>
</details>

**Discussion**: Community comments reveal mixed results: some models like GPT-4o can identify the hidden text when prompted, while Claude fails entirely. Users find the technique cool but question its practical utility, with one suggesting a Caesar cipher font for data poisoning.

**Tags**: `#AI`, `#typography`, `#adversarial`, `#computer vision`, `#security`

---

<a id="item-19"></a>
## [Classical ML for LLM Text Detection](https://blog.lyc8503.net/en/post/llm-classifier/) ⭐️ 7.0/10

A blog post explores using classical machine learning methods, such as TF-IDF and logistic regression, to detect text generated by large language models (LLMs). The author trains classifiers on features like n-gram frequencies and achieves high accuracy on a curated dataset. This approach offers a lightweight, interpretable alternative to deep learning detectors, potentially enabling real-time detection in browsers or edge devices. However, its long-term effectiveness is debated as LLMs evolve to mimic human writing more closely. The classifier uses features like character n-grams, word n-grams, and sentence length statistics, trained on a dataset of human-written and LLM-generated texts from multiple models. The model achieves over 90% accuracy on held-out test data but may not generalize to unseen LLMs or adversarial examples.

hackernews · uneven9434 · Jul 16, 16:41 · [Discussion](https://news.ycombinator.com/item?id=48936880)

**Background**: Detecting AI-generated text is an active research area, with methods ranging from watermarking to statistical analysis. Classical ML approaches like TF-IDF and logistic regression have been used for decades in text classification, offering simplicity and speed compared to deep neural networks. The challenge is that LLMs can be fine-tuned or prompted to produce text that evades detection.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/better-programming/detecting-llm-generated-texts-befce4426da9">Detecting LLM - Generated Texts . Is it possible to differentiate between</a></li>
<li><a href="https://arxiv.org/pdf/2303.07205">The Science of Detecting LLM - Generated Texts</a></li>

</ul>
</details>

**Discussion**: Commenters express skepticism about long-term effectiveness, comparing it to an 'accent detector' that may fail as models improve. Some suggest focusing on measuring writing effort rather than provenance, while others see potential for browser extensions to filter LLM-generated content.

**Tags**: `#LLM detection`, `#machine learning`, `#AI-generated text`, `#NLP`, `#security`

---

<a id="item-20"></a>
## [OnePlus Halts New Product Launches in US and Europe](https://community.oneplus.com/thread/2170715118587871237) ⭐️ 7.0/10

OnePlus has decided to stop launching new products in Europe and North America, though existing devices will continue to receive software updates and security patches as originally committed. This marks a significant retreat from key Western markets for OnePlus, which was once a popular 'hacker's choice' for its stock Android experience and unlocked bootloaders. The move signals a strategic shift toward focusing on other regions, likely Asia, and may disappoint loyal users who valued the brand's unique positioning. The news was confirmed via a OnePlus community post, and the company emphasized that existing devices will still receive support. The decision does not affect ongoing operations or support for current users, but no new OnePlus phones or products will be sold in these regions going forward.

hackernews · pilililo2 · Jul 16, 10:14 · [Discussion](https://news.ycombinator.com/item?id=48932539)

**Background**: OnePlus was founded in 2013 with a 'Never Settle' philosophy, offering high-spec phones with near-stock Android at competitive prices. It gained a strong following among enthusiasts for its unlocked bootloaders and developer-friendly approach. Over time, the brand shifted toward a more mainstream strategy, and after co-founder Carl Pei left to start Nothing, OnePlus increasingly integrated with parent company OPPO, losing some of its original identity.

**Discussion**: Community comments express mixed reactions: some former employees note the company's intense 996 culture and hollowed-out staffing, while others lament OnePlus's decline from its enthusiast roots. Users also correct the editorialized title, clarifying that only new product launches are halted, not full operations.

**Tags**: `#OnePlus`, `#smartphone`, `#business`, `#hardware`

---

<a id="item-21"></a>
## [Interactive Linear Algebra Book Wins Community Praise](https://immersivemath.com/ila/) ⭐️ 7.0/10

An immersive linear algebra book with interactive figures, available at immersivemath.com, has been highlighted for its innovative approach to teaching linear algebra through visualization. This interactive approach enhances understanding and retention of complex mathematical concepts, potentially transforming how linear algebra is taught and learned. The book features interactive figures that allow readers to manipulate and explore concepts, with tooltips providing additional explanations. It is praised for its clean presentation and effective progression between sections.

hackernews · srean · Jul 16, 15:32 · [Discussion](https://news.ycombinator.com/item?id=48935951)

**Background**: Linear algebra is a foundational subject in mathematics and engineering, often taught with static diagrams. Interactive visualizations can help students grasp abstract concepts like vector spaces and transformations more intuitively.

**Discussion**: Community members expressed enthusiasm, wishing similar interactive books existed for other subjects like statistics and robotics. Some noted that AI tools like LLMs could make creating such interactive content easier and faster.

**Tags**: `#linear algebra`, `#interactive learning`, `#mathematics education`, `#visualization`, `#open source`

---

<a id="item-22"></a>
## [Rust-to-Zig Rewrite: A Compiler Engineer's Perspective](https://rtfeldman.com/rust-to-zig) ⭐️ 7.0/10

Richard Feldman published a detailed blog post about rewriting a compiler from Rust to Zig, discussing trade-offs in memory safety, performance, and ergonomics. This post sparks debate on whether Rust's safety guarantees are always necessary for compilers, and highlights Zig's faster compilation and simpler memory model as potential advantages for systems programming. Feldman notes that compilers emitting machine code often require memory-unsafe operations, which Zig handles more ergonomically than Rust. Zig's incremental builds are cited as a killer feature, though Rust may eventually catch up.

hackernews · jorangreef · Jul 16, 11:39 · [Discussion](https://news.ycombinator.com/item?id=48933149)

**Background**: Rust and Zig are both modern systems programming languages that prioritize memory safety, but they take different approaches: Rust enforces safety at compile time through its borrow checker, while Zig offers runtime checks and manual control. Compilers are complex programs that often need low-level memory manipulation, making them a good test case for language trade-offs.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@shyamsundarb/memory-safety-in-c-vs-rust-vs-zig-f78fa903f41e">Memory Safety in C++ vs Rust vs Zig | by B Shyam Sundar | Medium</a></li>
<li><a href="https://blog.logrocket.com/comparing-rust-vs-zig-performance-safety-more/">Comparing Rust vs . Zig : Performance, safety , and... - LogRocket Blog</a></li>
<li><a href="https://users.rust-lang.org/t/is-zig-lang-faster-than-rust/70390">Is zig lang faster than rust? - The Rust Programming Language Forum</a></li>

</ul>
</details>

**Discussion**: Steveklabnik disagreed that compilers inherently need unsafe code for regular compilation, arguing only hot patching requires it. Landr0id questioned Zig's use-after-free detection claims. Others praised Zig's incremental builds but wondered if Rust will add similar features soon.

**Tags**: `#Rust`, `#Zig`, `#compilers`, `#systems programming`, `#memory safety`

---

<a id="item-23"></a>
## [TSMC pledges additional $100bn for US expansion](https://www.bbc.co.uk/news/articles/c62x8ldxr7eo?at_medium=RSS&at_campaign=rss) ⭐️ 7.0/10

TSMC announced an additional $100 billion investment to expand its US production facilities, bringing its total US commitment to $265 billion. This massive investment underscores the strategic shift of advanced semiconductor manufacturing to the US, aiming to reduce reliance on Asian supply chains and bolster national security. The company stated the expansion will create high-tech, high-paying jobs, though specific timelines and locations for the new investment were not detailed.

rss · BBC World News · Jul 16, 10:23

**Background**: TSMC is the world's largest contract semiconductor manufacturer, producing chips for companies like Apple and Nvidia. The US has been actively encouraging chip manufacturing on home soil through the CHIPS Act to secure supply chains.

**Tags**: `#semiconductors`, `#TSMC`, `#manufacturing`, `#investment`, `#geopolitics`

---

<a id="item-24"></a>
## [Telstra Outage Caused by Missing Software Update and Undocumented Change](https://www.theguardian.com/business/2026/jul/17/telstra-missing-software-update-undocumented-design-change-outage) ⭐️ 7.0/10

Telstra revealed that a nationwide mobile outage was caused by a missing software update for a critical time-keeping system and an undocumented design change that prevented proper reset. The company admitted that network redundancy did not prevent the failure. This incident underscores the fragility of critical telecommunications infrastructure when software maintenance is neglected, affecting millions of users and essential services. It highlights the need for rigorous change management and software update processes in telecom networks. The outage occurred last week, causing chaos for mobile users, trains, and retailers. Telstra's CEO Vicki Brady is set to appear at a Senate inquiry to discuss the failure.

rss · The Guardian World · Jul 17, 01:00

**Background**: Telecommunications networks rely on precise time-keeping systems to synchronize operations across devices and infrastructure. A missing software update can cause such systems to fail, and undocumented design changes can complicate recovery efforts. Network redundancy, while important, does not guarantee immunity from software-related failures.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/business/2026/jul/17/telstra-missing-software-update-undocumented-design-change-outage">Telstra staff unaware of mass outage risk as critical... | The Guardian</a></li>

</ul>
</details>

**Tags**: `#software failure`, `#network outage`, `#Telstra`, `#critical infrastructure`, `#software maintenance`

---

<a id="item-25"></a>
## [Trump Media to sell priority access to Truth Social posts](https://www.theguardian.com/us-news/2026/jul/16/trump-media-truth-social-posts) ⭐️ 7.0/10

Trump Media & Technology Group announced a paid service that will give Wall Street firms high-speed access to posts from top Truth Social accounts, including possibly President Trump's own posts, starting August 1, 2026. This move raises serious ethical and legal concerns, as it could allow financial institutions to profit from non-public information and potentially manipulate markets based on the president's statements, undermining fair access to information. The service is similar to existing paid data feeds from other platforms, but the key difference is that the most popular poster on Truth Social is the U.S. president, who is also the largest shareholder of the publicly traded parent company and would directly benefit financially.

rss · The Guardian World · Jul 17, 00:13

**Background**: Truth Social is an alt-tech social network launched by Trump Media & Technology Group, built on the open-source Mastodon platform. The company went public earlier this year, making Trump a major shareholder. Critics argue that selling priority access to the president's posts amounts to 'brazen corruption' and could pose national security risks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/us-news/2026/jul/16/trump-media-truth-social-posts">‘Brazen corruption’: critics denounce Trump Media plan... | The Guardian</a></li>
<li><a href="https://www.bbc.com/news/articles/c79gw4lj89eo">Trump Media to sell fast feed of key posts to Wall Street</a></li>
<li><a href="https://nypost.com/2026/07/16/media/trumps-media-firm-to-charge-for-high-speed-access-to-truth-social-posts/">Trump's media firm to charge for high speed access to Truth Social ...</a></li>

</ul>
</details>

**Tags**: `#social media`, `#finance`, `#ethics`, `#regulation`, `#Trump Media`

---

<a id="item-26"></a>
## [Updated Semgrep C/C++ Ruleset Released for Production Use](https://www.reddit.com/r/netsec/comments/1ux0sqt/hn_security_my_semgrep_cc_ruleset_is_ready_for/) ⭐️ 7.0/10

Security researcher 0xdea announced that their Semgrep ruleset for C/C++ vulnerability detection is now production-ready, with significant updates and improvements. The ruleset addresses the lack of C/C++ rules in Semgrep's standard offerings. This ruleset fills a critical gap in static analysis for C/C++ codebases, which are common in security-critical systems. It enables developers and security teams to detect vulnerabilities earlier in the development lifecycle using a fast, open-source tool. The ruleset includes dedicated C and C++ rules, with separate folders for each language, and also provides a specific ruleset for Rust. It can be run via Semgrep CLI with a command like 'semgrep --config semgrep-rules/rules/c/command-injection.yaml /path/to/source'.

reddit · r/netsec · /u/0xdea · Jul 15, 09:24

**Background**: Semgrep is a fast, open-source static analysis tool that supports 30+ languages and can be integrated into IDEs, pre-commit hooks, and CI/CD pipelines. It allows users to write custom rules for pattern matching to detect bugs and security vulnerabilities. The standard Semgrep registry has limited C/C++ rules, making community-contributed rulesets valuable.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/semgrep/semgrep">GitHub - semgrep / semgrep : Lightweight static analysis for many...</a></li>
<li><a href="https://hnsecurity.it/blog/semgrep-ruleset-for-c-c-vulnerability-research/">HN Security - Semgrep ruleset for C / C++ vulnerability research</a></li>
<li><a href="https://github.com/0xdea/semgrep-rules">GitHub - 0xdea/ semgrep - rules : A collection of my Semgrep rules to...</a></li>

</ul>
</details>

**Tags**: `#static analysis`, `#C/C++`, `#security`, `#Semgrep`, `#vulnerability detection`

---

<a id="item-27"></a>
## [Google Rebrands NotebookLM to Gemini Notebook](https://blog.google/innovation-and-ai/products/gemini-notebook/notebooklm-gemini-notebook/) ⭐️ 6.0/10

Google has rebranded NotebookLM to Gemini Notebook, integrating it into the broader Gemini ecosystem. The change reflects a strategic alignment of Google's AI-powered research and note-taking tool under the Gemini brand. This rebranding signals Google's push to unify its AI products under the Gemini umbrella, potentially improving user experience and cross-product integration. Users of NotebookLM may benefit from tighter integration with other Gemini services, but the change may also cause confusion among existing users. NotebookLM, now Gemini Notebook, is an online research and note-taking tool that uses retrieval-augmented generation (RAG) to help users interact with their documents. It features Audio Overviews that generate podcast-like discussions and Video Overviews that create AI-generated video summaries.

hackernews · xnx · Jul 16, 16:08 · [Discussion](https://news.ycombinator.com/item?id=48936451)

**Background**: NotebookLM was originally launched by Google Labs as a virtual research assistant. It uses Google's Gemini models to analyze uploaded documents and generate insights, summaries, and discussions. The rebranding to Gemini Notebook aligns it with Google's broader AI ecosystem, which includes Gemini models and services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NotebookLM">NotebookLM</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some users praise NotebookLM as one of the most useful applications, while others find the novelty wearing off and prefer alternatives like ChatGPT Live for audio learning. Some commenters speculate that the rebranding may be due to internal team consolidation at Google.

**Tags**: `#Google`, `#AI`, `#product update`, `#rebranding`, `#NotebookLM`

---

<a id="item-28"></a>
## [GOES-19 Weather Satellite Enters Safe Hold Mode](https://www.spaceweather.gov/news/goes-19-safe-hold) ⭐️ 6.0/10

On July 16, 2026, NOAA's GOES-19 weather satellite experienced an unexpected anomaly and entered a protective safe hold mode, suspending normal operations. Engineers have since resolved the safe hold and are restoring instruments, with the Advanced Baseline Imager (ABI) expected to resume imaging by 1900Z. GOES-19 is the primary satellite for tracking Atlantic hurricanes and Gulf Coast storms, so its temporary outage could impact real-time weather forecasting. The incident highlights the vulnerability of critical space-based infrastructure and the importance of robust engineering safeguards. The anomaly occurred around 5:00 p.m. EDT on July 15, 2026, triggering safe hold. Restoration order prioritizes ABI, then GLM, SUVI, and CCOR instruments; image navigation may be slightly degraded for the first hour after restart.

hackernews · yabones · Jul 16, 13:30 · [Discussion](https://news.ycombinator.com/item?id=48934286)

**Background**: GOES-19 is the latest in NOAA's Geostationary Operational Environmental Satellite (GOES) series, providing continuous weather monitoring over the Americas. Safe hold mode is a protective state that suspends non-essential operations when an anomaly is detected, allowing engineers to diagnose and resolve issues remotely.

<details><summary>References</summary>
<ul>
<li><a href="https://www.msn.com/en-us/weather/general/goes-19-weather-satellite-briefly-goes-offline/ar-AA284uiX">GOES - 19 weather satellite briefly goes offline</a></li>
<li><a href="https://asibiont.com/en/blog/sputnik-goes-19-pereshel-v-bezopasnyy-rezhim-chto-eto-znachit-dlya-meteorologii-i-kosmicheskoy-avtomatizatsii">GOES -19 Weather Satellite Enters Safe Hold Mode... — ASI Biont Blog</a></li>

</ul>
</details>

**Discussion**: A former GOES engineer noted that anomalies are common in the series, citing past issues like GOES-17's loop heat pipe anomaly and GOES-13's fuel tank problem. Other commenters shared updates on restoration progress and linked to articles explaining the satellite's critical role in hurricane tracking.

**Tags**: `#weather satellite`, `#GOES-19`, `#spacecraft anomaly`, `#NOAA`, `#engineering`

---

<a id="item-29"></a>
## [Global heating supercharged West Africa floods, displacing thousands](https://www.theguardian.com/world/2026/jul/16/how-global-heating-supercharged-floods-west-africa-displacing-thousands) ⭐️ 6.0/10

Scientists have concluded that the devastating floods in West Africa last month were supercharged by climate breakdown, turning a routine weather event into a catastrophe that drowned dozens, displaced thousands, and required hundreds of rescues. This finding underscores the urgent need for both adaptation to a frightening new normal and further rapid emission reductions, as climate change amplifies the severity of extreme weather events worldwide. The floods struck coastal areas of West Africa last month, with scientists attributing the intensified rainfall directly to global heating. The analysis emphasizes that even routine weather patterns are now being supercharged by climate breakdown.

rss · The Guardian World · Jul 16, 00:01

**Background**: Climate change, driven by greenhouse gas emissions, increases the frequency and intensity of extreme weather events such as floods. Warmer air holds more moisture, leading to heavier rainfall. West Africa is particularly vulnerable due to limited infrastructure and high population density in flood-prone areas.

**Tags**: `#climate change`, `#global heating`, `#floods`, `#West Africa`

---