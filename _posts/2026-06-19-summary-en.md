---
layout: default
title: "Horizon Summary: 2026-06-19 (EN)"
date: 2026-06-19
lang: en
---

> From 222 items, 30 important content pieces were selected

---

1. [10k GitHub Repos Found Distributing Trojan Malware](#item-1) ⭐️ 9.0/10
2. [GLM-5.2: Most Powerful Open-Weight Text LLM Released](#item-2) ⭐️ 9.0/10
3. [Squidbleed: Heartbleed-style memory leak in all Squid Proxy versions](#item-3) ⭐️ 9.0/10
4. [Project Valhalla Value Types Arrive in JDK 28 After a Decade](#item-4) ⭐️ 8.0/10
5. [Zero-Touch OAuth for MCP Simplifies Enterprise AI Agent Auth](#item-5) ⭐️ 8.0/10
6. [Hospitals and universities repurpose drugs at 90% lower cost](#item-6) ⭐️ 8.0/10
7. [Modos Color E-Paper Monitor Achieves 60Hz Refresh Rate](#item-7) ⭐️ 8.0/10
8. [Charity Majors: AI Demands More Engineering Discipline](#item-8) ⭐️ 8.0/10
9. [Popa Botnet Tied to Publicly-Traded Israeli Firm NetNut](#item-9) ⭐️ 8.0/10
10. [US Classifies Anthropic's Fable AI as Munition, Global Access Cut](#item-10) ⭐️ 8.0/10
11. [Spyware Uses Forbidden Text to Evade AI Analysis](#item-11) ⭐️ 8.0/10
12. [Scientists mobilize against Trump's proposed research grant rule](#item-12) ⭐️ 8.0/10
13. [CVE-2026-5667: Unauthenticated Remote Control of Mitsubishi WiFi Adapter](#item-13) ⭐️ 8.0/10
14. [Chrome Extension Silently Adds Affiliate Tracking](#item-14) ⭐️ 8.0/10
15. [AirPods and the New Social Norm of Acoustic Isolation](#item-15) ⭐️ 7.0/10
16. [Ubiquiti Unveils Enterprise NAS with ZFS and Dual 25GbE](#item-16) ⭐️ 7.0/10
17. [Japan's Railways Unified Brand After Privatization](#item-17) ⭐️ 7.0/10
18. [Cornell's CS 6120 Advanced Compilers Course Goes Self-Guided](#item-18) ⭐️ 7.0/10
19. [Beyond .gitignore: Git's Hidden Ignore Mechanisms](#item-19) ⭐️ 7.0/10
20. [W Social: European Digital Sovereignty or Political Theater?](#item-20) ⭐️ 7.0/10
21. [2.5-Hour Ice Water Drowning Survival with Severe Deficits](#item-21) ⭐️ 7.0/10
22. [Datasette Apps: Host sandboxed HTML apps inside Datasette](#item-22) ⭐️ 7.0/10
23. [Over-reliance on chatbots can diminish critical-thinking skills](#item-23) ⭐️ 7.0/10
24. [Datacenters Drive US Clean Energy Growth, Pose Climate Threat](#item-24) ⭐️ 7.0/10
25. [Monitoring Claude Execution Layer with OpenTelemetry](#item-25) ⭐️ 7.0/10
26. [uv 0.11.22 Released with Preview Features and Performance Boost](#item-26) ⭐️ 6.0/10
27. [Datasette-acl 0.6a0 expands to general resource sharing](#item-27) ⭐️ 6.0/10
28. [CDC Allocates $107M Emergency Ebola Funding](#item-28) ⭐️ 6.0/10
29. [Titan sub disaster report blames design flaws and groupthink](#item-29) ⭐️ 6.0/10
30. [KPMG admits leaking Optus data, surveilling whistleblower](#item-30) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [10k GitHub Repos Found Distributing Trojan Malware](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 9.0/10

A security researcher discovered over 10,000 GitHub repositories that are distributing Trojan malware, primarily targeting AI agents and automated systems by cloning legitimate projects and modifying README files to link to malicious ZIP archives. This massive supply chain attack poses a significant threat to the open-source ecosystem, as developers and automated agents may unknowingly clone infected repositories, leading to credential theft and further compromise. The malicious repositories have real commit histories and contributor profiles because they are clones of legitimate projects, with only the README altered to include a download link for a Trojan that steals cryptocurrency credentials.

hackernews · theorchid · Jun 18, 11:45 · [Discussion](https://news.ycombinator.com/item?id=48583928)

**Background**: Supply chain attacks in open source have increased dramatically, with attackers often hijacking or imitating trusted packages. In this campaign, attackers exploit the trust in GitHub repositories and the automated behavior of AI agents that search for and clone code, making the attack particularly effective against automated systems.

<details><summary>References</summary>
<ul>
<li><a href="https://cybernews.com/security/10k-repos-github-malware-campaign-targets-ai-agents/">10,000+ malicious GitHub repositories discovered distributing Trojans ...</a></li>
<li><a href="https://byteiota.com/10000-malicious-github-repos-are-pushing-trojans-now/">10,000 Malicious GitHub Repos Are Pushing Trojans Now</a></li>

</ul>
</details>

**Discussion**: Community comments highlight that the attack targets automated agents rather than humans, with repositories frequently updated to appear in search results. Some users report their names being attached to fake projects, and one commenter identified the malware as related to the Disco Trojan family.

**Tags**: `#malware`, `#GitHub`, `#supply chain attack`, `#security`, `#open source`

---

<a id="item-2"></a>
## [GLM-5.2: Most Powerful Open-Weight Text LLM Released](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai released GLM-5.2, a 753B-parameter open-weights LLM with 1M token context under MIT license, topping the Artificial Analysis Intelligence Index v4.1 among open models. This release sets a new benchmark for open-weights LLMs, offering state-of-the-art performance with a permissive license, which could accelerate AI research and application development. GLM-5.2 uses Mixture of Experts with 40 active parameters out of 753B total, has a 1M token context window, and is text-only. It ranks 2nd on Code Arena WebDev leaderboard behind Claude Fable 5.

rss · Simon Willison · Jun 17, 23:58

**Background**: Mixture of Experts (MoE) is a technique that uses multiple sub-models (experts) to improve LLM quality while keeping inference efficient. Open-weights models make trained parameters publicly available, enabling customization and local deployment.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tensorops.ai/post/what-is-mixture-of-experts-llm">LLM Mixture of Experts Explained</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://www.mindstudio.ai/blog/claude-1m-token-context-window-agents">Claude 1 M Token Context Window : What It Means for... | MindStudio</a></li>

</ul>
</details>

**Discussion**: The community is excited about GLM-5.2's performance and MIT license, but some note its high token usage per task (43k vs 24k for MiniMax-M3) and the disappointing opossum SVG output.

**Tags**: `#LLM`, `#open-weights`, `#GLM-5.2`, `#AI`, `#Mixture of Experts`

---

<a id="item-3"></a>
## [Squidbleed: Heartbleed-style memory leak in all Squid Proxy versions](https://www.reddit.com/r/netsec/comments/1u9y7yw/squidbleed_cve202647729_heartbleedstyle/) ⭐️ 9.0/10

A new vulnerability named Squidbleed (CVE-2026-47729) has been disclosed, affecting every version of Squid Proxy in its default configuration by leaking internal memory, similar to the Heartbleed bug. This is critical because Squid Proxy is widely used for caching and filtering web traffic, and the default configuration makes every deployment vulnerable, potentially exposing sensitive data such as passwords, session tokens, or private keys. The vulnerability is a buffer over-read in Squid's handling of certain requests, allowing an attacker to read beyond the intended buffer boundaries and retrieve chunks of memory. No authentication is required to exploit it.

reddit · r/netsec · /u/qwerty0x41 · Jun 19, 10:21

**Background**: Squid is a popular open-source caching and forwarding HTTP web proxy used to speed up web servers and filter traffic. The Heartbleed bug (CVE-2014-0160) was a similar memory leak in OpenSSL that affected millions of servers worldwide. Squidbleed shares the same class of vulnerability—a buffer over-read—and is equally severe due to its widespread impact.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Squid_proxy">Squid proxy</a></li>
<li><a href="https://en.wikipedia.org/wiki/Heartbleed_vulnerability">Heartbleed vulnerability</a></li>

</ul>
</details>

**Discussion**: The netsec community discussion is likely substantive, with users expressing concern over the severity and reminiscing about Heartbleed. Some may discuss mitigation strategies or criticize the lack of a patch at disclosure.

**Tags**: `#security`, `#vulnerability`, `#squid`, `#CVE`, `#memory leak`

---

<a id="item-4"></a>
## [Project Valhalla Value Types Arrive in JDK 28 After a Decade](https://www.jvm-weekly.com/p/project-valhalla-explained-how-a) ⭐️ 8.0/10

Project Valhalla's value types, a decade-long effort to add user-defined value types to Java, have finally arrived as a preview feature in JDK 28. Value types allow Java developers to define types that behave like primitives—stored by value without object overhead—potentially improving performance and memory efficiency for data-intensive applications. In JDK 28, value classes are still reference types; non-nullable types that enable flattening of larger value classes are planned for a future JEP. The feature currently only flattens value types that fit within a 64-bit cache line.

hackernews · philonoist · Jun 19, 06:35 · [Discussion](https://news.ycombinator.com/item?id=48595511)

**Background**: Java has long had primitive types (int, char, etc.) stored by value, while all other objects are reference types with heap allocation and identity overhead. Project Valhalla, announced in 2014, aims to allow user-defined types to enjoy similar performance benefits as primitives.

<details><summary>References</summary>
<ul>
<li><a href="https://www.jvm-weekly.com/p/project-valhalla-explained-how-a">Project Valhalla, Explained: How a Decade of Work Arrives in JDK 28</a></li>
<li><a href="https://en.wikipedia.org/wiki/Project_Valhalla_(Java_language)">Project Valhalla (Java language) - Wikipedia</a></li>
<li><a href="https://www.theregister.com/devops/2026/06/15/javas-project-valhalla-finally-lands-a-preview-in-jdk-28/5255557">Java 's Project Valhalla finally lands a preview in JDK 28</a></li>

</ul>
</details>

**Discussion**: Community comments show appreciation for the decade-long effort but also debate trade-offs: some argue that the null-safety model is not mentally heavy, while others note the limitation that value types only flatten when fitting a cache line. Comparisons to other languages like C# structs are also discussed.

**Tags**: `#Java`, `#Project Valhalla`, `#value types`, `#JVM`, `#performance`

---

<a id="item-5"></a>
## [Zero-Touch OAuth for MCP Simplifies Enterprise AI Agent Auth](https://blog.modelcontextprotocol.io/posts/enterprise-managed-auth/) ⭐️ 8.0/10

Anthropic, Okta, Microsoft, and others have introduced Enterprise-Managed Authorization (EMA) for the Model Context Protocol (MCP), enabling zero-touch OAuth flows that allow AI agents to authenticate without per-app configuration. This eliminates a major barrier to enterprise adoption of AI agents by isolating authentication outside the agent's context window, improving both security and user experience for large organizations deploying AI tools. The feature is powered by a new token format called ID-JAG (Identity-Justified Access Grant), which is not MCP-specific and can be used for secure data sharing across applications using the same SSO provider.

hackernews · niyikiza · Jun 18, 21:54 · [Discussion](https://news.ycombinator.com/item?id=48592163)

**Background**: MCP is an open standard for connecting AI applications to external data sources and tools, replacing fragmented integrations with a single protocol. Traditionally, OAuth flows required users to manually authorize each tool, which was cumbersome and insecure for enterprise environments.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.modelcontextprotocol.io/posts/enterprise-managed-auth/">Enterprise-Managed Authorization: Zero - touch OAuth for MCP</a></li>
<li><a href="https://news.ycombinator.com/item?id=48592163">Zero - Touch OAuth for MCP | Hacker News</a></li>
<li><a href="https://www.anthropic.com/news/model-context-protocol">Introducing the Model Context Protocol \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Community members expressed enthusiasm for the collaboration across companies like Okta and Microsoft, with one commenter noting that the real value of MCP is isolating auth outside the agent's context window. Another developer shared frustration with implementing Microsoft Entra ID auth for MCP, highlighting practical challenges.

**Tags**: `#OAuth`, `#MCP`, `#authentication`, `#AI agents`, `#enterprise security`

---

<a id="item-6"></a>
## [Hospitals and universities repurpose drugs at 90% lower cost](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 8.0/10

Hospitals and universities are repurposing existing drugs for new uses at 90% lower cost than developing new drugs, challenging traditional pharmaceutical pricing models. This approach could dramatically improve access to treatments for rare diseases and other conditions, reducing healthcare costs and bypassing high drug prices set by manufacturers. The article highlights using a cancer drug (bevacizumab/Avastin) to treat macular degeneration at $50 per dose versus $1,500 for the approved drug Lucentis, despite being molecularly similar.

hackernews · giuliomagnifico · Jun 18, 10:33 · [Discussion](https://news.ycombinator.com/item?id=48583386)

**Background**: Drug repurposing involves finding new therapeutic uses for already approved drugs, which can bypass many costly and time-consuming early-stage trials. However, regulatory pathways for off-label use often require manufacturer consent or becoming a manufacturer oneself, creating barriers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Drug_repurposing">Drug repurposing</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC9336118/">Drug repurposing : a systematic review on root causes, barriers and...</a></li>

</ul>
</details>

**Discussion**: Commenters shared personal experiences, such as using esketamine (Spravato) which is a patented modification of ketamine, and noted that repurposing is especially valuable for rare diseases like Huntington's where pharmaceutical companies lack incentives. Some pointed out regulatory hurdles that limit off-label use without manufacturer cooperation.

**Tags**: `#drug repurposing`, `#healthcare costs`, `#pharmaceutical policy`, `#rare diseases`, `#community insights`

---

<a id="item-7"></a>
## [Modos Color E-Paper Monitor Achieves 60Hz Refresh Rate](https://spectrum.ieee.org/modos-e-paper-monitor) ⭐️ 8.0/10

Modos, a two-person startup, is developing a 13.3-inch color e-paper monitor called Modos Flow with a native resolution of 3200x2400, touch input, and a 60Hz refresh rate, pushing the boundaries of e-paper display technology. This development brings e-paper displays closer to mainstream use by offering a high-resolution, color, and fast-refreshing screen that could replace traditional LCDs for reading, writing, and focused work, while maintaining low power consumption. The Modos Flow is an upcoming portable E Ink monitor that offers sub-100ms latency and a paper-like viewing experience, with a Dev Kit version already achieving 75Hz refresh rate. However, higher refresh rates may reduce energy efficiency, a trade-off noted by the community.

hackernews · Vinnl · Jun 18, 11:41 · [Discussion](https://news.ycombinator.com/item?id=48583897)

**Background**: E-paper displays, like those using E Ink technology, traditionally have low refresh rates (e.g., 10-15Hz) and are often monochrome, limiting them to e-readers and static signage. Recent advances have pushed color and video-rate capabilities, with Modos achieving 60-75Hz, comparable to basic LCDs.

<details><summary>References</summary>
<ul>
<li><a href="https://goodereader.com/blog/technology/modos-flow-is-a-new-13-3-inch-e-ink-monitor-with-60-hz">Modos Flow is a new 13.3 inch E Ink monitor with 60 Hz - Good e-Reader</a></li>
<li><a href="https://www.tomshardware.com/monitors/portable-monitors/hands-on-with-modos-tech-13-3-inch-e-paper-monitors">Hands-on with Modos Tech 13.3-inch e-paper monitors — we tried the current Dev Kit model and the next-gen Modos Flow touch | Tom's Hardware</a></li>
<li><a href="https://spectrum.ieee.org/e-paper-display-modos">E-Paper Display Refresh Rate Reaches New Heights - IEEE Spectrum</a></li>

</ul>
</details>

**Discussion**: The community is excited about Modos' progress, with comments praising the impressive specs and the potential for alternative display technologies. However, some users question the impact of high refresh rates on e-paper panel longevity and energy efficiency, noting that fast refresh may negate the power-saving advantage.

**Tags**: `#e-paper`, `#display technology`, `#hardware`, `#startup`, `#innovation`

---

<a id="item-8"></a>
## [Charity Majors: AI Demands More Engineering Discipline](https://simonwillison.net/2026/Jun/17/charity-majors/#atom-everything) ⭐️ 8.0/10

Charity Majors argues that AI has made code generation cheap and disposable, requiring more engineering discipline, not less. This insight challenges the common assumption that AI reduces the need for rigorous engineering, highlighting a paradigm shift in software development where code is now disposable and regenerable. Majors notes that in 2025, the economics of code production were upended: code went from being hard, time-consuming, and expensive to generate to being effectively free and instant.

rss · Simon Willison · Jun 17, 17:12

**Background**: Charity Majors is a respected industry figure known for her commentary on software engineering and operations. Her quote appears on Simon Willison's blog, which curates notable tech insights.

**Tags**: `#ai-assisted-programming`, `#software-engineering`, `#generative-ai`, `#industry-insight`

---

<a id="item-9"></a>
## [Popa Botnet Tied to Publicly-Traded Israeli Firm NetNut](https://krebsonsecurity.com/2026/06/popa-botnet-linked-to-publicly-traded-israeli-firm/) ⭐️ 8.0/10

Researchers have linked the Popa Android botnet, which has infected millions of TV boxes for ad fraud and account takeovers over four years, to NetNut, a residential proxy service owned by publicly-traded Alarum Technologies. This connection exposes how a legitimate residential proxy provider may be enabling cybercriminal infrastructure, raising serious questions about corporate accountability and the misuse of proxy services in the cybersecurity ecosystem. Popa is a plugin component of the Vo1d botnet, which targets unofficial Android TV boxes. NetNut provides residential IPs that mask malicious traffic, making detection difficult.

rss · Krebs on Security · Jun 18, 17:37

**Background**: A residential proxy service routes internet traffic through real residential IP addresses, making it appear as legitimate user activity. Botnets like Popa abuse such services to conduct ad fraud, account takeovers, and data scraping while evading detection. NetNut, acquired by Alarum Technologies, is a known provider of such proxies.

<details><summary>References</summary>
<ul>
<li><a href="https://krebsonsecurity.com/2026/06/popa-botnet-linked-to-publicly-traded-israeli-firm/">'Popa' Botnet Linked to Publicly-Traded Israeli Firm</a></li>
<li><a href="https://blog.ibvl.in/index.php/2026/06/18/popa-botnet-linked-to-publicly-traded-israeli-firm/">‘Popa’ Botnet Linked to Publicly-Traded Israeli Firm - Imperative Business Ventures Limited</a></li>
<li><a href="https://www.cryptika.com/popa-botnet-linked-to-publicly-traded-israeli-firm/">‘Popa’ Botnet Linked to Publicly-Traded Israeli Firm | Cryptika Cybersecurity</a></li>

</ul>
</details>

**Tags**: `#botnet`, `#cybersecurity`, `#Android`, `#ad fraud`, `#residential proxy`

---

<a id="item-10"></a>
## [US Classifies Anthropic's Fable AI as Munition, Global Access Cut](https://www.schneier.com/blog/archives/2026/06/anthropics-fable-and-the-state-of-ai.html) ⭐️ 8.0/10

On June 9, 2026, Anthropic released its Fable generative AI model, but three days later the US government classified it as a dangerous munition under export control laws, forcing Anthropic to shut off access for all users worldwide. This marks a significant escalation in AI export controls, treating advanced AI models as weapons. Bruce Schneier argues the real issue is the trend of increasing AI capabilities, not any single model, and that collective action is needed but currently impossible. The US government used its export-control authority to prohibit foreign nationals from accessing Fable, but Anthropic could not differentiate between Americans and foreigners, so it shut off access for everyone. The model is Claude Fable 5, a Mythos-class model priced at $10 per million input tokens.

rss · Schneier on Security · Jun 19, 11:03

**Background**: The US Munitions List (USML) and Commerce Control List (CCL) regulate exports of sensitive items with military applications. Classifying an AI model as a munition is unprecedented and reflects growing concerns about AI safety and national security. Bruce Schneier is a renowned security expert who often comments on technology policy.

**Tags**: `#AI policy`, `#export control`, `#Anthropic`, `#AI safety`, `#regulation`

---

<a id="item-11"></a>
## [Spyware Uses Forbidden Text to Evade AI Analysis](https://www.schneier.com/blog/archives/2026/06/embedding-forbidden-text-in-spyware-to-discourage-ai-analysis.html) ⭐️ 8.0/10

Malware developers are embedding text about nuclear and biological weapons inside JavaScript block comments in spyware to trigger refusal behavior in AI-based analysis tools, preventing the AI from examining the actual malicious code. This novel adversarial technique exploits the safety guardrails of AI models, potentially allowing malware to bypass automated analysis pipelines and evade detection, posing a significant challenge to AI-driven cybersecurity defenses. The forbidden text is placed inside a large JavaScript block comment, which does not affect code execution but is fed to AI analysis tools that may refuse to process the file due to policy violations. The real malware follows the comment with a try{eval(...)} wrapper and a ROT-style substitution function.

rss · Schneier on Security · Jun 18, 11:04

**Background**: AI-based malware analysis tools often use language models to examine code snippets for malicious behavior. These models are trained with safety guidelines that may cause them to refuse analyzing content related to dangerous topics like weapons of mass destruction. By embedding such text, attackers can trick the AI into aborting analysis before it reaches the actual payload.

<details><summary>References</summary>
<ul>
<li><a href="https://securityelites.com/adversarial-machine-learning-attacks-2026/">Adversarial Machine Learning — Fooling AI With Crafted Inputs</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights the cleverness of this evasion technique and raises concerns about the brittleness of AI safety filters. Some commenters note that this could be mitigated by better isolating untrusted input before feeding it to AI models, while others worry about an arms race between attackers and defenders.

**Tags**: `#AI safety`, `#malware`, `#adversarial attacks`, `#cybersecurity`

---

<a id="item-12"></a>
## [Scientists mobilize against Trump's proposed research grant rule](https://www.theguardian.com/us-news/2026/jun/19/trump-scientific-research-cuts) ⭐️ 8.0/10

Scientists, led by the group Stand Up for Science, are actively lobbying Congress to oppose a proposed Office of Management and Budget (OMB) rule that would impose new controls on federal research grants, warning it could dismantle the U.S. science ecosystem. This rule could fundamentally alter how federal research funds are allocated and used, potentially stifling scientific innovation and international collaboration, and affecting thousands of researchers and institutions across the U.S. The OMB proposal includes broad restrictions on international research collaborations and new criteria for grant eligibility, which critics argue would politicize science and reduce U.S. competitiveness.

rss · The Guardian World · Jun 19, 12:00

**Background**: Stand Up for Science is a non-profit organization formed in February 2025 to combat policy changes under Donald Trump's second term. It organized protests and declarations such as the Bethesda Declaration. The OMB proposal is part of a broader effort to control federal spending and align research with administration priorities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Stand_Up_for_Science_2025">Stand Up for Science 2025</a></li>
<li><a href="https://www.aip.org/fyi/omb-proposes-broad-restrictions-on-international-research">OMB Proposes Broad Restrictions on International Research</a></li>
<li><a href="https://www.researchamerica.org/omb-proposed-federal-grant-rule/">OMB 's Proposed Federal Grant Rule - Research !America</a></li>

</ul>
</details>

**Tags**: `#science policy`, `#research funding`, `#Trump administration`, `#political activism`, `#US science`

---

<a id="item-13"></a>
## [CVE-2026-5667: Unauthenticated Remote Control of Mitsubishi WiFi Adapter](https://www.reddit.com/r/netsec/comments/1u9dncq/cve20265667_unauthenticated_remote_control_of/) ⭐️ 8.0/10

A vulnerability (CVE-2026-5667) has been disclosed that allows unauthenticated remote control of Mitsubishi MAC-577IF-2E WiFi adapters via probe request reconnaissance. This vulnerability exposes millions of HVAC systems to remote takeover, potentially allowing attackers to manipulate heating and cooling in homes and businesses, leading to energy waste or safety risks. The exploit leverages probe request frames, which are normally used for network discovery, to send malicious commands to the adapter without authentication. The adapter's firmware does not validate the source of these requests.

reddit · r/netsec · /u/Ecstatic_Priority514 · Jun 18, 18:05

**Background**: The Mitsubishi MAC-577IF-2E is a WiFi adapter used to connect Mitsubishi heat pumps and air conditioners to home networks for remote control via a mobile app. Probe request reconnaissance is a technique where an attacker sends probe requests to discover nearby WiFi networks and devices; in this case, it is abused to inject commands.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.dest-unreach.be/2022/06/04/mitsubishi-wifi-adapter/">Reverse engineering the Mitsubishi heat-pump WiFi adapter</a></li>
<li><a href="https://github.com/pymitsubishi/mac-577if-e">GitHub - pymitsubishi/ mac - 577 if -e: MAC - 577 IF 2 - E Analysis Tools...</a></li>
<li><a href="https://www.easymanua.ls/mitsubishi-electric/mac-577if2-e/manual">Mitsubishi Electric MAC - 577 IF 2 - E - User Manual</a></li>

</ul>
</details>

**Discussion**: The r/netsec discussion includes technical analysis of the probe request injection method and suggests mitigations such as disabling WiFi or applying firmware patches. Some commenters note that similar vulnerabilities may exist in other IoT devices.

**Tags**: `#CVE`, `#IoT security`, `#vulnerability disclosure`, `#HVAC`, `#WiFi adapter`

---

<a id="item-14"></a>
## [Chrome Extension Silently Adds Affiliate Tracking](https://www.reddit.com/r/netsec/comments/1u8l66d/worth_a_malext_report_a_2_millionuser_chrome/) ⭐️ 8.0/10

A Chrome extension called Volume Booster, with 2 million users, added affiliate tracking code from Give Freely/Wildlink in a minor update from v1.0.3 to v1.0.4 between June 27 and July 2, 2025, without requesting new permissions. This raises significant privacy and transparency concerns because the extension silently expanded its functionality to include affiliate tracking across all websites, potentially without user consent, affecting millions of users. The update added content scripts matching <all_urls> that load GiveFreely-content.umd.js and content-script.js, enabling merchant detection, affiliate attribution, and donation campaigns, but no new permissions were required so the update was automatic.

reddit · r/netsec · /u/Huge-Skirt-6990 · Jun 17, 20:10

**Background**: Chrome extensions can update automatically if they don't request new permissions, which can be exploited to add unexpected functionality. Give Freely/Wildlink is an affiliate tracking SDK that monetizes user activity by inserting affiliate links. MalExt is a community-driven database tracking malicious or policy-violating browser extensions.

<details><summary>References</summary>
<ul>
<li><a href="https://malext.io/">MalExt Sentry - Malicious Browser Extension Tracker</a></li>
<li><a href="https://github.com/wildlink/wildlink-api-ios">GitHub - wildlink / wildlink -api-ios: Wildlink SDK · GitHub</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed concern about the silent addition of tracking, with many viewing it as a privacy violation. Some noted that the same SDK appears in multiple unrelated extensions, suggesting a white-label monetization model. Others debated whether this constitutes malware or just aggressive monetization.

**Tags**: `#chrome extension`, `#security`, `#malware analysis`, `#privacy`, `#affiliate tracking`

---

<a id="item-15"></a>
## [AirPods and the New Social Norm of Acoustic Isolation](https://www.theescapenewsletter.com/p/the-airpods-effect) ⭐️ 7.0/10

An article titled 'The AirPods Effect' examines how wireless earbuds enable people to acoustically isolate themselves in public, sparking debate about whether this behavior is natural or harmful to social interaction. This phenomenon reflects a major shift in social norms, as millions of people now routinely use earbuds to filter out their environment, potentially reducing spontaneous interactions and altering cognitive processes like daydreaming. The article and community comments highlight that wearing earbuds can normalize unnatural crowded environments, but may also suppress the default mode network (DMN) responsible for creative thinking and problem-solving.

hackernews · herbertl · Jun 18, 23:08 · [Discussion](https://news.ycombinator.com/item?id=48592832)

**Background**: The default mode network (DMN) is a brain network active when a person is at rest and not focused on external tasks; it is associated with daydreaming, self-reflection, and creative insight. Acoustic isolation through earbuds reduces ambient noise, which can either help concentration or, if used constantly, deprive the brain of downtime needed for DMN activity.

<details><summary>References</summary>
<ul>
<li><a href="https://www.researchgate.net/publication/396657828_Chronic_Use_of_Wireless_Earbuds_and_Head-Worn_Devices_Potential_Impacts_on_Brain_Function_and_Cognitive_Focus_A_Narrative_Review">(PDF) Chronic Use of Wireless Earbuds and Head-Worn Devices: Potential Impacts on Brain Function and Cognitive Focus A Narrative Review</a></li>
<li><a href="https://www.uhhospitals.org/blog/articles/2024/10/protect-your-hearing-safe-listening-with-earbuds">Protect Your Hearing: Safe Listening with Earbuds | University Hospitals</a></li>
<li><a href="https://www.betterhealthfacts.com/2025/07/wireless-earbuds-affect-brain-function.html">Can Daily Use of Wireless Earbuds Affect Brain Function or Hearing Health?</a></li>

</ul>
</details>

**Discussion**: Commenters debated whether earbud use is unnatural: some argued that crowded urban environments are themselves unnatural, and earbuds help restore a comfortable sensory level. Others noted that missing daydreaming time due to constant audio input is a bigger concern, with one user reporting increased ideas after stopping listening while walking.

**Tags**: `#technology and society`, `#human behavior`, `#social norms`, `#cognitive science`

---

<a id="item-16"></a>
## [Ubiquiti Unveils Enterprise NAS with ZFS and Dual 25GbE](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 7.0/10

Ubiquiti announced an enterprise NAS built on ZFS, featuring dual 25 Gigabit SFP28 ports and redundant power supplies, priced at $3999. This marks Ubiquiti's entry into the NAS market, leveraging ZFS's advanced data integrity and snapshot features, potentially disrupting the enterprise storage space with its no-subscription model. The NAS uses spinning HDDs, raising concerns about saturating the 25GbE links; it also lacks NVMe caching in the base model, which may limit performance.

hackernews · ksec · Jun 18, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48585866)

**Background**: ZFS is an advanced file system known for data integrity, snapshots, and pooled storage, commonly used in enterprise NAS solutions. Ubiquiti is known for networking equipment and a cloud-managed ecosystem, but has faced past software reliability issues.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ui.com/integrations/network-storage">UniFi Network Attached Storage - Ubiquiti</a></li>
<li><a href="https://www.storagereview.com/review/ubiquiti-unas-pro-8-review-2u-10gbe-nas-with-redundant-power-nvme-cache">Ubiquiti UNAS Pro 8 Review: 2U 10GbE NAS With Redundant Power & NVMe Cache - StorageReview.com</a></li>
<li><a href="https://docs.freebsd.org/en/books/handbook/zfs/">Chapter 22. The Z File System ( ZFS ) | FreeBSD Documentation Portal</a></li>

</ul>
</details>

**Discussion**: Community comments show excitement about Ubiquiti entering the NAS space with ZFS, but significant concerns about software quality and past security incidents. Users also question whether spinning disks can saturate the 25GbE links.

**Tags**: `#Ubiquiti`, `#NAS`, `#ZFS`, `#storage`, `#enterprise`

---

<a id="item-17"></a>
## [Japan's Railways Unified Brand After Privatization](https://arun.is/blog/jr-logo/) ⭐️ 7.0/10

An article explains how Japan's railway companies, after the 1987 privatization of Japanese National Railways, maintained a unified brand identity through a cooperative trademark arrangement rooted in Japanese culture. This case offers a unique cultural and legal solution to trademark and corporate identity challenges, contrasting with Western trademark law and highlighting how cultural values can shape business practices. The JR Group companies share the 'JR' trademark under a licensing agreement that reflects the Japanese concept of 'noren-wake' (branching out with shared goodwill), rather than strict trademark enforcement.

hackernews · ddrmaxgt37 · Jun 17, 14:03 · [Discussion](https://news.ycombinator.com/item?id=48570730)

**Background**: In 1987, the Japanese government privatized the debt-ridden Japanese National Railways, splitting it into six regional passenger companies and one freight company, collectively known as the JR Group. Each company operates independently but uses the unified 'JR' brand, a rare example of cooperative trademark sharing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Japan_Railways_Group">Japan Railways Group - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Division_and_privatization_of_Japanese_National_Railways">Division and privatization of Japanese National Railways - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the Japanese approach as more cooperative and beautiful compared to Western trademark law, noting cultural factors like duty and honor. Some also shared practical travel tips about JR Pass pricing and a project to catalog train platform melodies.

**Tags**: `#Japan`, `#railways`, `#trademark`, `#corporate identity`, `#culture`

---

<a id="item-18"></a>
## [Cornell's CS 6120 Advanced Compilers Course Goes Self-Guided](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 7.0/10

Cornell University's CS 6120 Advanced Compilers course is now available as a free, self-guided online resource, featuring lessons and labs for independent study. This provides high-quality, university-level compiler education to a global audience for free, benefiting enthusiasts and professionals who lack access to formal coursework. The course covers advanced topics like SSA form, data flow analysis, and optimization, but some community members note it may overlap with introductory compiler courses.

hackernews · ibobev · Jun 18, 11:04 · [Discussion](https://news.ycombinator.com/item?id=48583606)

**Background**: Compiler design is a core area of computer science that translates high-level code into machine code. Advanced compilers courses typically cover optimization techniques and runtime systems. Cornell's CS 6120 is a well-regarded graduate-level course taught by Adrian Sampson.

**Discussion**: Community feedback is mixed: some praise the availability of the material, while others critique the focus on trace compilation as outdated and question the 'advanced' label due to overlap with introductory topics. Comparisons to other resources like Nora Sandler's 'Writing a C Compiler' are also discussed.

**Tags**: `#compilers`, `#online course`, `#computer science education`, `#programming languages`

---

<a id="item-19"></a>
## [Beyond .gitignore: Git's Hidden Ignore Mechanisms](https://nelson.cloud/.gitignore-isnt-the-only-way-to-ignore-files-in-git/) ⭐️ 7.0/10

An article explores alternative Git ignore mechanisms beyond .gitignore, including the local .git/info/exclude file and global excludes via core.excludesFile, with community comments adding .gitattributes and scratch directory tricks. This matters because many developers only know .gitignore, leading to unnecessary commits of personal or IDE files to shared repositories. Understanding these alternatives improves team collaboration and personal workflow efficiency. The .git/info/exclude file works like a local .gitignore that is not shared, while core.excludesFile sets a global ignore file for all repositories. The scratch directory trick involves creating a scratch/.gitignore containing only '*' to ignore everything in that folder.

hackernews · FergusArgyll · Jun 18, 10:29 · [Discussion](https://news.ycombinator.com/item?id=48583356)

**Background**: Git uses .gitignore files to specify intentionally untracked files that Git should ignore. However, there are other mechanisms for ignoring files locally without affecting other collaborators: the per-repository .git/info/exclude file and a global exclude file configured via git config. These are useful for personal preferences like editor artifacts or scratch notes.

<details><summary>References</summary>
<ul>
<li><a href="https://stackoverflow.com/questions/1753070/how-do-i-configure-git-to-ignore-some-files-locally">How do I configure git to ignore some files locally? - Stack Overflow</a></li>
<li><a href="https://git-scm.com/docs/gitignore">Git - gitignore Documentation</a></li>
<li><a href="https://underlap.org/managing-scratch-files-in-a-git-project/">Managing scratch files in a git project</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article for revealing lesser-known features, with many expressing surprise at the global exclude file. Some shared additional tips like using .gitattributes to ignore diffs for certain files, and the scratch directory trick for personal notes. The overall sentiment was positive and appreciative of the learning opportunity.

**Tags**: `#Git`, `#version control`, `#developer tools`, `#productivity`

---

<a id="item-20"></a>
## [W Social: European Digital Sovereignty or Political Theater?](https://blog.elenarossini.com/w-social-public-institutions-and-the-theater-of-european-digital-sovereignty/) ⭐️ 7.0/10

A blog post by Elena Rossini critiques W Social, a European social media platform launched with high-profile EU politician support, as a performative digital sovereignty project lacking transparency, contrasting it with the more open alternative Eurosky. This critique highlights growing skepticism about the authenticity of European digital sovereignty initiatives, questioning whether they serve genuine public interest or political agendas, and could influence public trust and policy direction. W Social is an LLC with a founder from the financial sector, raising concerns about profit motives and closed-source development, while Eurosky, built on AT Protocol, operates transparently via a non-profit foundation.

hackernews · nemoniac · Jun 18, 12:46 · [Discussion](https://news.ycombinator.com/item?id=48584497)

**Background**: European digital sovereignty refers to the EU's efforts to reduce reliance on non-European tech providers by developing its own digital infrastructure and platforms. W Social positions itself as a European alternative to X (formerly Twitter), but critics argue it lacks the openness and community governance seen in projects like Eurosky.

<details><summary>References</summary>
<ul>
<li><a href="https://digital-strategy.ec.europa.eu/en/policies/eu-tech-sovereignty">Strengthening Europe’s Tech Sovereignty | Shaping Europe’s digital future</a></li>
<li><a href="https://www.atlanticcouncil.org/in-depth-research-reports/report/digital-sovereignty-europes-declaration-of-independence/">Digital sovereignty: Europe’s declaration of independence? - Atlantic Council</a></li>

</ul>
</details>

**Discussion**: Community comments express strong skepticism, with users comparing W Social to Truth Social and noting its lack of transparency, such as allowing multiple accounts despite claiming human verification. Some highlight Eurosky as a more credible alternative.

**Tags**: `#digital sovereignty`, `#social media`, `#European politics`, `#open source`, `#platform governance`

---

<a id="item-21"></a>
## [2.5-Hour Ice Water Drowning Survival with Severe Deficits](https://www.jacc.org/doi/10.1016/j.jaccas.2025.104885) ⭐️ 7.0/10

A 2.5-year-old boy survived 2.5 hours of submersion in ice water followed by 1.5 hours of CPR, with core temperature at 7°C, and was successfully rewarmed using ECMO, demonstrating the 'not dead until warm and dead' principle. This case pushes the boundaries of hypothermic resuscitation, showing that prolonged submersion can be survivable with aggressive rewarming, but highlights the severe neurological deficits that may result, informing future protocols and family counseling. At 6-month follow-up, the boy could give short commands, stand without support, ride a tricycle, eat soft foods, and relearn simple tasks, but had persistent peripheral neuromuscular weakness. The rewarming protocol delayed active rewarming until hospital arrival to avoid afterdrop.

hackernews · js2 · Jun 19, 03:50 · [Discussion](https://news.ycombinator.com/item?id=48594592)

**Background**: Hypothermia dramatically slows metabolism and reduces oxygen demand, allowing the brain to survive prolonged ischemia. The 'not dead until warm and dead' principle guides resuscitation: patients in hypothermic cardiac arrest should not be declared dead until rewarmed to near-normal temperature, as full recovery is possible even after hours of arrest. ECMO (extracorporeal membrane oxygenation) is often used for controlled rewarming in severe cases.

<details><summary>References</summary>
<ul>
<li><a href="https://www.jacc.org/doi/10.1016/j.jaccas.2025.104885">Ice Water Drowning Survival After 147-Minute Submersion and 7 °C Hypothermic Circulatory Arrest | JACC: Case Reports</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hypothermia">Hypothermia - Wikipedia</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC8744717/">Accidental Hypothermia: 2021 Update - PMC - NIH</a></li>

</ul>
</details>

**Discussion**: Commenters expressed amazement at the survival but noted the severe neurological outcome, with one calling it 'rough on everyone involved.' Others referenced similar cases, such as a Norwegian tourist who was 'dead' for 20 hours and recovered well, and diver Chris Lemons, highlighting the role of cold water and calmness.

**Tags**: `#medicine`, `#hypothermia`, `#resuscitation`, `#case report`, `#neurology`

---

<a id="item-22"></a>
## [Datasette Apps: Host sandboxed HTML apps inside Datasette](https://simonwillison.net/2026/Jun/18/datasette-apps/#atom-everything) ⭐️ 7.0/10

The datasette-apps plugin was launched, allowing users to host sandboxed HTML+JavaScript applications inside Datasette that can run read-only and write SQL queries against Datasette data. This plugin significantly expands Datasette's capabilities by enabling custom interactive applications directly within the platform, making it a more versatile tool for data exploration and visualization. Apps run in a tightly constrained iframe sandbox with CSP headers that prevent external HTTP requests, protecting against data exfiltration. Write queries require configured stored queries with appropriate permissions.

rss · Simon Willison · Jun 18, 23:58

**Background**: Datasette is an open-source tool for exploring and publishing data, providing a JSON API for custom frontends. The datasette-apps plugin builds on this by allowing those frontends to be hosted directly within Datasette, inspired by the author's work on Datasette Agent and vibe-coded HTML tools.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/18/datasette-apps/">Datasette Apps: Host custom HTML applications inside Datasette</a></li>
<li><a href="https://github.com/datasette/datasette-apps">GitHub - datasette/datasette-apps: Apps that live inside Datasette · GitHub</a></li>
<li><a href="https://datasette.io/blog/2026/datasette-apps">Host applications inside Datasette with Datasette Apps - Datasette Blog</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#plugin`, `#sql`, `#web-applications`, `#data-visualization`

---

<a id="item-23"></a>
## [Over-reliance on chatbots can diminish critical-thinking skills](https://www.theguardian.com/us-news/2026/jun/19/chatbots-critical-thinking-skills) ⭐️ 7.0/10

A new study from MIT finds that over-reliance on AI chatbots can reduce critical-thinking skills and the ability to discern misinformation. This research highlights a potential cognitive cost of using AI tools, with implications for education, media literacy, and how society integrates AI into daily life. The study suggests that while AI can help identify fake content, over-dependence on it may impair users' own judgment and critical evaluation of information.

rss · The Guardian World · Jun 19, 11:00

**Background**: Chatbots and AI tools are increasingly used to verify information online, but this reliance may come at the expense of developing personal critical-thinking skills. The MIT study adds to growing concerns about the unintended cognitive effects of AI assistance.

**Tags**: `#AI`, `#critical thinking`, `#misinformation`, `#education`, `#chatbots`

---

<a id="item-24"></a>
## [Datacenters Drive US Clean Energy Growth, Pose Climate Threat](https://www.theguardian.com/us-news/2026/jun/19/datacenters-us-clean-energy-growth-climate) ⭐️ 7.0/10

A Guardian article reports that datacenters, fueled by the AI boom, are paradoxically driving unprecedented growth in US clean energy industries like wind and solar, while still posing significant environmental challenges. This highlights a critical tension between AI infrastructure expansion and climate goals, as datacenters both accelerate clean energy deployment and increase overall energy consumption and environmental impacts. Datacenters are spurring development of batteries and solar for onsite power, but have little direct benefit for home rooftop solar. Observers warn that datacenters remain a 'climate nightmare' despite boosting clean energy.

rss · The Guardian World · Jun 19, 11:00

**Background**: Datacenters are large facilities that house computer servers and networking equipment, consuming vast amounts of electricity to power and cool AI models like ChatGPT. The AI boom has dramatically increased demand for datacenter capacity, leading to a surge in energy use and associated environmental concerns such as water scarcity and grid emissions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/us-news/2026/jun/19/datacenters-us-clean-energy-growth-climate">Datacenters driving US clean energy growth while still... | The Guardian</a></li>
<li><a href="https://news.cornell.edu/stories/2025/11/roadmap-shows-environmental-impact-ai-data-center-boom">‘Roadmap’ shows the environmental impact of AI data center boom | Cornell Chronicle</a></li>
<li><a href="https://news.mit.edu/2025/explained-generative-ai-environmental-impact-0117">Explained: Generative AI’s environmental impact | MIT News | Massachusetts Institute of Technology</a></li>

</ul>
</details>

**Tags**: `#datacenters`, `#clean energy`, `#AI`, `#climate`, `#sustainability`

---

<a id="item-25"></a>
## [Monitoring Claude Execution Layer with OpenTelemetry](https://www.reddit.com/r/netsec/comments/1u9ybfu/monitoring_the_claude_execution_layer_with/) ⭐️ 7.0/10

A Reddit post on r/netsec discusses monitoring the Claude execution layer using OpenTelemetry, bridging AI safety and observability. This approach enables real-time visibility into LLM execution, helping detect anomalous behavior and improve AI safety in production environments. The post likely covers how OpenTelemetry traces can capture tool calls, subprocess spawning, and state tracking within Claude Code's execution layer.

reddit · r/netsec · /u/TheAlphaBravo · Jun 19, 10:27

**Background**: OpenTelemetry is a vendor-neutral observability framework for collecting traces, metrics, and logs. Claude Code uses Claude models to understand code and execute tasks via tool calls and subprocesses. Monitoring this execution layer is critical for ensuring AI safety and reliability.

<details><summary>References</summary>
<ul>
<li><a href="https://opentelemetry.io/blog/2024/otel-generative-ai/">OpenTelemetry for Generative AI | OpenTelemetry</a></li>
<li><a href="https://code.claude.com/docs/en/how-claude-code-works">How Claude Code works - Claude Code Docs</a></li>
<li><a href="https://www.fiddler.ai/blog/opentelemetry-ai-observability-guide">OpenTelemetry AI Observability Guide | Fiddler AI Blog</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#OpenTelemetry`, `#observability`, `#LLM`, `#security`

---

<a id="item-26"></a>
## [uv 0.11.22 Released with Preview Features and Performance Boost](https://github.com/astral-sh/uv/releases/tag/0.11.22) ⭐️ 6.0/10

Astral released uv 0.11.22 on June 18, 2026, introducing preview feature configuration in uv.toml and pyproject.toml, SARIF output for uv audit, and a more deadlock-resistant concurrent hashmap in the resolver. This release enhances uv's flexibility for early adopters of preview features and improves reliability for complex dependency resolution, benefiting Python developers managing large projects. Notable changes include publishing wheels before sdists in uv publish, new TY and RUFF environment variables for uv format and uv check, and multiple bug fixes such as transparent Python upgrades and correct handling of workspace-exclusive dependency groups.

github · github-actions[bot] · Jun 18, 23:05

**Background**: uv is a fast Python package and project manager written in Rust, developed by Astral. It aims to replace tools like pip, pyenv, pipx, and virtualenv with a single, high-performance binary. Preview features allow users to opt into upcoming functionality before it becomes stable.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/astral-sh/uv">GitHub - astral-sh/uv: An extremely fast Python package and project manager, written in Rust. · GitHub</a></li>
<li><a href="https://docs.astral.sh/uv/concepts/configuration-files/">Configuration files | uv</a></li>
<li><a href="https://docs.oasis-open.org/sarif/sarif/v2.1.0/sarif-v2.1.0.html">Static Analysis Results Interchange Format ( SARIF ) Version 2.1.0 Plus...</a></li>

</ul>
</details>

**Tags**: `#python`, `#package-manager`, `#release`, `#uv`

---

<a id="item-27"></a>
## [Datasette-acl 0.6a0 expands to general resource sharing](https://simonwillison.net/2026/Jun/18/datasette-acl/#atom-everything) ⭐️ 6.0/10

Datasette-acl 0.6a0 has been released, expanding from table-only permissions toward a general resource-sharing system for multi-user Datasette instances. The release was primarily developed by Alex Garcia. This update is significant for users running multi-user Datasette instances, as it provides more finely grained control over access to various resources within Datasette. It enhances the plugin's capability to manage permissions beyond just tables, making it more versatile for collaborative data exploration. The plugin is under active development and currently supports configuring permissions for individual tables, including insert-row. This alpha release marks a step toward supporting permissions for other resource types.

rss · Simon Willison · Jun 18, 19:03

**Background**: Datasette is an open-source multi-tool for exploring and publishing data, often used for sharing datasets with others. The datasette-acl plugin provides access control lists for Datasette instances, allowing administrators to restrict who can view or modify data. Previously, it only supported table-level permissions; this release begins to generalize that system.

<details><summary>References</summary>
<ul>
<li><a href="https://pypi.org/project/datasette-acl/">datasette - acl · PyPI</a></li>
<li><a href="https://simonwillison.net/2026/Jun/18/datasette-acl/">Release: datasette - acl 0.6a0 | Simon Willison’s Weblog</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#access-control`, `#plugin`, `#permissions`

---

<a id="item-28"></a>
## [CDC Allocates $107M Emergency Ebola Funding](https://www.theguardian.com/us-news/2026/jun/18/cdc-emergency-ebola-funding) ⭐️ 6.0/10

The U.S. Centers for Disease Control and Prevention (CDC) announced it will allocate $107 million in emergency funding to support Ebola outbreak response in the Democratic Republic of the Congo (DRC) and Uganda, as the number of infections surpasses 1,000. This funding is critical to containing the third-largest Ebola outbreak on record, which has been declared a Public Health Emergency of International Concern by the WHO, and to preventing further spread during the FIFA World Cup when international travel is high. The outbreak is caused by the Bundibugyo virus, with 232 confirmed deaths in the DRC and two in Uganda as of mid-June 2026. The CDC's emergency funding will be drawn from its existing emergency response fund mechanisms.

rss · The Guardian World · Jun 18, 18:55

**Background**: Ebola is a severe, often fatal viral disease with symptoms including fever, vomiting, and bleeding. The CDC has established emergency funding mechanisms to rapidly deploy resources during public health crises, such as the 2014 West Africa epidemic. The current outbreak was declared a PHEIC on May 16, 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cdc.gov/readiness/php/funding/index.html">Public Health Crisis Response Funding | State and Local Readiness | CDC</a></li>
<li><a href="https://en.wikipedia.org/wiki/2026_Ebola_epidemic">2026 Ebola epidemic - Wikipedia</a></li>
<li><a href="https://www.who.int/emergencies/disease-outbreak-news/item/2026-DON602">Ebola disease caused by Bundibugyo virus, Democratic Republic of the Congo & Uganda</a></li>

</ul>
</details>

**Tags**: `#public health`, `#Ebola`, `#CDC`, `#funding`

---

<a id="item-29"></a>
## [Titan sub disaster report blames design flaws and groupthink](https://www.theguardian.com/world/2026/jun/17/titan-sub-design-flaws-company-groupthink-report) ⭐️ 6.0/10

Canadian safety officials released a report on June 17, 2026, concluding that design flaws in the carbon fiber hull and a culture of groupthink at OceanGate were central causes of the Titan submersible's catastrophic implosion in June 2023. This report provides a definitive official analysis of a high-profile disaster, highlighting how engineering failures and organizational culture can combine to produce catastrophic outcomes, with implications for safety regulations in deep-sea tourism and experimental submersible design. The 6.7-meter carbon fiber hull had manufacturing imperfections and was not adequately tested for its novel design; the company exhibited confirmation bias and failed to recognize the risks, leading to the implosion that killed all five passengers.

rss · The Guardian World · Jun 17, 18:24

**Background**: The Titan submersible, operated by OceanGate, imploded on June 18, 2023, during a dive to the Titanic wreck. The disaster prompted a massive search and raised questions about the safety of using carbon fiber for deep-sea pressure vessels. Groupthink, a phenomenon where the desire for consensus overrides critical evaluation, has been cited in other engineering disasters like the Challenger space shuttle explosion.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Titan_submersible_implosion">Titan submersible implosion - Wikipedia</a></li>
<li><a href="https://www.wkyt.com/2024/09/25/ntsb-engineer-says-carbon-fiber-hull-titan-submersible-showed-signs-flaws/">NTSB engineer says carbon fiber hull from Titan submersible ...</a></li>
<li><a href="https://www.foxnews.com/us/explosive-new-report-blames-oceangate-and-its-ceo-for-preventable-titan-sub-disaster">OceanGate Titan submersible tragedy 'preventable... | Fox News</a></li>

</ul>
</details>

**Tags**: `#engineering`, `#safety`, `#disaster`, `#submersible`, `#groupthink`

---

<a id="item-30"></a>
## [KPMG admits leaking Optus data, surveilling whistleblower](https://www.theguardian.com/australia-news/2026/jun/19/kpmg-scandal-optus-leak-as-whistleblower-claims-ntwnfb) ⭐️ 6.0/10

KPMG has admitted to leaking confidential Optus information to colleagues bidding for a Telstra audit contract and surveilling a whistleblower's laptop, as revealed in a parliamentary inquiry on June 19, 2026. This scandal underscores serious ethical failures in a major consulting firm, potentially eroding trust in corporate governance and data privacy practices, and may lead to stricter regulations for consultants handling sensitive client data. KPMG's chair Martin Sheppard publicly confirmed the leak for the first time, and the firm also surveilled the whistleblower's laptop, dismissing the individual as having 'workplace grievances'.

rss · The Guardian World · Jun 19, 07:25

**Background**: KPMG is one of the Big Four accounting firms, providing audit and consulting services globally. The leaked information involved Optus, an Australian telecom company that suffered a major data breach in 2022. The whistleblower alleged that KPMG staff shared unredacted confidential Optus data with the team pursuing a Telstra audit contract, a competitor telco.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/australia-news/2026/jun/19/kpmg-scandal-optus-leak-as-whistleblower-claims-ntwnfb">KPMG leaked confidential Optus information and surveilled whistleblower’s laptop, inquiry hears | Business | The Guardian</a></li>
<li><a href="https://www.theguardian.com/australia-news/2026/jun/10/kpmg-scandal-alleged-confidential-leaks-contracts-lost-leaders-quit-ntwnfb">KPMG loses contracts and leaders amid scandal over alleged confidential leaks. Here’s what you need to know | Consulting (Australia) | The Guardian</a></li>
<li><a href="https://en.wikipedia.org/wiki/2022_Optus_data_breach">2022 Optus data breach - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#data breach`, `#corporate ethics`, `#whistleblower`, `#privacy`, `#consulting`

---