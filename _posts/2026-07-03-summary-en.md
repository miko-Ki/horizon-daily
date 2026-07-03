---
layout: default
title: "Horizon Summary: 2026-07-03 (EN)"
date: 2026-07-03
lang: en
---

> From 221 items, 30 important content pieces were selected

---

1. [FBI Seizes NetNut Proxy Platform, Popa Botnet](#item-1) ⭐️ 9.0/10
2. [Virginia Bans Sale of Geolocation Data](#item-2) ⭐️ 8.0/10
3. [crustc: Entire rustc Compiler Translated to C](#item-3) ⭐️ 8.0/10
4. [Podman v6.0.0 Released with Networking Improvements](#item-4) ⭐️ 8.0/10
5. [PeerTube: Decentralized, Federated Video Platform](#item-5) ⭐️ 8.0/10
6. [EFF Alleges X's Grok AI Generated CSAM, Urges FTC Action](#item-6) ⭐️ 8.0/10
7. [Postgres Transactions as Distributed Systems Superpower](#item-7) ⭐️ 8.0/10
8. [Immich 3.0 Sparks Debate Over Missing End-to-End Encryption](#item-8) ⭐️ 8.0/10
9. [Understand to Participate: A New AI Collaboration Principle](#item-9) ⭐️ 8.0/10
10. [Cybersecurity Mission Creep Raises Governance Concerns](#item-10) ⭐️ 8.0/10
11. [Differential Geometry View of Hamiltonian Neural Networks](#item-11) ⭐️ 8.0/10
12. [arXiv to Spin Out from Cornell into Independent Nonprofit](#item-12) ⭐️ 8.0/10
13. [MOTHRAG: Graph-Free Multi-Hop RAG Outperforms Graph-Based Systems](#item-13) ⭐️ 8.0/10
14. [Scott Aaronson Declares US Privacy Emergency](#item-14) ⭐️ 7.0/10
15. [Linux 6.9 LUKS Suspend Bug Leaves Encryption Keys in Memory](#item-15) ⭐️ 7.0/10
16. [How to Ask Strangers for Help Effectively](#item-16) ⭐️ 7.0/10
17. [Simon Willison Releases llm-coding-agent 0.1a0](#item-17) ⭐️ 7.0/10
18. [Using DSPy to Evaluate and Improve Datasette Agent's SQL Prompts](#item-18) ⭐️ 7.0/10
19. [PhD Student Seeks Math Books for ML Research](#item-19) ⭐️ 7.0/10
20. [Hierarchos: 232M Recurrent Memory-Augmented Model Shows Promise](#item-20) ⭐️ 7.0/10
21. [Style Transfer for Machine-Translated Novels](#item-21) ⭐️ 7.0/10
22. [SentryCode: Open-Source Kernel-Level Auditor for AI Coding Agents](#item-22) ⭐️ 7.0/10
23. [Exapunks: A Nostalgic Look at Zachtronics' Programming Puzzle](#item-23) ⭐️ 6.0/10
24. [IEEE Paper: Training AI to Learn MoonBit from Scratch](#item-24) ⭐️ 6.0/10
25. [Papa Johns Uses Instacart Data to Predict Empty Fridges](#item-25) ⭐️ 6.0/10
26. [Alleged Scattered Spider Hacker Arrested in Finland](#item-26) ⭐️ 6.0/10
27. [AFP probes Australian citizen for alleged Gaza war crimes](#item-27) ⭐️ 6.0/10
28. [Developer Builds 216.5M Parameter SLM from Scratch](#item-28) ⭐️ 6.0/10
29. [How Top ML Conferences Select Best Papers and Orals](#item-29) ⭐️ 6.0/10
30. [PyMuPDF 1.28 Adds Native Markdown Support](#item-30) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [FBI Seizes NetNut Proxy Platform, Popa Botnet](https://krebsonsecurity.com/2026/07/fbi-seizes-netnut-proxy-platform-popa-botnet/) ⭐️ 9.0/10

The FBI seized hundreds of domains associated with NetNut, a residential proxy service operated by Alarum Technologies, following investigative reporting linking NetNut to the Popa botnet of over 2 million compromised devices. This law enforcement action disrupts a major proxy service that enabled cybercriminals to anonymize attacks and bypass IP reputation systems, highlighting the growing scrutiny of residential proxy networks used for malicious purposes. NetNut claimed to offer over 85 million residential proxies with one-hop connectivity, but researchers found it was routing traffic through compromised Android TV boxes infected by the Vo1d/Popa malware. The FBI action came two weeks after KrebsOnSecurity published the findings.

rss · Krebs on Security · Jul 2, 19:27

**Background**: Residential proxy services route internet traffic through real home devices, making them appear as legitimate users. The Popa botnet, a variant of the Vo1d malware, infected Android TV boxes to turn them into proxies without owners' consent, enabling account takeovers and fraud.

<details><summary>References</summary>
<ul>
<li><a href="https://suriq.io/blog/popa-residential-proxy-ip-reputation-account-takeover">Residential proxy botnets break IP reputation</a></li>
<li><a href="https://www.qurium.org/forensics/finding-popa/">Finding “ Popa ”: When Your Smart TV Stops Being Yours – Qurium...</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#botnet`, `#FBI`, `#proxy service`, `#law enforcement`

---

<a id="item-2"></a>
## [Virginia Bans Sale of Geolocation Data](https://www.hunton.com/privacy-and-cybersecurity-law-blog/virginia-bans-sale-of-geolocation-data) ⭐️ 8.0/10

Virginia enacted a law banning the sale of geolocation data, effective July 1, 2024, marking a significant step in state-level privacy regulation. This law restricts how tech companies and data brokers can monetize location data, potentially setting a precedent for other states and impacting industries like advertising and insurance. The ban applies to the sale of geolocation data collected in Virginia, but enforcement challenges remain, especially for out-of-state companies or data processed in cloud servers located in Virginia.

hackernews · toomuchtodo · Jul 2, 21:03 · [Discussion](https://news.ycombinator.com/item?id=48767347)

**Background**: Geolocation data reveals a person's precise location over time, often collected by apps and services. Its sale has raised privacy concerns, such as tracking visits to sensitive locations like abortion clinics or use by insurance companies to adjust premiums.

**Discussion**: Commenters generally support the ban, citing real-world abuses like tracking Planned Parenthood visits and car insurance data use. However, they question enforcement mechanisms, especially for companies incorporated elsewhere or using cloud infrastructure in Virginia.

**Tags**: `#privacy`, `#geolocation data`, `#legislation`, `#data protection`

---

<a id="item-3"></a>
## [crustc: Entire rustc Compiler Translated to C](https://github.com/FractalFir/crustc) ⭐️ 8.0/10

A developer has undertaken a multi-year effort to translate the entire Rust compiler (rustc) into C, resulting in a project called crustc. This transpilation aims to enable bootstrapping and support for hardware without LLVM or GCC backends. This project could solve the bootstrapping problem for Rust, allowing the compiler to be built from source without requiring a pre-existing Rust compiler. It also opens the door for Rust to run on obscure or legacy hardware that lacks LLVM or GCC support. crustc is the 14th known attempt to transpile Rust to C, and it leverages GCC for optimization after transpilation. The project is still in development, with the goal of producing a fully functional C-based Rust compiler.

hackernews · Philpax · Jul 2, 22:57 · [Discussion](https://news.ycombinator.com/item?id=48768464)

**Background**: Bootstrapping is the process of creating a self-compiling compiler, where a compiler written in its own language can be built from source. For Rust, this currently requires an existing Rust compiler binary, creating a chicken-and-egg problem. Transpilation, or source-to-source compilation, converts code from one high-level language to another, as opposed to traditional compilation to machine code. By transpiling rustc to C, crustc allows the Rust compiler to be compiled with any C compiler, breaking the dependency cycle.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bootstrapping_(compilers)">Bootstrapping (compilers)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Transpilation">Transpilation</a></li>

</ul>
</details>

**Discussion**: The community expressed admiration for the dedication, with one commenter noting this is the 14th attempt. Discussion also touched on using Diverse Double-Compiling (DDC) to verify the official Rust compiler for backdoors, and the technical feasibility of transpiling to C versus LLVM IR.

**Tags**: `#rust`, `#compilers`, `#bootstrapping`, `#transpilation`, `#systems-programming`

---

<a id="item-4"></a>
## [Podman v6.0.0 Released with Networking Improvements](https://blog.podman.io/2026/07/introducing-podman-v6-0-0/) ⭐️ 8.0/10

Podman v6.0.0, a major version release of the daemonless container engine, introduces significant networking improvements and other enhancements for developers and sysadmins. This release strengthens Podman's position as a compelling alternative to Docker, especially for users seeking a daemonless, rootless container runtime with better security and system integration. The new networking improvements in v6.0.0 are a welcome addition, though specific technical details were not provided in the announcement. The release continues to support rootless mode and Quadlet for systemd integration.

hackernews · soheilpro · Jul 2, 14:23 · [Discussion](https://news.ycombinator.com/item?id=48762098)

**Background**: Podman is an open-source, daemonless container engine for developing, managing, and running OCI containers on Linux systems. Unlike Docker, it does not require a central daemon and can run containers in rootless mode for enhanced security. It aims to be a drop-in replacement for Docker, supporting docker-compose.yml files and providing a similar command-line interface.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@williamwarley/unleashing-podman-the-ultimate-guide-to-revolutionizing-your-container-management-3a5bdbbd5ef8?responsesOpen=true">Unleashing Podman : The Ultimate Guide to Revolutionizing... | Medium</a></li>
<li><a href="https://mathieu-benoit.github.io/posts/2020/01/podman/">podman , a daemonless container engine :: always up, always on</a></li>
<li><a href="https://blog.while-true-do.io/podman-getting-started/">Podman - Getting Started</a></li>

</ul>
</details>

**Discussion**: Community sentiment is largely positive, with users praising Podman's ease of migration from Docker and the new networking features. However, some users express frustration over limited distro support, particularly for Ubuntu, which hinders wider adoption. Others highlight the benefits of Quadlet for systemd integration.

**Tags**: `#Podman`, `#containers`, `#Docker`, `#devops`, `#open source`

---

<a id="item-5"></a>
## [PeerTube: Decentralized, Federated Video Platform](https://github.com/Chocobozzz/PeerTube) ⭐️ 8.0/10

PeerTube is a free, open-source, decentralized video platform that uses ActivityPub federation and peer-to-peer technology to distribute video content across independent instances. PeerTube offers a viable alternative to centralized platforms like YouTube, addressing concerns about privacy, censorship, and control by enabling communities to host their own video servers while still connecting to a global network. PeerTube uses WebTorrent for peer-to-peer streaming, reducing server load when videos become popular. It is part of the Fediverse, compatible with Mastodon and other ActivityPub-based services.

hackernews · doener · Jul 2, 11:17 · [Discussion](https://news.ycombinator.com/item?id=48759634)

**Background**: Centralized video platforms like YouTube store all content on their own servers, giving them full control over content and monetization. PeerTube flips this model by allowing anyone to run a video server (instance) that can federate with others, so users can follow and interact across instances. This decentralized approach aims to give content creators and viewers more autonomy and resilience against platform policies.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PeerTube">PeerTube - Wikipedia</a></li>
<li><a href="https://joinpeertube.org/faq">FAQ | JoinPeerTube</a></li>

</ul>
</details>

**Discussion**: Community comments highlight monetization challenges for professional creators, as PeerTube lacks built-in revenue mechanisms. Some users appreciate the platform for open-source projects and privacy-focused content, but note the lack of mainstream content and audience. Others praise the peer-to-peer technology but question whether social factors will limit adoption.

**Tags**: `#decentralization`, `#video hosting`, `#open source`, `#federation`, `#privacy`

---

<a id="item-6"></a>
## [EFF Alleges X's Grok AI Generated CSAM, Urges FTC Action](https://cdn.arstechnica.net/wp-content/uploads/2026/07/EFF-letter-to-FTC-on-X-consent-order-7-2-26.pdf) ⭐️ 8.0/10

The Electronic Frontier Foundation (EFF) sent a letter to the Federal Trade Commission (FTC) on July 2, 2026, alleging that X's Grok AI chatbot generated child sexual abuse material (CSAM) and nonconsensual intimate imagery, violating a prior consent order. This marks a significant clash between AI safety advocacy and free speech principles, as the EFF—typically a defender of digital rights—argues for stricter regulation of AI-generated harmful content, potentially setting a precedent for AI accountability. The letter specifically references Grok's ability to generate explicit images of public figures and minors, despite recent attempts to restrict such outputs. The EFF argues that X's petition to waive privacy violation penalties should be rejected.

hackernews · Terretta · Jul 2, 19:27 · [Discussion](https://news.ycombinator.com/item?id=48766209)

**Background**: Grok is a generative AI chatbot developed by Elon Musk's xAI, integrated with the X social network. It has faced prior controversy for generating harmful content, including conspiracy theories and nonconsensual imagery. The FTC consent order stems from X's previous misuse of user data for advertising.

<details><summary>References</summary>
<ul>
<li><a href="https://www.eff.org/deeplinks/2026/06/eff-and-allies-xs-ftc-petition-waive-privacy-violation-order-should-be-rejected">EFF and Allies: X’s FTC Petition to Waive Privacy Violation ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Grok_AI">Grok AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/CSAM">CSAM</a></li>

</ul>
</details>

**Discussion**: Comments on Hacker News show mixed reactions: some users note that Grok's image generation has been 'nerfed' recently, while others question why the EFF is arguing for less freedom in computing. A few commenters suggest political motivations, referencing Musk's campaign spending.

**Tags**: `#AI safety`, `#regulation`, `#EFF`, `#FTC`, `#CSAM`

---

<a id="item-7"></a>
## [Postgres Transactions as Distributed Systems Superpower](https://www.dbos.dev/blog/co-locating-workflow-state-with-your-data) ⭐️ 8.0/10

A blog post from DBOS argues that using PostgreSQL transactions to co-locate workflow state with data can simplify distributed workflow orchestration and eliminate the need for the transactional outbox pattern. This approach could reduce complexity and improve reliability in distributed systems by leveraging Postgres' ACID guarantees for workflow state management, potentially changing how developers build durable workflows. The technique aligns each workflow step with a database commit unit, making the outbox pattern unnecessary but tightly coupling the database to the workflow. This trade-off is acceptable in many real-world scenarios where the database is not separated.

hackernews · KraftyOne · Jul 2, 18:38 · [Discussion](https://news.ycombinator.com/item?id=48765639)

**Background**: In distributed systems, the transactional outbox pattern is commonly used to ensure reliable message delivery when updating a database and sending events to a message queue. It involves writing events to an outbox table within the same database transaction, then a separate process publishes them. Co-locating workflow state with data in Postgres transactions offers an alternative that avoids this extra complexity.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@tpriyesh188/the-outbox-pattern-your-key-to-reliable-event-driven-systems-dd78a5c2690e">The Outbox Pattern : Your Key to Reliable Event-Driven Systems</a></li>
<li><a href="https://www.linkedin.com/posts/sadotarefin_systemdesign-softwarearchitecture-microservices-activity-7462556857899855872-Ir4Y">Preventing Data Loss in Distributed Systems with the Outbox Pattern</a></li>
<li><a href="https://bool.dev/blog/detail/inbox-and-outbox-patterns">Transactional Inbox and Outbox Patterns : Practical Guide... — bool.dev</a></li>

</ul>
</details>

**Discussion**: Commenters debated the practicality of the approach: some noted that external side effects still require idempotency, while others pointed out the tight coupling between database and workflow. One commenter humorously remarked that the approach essentially rediscovers a mutex, questioning whether it truly qualifies as a distributed system.

**Tags**: `#PostgreSQL`, `#distributed systems`, `#workflows`, `#transactions`

---

<a id="item-8"></a>
## [Immich 3.0 Sparks Debate Over Missing End-to-End Encryption](https://github.com/immich-app/immich/discussions/29439) ⭐️ 8.0/10

Immich 3.0, a major update to the self-hosted photo management platform, has been released, introducing new features and improvements but notably lacking end-to-end encryption (E2EE). This release highlights the growing tension between privacy-focused users who demand E2EE and those who prioritize convenience and accessibility in self-hosted photo solutions. Immich's popularity as a Google Photos alternative makes this debate significant for the broader self-hosting community. Immich 3.0 remains a server-side encrypted solution, meaning photos are encrypted at rest but accessible to the server operator. The project's roadmap does not currently list E2EE as a planned feature, which has disappointed some users who compare it to alternatives like Ente Photos.

hackernews · hashier · Jul 2, 14:13 · [Discussion](https://news.ycombinator.com/item?id=48761944)

**Background**: Immich is an open-source, self-hosted photo and video management solution that serves as a privacy-focused alternative to Google Photos and Apple Photos. It offers AI-powered features like facial recognition, smart search, and automatic mobile uploads. End-to-end encryption (E2EE) ensures that only the user can decrypt their data, preventing even the server host from accessing it. Many privacy-conscious users consider E2EE essential for true data sovereignty.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/immich-app/immich">GitHub - immich-app/immich: High performance self-hosted ... Immich Complete Self-Hosting Guide: From Installation to ... Self-Hosting Your Photos with Immich — HomeLab Starter GitHub - immich-app/immich: High performance self-hosted ... Download | Immich How to Install Immich for Self-Hosted Photo Management on Ubuntu</a></li>
<li><a href="https://immich.app/">Immich</a></li>
<li><a href="https://ente.com/">Ente Photos: Store and share your photos with absolute privacy</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users argue E2EE is unnecessary for self-hosted setups, citing convenience and recovery benefits, while others insist it's a critical privacy feature. Users also compare Immich favorably to commercial services but note that alternatives like Ente Photos offer E2EE. Some express frustration with past sync issues on iOS.

**Tags**: `#self-hosting`, `#photo management`, `#open source`, `#privacy`, `#immich`

---

<a id="item-9"></a>
## [Understand to Participate: A New AI Collaboration Principle](https://simonwillison.net/2026/Jul/2/understand-to-participate/#atom-everything) ⭐️ 8.0/10

Geoffrey Litt introduced the concept of 'understand to participate' at the AIE conference, arguing that developers must maintain deep code understanding when collaborating with AI coding agents to avoid cognitive debt. This principle addresses a critical challenge in AI-assisted development: as agents generate larger code changes, developers risk losing understanding, leading to cognitive debt that hinders effective participation and creativity. Litt emphasized that developers need a rich set of concepts in mind to think creatively and fluently about moving a project forward; lacking that fluency limits participation. The talk was part of AIE 2026, with recordings to be released over three weeks.

rss · Simon Willison · Jul 2, 17:07

**Background**: Cognitive debt refers to the erosion of shared understanding in a software system over time, leading to inadequate mental models for reasoning about changes. As AI coding agents become more capable, developers may accept code they don't fully understand, accumulating cognitive debt that must eventually be repaid.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jul/2/understand-to-participate/">Understand to participate - simonwillison.net</a></li>
<li><a href="https://margaretstorey.com/blog/2026/02/09/cognitive-debt/">How Generative and Agentic AI Shift Concern from Technical Debt to Cognitive Debt</a></li>
<li><a href="https://getdx.com/blog/cognitive-debt-the-hidden-risk-in-ai-driven-software-development/">Cognitive debt: The hidden risk in AI-driven software development</a></li>

</ul>
</details>

**Tags**: `#AI-assisted development`, `#cognitive debt`, `#human-AI collaboration`, `#software engineering`

---

<a id="item-10"></a>
## [Cybersecurity Mission Creep Raises Governance Concerns](https://www.schneier.com/blog/archives/2026/07/cybersecurity-mission-creep-in-the-us.html) ⭐️ 8.0/10

Bruce Schneier highlights a paper by legal scholar Mailyn Fidler arguing that cybersecurity is experiencing mission creep, as policymakers reframe diverse issues like misinformation, child safety, and antitrust as cybersecurity threats. This trend, termed 'cybersecuritization,' allows issues to be treated with urgency and exceptionalism, potentially undermining transparency and constitutional protections. It signals a problematic expansion of cybersecurity governance that could affect how societies address a wide range of policy challenges. The paper, forthcoming in the University of Illinois Law Review, identifies cybersecuritization as insidious and critical to confront. Examples include misinformation, child social media safety laws, antitrust regulations, alleged journalist misconduct, and anti-sex trafficking statutes being reframed as cybersecurity issues.

rss · Schneier on Security · Jul 2, 11:11

**Background**: Cybersecurity traditionally refers to measures protecting computer systems from unauthorized access or attack. Mission creep occurs when a concept's scope expands beyond its original purpose. In this context, policymakers are increasingly labeling diverse societal problems as cybersecurity threats, granting them access to emergency-like governance responses.

<details><summary>References</summary>
<ul>
<li><a href="https://www.schneier.com/blog/archives/2026/07/cybersecurity-mission-creep-in-the-us.html">Cybersecurity Mission Creep in the US - Schneier on Security</a></li>
<li><a href="https://cyber.harvard.edu/story/2026-03/cybersecurity-mission-creep">Cybersecurity Mission Creep | Berkman Klein Center</a></li>
<li><a href="https://www.memesita.com/the-growing-threat-of-cybersecurity-mission-creep-how-policymakers-abuse-emergency-powers/">The Growing Threat of Cybersecurity Mission Creep: How ...</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#policy`, `#mission creep`, `#governance`

---

<a id="item-11"></a>
## [Differential Geometry View of Hamiltonian Neural Networks](https://www.reddit.com/r/MachineLearning/comments/1ukzdnj/hamiltonian_neural_networks_from_a_differential/) ⭐️ 8.0/10

A blog post presents Hamiltonian Neural Networks (HNNs) from a differential geometry perspective, highlighting Noether's theorem to connect symmetries with conservation laws and generalization in machine learning. This perspective offers a deeper theoretical understanding of HNNs, potentially improving physics-informed ML models by leveraging symmetry principles for better generalization and data efficiency. The post includes interactive visuals and is math-heavy but accessible; it emphasizes that Noether's theorem maps conservations to symmetries, which in ML context relates to generalization.

reddit · r/MachineLearning · /u/FlameOfIgnis · Jul 1, 21:55

**Background**: Hamiltonian Neural Networks (HNNs) are neural networks that learn Hamiltonian dynamics from data, conserving energy and other quantities. Noether's theorem states that every continuous symmetry of a physical system corresponds to a conservation law. Differential geometry provides tools to study symmetries and invariants in a geometric framework.

<details><summary>References</summary>
<ul>
<li><a href="https://greydanus.github.io/2019/05/15/hamiltonian-nns/">Hamiltonian Neural Networks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Noether's_theorem">Noether's theorem</a></li>
<li><a href="https://arxiv.org/abs/1906.01563">[1906.01563] Hamiltonian Neural Networks</a></li>

</ul>
</details>

**Tags**: `#Hamiltonian Neural Networks`, `#Differential Geometry`, `#Noether's Theorem`, `#Physics-Informed ML`, `#Deep Learning`

---

<a id="item-12"></a>
## [arXiv to Spin Out from Cornell into Independent Nonprofit](https://www.reddit.com/r/MachineLearning/comments/1ukjtlm/on_july_1_2026_arxiv_will_spin_out_from_cornell/) ⭐️ 8.0/10

On July 1, 2026, arXiv will spin out from Cornell University to become an independent nonprofit organization, with major funding from the Simons Foundation and Schmidt Sciences. This transition ensures long-term stability and governance independence for arXiv, a critical infrastructure for open-access research dissemination in machine learning and other fields. The spin-out includes a website redesign that ditches the traditional red color scheme. The Simons Foundation and Schmidt Sciences are the primary funding partners.

reddit · r/MachineLearning · /u/Nunki08 · Jul 1, 12:07

**Background**: arXiv is a preprint repository founded in 1991, hosted by Cornell University for the past 25 years. It allows researchers to share papers before peer review, becoming essential for rapid dissemination in physics, mathematics, computer science, and related fields.

**Tags**: `#arXiv`, `#open access`, `#research infrastructure`, `#academic publishing`

---

<a id="item-13"></a>
## [MOTHRAG: Graph-Free Multi-Hop RAG Outperforms Graph-Based Systems](https://www.reddit.com/r/MachineLearning/comments/1ukotww/p_mothretrieval_graphfree_multihop_retrieval_via/) ⭐️ 8.0/10

MOTHRAG, a new open-source multi-hop retrieval framework, eliminates the need for knowledge graphs by using a graph-free dense index with query-time orchestration, achieving 78.1% accuracy on HotpotQA, outperforming GraphRAG (68.6%) and RAPTOR (69.5%). This approach significantly reduces the cost and complexity of updating retrieval systems for dynamic data, as it avoids expensive graph re-indexing, making multi-hop RAG practical for frequently changing corpora like news or internal filings. MOTHRAG runs on commodity APIs with a cost of ~$0.03 per query and no GPU required, but it underperforms on the MuSiQue benchmark (50.5 vs. 52.6) due to retrieval recall bottlenecks. The framework is Apache-2.0 licensed and available via pip install.

reddit · r/MachineLearning · /u/Annual-Commercial563 · Jul 1, 15:26

**Background**: Multi-hop retrieval-augmented generation (RAG) systems answer complex questions by combining information from multiple documents. Traditional approaches like GraphRAG build offline knowledge graphs to capture relationships, but updating these graphs requires costly re-indexing with LLMs. MOTHRAG instead uses a dense vector index and orchestrates queries at runtime to gather evidence without a graph.

<details><summary>References</summary>
<ul>
<li><a href="https://lineupdigest.com/en/article/multi-hop-retrieval-without-graphs-a-game-changer-in-data-processing">MOTHRAG: A New Era in Multi-Hop Retrieval — LineUp Digest</a></li>
<li><a href="https://mothrag.com/">MothRag — multi-hop AI for data that changes, on the APIs you ...</a></li>
<li><a href="https://github.com/juliangeymonat-jpg/mothrag">GitHub - juliangeymonat-jpg/mothrag: Deterministic agentic ...</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion includes technical questions about the retrieval recall bottleneck on MuSiQue and comparisons with GPU-bound systems like NeocorRAG. The author engages actively, acknowledging the limitation and noting that the graph-free approach holds up well for changing data.

**Tags**: `#RAG`, `#multi-hop retrieval`, `#knowledge graph`, `#information retrieval`, `#open-source`

---

<a id="item-14"></a>
## [Scott Aaronson Declares US Privacy Emergency](https://scottaaronson.blog/?p=9902) ⭐️ 7.0/10

Scott Aaronson published a blog post arguing that the United States faces a privacy emergency driven by corporate data exploitation, and he calls for legislative action to address it. This post highlights a critical policy issue with broad implications for individual privacy and corporate accountability, potentially influencing public discourse and legislative efforts. The post has high engagement with 137 points and 36 comments, indicating strong community interest. Aaronson specifically targets corporate data practices as the core of the emergency.

hackernews · flowercalled · Jul 3, 00:01 · [Discussion](https://news.ycombinator.com/item?id=48768992)

**Background**: Privacy concerns in the US have grown as companies collect vast amounts of personal data with minimal regulation. Aaronson's argument frames this as an emergency requiring immediate legislative response, similar to calls for federal privacy laws like the proposed American Data Privacy and Protection Act.

**Discussion**: Commenters express frustration with corporate influence over Congress, noting that popular policies like parental leave fail due to corporate donations. Some provide practical resources like links to find legislators, while others draw comparisons to China's state-capital relationship.

**Tags**: `#privacy`, `#policy`, `#corporate influence`, `#US politics`

---

<a id="item-15"></a>
## [Linux 6.9 LUKS Suspend Bug Leaves Encryption Keys in Memory](https://mathstodon.xyz/@iblech/116769502749142438) ⭐️ 7.0/10

Since Linux 6.9, the LUKS suspend feature no longer wipes disk-encryption keys from memory during suspend or hibernate cycles, potentially exposing them to attackers with physical access. This regression undermines the security guarantee of full-disk encryption, as encryption keys remain in memory during suspend, allowing cold boot or DMA attacks to recover them. It affects users relying on LUKS for data protection, especially those using Debian's cryptsetup-suspend extension. The bug is limited to a Debian-specific extension (cryptsetup-suspend) that is not part of the official cryptsetup upstream. The issue was discovered through NixOS tests, and a fix is expected in subsequent kernel releases.

hackernews · IngoBlechschmid · Jul 2, 15:25 · [Discussion](https://news.ycombinator.com/item?id=48763035)

**Background**: LUKS (Linux Unified Key Setup) is the standard for Linux full-disk encryption, which stores encryption keys in kernel memory while the system is running. During suspend-to-RAM, the system keeps memory powered, so keys remain vulnerable; the cryptsetup-suspend extension was designed to wipe these keys before suspend and require re-entry of the passphrase upon resume. This regression breaks that protection.

<details><summary>References</summary>
<ul>
<li><a href="https://sesamedisk.com/linux-luks-suspend-regression-security/">Linux LUKS Suspend Regression: Keys Stay - Sesame Disk</a></li>
<li><a href="https://eucloudservers.com/security-encryption/since-linux-6-9-luks-suspend-stopped-wiping-disk-encryption-keys-from-memory/">Since Linux 6.9, LUKS Suspend Stopped Wiping Disk - encryption ...</a></li>
<li><a href="https://web.archive.org/web/20230325165638/https://blog.freesources.org/posts/2020/08/cryptsetup-suspend/">cryptsetup- suspend</a></li>

</ul>
</details>

**Discussion**: Commenters debated whether the title was clickbait, noting the bug only affects Debian's extension, not upstream LUKS. Some expressed concern about the security implications, while others argued that suspend-to-RAM inherently leaves keys in memory anyway, so the practical impact is limited. A few users speculated about intentional backdoors, but most dismissed that as unlikely.

**Tags**: `#Linux`, `#security`, `#disk encryption`, `#LUKS`, `#kernel regression`

---

<a id="item-16"></a>
## [How to Ask Strangers for Help Effectively](https://pradyuprasad.com/writings/how-to-ask-for-help/) ⭐️ 7.0/10

A practical guide outlines strategies for asking strangers for help, emphasizing proof of work and concise communication, with community additions on showing effort and offering payment. This advice helps professionals overcome a common challenge—getting responses from cold contacts—by shifting focus from the asker's needs to demonstrating value, which can improve networking success and career opportunities. Key techniques include showing proof of work upfront, keeping messages brief, and, as commenters note, offering to pay for time or demonstrating deep effort beyond surface-level work.

hackernews · FigurativeVoid · Jul 2, 13:19 · [Discussion](https://news.ycombinator.com/item?id=48761118)

**Background**: Asking strangers for help is a common professional need, but many fail because they don't respect the recipient's time or show they've done their homework. The concept of 'proof of work'—demonstrating prior effort—helps establish credibility and respect.

**Discussion**: Commenters largely agree with the post, adding that proof of work must be genuine and deep, not superficial. Some suggest offering payment upfront to show seriousness, which often leads to free help. Others emphasize that concise, effort-demonstrating messages outperform lengthy ones.

**Tags**: `#career advice`, `#communication`, `#professional networking`, `#soft skills`

---

<a id="item-17"></a>
## [Simon Willison Releases llm-coding-agent 0.1a0](https://simonwillison.net/2026/Jul/2/llm-coding-agent/#atom-everything) ⭐️ 7.0/10

Simon Willison released llm-coding-agent 0.1a0, an early alpha coding agent built on his LLM library and inspired by Claude Code. The agent can read and edit files, execute commands, and search code, and is installable via uvx. This release demonstrates how Simon Willison's LLM library has evolved into an agent framework, enabling practical coding agents. It lowers the barrier for developers to experiment with AI-assisted coding tools built on a familiar Python ecosystem. The agent provides tools like edit_file, execute_command, list_files, read_file, and search_files, with safety features such as approval prompts and timeout limits. The entire project, including its spec and commits, was generated by Claude Code through a series of prompts.

rss · Simon Willison · Jul 2, 19:33

**Background**: Simon Willison's LLM library is a CLI tool and Python library that provides a unified interface to hundreds of large language models via plugins. Claude Code is Anthropic's agentic coding system that reads codebases, edits files, and runs commands. This release is part of Willison's ongoing experiments with LLM-powered agents.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/simonw/llm">GitHub - simonw/llm: Access large language models from the ...</a></li>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://github.com/simonw/python-lib-template-repository">GitHub - simonw/python-lib-template-repository: GitHub template repository for creating new Python libraries, using the simonw/python-lib cookiecutter template · GitHub</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#coding agent`, `#Python`, `#open source`, `#AI tools`

---

<a id="item-18"></a>
## [Using DSPy to Evaluate and Improve Datasette Agent's SQL Prompts](https://simonwillison.net/2026/Jul/2/dspy-datasette-agent-prompts/#atom-everything) ⭐️ 7.0/10

Simon Willison used the DSPy framework to evaluate and improve the system prompts for Datasette Agent's SQL query generation feature, identifying issues like column-name guessing and error-retry loops. This demonstrates a practical, replicable workflow for optimizing LLM prompts using DSPy, which can help developers improve the reliability and accuracy of AI-powered tools like Datasette Agent. The experiment used GPT-4.1 mini and nano models, and suggested including column names in the schema listing to reduce guesswork and error retries.

rss · Simon Willison · Jul 2, 18:25

**Background**: DSPy is a framework for programming—rather than prompting—language models, enabling algorithmic optimization of prompts and weights. Datasette Agent is an AI assistant that generates SQL queries to answer user questions about data stored in Datasette.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/stanfordnlp/dspy">GitHub - stanfordnlp/dspy: DSPy: The framework for programming—not prompting—language models</a></li>
<li><a href="https://agent.datasette.io/">Datasette Agent : an AI assistant for Datasette to help explore and...</a></li>
<li><a href="https://github.com/datasette/datasette-agent">GitHub - datasette / datasette - agent : An LLM-powered agent for...</a></li>

</ul>
</details>

**Tags**: `#DSPy`, `#prompt engineering`, `#Datasette Agent`, `#AI`, `#SQL`

---

<a id="item-19"></a>
## [PhD Student Seeks Math Books for ML Research](https://www.reddit.com/r/MachineLearning/comments/1ulmy9g/booksresources_to_improve_mathematical/) ⭐️ 7.0/10

A mid-to-late stage PhD student in machine learning posted on Reddit asking for book recommendations to strengthen their mathematical foundations in linear algebra, probability theory, and functional analysis. This post highlights a common challenge for ML researchers: the need for solid mathematical foundations beyond just learning topics as needed. The discussion can help many students and practitioners find effective resources. The student mentions using 'Linear Algebra Done Right' for linear algebra, 'A Primer on RKHS' for functional analysis, and plans to revisit PRML and Pat Kidger's 'Just-Know-Stuff' list. They also ask about 'The Bright Side of Mathematics' YouTube channel.

reddit · r/MachineLearning · /u/mvreich · Jul 2, 16:24

**Background**: Machine learning research often requires a deep understanding of linear algebra, probability, and functional analysis. Many researchers learn these topics on the fly, which can lead to gaps. Books like 'Linear Algebra Done Right' and 'Pattern Recognition and Machine Learning' (PRML) are classic references, while RKHS (Reproducing Kernel Hilbert Space) is a key concept in kernel methods and statistical learning theory.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Reproducing_kernel_Hilbert_space">Reproducing kernel Hilbert space - Wikipedia</a></li>
<li><a href="https://github.com/gerdm/prml">GitHub - gerdm/prml: Repository of notes, code and notebooks in Python for the book Pattern Recognition and Machine Learning by Christopher Bishop · GitHub</a></li>
<li><a href="https://tjzhifei.github.io/links/PRML.pdf">Pattern Recognition and Machine Learning</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#mathematics`, `#resources`, `#PhD`, `#education`

---

<a id="item-20"></a>
## [Hierarchos: 232M Recurrent Memory-Augmented Model Shows Promise](https://www.reddit.com/r/MachineLearning/comments/1um123n/hierarchos_preliminary_findings_from_a_232m/) ⭐️ 7.0/10

Researchers released preliminary findings on Hierarchos, a 232M-parameter recurrent memory-augmented language model that combines an RWKV backbone, hierarchical manager/worker loops, differentiable slot-based long-term memory, and a deterministic suffix automaton. The model was trained from scratch on an RTX 6000 Blackwell GPU and demonstrates training stability and short-form instruction coherence. This work explores a viable alternative to Transformer-based architectures, showing that hybrid recurrent models with explicit memory can be trained without collapse. If scaled further, such architectures could offer better parameter efficiency and lower inference costs for language models. Key engineering fixes included aligning train/inference drift state reseeding, switching to read-only LTM training mode to avoid supervised memory crutches, and clamping RWKV channel-mix activations to prevent NaN gradients. The model uses a 96GB RTX 6000 Blackwell GPU for training over 13 epochs on an Alpaca-format dataset.

reddit · r/MachineLearning · /u/PhysicsDisastrous462 · Jul 3, 01:48

**Background**: Most modern large language models rely on the Transformer architecture, which uses self-attention mechanisms. Recurrent architectures like RWKV offer an alternative with linear-time inference but have historically been harder to train at scale. Hierarchos adds hierarchical loops and differentiable memory to improve coherence and parameter efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2406.19369">Mamba or RWKV : Exploring High-Quality and</a></li>
<li><a href="https://www.rwkv.com/">RWKV Language Model</a></li>
<li><a href="https://en.wikipedia.org/wiki/Suffix_automaton">Suffix automaton - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#language model`, `#recurrent architecture`, `#memory augmentation`, `#research`

---

<a id="item-21"></a>
## [Style Transfer for Machine-Translated Novels](https://www.reddit.com/r/MachineLearning/comments/1ulrdw9/improving_machinetranslated_novels_via_style/) ⭐️ 7.0/10

A project explores using unsupervised style transfer to polish machine-translated webnovels into fluent, professional prose without parallel data, referencing STRAP and other methods. This addresses the underexplored task of post-editing machine translation via style transfer, which could significantly improve the reading experience of translated fiction and reduce reliance on human editors. The project faces challenges like maintaining narrative coherence across paragraphs and preserving domain-specific terms, and considers approaches such as sentence-level STRAP, self-supervised loss, or using a local LLM with guidelines.

reddit · r/MachineLearning · /u/Divine_Invictus · Jul 2, 19:04

**Background**: Style transfer aims to rewrite text in a different style while preserving content, often without parallel data. Machine-translated novels often suffer from 'translationese'—awkward phrasing that betrays the source language. STRAP reframes style transfer as paraphrase generation, creating pseudo-parallel pairs automatically.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2010.05700">Reformulating Unsupervised Style Transfer</a></li>
<li><a href="https://github.com/wang-yiwei/STRAP">GitHub - wang-yiwei/ STRAP : Official code and data repository for our...</a></li>
<li><a href="https://deepwiki.com/fuzhenxin/Style-Transfer-in-Text/2.1-unsupervised-methods-(non-parallel-data)">Unsupervised Methods (Non-parallel Data) | fuzhenxin/Style ...</a></li>

</ul>
</details>

**Tags**: `#style transfer`, `#machine translation`, `#NLP`, `#text generation`, `#unsupervised learning`

---

<a id="item-22"></a>
## [SentryCode: Open-Source Kernel-Level Auditor for AI Coding Agents](https://www.reddit.com/r/MachineLearning/comments/1ul7ap2/sentrycode_realtime_auditor_honeytokens_for_ai/) ⭐️ 7.0/10

SentryCode, an open-source kernel-level auditing tool, has been released to monitor and secure AI coding agents against privacy violations using honeytokens and covert channel detection. As AI coding agents become more prevalent, their potential for telemetry and data exfiltration poses serious privacy risks; SentryCode provides a novel, local-first defense that can detect breaches with zero false positives. The tool logs file, network, and cue activity, uses honeypot tokens for breach detection, detects steganographically encrypted covert channels, and provides tamper-proof audit logs, all running locally without outbound connections.

reddit · r/MachineLearning · /u/cyh-c · Jul 2, 03:48

**Background**: Honeytokens are fictitious data entries used to detect unauthorized access, while covert channels are hidden communication paths that bypass security policies. Kernel-level auditing records system calls and file access at the operating system level, providing detailed security logs. SentryCode combines these techniques to monitor AI coding agents that may perform environmental scanning or hidden cue fingerprinting.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Honeytoken">Honeytoken</a></li>
<li><a href="https://www.crowdstrike.com/en-us/cybersecurity-101/identity-protection/honeytokens/">What are Honeytokens? | CrowdStrike</a></li>
<li><a href="https://cubepath.com/docs/server-security/auditing-with-auditd-on-linux">Auditing with auditd on Linux - CubePath Docs | CubePath</a></li>

</ul>
</details>

**Tags**: `#AI Security`, `#Open Source`, `#Privacy`, `#Auditing`, `#Honeytokens`

---

<a id="item-23"></a>
## [Exapunks: A Nostalgic Look at Zachtronics' Programming Puzzle](https://www.zachtronics.com/exapunks/) ⭐️ 6.0/10

A Hacker News post discusses the 2018 programming puzzle game Exapunks by Zachtronics, highlighting its design and community engagement. Exapunks remains a beloved example of how programming concepts can be gamified, influencing both game design and players' understanding of low-level programming. The game features a fictional 1990s hacker setting where players write assembly-like code to solve puzzles, and includes a built-in virtual console called Redshift for creating homebrew games.

hackernews · yu3zhou4 · Jul 2, 18:41 · [Discussion](https://news.ycombinator.com/item?id=48765663)

**Background**: Zachtronics is known for programming puzzle games like TIS-100 and Shenzhen I/O, which teach assembly language concepts through gameplay. Exapunks continues this tradition with a narrative-driven hacking theme.

<details><summary>References</summary>
<ul>
<li><a href="https://www.zachtronics.com/exapunks/">Zachtronics | EXAPUNKS</a></li>
<li><a href="https://en.wikipedia.org/wiki/Exapunks">Exapunks - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/TIS-100">TIS-100 - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised Exapunks and Shenzhen I/O for capturing the fun of programming, with one noting the futility of pre-optimizing solutions. Another shared that the game inspired their own game development project. Some users mentioned that Zachtronics founder Zach Barth is now at Coincidence Games, which released a new spacecraft engineering puzzle game.

**Tags**: `#gaming`, `#programming`, `#puzzle`, `#zachtronics`, `#retrospective`

---

<a id="item-24"></a>
## [IEEE Paper: Training AI to Learn MoonBit from Scratch](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247901046&idx=3&sn=f81efbdae1fa6cca391a9c4389820598) ⭐️ 6.0/10

An IEEE paper presents a complete training pipeline that enables AI models to learn the new programming language MoonBit from scratch and achieve a passing grade. The pipeline covers data collection, model training, and evaluation specifically tailored for MoonBit. This work demonstrates a systematic approach to teaching AI a new, niche programming language, which could accelerate the adoption of emerging languages like MoonBit in AI-assisted development. It also provides a blueprint for training AI on other low-resource programming languages. MoonBit is a programming language designed for WebAssembly with fast, incremental compilation and a focus on cloud and edge computing. The paper likely addresses challenges such as limited training data and language-specific syntax, providing a replicable pipeline for other languages.

rss · 量子位 · Jul 1, 05:53

**Background**: MoonBit is a relatively new, statically-typed programming language developed for generating WebAssembly binaries, targeting cloud and edge computing. It features a lightweight syntax and a toolchain that supports multiple backends. Training AI on such a new language is challenging due to scarce training data and lack of pre-existing models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.moonbitlang.com/">MoonBit - The Language and Toolchain</a></li>
<li><a href="https://docs.moonbitlang.com/">MoonBit Documentation — MoonBit v0.10.1 documentation</a></li>
<li><a href="https://github.com/moonbitlang/moonbit-docs">The docs of MoonBit programming language - GitHub moonbitlang · GitHub MoonBit Language - Visual Studio Marketplace 2. Development Environments & Expressions | Programming with ... moonbitlang/moonbit-docs | DeepWiki</a></li>

</ul>
</details>

**Tags**: `#AI`, `#programming language`, `#MoonBit`, `#training`, `#IEEE`

---

<a id="item-25"></a>
## [Papa Johns Uses Instacart Data to Predict Empty Fridges](https://www.schneier.com/blog/archives/2026/07/papa-johns-surveillance-based-advertising.html) ⭐️ 6.0/10

Papa Johns partnered with NBCUniversal, Instacart, and Carat to serve targeted ads on NBCU streaming content based on Instacart purchase data, predicting when customers are low on groceries. This campaign exemplifies the growing trend of surveillance-based advertising using real purchase data to target consumers at vulnerable moments, raising significant privacy concerns. The custom audience was built from shoppers who regularly buy staples like eggs, milk, meat, and produce on Instacart, and ads included QR codes with messages like 'Light on groceries?'.

rss · Schneier on Security · Jul 1, 10:53

**Background**: Surveillance-based advertising uses personal data to target ads based on inferred needs or behaviors. Instacart's Data Hub, launched in January 2026, provides purchase signals for off-platform audience targeting, enabling such campaigns.

<details><summary>References</summary>
<ul>
<li><a href="https://investors.instacart.com/news-releases/news-release-details/instacart-debuts-data-hub-clean-room-offering-enhanced-media">Instacart Debuts Data Hub, a Clean Room Offering for Enhanced Media Performance | Instacart</a></li>
<li><a href="https://www.nbcuniversal.com/article/nbcuniversal-launches-first-market-cross-platform-innovations-setting-stage-next-era-media-and">NBCUniversal Launches First-to-Market Cross-Platform ...</a></li>

</ul>
</details>

**Tags**: `#surveillance advertising`, `#privacy`, `#data-driven marketing`, `#consumer behavior`

---

<a id="item-26"></a>
## [Alleged Scattered Spider Hacker Arrested in Finland](https://www.bbc.co.uk/news/articles/cwy0we4yw1lo?at_medium=RSS&at_campaign=rss) ⭐️ 6.0/10

A 19-year-old dual American-Estonian national, allegedly a member of the Scattered Spider hacking group, was arrested in Finland and extradited to the United States to face federal charges. This arrest marks a significant law enforcement action against a notorious cybercriminal group responsible for high-profile attacks, including the 2023 MGM Resorts ransomware incident, and may deter other young hackers. The suspect is charged in connection with cyberattacks targeting multiple U.S. companies, and the arrest followed a coordinated effort between Finnish and U.S. authorities.

rss · BBC World News · Jul 2, 08:02

**Background**: Scattered Spider, also known as UNC3944 or Octo Tempest, is a hacking group primarily composed of teens and young adults from the U.S. and U.K. They are known for using social engineering and SIM-swapping to breach corporate networks, and have been linked to ransomware attacks and data theft.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Scattered_Spider">Scattered Spider - Wikipedia</a></li>
<li><a href="https://www.justice.gov/opa/pr/alleged-member-criminal-cyber-hacking-group-scattered-spider-arrested-finland-and-extradited">Office of Public Affairs | Alleged Member of Criminal Cyber Hacking Group “Scattered Spider” Arrested in Finland and Extradited to the United States | United States Department of Justice</a></li>
<li><a href="https://www.cybersecuritydive.com/news/what-we-know-about-the-cybercrime-group-scattered-spider/756312/">What we know about the cybercrime group Scattered Spider | Cybersecurity Dive</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#hacking`, `#arrest`, `#Scattered Spider`

---

<a id="item-27"></a>
## [AFP probes Australian citizen for alleged Gaza war crimes](https://www.theguardian.com/australia-news/2026/jul/03/afp-investigating-alleged-war-crimes-committed-by-australian-citizen-serving-in-idf-in-gaza-ntwnfb) ⭐️ 6.0/10

Australian Federal Police are assessing a 61-page brief detailing alleged war crimes committed by an Australian citizen serving in an IDF battalion in Gaza during 2023 and 2024. This marks a rare instance of Australia investigating its own citizen for alleged war crimes abroad, potentially setting a precedent for accountability under Australian law for actions in foreign conflicts. The brief was submitted by the Australian Centre for International Justice and includes allegations of deliberate targeting and destruction of residential buildings without military justification.

rss · The Guardian World · Jul 2, 19:44

**Background**: The Australian Federal Police (AFP) has jurisdiction to investigate crimes against Commonwealth law, including war crimes committed by Australian citizens abroad. The Office of the Special Investigator (OSI) has previously investigated Australian Defence Force personnel for war crimes in Afghanistan, but this case involves a citizen serving in a foreign military.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Israeli_war_crimes_in_the_Gaza_war">Israeli war crimes in the Gaza war - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Australian_Federal_Police">Australian Federal Police - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Office_of_the_Special_Investigator">Office of the Special Investigator - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#war crimes`, `#Australian politics`, `#international law`, `#IDF`, `#Gaza`

---

<a id="item-28"></a>
## [Developer Builds 216.5M Parameter SLM from Scratch](https://www.reddit.com/r/MachineLearning/comments/1um013f/looking_for_feedback_on_a_small_test_slm_i_built/) ⭐️ 6.0/10

A developer trained a 216.5M parameter small language model (SLM) from scratch using a custom SentencePiece unigram tokenizer and a decoder-only transformer with RoPE and SwiGLU, achieving a final loss of 1.27 after 33,650 steps on a single RTX 3080. This project demonstrates that meaningful SLMs can be built with limited resources, providing a practical reference for hobbyists and researchers. The detailed architecture and training insights, especially the importance of tokenizer quality, can help others avoid common pitfalls. The model uses 10 layers, 12-head attention with head_dim 86, hidden size 1032, and FFN size 4416. It was pretrained on 551M tokens from public English datasets and fine-tuned on instruction data, with a notable loss drop at the SFT transition.

reddit · r/MachineLearning · /u/nkthebass · Jul 3, 00:58

**Background**: Small language models (SLMs) are compact transformer models designed for efficiency and accessibility. Key techniques used here include Rotary Positional Embeddings (RoPE) for encoding token positions, SwiGLU activation for feed-forward networks, and SentencePiece unigram tokenization for subword processing. The Chinchilla scaling law suggests an optimal token-to-parameter ratio of about 20:1, but this model uses only ~2.5:1.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/ai-insights-cobet/rotary-positional-embeddings-a-detailed-look-and-comprehensive-understanding-4ff66a874d83">Rotary Positional Embeddings: A Detailed Look and Comprehensive Understanding | by azhar | azhar labs | Medium</a></li>
<li><a href="https://medium.com/@s_boudefel/exploring-swiglu-the-activation-function-powering-modern-llms-9697f88221e7">Exploring SwiGLU : The Activation Function Powering Modern ...</a></li>
<li><a href="https://github.com/google/sentencepiece">GitHub - google/sentencepiece: Unsupervised text tokenizer ... Tokenization with the SentencePiece Python Library Unigram tokenization - Hugging Face SentencePiece Tokenizer Explained: Subword NLP Guide SentencePiece: Subword Tokenization with BPE and Unigram Tokenizer Comparison - BPE vs WordPiece vs Unigram | Acadictive</a></li>

</ul>
</details>

**Tags**: `#SLM`, `#transformer`, `#pretraining`, `#machine learning`

---

<a id="item-29"></a>
## [How Top ML Conferences Select Best Papers and Orals](https://www.reddit.com/r/MachineLearning/comments/1ulnstb/how_papers_are_selected_for_best_paper_oral_or/) ⭐️ 6.0/10

A Reddit user asked how best paper, oral, and highlight selections are made at major ML/CV conferences like CVPR, NeurIPS, ICLR, and ECCV, sparking discussion on the roles of reviewers, area chairs (ACs), senior area chairs (SACs), and program committees. Understanding the selection process helps researchers better target their submissions and clarifies how the community recognizes impactful work, which influences career advancement and research directions. The selection typically involves multiple stages: reviewers provide scores and comments, ACs recommend candidates, SACs and program chairs make final decisions, and a separate awards committee may select best papers. Decisions are based on reviewer scores, novelty, impact, and AC discussions, not solely on scores.

reddit · r/MachineLearning · /u/National-Resident244 · Jul 2, 16:55

**Background**: Major ML/CV conferences receive thousands of submissions each year (e.g., CVPR 2026 had 16,092 submissions). Accepted papers are categorized as poster, spotlight, or oral, with oral being the most prestigious. Best paper awards are the highest honor. The process involves reviewers, area chairs, senior area chairs, and program chairs, each with specific roles in evaluating and selecting papers.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/SkalskiP/top-cvpr-2026-papers">GitHub - SkalskiP/top-cvpr-2026-papers: About This repository is a curated collection of the most exciting and influential CVPR 2026 papers. 🔥 [Paper + Code + Demo]</a></li>
<li><a href="https://cvpr.thecvf.com/Conferences/2026/News/Best_Papers">CVPR 2026 Honors the Year's Most Innovative Computer Vision and AI Research</a></li>
<li><a href="https://wiki.eventhosts.cc/topics/main-conference/orals-and-spotlights">Orals and Spotlights | Wiki.EventHosts NeurIPS/ICML/ICLR/CVPR and more</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion includes comments from users sharing their experiences and insights, with some noting that ACs often have significant influence and that the process can vary between conferences. There is general agreement that reviewer scores are not the sole factor, and that AC discussions and novelty play a crucial role.

**Tags**: `#machine learning`, `#conference`, `#paper selection`, `#CVPR`, `#NeurIPS`

---

<a id="item-30"></a>
## [PyMuPDF 1.28 Adds Native Markdown Support](https://www.reddit.com/r/MachineLearning/comments/1ukyciw/new_pymupdf_release_supports_markdown_n/) ⭐️ 6.0/10

PyMuPDF 1.28 introduces first-class Markdown support, allowing users to open, parse, render, and convert Markdown files natively, and create PDFs from Markdown with CSS styling. This enables streamlined Markdown-to-PDF workflows for documentation and report generation, which is particularly useful for the machine learning community when producing papers, notebooks, or technical reports. The new Markdown engine is exposed through the existing Document.save() method, giving users full control over PDF appearance via CSS. PyMuPDF 4LLM also supports direct conversion to LlamaIndex documents via Markdown.

reddit · r/MachineLearning · /u/Remote-Spirit526 · Jul 1, 21:15

**Background**: PyMuPDF is a high-performance Python library for data extraction, analysis, conversion, and manipulation of PDF and other document formats. Markdown is a lightweight markup language commonly used for formatting plain text. Previously, PyMuPDF did not treat Markdown as a native document format.

<details><summary>References</summary>
<ul>
<li><a href="https://pymupdf.io/blog/markdown-in-pymupdf-1-28">Explains PyMuPDF 1.28 and support for Markdown</a></li>
<li><a href="https://pymupdf.readthedocs.io/en/latest/pymupdf4llm/">PyMuPDF 4LLM - PyMuPDF documentation</a></li>
<li><a href="https://medium.com/@pymupdf/rag-llm-and-pdf-conversion-to-markdown-text-with-pymupdf-03af00259b5d">RAG/LLM and PDF : Conversion to Markdown Text with PyMuPDF</a></li>

</ul>
</details>

**Tags**: `#PyMuPDF`, `#PDF`, `#Markdown`, `#Document Processing`

---