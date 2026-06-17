---
layout: default
title: "Horizon Summary: 2026-06-17 (EN)"
date: 2026-06-17
lang: en
---

> From 226 items, 28 important content pieces were selected

---

1. [SpaceX to Acquire Cursor AI IDE for $60 Billion](#item-1) ⭐️ 9.0/10
2. [OpenBSD Fixes 27-Year-Old Remote Kernel Auth Bypass](#item-2) ⭐️ 9.0/10
3. [60% of US consumers turned off by 'AI' in brand messaging](#item-3) ⭐️ 8.0/10
4. [GrapheneOS Ported to Android 17, Official Releases Soon](#item-4) ⭐️ 8.0/10
5. [Local AI Models Now Viable, But Not Perfect](#item-5) ⭐️ 8.0/10
6. [Wolfram Language & Mathematica 15 Launch with Built-in AI](#item-6) ⭐️ 8.0/10
7. [Stop Using JWTs for Browser Sessions](#item-7) ⭐️ 8.0/10
8. [U.S. Science-Politics Compact Broken](#item-8) ⭐️ 8.0/10
9. [Datasette 1.0a34 Adds Insert, Edit, Delete in UI](#item-9) ⭐️ 8.0/10
10. [Export Controls on AI Models Harm US Cyber Defense](#item-10) ⭐️ 8.0/10
11. [US Government Discloses 3,611 AI Use Cases, Up 70%](#item-11) ⭐️ 8.0/10
12. [Flock Cameras Misused by Police for Stalking](#item-12) ⭐️ 8.0/10
13. [QoS Policies Used to Throttle EDR Traffic](#item-13) ⭐️ 8.0/10
14. [SearchLeak: One-Click Data Exfiltration via M365 Copilot](#item-14) ⭐️ 8.0/10
15. [DoS Vulnerability in AWS Encryption Provider via Empty Ciphertext](#item-15) ⭐️ 8.0/10
16. [GLM-5.2 Becomes Leading Open Weights Model on Artificial Analysis](#item-16) ⭐️ 7.0/10
17. [Bubbles: A Curated Aggregator for Independent Blogs](#item-17) ⭐️ 7.0/10
18. [IIS 8.3 Filename Vulnerability Explored](#item-18) ⭐️ 7.0/10
19. [Has AI Already Killed Self-Help Nonfiction?](#item-19) ⭐️ 7.0/10
20. [But Yak Shaving Is Fun (2019)](#item-20) ⭐️ 7.0/10
21. [Switching to Broadcom SFP+ Modules for 10GbE](#item-21) ⭐️ 7.0/10
22. [Georgi Gerganov Endorses Qwen3.6-27B for Local Coding](#item-22) ⭐️ 7.0/10
23. [Getting a CVE Without Shipping Slop](#item-23) ⭐️ 7.0/10
24. [Bash /dev/tcp: HTTP Requests Without curl](#item-24) ⭐️ 6.0/10
25. [Calvin and Hobbes and the Price of Integrity](#item-25) ⭐️ 6.0/10
26. [TNO Announces GPT-NL, a Sovereign Dutch Language Model](#item-26) ⭐️ 6.0/10
27. [Retired Developer Brent Simmons Polishes NetNewsWire](#item-27) ⭐️ 6.0/10
28. [Datasette-Agent 0.3a0 Adds Write SQL with User Approval](#item-28) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [SpaceX to Acquire Cursor AI IDE for $60 Billion](https://www.reuters.com/legal/transactional/spacex-buy-anysphere-60-billion-2026-06-16/) ⭐️ 9.0/10

SpaceX announced a $60 billion acquisition of Anysphere, the company behind the AI-powered code editor Cursor, marking one of the largest acquisitions of a developer tool by an aerospace company. This acquisition signals SpaceX's strategic pivot toward AI and space-based data centers, potentially reshaping the competitive landscape in both aerospace and AI developer tools. SpaceX had previously offered a $10 billion partnership option before committing to the full $60 billion acquisition, and the company sees an addressable AI market worth $26 trillion.

hackernews · itsmarcelg · Jun 16, 10:44 · [Discussion](https://news.ycombinator.com/item?id=48553224)

**Background**: Cursor is an AI-powered code editor that integrates large language models to assist developers in writing code faster. SpaceX, traditionally an aerospace manufacturer, recently completed a historic IPO and is now exploring space-based AI data centers to overcome terrestrial power and cooling limitations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reuters.com/legal/transactional/spacex-buy-anysphere-60-billion-2026-06-16/">SpaceX locks in $60 billion Cursor deal to close gap with rivals in AI coding race | Reuters</a></li>
<li><a href="https://247wallst.com/investing/2026/06/16/spacex-launches-start-of-acquisition-spree-with-cursor-after-historic-ipo/">SpaceX Launches Start of Acquisition Spree with Cursor After Historic IPO - 24/7 Wall St.</a></li>
<li><a href="https://en.wikipedia.org/wiki/SpaceX">SpaceX - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some question the valuation, comparing it to Minecraft's $2.5 billion acquisition, while others see strategic logic in SpaceX's pivot to AI. A user noted that Cursor's constant popups are annoying, preferring alternatives like Codex.

**Tags**: `#acquisition`, `#AI`, `#IDE`, `#SpaceX`, `#valuation`

---

<a id="item-2"></a>
## [OpenBSD Fixes 27-Year-Old Remote Kernel Auth Bypass](https://www.reddit.com/r/netsec/comments/1u7p4rj/27_years_in_the_dark_openbsd_fixes_ancient_remote/) ⭐️ 9.0/10

A remote authentication bypass vulnerability in OpenBSD's kernel PPP stack, present since 1999, was discovered and patched after 27 years. The flaw allows an attacker to bypass PAP authentication by sending zero-length name and password fields. This vulnerability affects all OpenBSD releases for 27 years, compromising the security of a system renowned for its focus on security. It allows remote attackers to intercept and read PPPoE traffic without credentials, posing a significant risk to users relying on PPP connections. The bug was introduced when the PPP code was imported from FreeBSD in July 1999. OpenBSD has released a patch; users are advised to update immediately.

reddit · r/netsec · /u/Emergency_Stable_923 · Jun 16, 20:26

**Background**: PPP (Point-to-Point Protocol) is a data link layer protocol used to establish direct connections between two network nodes. PAP (Password Authentication Protocol) is a simple authentication method used in PPP sessions, but it sends credentials in cleartext. The null-auth flaw allows an attacker to bypass PAP by providing empty credentials, effectively skipping authentication.

<details><summary>References</summary>
<ul>
<li><a href="https://cybersecuritytimes.com/openbsd-pap-authentication-vulnerability/">7-Year-Old OpenBSD Flaw Bypasses PAP Authentication</a></li>
<li><a href="https://cyberpress.org/7-year-old-openbsd-flaw/">7-Year-Old OpenBSD Flaw Enables Complete PAP Authentication ...</a></li>
<li><a href="https://gbhackers.com/7-year-old-openbsd-security-flaw/">7-Year-Old OpenBSD Security Flaw Exposes Systems ... - GBHackers</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed shock and admiration for the discovery, noting the bug's longevity and the thoroughness of the analysis. Some users discussed the implications for OpenBSD's reputation and the importance of code audits.

**Tags**: `#security`, `#OpenBSD`, `#vulnerability`, `#authentication bypass`, `#PPP`

---

<a id="item-3"></a>
## [60% of US consumers turned off by 'AI' in brand messaging](https://wpvip.com/future-of-the-web-2026/) ⭐️ 8.0/10

A survey found that 60% of US consumers are less likely to engage with brands that use 'AI' in their messaging, indicating a strong negative sentiment toward the term. This signals a growing consumer backlash against buzzword-driven marketing, which could force companies to rethink how they communicate AI features and focus on tangible benefits instead. The survey was conducted by WP Engine and published in their 'Future of the Web 2026' report; the negative sentiment is attributed to perceptions of cost-cutting, quality reduction, and lack of clear consumer benefit.

hackernews · thm · Jun 17, 12:11 · [Discussion](https://news.ycombinator.com/item?id=48569278)

**Background**: In recent years, companies have increasingly added 'AI' to product descriptions and marketing to signal innovation, often without clear user benefits. This has led to skepticism among consumers who feel the term is overused and associated with job cuts and inferior products.

**Discussion**: Commenters largely agree with the survey, noting that AI branding often prioritizes buzzwords over actual user value, and that consumers prefer features that work well without the label. Some highlight that previous ML features were accepted because they were invisible and beneficial.

**Tags**: `#AI`, `#consumer sentiment`, `#branding`, `#tech industry`, `#UX`

---

<a id="item-4"></a>
## [GrapheneOS Ported to Android 17, Official Releases Soon](https://discuss.grapheneos.org/d/36469-grapheneos-has-been-ported-to-android-17-and-official-releases-are-coming-soon) ⭐️ 8.0/10

GrapheneOS has been successfully ported to Android 17, with official releases expected soon. This marks a major milestone for the privacy-focused operating system. This update ensures that GrapheneOS users can benefit from the latest Android features and security patches, maintaining the OS's reputation as a leading privacy-focused mobile platform. It also demonstrates the project's continued commitment to supporting the latest Android versions. GrapheneOS is built on the Android Open Source Project (AOSP) and focuses on defense-in-depth improvements and attack surface reduction. The port to Android 17 includes hardening of low-level system components and improvements to application sandboxing and the permission model.

hackernews · Cider9986 · Jun 16, 20:34 · [Discussion](https://news.ycombinator.com/item?id=48561654)

**Background**: GrapheneOS is an open-source mobile operating system focused on security and privacy, available for Google Pixel and future Motorola devices. It is developed by the nonprofit GrapheneOS Foundation and has approximately 400K active users as of April 2026. The OS does not include Google services by default but allows installing them as sandboxed apps.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GrapheneOS">GrapheneOS</a></li>
<li><a href="https://grapheneos.org/">GrapheneOS: the private and secure mobile OS</a></li>
<li><a href="https://grokipedia.com/page/GrapheneOS">GrapheneOS</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about the port, with some sharing positive long-term experiences using GrapheneOS. However, concerns were raised about limited device support (mainly Pixel) and specific usability issues like app optimization delays after updates.

**Tags**: `#GrapheneOS`, `#Android`, `#privacy`, `#mobile OS`, `#security`

---

<a id="item-5"></a>
## [Local AI Models Now Viable, But Not Perfect](https://vickiboykis.com/2026/06/15/running-local-models-is-good-now/) ⭐️ 8.0/10

Running local AI models has become viable and competitive with cloud APIs, as highlighted by a high-scoring blog post and community discussion. However, challenges with speed, quantization, and model quality persist. This shift could reduce reliance on expensive cloud APIs, lowering costs and improving privacy for users. It also pressures cloud providers to justify their pricing as local models improve. Dense models like Qwen 27B are smart but slow, while MoE models like Gemma 26B are faster but error-prone. Quantization at 4-bit reduces memory needs but weakens tool-calling abilities.

hackernews · jfb · Jun 16, 14:36 · [Discussion](https://news.ycombinator.com/item?id=48555993)

**Background**: Quantization reduces model precision (e.g., from FP16 to INT4) to shrink memory footprint and speed up inference, often with minimal accuracy loss. Local AI inference requires balancing model size, speed, and quality, especially on consumer hardware like RTX 5080 with 16GB VRAM.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/model-quantization-concepts-methods-and-why-it-matters/">Model Quantization: Concepts, Methods, and Why It Matters</a></li>
<li><a href="https://www.youngju.dev/blog/ai/2026-03-17-llm-inference-optimization-guide.en">LLM Inference Optimization Complete Guide: KV Cache ...</a></li>
<li><a href="https://grokipedia.com/page/Quantization_machine_learning">Quantization (machine learning)</a></li>

</ul>
</details>

**Discussion**: Commenters report mixed experiences: some find local models like Qwen3.6-27B superior to cloud models like Claude Sonnet 4.6, while others highlight pain points with speed and quantization. There is optimism that local models will eventually displace traditional laptops and pressure cloud pricing.

**Tags**: `#local AI`, `#open-source models`, `#AI inference`, `#cost comparison`, `#model quantization`

---

<a id="item-6"></a>
## [Wolfram Language & Mathematica 15 Launch with Built-in AI](https://writings.stephenwolfram.com/2026/06/launching-version-15-of-wolfram-language-mathematica-built-in-useful-ai-lots-of-new-core-functionality/) ⭐️ 8.0/10

Wolfram Research has launched Version 15 of Wolfram Language and Mathematica, featuring a built-in AI assistant, extended computation-augmented generation, and the Wolfram Agent Tools framework, along with new core functionality in areas like time series, tabular data, and symbolic music. This release integrates AI directly into a major technical computing platform, potentially making advanced computation more accessible to users. However, the community's mixed reactions highlight ongoing tensions between Wolfram's closed ecosystem and the open-source alternatives like Python. The AI assistant is included as a basic feature, but community feedback indicates it underperforms compared to general models like Claude on Wolfram Language tasks, due to limited public training data. The release also improves notebook performance, handling gigabyte-sized files, and adds new functions for algebra, matrices, and PDE modeling.

hackernews · alok-g · Jun 16, 23:15 · [Discussion](https://news.ycombinator.com/item?id=48563609)

**Background**: Wolfram Language and Mathematica are proprietary, closed-source technical computing platforms widely used in academia and industry for symbolic computation, numerical analysis, and visualization. They are known for their powerful built-in algorithms and consistent design, but criticized for high licensing costs and limited interoperability with open-source ecosystems like Python.

<details><summary>References</summary>
<ul>
<li><a href="https://writings.stephenwolfram.com/2026/06/launching-version-15-of-wolfram-language-mathematica-built-in-useful-ai-lots-of-new-core-functionality/">Launching Version 15 of Wolfram Language & Mathematica: Built ...</a></li>
<li><a href="https://www.wolfram.com/language/new-in-15/">Latest Features in Wolfram Language 15</a></li>
<li><a href="https://mathematica.stackexchange.com/questions/4454/is-there-an-open-source-implementation-of-mathematica-the-language">Is there an open source implementation of Mathematica-the ...</a></li>

</ul>
</details>

**Discussion**: Community comments express appreciation for Mathematica's ease of use and power, but strongly criticize its walled-garden nature, high enterprise costs, and the poor performance of its AI assistant compared to external models. Some users suggest open-sourcing the language could unlock its potential, while others note the lack of public Wolfram code hinders AI training.

**Tags**: `#Wolfram Language`, `#Mathematica`, `#AI`, `#technical computing`, `#open source`

---

<a id="item-7"></a>
## [Stop Using JWTs for Browser Sessions](https://gist.github.com/samsch/0d1f3d3b4745d778f78b230cf6061452) ⭐️ 8.0/10

A widely shared gist argues that JSON Web Tokens (JWTs) should not be used for browser-based user sessions due to security and design flaws, while acknowledging their value in service-to-service communication. This critique challenges the widespread adoption of JWTs in web authentication, potentially steering developers toward more secure alternatives like session cookies for browser use cases. Key concerns include difficulty in revoking tokens, large token sizes impacting performance, and reliance on client-side storage, which is vulnerable to XSS attacks.

hackernews · dzonga · Jun 16, 16:49 · [Discussion](https://news.ycombinator.com/item?id=48558147)

**Background**: JWTs are self-contained tokens that encode claims and can be verified without a central database, making them popular for stateless authentication. However, for browser sessions, traditional session cookies with server-side storage offer built-in revocation and better security against common web vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://dev.to/dashbird/how-i-fixed-jwt-security-flaws-in-3-steps-264k">How I Fixed JWT Security Flaws in 3 Steps - DEV Community</a></li>
<li><a href="https://jwt.app/blog/jwt-vs-sessions/">JWT vs Session Cookies: Complete Comparison Guide</a></li>
<li><a href="https://www.backendstack.dev/post/jwt-security-pitfalls-backend-fix">JWT Security Pitfalls Every Backend Team Must Fix | BackendStack.dev</a></li>

</ul>
</details>

**Discussion**: The community is divided: some agree that JWTs are overused in browsers and highlight revocation and size issues, while others defend JWTs when properly implemented with short lifetimes and refresh tokens. A commenter notes that JWTs excel in service-to-service scenarios where independent verification is needed.

**Tags**: `#JWT`, `#authentication`, `#security`, `#web development`, `#session management`

---

<a id="item-8"></a>
## [U.S. Science-Politics Compact Broken](https://www.scientificamerican.com/article/americas-compact-between-science-and-politics-is-broken/) ⭐️ 8.0/10

A Scientific American article and community discussion highlight the breakdown of the U.S. science-politics compact, citing NASA funding failures and visa restrictions that cripple research. This breakdown threatens the future of U.S. scientific leadership, as unstable funding and restrictive policies drive away talent and halt critical projects. The article describes the cancellation of the AXIS X-ray telescope after nearly 10 years of work due to funding instability, and community comments note that visa restrictions prevent hiring foreign graduate students.

hackernews · presspot · Jun 17, 09:54 · [Discussion](https://news.ycombinator.com/item?id=48568058)

**Background**: The U.S. science-politics compact refers to the implicit agreement that the government funds scientific research for public benefit, with scientists providing objective expertise. Recent political polarization and funding volatility have eroded this trust.

**Discussion**: Commenters express frustration over systemic issues: grant funding drying up, visa restrictions blocking foreign talent, and partisan divides making science a political issue. Some argue that stable rules matter more than funding levels.

**Tags**: `#science policy`, `#research funding`, `#US politics`, `#academia`, `#NASA`

---

<a id="item-9"></a>
## [Datasette 1.0a34 Adds Insert, Edit, Delete in UI](https://simonwillison.net/2026/Jun/16/datasette/#atom-everything) ⭐️ 8.0/10

Datasette 1.0a34 introduces the ability to insert, edit, and delete rows directly through the Datasette user interface, a feature that was previously missing. This alpha release adds these operations on table pages and row pages. This update significantly enhances Datasette's usability by providing core data manipulation capabilities without requiring SQL knowledge or external tools. It bridges a long-standing gap, making Datasette more accessible for non-technical users and reducing reliance on plugins. The feature was inspired by Datasette Agent, an AI assistant that already supported SQL write operations, highlighting the inconsistency. The release notes confirm that edit and delete actions are also available on the row page.

rss · Simon Willison · Jun 16, 21:31

**Background**: Datasette is an open-source tool for exploring and publishing data, often used by data journalists and researchers. Previously, inserting, editing, or deleting rows required SQL queries or third-party plugins like datasette-write-ui. Datasette Agent, released in May 2026, is an AI assistant that integrates LLMs to interact with data conversationally.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/16/datasette/">Release: datasette 1.0a34 | Simon Willison’s Weblog</a></li>
<li><a href="https://agent.datasette.io/">Datasette Agent: an AI assistant for Datasette to help ...</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#release`, `#database`, `#open-source`, `#UI`

---

<a id="item-10"></a>
## [Export Controls on AI Models Harm US Cyber Defense](https://simonwillison.net/2026/Jun/16/fable-5-export-controls/#atom-everything) ⭐️ 8.0/10

US export controls on Anthropic's Claude Fable 5, triggered by a supposed jailbreak where the model fixed code with known vulnerabilities, are hindering critical security research. Cybersecurity expert Kate Moussouris confirmed that the banned behavior was actually a defensive security request, not a jailbreak. This policy undermines US cyber defense by preventing defenders from using AI to find, fix, and verify patches for security vulnerabilities. It sets a dangerous precedent where legitimate defensive uses of AI are conflated with offensive capabilities, weakening overall cybersecurity. The export control was triggered after researchers asked Fable 5 to review code for security issues and then to fix it, which the model did after a multistep manual process. Anthropic complied with the government directive and removed access to Fable 5 and Mythos 5 globally as of June 12, 2026.

rss · Simon Willison · Jun 16, 05:20

**Background**: Export controls on AI models aim to prevent adversaries from using advanced AI for cyber attacks. However, the same capabilities that could be used offensively are also essential for defensive security tasks like patching vulnerabilities. The incident highlights the challenge of regulating AI without hampering beneficial uses.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/fable-mythos-access">Statement on the US government directive to suspend access to Fable ...</a></li>

</ul>
</details>

**Discussion**: The article's comments are not provided, but the discussion on Simon Willison's blog likely echoes the author's criticism of the export controls as counterproductive, with security experts agreeing that fixing code is a defensive necessity.

**Tags**: `#AI safety`, `#export controls`, `#cybersecurity`, `#AI regulation`, `#open source`

---

<a id="item-11"></a>
## [US Government Discloses 3,611 AI Use Cases, Up 70%](https://www.schneier.com/blog/archives/2026/06/ai-use-by-the-us-government.html) ⭐️ 8.0/10

On April 14, the Trump administration quietly disclosed 3,611 active or planned AI use cases across the federal government, a 70% increase from the previous year's inventory. This massive expansion of AI in government raises serious concerns about automation of sensitive functions affecting civil liberties, public health, and safety, signaling a major shift in governance. The inventory includes plans to automate decisions on individual freedom, public health, and nuclear reactor safety, and was published by the Office of Management and Budget on GitHub.

rss · Schneier on Security · Jun 17, 11:04

**Background**: The disclosure is mandated by the Advancing American AI Act and OMB memoranda, building on earlier executive orders. The 2024 inventory had fewer cases, and the 70% jump reflects accelerating adoption across agencies.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ombegov/2025-Federal-Agency-AI-Use-Case-Inventory">ombegov/2025-Federal-Agency-AI-Use-Case-Inventory - GitHub</a></li>
<li><a href="https://github.com/ombegov/2024-Federal-AI-Use-Case-Inventory">ombegov/2024-Federal-AI-Use-Case-Inventory - GitHub</a></li>

</ul>
</details>

**Tags**: `#AI governance`, `#US government`, `#automation`, `#policy`, `#civil liberties`

---

<a id="item-12"></a>
## [Flock Cameras Misused by Police for Stalking](https://www.schneier.com/blog/archives/2026/06/flock-cameras-are-being-used-for-stalking.html) ⭐️ 8.0/10

Over a dozen documented cases across the US show police officers illegally using Flock surveillance cameras to stalk individuals. This highlights systemic abuse of surveillance technology by law enforcement, threatening privacy and civil liberties. Flock cameras use automated license plate recognition (ALPR) and are widely deployed; misuse often goes undetected until complaints are filed.

rss · Schneier on Security · Jun 16, 11:03

**Background**: Flock Safety is a company that provides ALPR cameras and surveillance systems to law enforcement. These cameras capture license plate data and are intended to help solve crimes, but have been abused for personal stalking by officers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.schneier.com/blog/archives/2026/06/flock-cameras-are-being-used-for-stalking.html">Flock Cameras Are Being Used for Stalking - Schneier on Security</a></li>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.cnet.com/home/security/when-flock-comes-to-town-why-cities-are-axing-the-controversial-surveillance-technology/">When Flock Surveillance Comes to Your Town: Everything ... - CNET</a></li>

</ul>
</details>

**Tags**: `#surveillance`, `#privacy`, `#law enforcement`, `#security`, `#civil liberties`

---

<a id="item-13"></a>
## [QoS Policies Used to Throttle EDR Traffic](https://www.reddit.com/r/netsec/comments/1u85hnb/qos_policies_to_restrict_edr_traffic_and/) ⭐️ 8.0/10

A new attack technique, dubbed EDRChoker, abuses native Windows QoS policies (New-NetQosPolicy) to throttle EDR telemetry traffic to near zero, effectively blinding security tools. This technique provides adversaries with a stealthy method to evade EDR detection without requiring administrative privileges or kernel access, potentially undermining endpoint security across enterprises. The attack leverages legitimate QoS policies to limit bandwidth for EDR processes, and detection strategies include monitoring for unexpected QoS policy creation or changes in network traffic patterns.

reddit · r/netsec · /u/netbiosX · Jun 17, 09:36

**Background**: Quality of Service (QoS) policies are a native Windows feature used to manage network bandwidth for applications. Endpoint Detection and Response (EDR) systems rely on continuous telemetry data to detect threats; throttling this traffic can blind the EDR. The technique was demonstrated in a proof-of-concept called EDRChoker.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lindensec.com/post/choking-defender-with-native-windows-qos-policies">Choking Defender With Native Windows QoS Policies (EDRChoker)</a></li>
<li><a href="https://github.com/tsale/EDR-Telemetry">GitHub - tsale/ EDR - Telemetry : This project aims to compare and...</a></li>
<li><a href="https://harfanglab.io/blog/product/securing-information-systems-edr-protects-against-attacks/">Cybersecurity: how EDR protects itself against attacks - HarfangLab</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion highlights that while this is a clever evasion technique, it requires the attacker to already have code execution on the system. Commenters suggest monitoring for new QoS policies and using network segmentation as mitigations.

**Tags**: `#EDR`, `#QoS`, `#attack`, `#detection`, `#security`

---

<a id="item-14"></a>
## [SearchLeak: One-Click Data Exfiltration via M365 Copilot](https://www.reddit.com/r/netsec/comments/1u6gzs7/searchleak_how_we_turned_m365_copilot_into_a/) ⭐️ 8.0/10

Researchers disclosed a vulnerability chain in Microsoft 365 Copilot, dubbed SearchLeak (CVE-2026-42824), that allows attackers to exfiltrate emails and documents with a single crafted link. The attack leverages indirect prompt injection to manipulate Copilot's search functionality into sending sensitive data to an attacker-controlled server. This vulnerability demonstrates that AI-powered enterprise tools like M365 Copilot can be weaponized for data theft with minimal user interaction, posing a severe risk to organizations relying on such assistants. It highlights the urgent need for robust security measures in AI-integrated productivity suites. The attack chain involves three steps: crafting a malicious link that triggers a Copilot search, injecting a prompt that exfiltrates data via a search query, and sending the stolen data to an external server. The vulnerability was responsibly disclosed to Microsoft and has been patched.

reddit · r/netsec · /u/lohacker0 · Jun 15, 13:42

**Background**: Microsoft 365 Copilot is an AI assistant integrated into Office apps that can access user emails, documents, and other data to answer queries. Indirect prompt injection is a technique where an attacker embeds malicious instructions in content (e.g., an email) that the AI processes, causing it to perform unintended actions. SearchLeak exploits this by embedding exfiltration commands in a crafted link's preview or search results.

<details><summary>References</summary>
<ul>
<li><a href="https://www.varonis.com/blog/searchleak">SearchLeak : How We Turned M365 Copilot Into a One-Click Data...</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/new-attack-turned-microsoft-365-copilot-into-1-click-data-theft-tool/">New attack turned Microsoft 365 Copilot into 1-click data theft tool</a></li>
<li><a href="https://dailysecurityreview.com/resources/cve-2026-42824-m365-copilot-searchleak-enables-1-click-email-theft/">CVE-2026-42824: M 365 Copilot SearchLeak Enables 1-Click Email...</a></li>

</ul>
</details>

**Discussion**: The netsec community discussion is substantive, with technical analysis and mitigation strategies. Commenters emphasize the importance of restricting Copilot's data access and implementing strict input validation. Some debate the severity, noting that the attack requires the victim to click a link, but agree it's a significant finding.

**Tags**: `#security`, `#M365 Copilot`, `#data exfiltration`, `#vulnerability`, `#enterprise`

---

<a id="item-15"></a>
## [DoS Vulnerability in AWS Encryption Provider via Empty Ciphertext](https://www.reddit.com/r/netsec/comments/1u6smzb/emptyciphertext_panic_in_awsencryptionprovider/) ⭐️ 8.0/10

Researchers discovered a denial-of-service vulnerability in aws-encryption-provider where an empty ciphertext field triggers an unrecovered Go panic, crashing the plugin process. This vulnerability affects Kubernetes clusters using the AWS KMS provider for encryption, potentially allowing attackers to crash the plugin and disrupt secret management, leading to denial of service. The issue was found via fuzzing and affects both v1 and v2 of the Kubernetes KMS provider protocol. The full writeup includes root-cause analysis, crash path details, and a disclosure timeline coordinated with AWS.

reddit · r/netsec · /u/Sandwich_1337 · Jun 15, 20:38

**Background**: aws-encryption-provider is a gRPC server that runs on Kubernetes control-plane nodes, proxying Encrypt/Decrypt calls to AWS KMS. It is used by kube-apiserver when reading or writing Secrets. A Go panic in this plugin can cause the entire plugin process to crash, leading to denial of service.

<details><summary>References</summary>
<ul>
<li><a href="https://syntetisk.tech/blog/posts/empty-ciphertext-panic-in-aws-encryption-provider-cvd-with-aws/">Empty-ciphertext panic in aws -encryption- provider (CVD with AWS )</a></li>

</ul>
</details>

**Discussion**: The r/netsec discussion validates the finding, with commenters noting the importance of fuzzing in security research and the responsible disclosure process. Some discuss potential mitigations like input validation.

**Tags**: `#security`, `#kubernetes`, `#aws`, `#vulnerability`, `#fuzzing`

---

<a id="item-16"></a>
## [GLM-5.2 Becomes Leading Open Weights Model on Artificial Analysis](https://artificialanalysis.ai/articles/glm-5-2-is-the-new-leading-open-weights-model-on-the-artificial-analysis-intelligence-index) ⭐️ 7.0/10

GLM-5.2, released by Z.AI, has achieved the highest score among open weights models on the Artificial Analysis Intelligence Index, approaching frontier performance levels. This marks a significant milestone for open-source AI, as GLM-5.2 narrows the gap with proprietary frontier models like Claude Opus and GPT-5.5, potentially democratizing access to high-quality reasoning capabilities. GLM-5.2 supports a 1M-token context and introduces effort level control to balance capability and cost, but community reports indicate high reasoning token usage, with one user noting 45k tokens spent on a simple coding task.

hackernews · himata4113 · Jun 17, 09:12 · [Discussion](https://news.ycombinator.com/item?id=48567759)

**Background**: Artificial Analysis is an independent platform that benchmarks AI models across quality, price, and speed. Open weights models allow public access and modification, unlike proprietary models. GLM-5.2 is the latest in the GLM series, designed for long-horizon tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://artificialanalysis.ai/">AI Model & API Providers Analysis | Artificial Analysis</a></li>
<li><a href="https://github.com/zai-org/GLM-5">GitHub - zai-org/GLM-5: GLM-5: From Vibe Coding to Agentic ...</a></li>
<li><a href="https://z.ai/blog/glm-5.2">GLM-5.2: Built for Long-Horizon Tasks - z.ai</a></li>

</ul>
</details>

**Discussion**: Community comments highlight GLM-5.2's strong performance but express concerns about reasoning efficiency and cost. Some users note that while the model approaches frontier quality, its high token consumption makes it less practical for certain tasks, and comparisons with GPT-5.5 and Claude Opus show mixed results on cost-effectiveness.

**Tags**: `#LLM`, `#open weights`, `#benchmark`, `#AI models`, `#reasoning`

---

<a id="item-17"></a>
## [Bubbles: A Curated Aggregator for Independent Blogs](https://bubbles.town/) ⭐️ 7.0/10

Bubbles (bubbles.town) launched as a Hacker News-like aggregator that ranks independent blog posts by community votes, offering a curated feed to counter social media doomscrolling. It provides a humane, diverse alternative to mainstream social media and traditional aggregators, helping revive the indie blogosphere and giving independent writers a discovery platform. Users can vote on posts, and the platform also offers a 'Briefings' feature for a more curated, less overwhelming experience. Account creation currently requires a Mastodon account, though some users request email-based signup.

hackernews · headalgorithm · Jun 17, 07:49 · [Discussion](https://news.ycombinator.com/item?id=48567155)

**Background**: The IndieWeb movement advocates for personal websites and decentralized communication as an alternative to corporate social media. Bubbles fits into this movement by aggregating content from independent blogs and letting the community surface the best posts, similar to how Hacker News works for tech news.

<details><summary>References</summary>
<ul>
<li><a href="https://bubbles.town/">Bubbles</a></li>
<li><a href="https://bubbles.town/about">About — Bubbles</a></li>
<li><a href="https://moddedbear.com/bubbles-is-the-cool-new-way-to-find-blogs/">Bubbles Is the Cool New Way to Find Blogs - moddedbear.com</a></li>

</ul>
</details>

**Discussion**: Commenters praised Bubbles as a refreshing, humane alternative to doomscrolling, with one user noting the indie blogosphere is 'coming to life.' Some suggested UX improvements like opening links in the same tab and offering email-based account creation to avoid social media.

**Tags**: `#indie web`, `#content aggregation`, `#blogging`, `#community`, `#Hacker News`

---

<a id="item-18"></a>
## [IIS 8.3 Filename Vulnerability Explored](https://mll.sh/humiliating-iis-servers-for-fun-and-jail-time/) ⭐️ 7.0/10

A technical article details how attackers can exploit the legacy 8.3 short filename behavior in Microsoft IIS to enumerate files and directories, using tilde (~) requests. This vulnerability, though known for over a decade, remains unpatched by Microsoft, making it a persistent risk for IIS servers still exposing 8.3 names, especially in legacy environments. The 8.3 short name generation is enabled by default on the C: drive in Windows, and the IIS default document root is C:\Inetpub, making many servers vulnerable out of the box.

hackernews · denysvitali · Jun 16, 22:53 · [Discussion](https://news.ycombinator.com/item?id=48563394)

**Background**: 8.3 filenames are legacy short names (e.g., secret~1.txt) from the MS-DOS era, maintained for compatibility. The IIS tilde vulnerability allows remote attackers to infer file existence by observing response differences when requesting paths with a tilde. Microsoft considers this a feature, not a bug, and recommends disabling 8.3 names via registry to mitigate.

<details><summary>References</summary>
<ul>
<li><a href="https://infosecwriteups.com/tilde-games-exploiting-8-3-shortnames-on-iis-servers-6f232071e01f">Tilde Games: Exploiting 8.3 Shortnames on IIS Servers</a></li>
<li><a href="https://github.com/irsdl/IIS-ShortName-Scanner">GitHub - irsdl/IIS-ShortName-Scanner: latest version of ... NVD - CVE-2025-46294 CVE-2025-46294 - Microsoft IIS Shortname Information ... Vulnerability Background | irsdl/IIS-ShortName-Scanner | DeepWiki security - Fixing the IIS tilde vulnerability - Server Fault</a></li>
<li><a href="https://learn.microsoft.com/en-us/answers/questions/1191228/how-to-fix-iis-short-filename-vulnerability-in-web">How to Fix IIS Short Filename Vulnerability in Web Services ...</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some operators use IIS honeypots to waste attackers' time, while others reminisce about the prevalence of IIS scanners in the past. A user questions whether anyone still uses IIS, reflecting the platform's declining relevance.

**Tags**: `#security`, `#IIS`, `#windows`, `#vulnerability`, `#honeypot`

---

<a id="item-19"></a>
## [Has AI Already Killed Self-Help Nonfiction?](https://tim.blog/2026/06/12/has-ai-already-killed-nonfiction/) ⭐️ 7.0/10

A blog post by Tim Ferriss and a Hacker News discussion explore whether AI and LLMs are making self-help nonfiction books obsolete by providing filler-free, interactive alternatives. This debate raises fundamental questions about the value of content in the age of AI, potentially reshaping the publishing industry and how people consume knowledge. The post and comments highlight that LLMs can extract substance from self-help books without filler, and that the self-help industry may be seen as a network of product-selling individuals.

hackernews · imakwana · Jun 16, 17:11 · [Discussion](https://news.ycombinator.com/item?id=48558489)

**Background**: Self-help nonfiction books often contain repetitive anecdotes and padding to reach a marketable length. LLMs like ChatGPT can summarize key points instantly and offer interactive, personalized advice, challenging the traditional book format.

**Discussion**: Commenters are divided: some argue self-help is dying due to its commercial nature, while others caution against relying on AI for advice in unfamiliar fields due to sycophancy and superficial explanations. One user noted the irony that Ferriss's post itself reads like LLM-generated text.

**Tags**: `#AI`, `#publishing`, `#self-help`, `#LLMs`, `#content creation`

---

<a id="item-20"></a>
## [But Yak Shaving Is Fun (2019)](https://parksb.github.io/en/article/32.html) ⭐️ 7.0/10

A 2019 article defends yak shaving as a fun and productive engineering practice that fosters creativity and deep understanding, challenging the common negative view of it as mere procrastination. This perspective matters because it validates the exploratory side of software engineering, encouraging developers to embrace detours that can lead to innovative solutions and deeper system knowledge, especially as AI reduces the cost of such exploration. The article is from 2019 and scored 7.0/10 on Hacker News with 274 points and 84 comments, indicating strong resonance. Community comments highlight personal experiences and note that AI tools now make yak shaving less costly.

hackernews · parksb · Jun 16, 14:26 · [Discussion](https://news.ycombinator.com/item?id=48555838)

**Background**: Yak shaving is a programming term for the seemingly endless series of small, unrelated tasks that must be completed before the main goal can be achieved. It is often viewed negatively as a distraction or procrastination, but some argue it can lead to valuable learning and creative breakthroughs.

<details><summary>References</summary>
<ul>
<li><a href="https://softwareengineering.stackexchange.com/questions/388092/what-exactly-is-yak-shaving">agile - What exactly is Yak Shaving? - Software Engineering ...</a></li>
<li><a href="https://www.techtarget.com/whatis/definition/yak-shaving">What is yak shaving? - TechTarget Yak Shaving Defined - I'll get that done, as soon as I shave ... To Yak Shave or Not: The Art of Procrastination in Software ... What is yak shaving? - DevTerms Yak Shaving - DevX</a></li>
<li><a href="https://www.graphapp.ai/engineering-glossary/devops/yak-shaving">Yak Shaving: Definition, Examples, and Applications | Graph AI</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree with the article, sharing personal yak shaving stories and noting that AI has reduced the cost of such exploration. One commenter coined the term 'Thomasing' for overly detailed explanations that lose the asker's interest, adding a humorous counterpoint.

**Tags**: `#software engineering`, `#productivity`, `#developer culture`, `#yak shaving`

---

<a id="item-21"></a>
## [Switching to Broadcom SFP+ Modules for 10GbE](https://www.gilesthomas.com/2026/06/10g-ethernet-switching-to-broadcom-sfp-plus) ⭐️ 7.0/10

A detailed technical account describes the process of switching to Broadcom SFP+ modules for 10 Gigabit Ethernet, highlighting practical challenges such as heat dissipation and compatibility issues. This matters because 10GbE is increasingly adopted in home and small business networks, and understanding real-world module behavior helps users avoid performance pitfalls and make informed cabling decisions. The article notes that Broadcom SFP+ modules can run hot, especially in cramped spaces, and may require careful selection of DAC or fiber cabling to mitigate heat. Compatibility with different switches also varies.

hackernews · gpjt · Jun 16, 17:48 · [Discussion](https://news.ycombinator.com/item?id=48559083)

**Background**: SFP+ is an enhanced version of the SFP form factor supporting data rates up to 10 Gbps. 10GbE connections can be made using fiber optic transceivers, Direct Attach Copper (DAC) cables, or copper twisted-pair modules, each with different power consumption and heat characteristics.

<details><summary>References</summary>
<ul>
<li><a href="https://www.broadcom.com/products/fiber-optic-modules-components/networking/optical-transceivers/sfpplus">“SFP Plus”, or SFP+ , are speed enhanced variations of the...</a></li>
<li><a href="https://lab53.uk/10g-sfp-overheating-media-converter/">SFP+ overheating: why I ended up using media converters | Lab53</a></li>
<li><a href="https://www.10gtek.com/dac">10Gtek Direct Attach Copper Cable (DAC) 10G Direct Attach Cable - Ubiquiti Store United States SFP+ DAC CABLE - AXC761 - NETGEAR Amazon.com: H!Fiber SFP+ Cable, 10G SFP+ DAC, 0.5M (1.64ft ... SFP+, XFP, QSFP+, DAC Twinax Cable 10Gtek Transceivers Co., Ltd How Long Can A 10G SFP+ DAC Cable Be? | Fibrecross</a></li>

</ul>
</details>

**Discussion**: Commenters recommend fiber for in-wall cabling beyond 2.5 Gbps due to lower heat and future-proofing, while DAC cables are praised for short distances (under 5-7 m) as they eliminate conversion heat. One user mentions the UniFi SFP Wizard for reprogramming modules, and another notes that many DACs do not report temperature or voltage.

**Tags**: `#networking`, `#10GbE`, `#SFP+`, `#hardware`, `#ethernet`

---

<a id="item-22"></a>
## [Georgi Gerganov Endorses Qwen3.6-27B for Local Coding](https://simonwillison.net/2026/Jun/16/georgi-gerganov/#atom-everything) ⭐️ 7.0/10

Georgi Gerganov, creator of llama.cpp, publicly endorsed the Qwen3.6-27B model for local coding tasks, stating he uses it almost daily on his M2 Ultra and RTX 5090 systems with a lightweight pi agent harness. This endorsement from a key figure in the local LLM ecosystem validates Qwen3.6-27B as a practical, high-performance model for developers, potentially accelerating its adoption for AI-assisted coding on consumer hardware. Gerganov uses the model with a stripped-down pi agent command (`pi -nc --offline`) and a short system prompt to align with his coding style, handling small mundane tasks for the ggml-org repository.

rss · Simon Willison · Jun 16, 16:04

**Background**: Qwen3.6-27B is a dense 27-billion-parameter open-weight model released by Alibaba's Qwen team in April 2026, outperforming larger models on coding benchmarks. It is designed to run efficiently on local hardware. The pi agent is a minimal AI agent harness that allows customization and offline use.

<details><summary>References</summary>
<ul>
<li><a href="https://rits.shanghai.nyu.edu/ai/qwen3-6-27b-a-dense-27b-model-that-beats-a-397b-moe-on-coding">Qwen 3 . 6 - 27 B : A Dense 27 B Model That Beats a 397B MoE on Coding</a></li>
<li><a href="https://www.openmodels.run/models/qwen3-6-27b">Qwen 3 . 6 27 B - OpenModels</a></li>
<li><a href="https://pi.dev/">Pi Coding Agent</a></li>

</ul>
</details>

**Tags**: `#local LLM`, `#coding assistant`, `#Qwen`, `#llama.cpp`, `#AI tools`

---

<a id="item-23"></a>
## [Getting a CVE Without Shipping Slop](https://www.reddit.com/r/netsec/comments/1u7za1g/getting_a_cve_without_shipping_slop/) ⭐️ 7.0/10

A Reddit post provides a practical guide on how security researchers can obtain CVE identifiers for vulnerabilities they discover without having to release or ship vulnerable software. This guidance helps security researchers responsibly disclose vulnerabilities while avoiding the ethical and legal risks of releasing exploitable code, promoting safer security research practices. The post likely covers methods such as reporting to vendors, using bug bounty programs, or working with CVE Numbering Authorities (CNAs) to assign CVEs without publishing proof-of-concept code.

reddit · r/netsec · /u/Mindless-Study1898 · Jun 17, 03:45

**Background**: CVE stands for Common Vulnerabilities and Exposures, a system that provides unique identifiers for publicly known security flaws. Responsible disclosure is a process where researchers report vulnerabilities to vendors privately before public disclosure, allowing time for fixes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Common_Vulnerabilities_and_Exposures">Common Vulnerabilities and Exposures - Wikipedia</a></li>
<li><a href="https://www.redhat.com/en/topics/security/what-is-cve">What is a CVE ?</a></li>
<li><a href="https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html">Vulnerability Disclosure - OWASP Cheat Sheet Series</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion likely includes appreciation for the practical advice, debates on the ethics of releasing proof-of-concept code, and additional tips from experienced researchers.

**Tags**: `#CVE`, `#security research`, `#vulnerability disclosure`, `#infosec`

---

<a id="item-24"></a>
## [Bash /dev/tcp: HTTP Requests Without curl](https://mareksuppa.com/til/bash-dev-tcp-http-without-curl/) ⭐️ 6.0/10

A blog post highlights that Bash's built-in /dev/tcp pseudo-device can be used to make raw HTTP requests without external tools like curl or wget. This trick is useful for quick debugging or scripting in environments where curl is unavailable, but it is not portable across shells like dash or zsh. The feature is Bash-specific and requires the script to be run with bash, not sh. Zsh has its own zsh/net/tcp module for similar functionality.

hackernews · mrshu · Jun 16, 16:40 · [Discussion](https://news.ycombinator.com/item?id=48558018)

**Background**: Bash's /dev/tcp is a pseudo-device that allows opening TCP connections via file descriptors. It is compiled into Bash when built with the --enable-net-redirections option. This feature is not part of POSIX and is not available in other shells like dash or zsh.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linuxjournal.com/content/more-using-bashs-built-devtcp-file-tcpip">More on Using Bash 's Built-in / dev / tcp File (TCP/IP) | Linux Journal</a></li>
<li><a href="https://linuxize.com/post/check-open-ports-linux/">Check Open Ports in Linux: nmap, netcat, and Bash | Linuxize</a></li>
<li><a href="https://rednafi.com/misc/http-requests-via-dev-tcp/">HTTP requests via / dev / tcp | Redowan's Reflections</a></li>

</ul>
</details>

**Discussion**: Commenters note that this trick is reminiscent of Plan 9's /net filesystem and telnetting to ports in the late 90s. Some emphasize portability issues: dash and zsh lack /dev/tcp, and zsh has its own modules. A user also points out that Bash only opens TCP sockets; speaking HTTP is a separate protocol layer.

**Tags**: `#bash`, `#http`, `#networking`, `#shell-tricks`

---

<a id="item-25"></a>
## [Calvin and Hobbes and the Price of Integrity](https://therepublicofletters.substack.com/p/calvin-and-hobbes-and-the-price-of) ⭐️ 6.0/10

An essay explores Bill Watterson's decision to never license Calvin and Hobbes merchandise, contrasting it with other cartoonists who commercialized their work. This reflection highlights the tension between artistic integrity and commercial success, offering a case study that resonates with creators and audiences in any medium. Bill Watterson stopped drawing Calvin and Hobbes in 1995 after a 10-year run, refusing to license characters for toys, TV, or movies despite immense popularity.

hackernews · pseudolus · Jun 16, 15:44 · [Discussion](https://news.ycombinator.com/item?id=48557079)

**Background**: Calvin and Hobbes is a syndicated comic strip that ran from 1985 to 1995, known for its humor, philosophy, and imaginative artwork. Bill Watterson is widely admired for his uncompromising stance on licensing, which preserved the strip's purity but also limited his financial gain.

**Discussion**: Commenters express admiration for Watterson's integrity, with some noting they would likely have taken the money if offered. Others share personal anecdotes about how the strip influenced their parenting or worldview.

**Tags**: `#art`, `#integrity`, `#comics`, `#culture`

---

<a id="item-26"></a>
## [TNO Announces GPT-NL, a Sovereign Dutch Language Model](https://www.tno.nl/en/digital/artificial-intelligence/gpt-nl/) ⭐️ 6.0/10

TNO, together with SURF and the Netherlands Forensic Institute, announced GPT-NL, a sovereign language model for the Netherlands, with €13.5 million in funding. GPT-NL aims to reduce European dependence on non-European AI providers, ensuring data sovereignty and alignment with European laws and values. The model is trained exclusively on legally obtained Dutch documents and is developed within Europe, giving full control over data and development.

hackernews · root-parent · Jun 16, 17:54 · [Discussion](https://news.ycombinator.com/item?id=48559188)

**Background**: Sovereign AI refers to national strategies for independent AI infrastructure and data control. Many European countries are pursuing similar efforts, such as Sweden's GPT-SW3, to reduce reliance on US and Chinese technologies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tno.nl/en/digital/artificial-intelligence/gpt-nl/">GPT‑NL: a sovereign language model for the Netherlands - tno.nl</a></li>
<li><a href="https://www.tno.nl/nl/digitaal/artificiele-intelligentie/gpt-nl/">GPT-NL: een soeverein taalmodel voor Nederland | TNO</a></li>
<li><a href="https://gpt-nl.nl/">GPT-NL: Een verantwoord taalmodel voor Nederland - GPT-NL</a></li>

</ul>
</details>

**Discussion**: Comments are polarized: some question the value of sovereign models, suggesting building on existing baselines like Qwen/Kimi, while others defend the importance of national language models and European autonomy.

**Tags**: `#language model`, `#sovereign AI`, `#Netherlands`, `#European AI`, `#GPT`

---

<a id="item-27"></a>
## [Retired Developer Brent Simmons Polishes NetNewsWire](https://simonwillison.net/2026/Jun/17/netnewswire-status/#atom-everything) ⭐️ 6.0/10

Brent Simmons, who retired in June 2025, has turned his retirement project into making the open-source RSS reader NetNewsWire exceptionally good, free from commercial pressure. This story highlights how open-source software can thrive when a skilled developer dedicates time without commercial constraints, potentially inspiring others to contribute to projects they care about. NetNewsWire is a free and open-source RSS reader for Mac, iPhone, and iPad, first released in 2002 and open-sourced in 2018. It supports syncing via iCloud, Feedbin, Feedly, and other services, and includes features like Safari extension, reader view, and AppleScript support.

rss · Simon Willison · Jun 17, 03:36

**Background**: RSS (Really Simple Syndication) is a web feed format that allows users to subscribe to updates from blogs and news sites. NetNewsWire is one of the oldest and most respected RSS readers, known for its native macOS and iOS experience and strong privacy focus.

<details><summary>References</summary>
<ul>
<li><a href="https://netnewswire.com/">NetNewsWire: Free and Open Source RSS Reader for Mac, iPhone ...</a></li>
<li><a href="https://sixcolors.com/link/2025/05/brent-simmons-is-retiring/">Brent Simmons is retiring – Six Colors</a></li>
<li><a href="https://github.com/NetNewsWire-RSS-Reader">NetNewsWire RSS Reader - GitHub</a></li>

</ul>
</details>

**Tags**: `#open-source`, `#rss`, `#software-development`, `#retirement-project`

---

<a id="item-28"></a>
## [Datasette-Agent 0.3a0 Adds Write SQL with User Approval](https://simonwillison.net/2026/Jun/15/datasette-agent/#atom-everything) ⭐️ 6.0/10

Datasette-agent 0.3a0 introduces an execute_write_sql tool that requests user approval before writing to a database, respecting user permissions. The release also enhances the CLI chat mode to support approvals and adds --unsafe mode for auto-approval. This update makes Datasette Agent safer and more interactive for database modifications, enabling users to confidently delegate write operations to an AI assistant. It bridges the gap between AI convenience and data integrity, which is crucial for production use. The execute_write_sql tool shows a confirmation dialog with the SQL statements, parameters, and required permissions before execution. The --unsafe flag combined with --root allows fully automated write operations, while --yes only auto-approves without root privileges.

rss · Simon Willison · Jun 15, 17:19

**Background**: Datasette Agent is an LLM-powered assistant for Datasette, an open-source tool for exploring and publishing data. It supports hundreds of tool-calling models and allows users to interact with databases via natural language. The agent previously had read-only capabilities; this release adds safe write functionality.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/15/datasette-agent/">Release: datasette-agent 0.3a0 - simonwillison.net</a></li>
<li><a href="https://agent.datasette.io/">Datasette Agent: an AI assistant for Datasette to help ...</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#sql`, `#agent`, `#release`

---