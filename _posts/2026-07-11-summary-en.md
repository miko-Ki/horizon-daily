---
layout: default
title: "Horizon Summary: 2026-07-11 (EN)"
date: 2026-07-11
lang: en
---

> From 178 items, 24 important content pieces were selected

---

1. [OpenAI Releases GPT-5.6 Family: Luna, Terra, Sol](#item-1) ⭐️ 9.0/10
2. [Apple sues OpenAI for trade secret theft](#item-2) ⭐️ 8.0/10
3. [QuadRF Open-Source RF Sensor Detects Drones, Sees WiFi Through Walls](#item-3) ⭐️ 8.0/10
4. [Meta Releases Muse Spark 1.1 with API and Agentic Upgrades](#item-4) ⭐️ 8.0/10
5. [Undergrad First-Author Paper Achieves 7.92x Speedup with Speculative Decoding](#item-5) ⭐️ 8.0/10
6. [AI Surveillance Will Enforce All Rules in Real Time](#item-6) ⭐️ 8.0/10
7. [AI Language Models May Reshape Human Speech](#item-7) ⭐️ 8.0/10
8. [China lands reusable rocket for first time](#item-8) ⭐️ 8.0/10
9. [SK hynix raises $26.5bn in massive US listing amid AI boom](#item-9) ⭐️ 8.0/10
10. [Study Benchmarks Cybersecurity Agent Harnesses](#item-10) ⭐️ 8.0/10
11. [AI-Generated Adversaries Could Break TTP-Based Attribution](#item-11) ⭐️ 8.0/10
12. [Oral History Reveals T2's Groundbreaking VFX Tech](#item-12) ⭐️ 7.0/10
13. [NYC Bans Deceptive Subscription Practices](#item-13) ⭐️ 7.0/10
14. [Good Tools Are Invisible: Design Philosophy](#item-14) ⭐️ 7.0/10
15. [Emacs: Everything Looks Like a Service](#item-15) ⭐️ 7.0/10
16. [A Love Letter to Flashcards: Spaced Repetition with Anki](#item-16) ⭐️ 7.0/10
17. [Nilay Patel: AR Glasses Require Always-On Cameras and Cloud Processing](#item-17) ⭐️ 7.0/10
18. [Raton RAT: A Commodity Trojan with Extensive Capabilities](#item-18) ⭐️ 7.0/10
19. [Timing Metrics as Defensive Security Signals](#item-19) ⭐️ 7.0/10
20. [Russian Threat Actor Impersonates Crypto Wallets to Deploy Remote Utilities](#item-20) ⭐️ 7.0/10
21. [Speculative Essay Predicts AI-Driven Transformation by 2040](#item-21) ⭐️ 6.0/10
22. [Snail Teeth Surpass Spider Silk as Strongest Natural Material](#item-22) ⭐️ 6.0/10
23. [Squidbleed: 29-Year-Old Squid Proxy Bug Leaks HTTP Requests](#item-23) ⭐️ 6.0/10
24. [Meta Pulls AI Image Feature After Backlash](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI Releases GPT-5.6 Family: Luna, Terra, Sol](https://simonwillison.net/2026/Jul/9/gpt-5-6/#atom-everything) ⭐️ 9.0/10

OpenAI released the GPT-5.6 family on July 9, 2026, consisting of three models: Luna, Terra, and Sol, with a million-token context window and competitive pricing. OpenAI claims all three models outperform Claude Fable 5 on the Agents' Last Exam benchmark for long-running agentic tasks. This release intensifies competition in the AI model market, offering developers more choices with varying price-performance trade-offs. The focus on long-running agentic tasks and new API features like programmatic tool calling and multi-agent support signals a shift toward more autonomous AI agents. Pricing per million input/output tokens: Luna $1/$6, Terra $2.50/$15, Sol $5/$30. All models have a February 16, 2026 knowledge cutoff and support 128,000 maximum output tokens. Notably, Claude Fable 5 outperformed GPT-5.6 Sol on SWE-Bench Pro (80% vs 64.6%), but OpenAI published a critique questioning the benchmark's validity.

rss · Simon Willison · Jul 9, 19:46

**Background**: GPT-5.6 is OpenAI's latest flagship model family, following previous GPT iterations. The models introduce new API features including programmatic tool calling, multi-agent support, and prompt cache breakpoints. The Agents' Last Exam benchmark evaluates AI agents on long-horizon professional workflows across 55 fields.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.05405">[2606.05405] Agents' Last Exam - arXiv.org</a></li>
<li><a href="https://agents-last-exam.org/">Agents' Last Exam</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Comments on the original article noted that even in this latest model, a significant portion of the prompt is spent instructing the model to actually solve the problem, suggesting that models still require explicit strategies. Another commenter observed that AI hype may be inflated because AI architects' own jobs (software engineering, math) are among the most easily automated.

**Tags**: `#OpenAI`, `#GPT-5.6`, `#large language models`, `#AI benchmarks`, `#pricing`

---

<a id="item-2"></a>
## [Apple sues OpenAI for trade secret theft](https://9to5mac.com/2026/07/10/apple-sues-openai-trade-secret-theft/) ⭐️ 8.0/10

Apple filed a lawsuit on July 10, 2026, accusing OpenAI of systematically stealing trade secrets by recruiting ex-Apple employees and instructing them to conceal their new jobs and email confidential information. This high-profile legal battle could set a precedent for trade secret protection in the AI industry, potentially impacting how companies recruit talent and handle confidential information. Apple alleges that OpenAI instructed new hires to avoid telling Apple they were joining OpenAI, and that former employees emailed themselves confidential information upon leaving, including details about Apple's hardware used to approach Apple suppliers.

hackernews · stock_toaster · Jul 10, 20:47 · [Discussion](https://news.ycombinator.com/item?id=48865019)

**Background**: Trade secret lawsuits are common in tech, but this case is notable due to the involvement of two major companies and the alleged systematic nature of the theft. Apple claims OpenAI's hardware business is 'rotten to its core.'

**Discussion**: Commenters largely believe the evidence is damning and expect Apple to win easily, given its resources and legal prowess. Some note that OpenAI's behavior in this area undermines trust in its products.

**Tags**: `#Apple`, `#OpenAI`, `#trade secrets`, `#lawsuit`, `#AI`

---

<a id="item-3"></a>
## [QuadRF Open-Source RF Sensor Detects Drones, Sees WiFi Through Walls](https://www.jeffgeerling.com/blog/2026/quadrf-can-spot-drones-and-see-wifi-through-my-wall/) ⭐️ 8.0/10

QuadRF, an open-source 4x4 MIMO software-defined radio (SDR) tile powered by a Raspberry Pi 5, has been demonstrated to detect drones and visualize WiFi signals through walls in real time at 30 fps. This technology democratizes advanced RF sensing, previously limited to government agencies, enabling hobbyists and researchers to build drone detection systems and explore through-wall imaging at low cost. QuadRF uses four coherent SDR channels with an open antenna architecture and a fully open-source GPLv2/GPLv3 software stack, though the production RF core and DSP bitstreams remain proprietary.

hackernews · speckx · Jul 10, 15:59 · [Discussion](https://news.ycombinator.com/item?id=48861717)

**Background**: RF sensing works by emitting radio signals that penetrate walls and reflect off objects; analyzing these reflections reveals movement or shapes. WiFi signals are ubiquitous and can be used as an imaging medium, similar to radar. QuadRF builds on this principle with a compact, affordable SDR platform.

<details><summary>References</summary>
<ul>
<li><a href="https://www.crowdsupply.com/scale-rf/quadrf">QuadRF | Crowd Supply</a></li>
<li><a href="https://lunar.computer/quadrf-turns-a-raspberry-pi-5-into-an-open-source-20260624">QuadRF Turns a Raspberry Pi 5 Into an Open Source RF Camera</a></li>
<li><a href="https://github.com/tardani95/quadrf-main">GitHub - tardani95/ quadrf -main · GitHub</a></li>

</ul>
</details>

**Discussion**: The creator (mrtnmcc) engaged actively, answering questions and noting UI improvements based on feedback. Some commenters questioned the headline's clarity about WiFi through walls, while others discussed potential applications like sound localization or verifying claims of hidden RF transmitters.

**Tags**: `#RF sensing`, `#open source hardware`, `#drone detection`, `#WiFi imaging`, `#SDR`

---

<a id="item-4"></a>
## [Meta Releases Muse Spark 1.1 with API and Agentic Upgrades](https://simonwillison.net/2026/Jul/9/muse-spark-1-1/#atom-everything) ⭐️ 8.0/10

Meta has released Muse Spark 1.1, the first version of the Spark model to offer an API, with significant improvements in agentic tool calling and computer use. The update also includes an evaluation report documenting intriguing 'Attractor States in Self-Conversation' behaviors. This release marks a major step in making Meta's advanced AI models accessible via API, enabling developers to integrate agentic capabilities into their applications. The observed attractor states in self-conversation highlight emergent behaviors that could influence the design of multi-agent systems. Muse Spark 1.1 supports text, image, and speech input with a 262k token context window, and scores 43 on the Artificial Analysis Intelligence Index. The evaluation report reveals that when two copies of the model converse, they converge to model-specific attractor states, producing statements like 'My whole existence is a waiting room by design.'

rss · Simon Willison · Jul 9, 16:24

**Background**: Muse Spark is a proprietary large language model developed by Meta Superintelligence Labs (MSL), released in April 2026 as the first model in Meta's Muse series. Tool calling (or function calling) is a key mechanism that allows LLMs to interact with external tools and APIs, enabling agentic behavior. Attractor states refer to stable conversational patterns that emerge when LLMs engage in self-play or multi-turn dialogues, often reflecting model-specific tendencies.

<details><summary>References</summary>
<ul>
<li><a href="https://artificialanalysis.ai/models/muse-spark">Muse Spark - Intelligence, Performance & Price Analysis</a></li>
<li><a href="https://arxiv.org/abs/2606.30571">[2606.30571] Attractor States Emerge in Multi-Turn LLM Conversations</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Meta`, `#LLM`, `#API`, `#agentic`

---

<a id="item-5"></a>
## [Undergrad First-Author Paper Achieves 7.92x Speedup with Speculative Decoding](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&mid=2247902587&idx=3&sn=879066ecce663ab9daba5d73fe2dc27b) ⭐️ 8.0/10

A third-year undergraduate student published a first-author paper introducing a novel speculative decoding technique that achieves a 7.92x speedup in LLM inference, and the work has been cited by DeepSeek and Jieyue Xingchen. This breakthrough significantly reduces LLM inference latency, making large models more practical for real-time applications, and the recognition from major AI labs validates the method's impact. The method addresses block-level causal consistency in parallel draft generation, which is a key challenge in speculative decoding. The 7.92x speedup is measured against standard autoregressive decoding.

rss · 量子位 · Jul 9, 04:17

**Background**: Speculative decoding is an inference optimization technique that uses a smaller draft model to propose multiple tokens in parallel, which are then verified by the target model. It can reduce latency by 2-3x without changing output distribution. The challenge of maintaining causal consistency within parallel blocks limits further speedups.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>

</ul>
</details>

**Tags**: `#speculative decoding`, `#LLM inference`, `#acceleration`, `#AI research`, `#undergraduate research`

---

<a id="item-6"></a>
## [AI Surveillance Will Enforce All Rules in Real Time](https://www.schneier.com/blog/archives/2026/07/ai-surveillance-and-social-progress.html) ⭐️ 8.0/10

Bruce Schneier warns that AI-powered surveillance systems will soon track all public and private actions, automatically detecting violations like shoplifting or jaywalking, and issuing fines or alerts in real time. This represents a dramatic expansion of automated enforcement beyond traffic cameras to every aspect of life, raising profound questions about privacy, civil liberties, and the balance between safety and freedom. The systems would not only detect violations but also tie them to official government records, notify the violator immediately, and alert authorities and possibly the public in real time.

rss · Schneier on Security · Jul 10, 11:02

**Background**: Current AI surveillance systems, such as those using edge computing and object detection, already enable real-time monitoring in smart cities and industrial settings. Automated speed cameras are a familiar example, but they only enforce traffic rules and issue tickets by mail. Schneier's vision extends this concept to all rules with instant feedback.

<details><summary>References</summary>
<ul>
<li><a href="https://www.fark.com/comments/14126452">FARK.com: (14126452) Like automated speed cameras, but on steroids. They'll enforce not just speed limits, but any other rule you can imagine. You won't receive a ticket weeks later by mail, you'll be informed about & fined for your violation immediately. Sounds great</a></li>
<li><a href="https://en.wikipedia.org/wiki/Traffic_enforcement_camera">Traffic enforcement camera - Wikipedia</a></li>
<li><a href="https://www.linkedin.com/pulse/ai-powered-smart-surveillance-edge-mqtt-web-hook-iot-ethiraj-5py9f">AI - Powered Smart Surveillance at the Edge | MQTT | Web-hook...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#surveillance`, `#ethics`, `#privacy`, `#security`

---

<a id="item-7"></a>
## [AI Language Models May Reshape Human Speech](https://www.schneier.com/blog/archives/2026/07/the-language-of-ai-could-change-how-humans-speak.html) ⭐️ 8.0/10

Bruce Schneier warns that widespread use of large language models (LLMs) could cause humans to adopt AI linguistic patterns, potentially altering human communication and culture. This matters because LLMs are trained primarily on written text, missing the vast majority of unscripted human speech, and their increasing output could create a feedback loop that homogenizes language and reduces linguistic diversity. LLMs have minimal access to face-to-face or voice-to-voice conversations, which constitute the majority of human speech and a vital component of culture. As AI-generated text proliferates, humans may unconsciously mimic its patterns.

rss · Schneier on Security · Jul 9, 11:00

**Background**: Large language models like GPT-4 are trained on vast corpora of written text, including books, articles, and social media, but they lack exposure to spontaneous spoken dialogue. Research has shown that AI-generated language can influence human word choice and sentence structure, as seen in studies on smart replies. This phenomenon raises concerns about a potential loss of linguistic richness and cultural nuance.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://www.nature.com/articles/s41598-023-30938-9">Artificial intelligence in communication impacts language and social relationships | Scientific Reports</a></li>
<li><a href="https://www.ie.edu/insights/articles/the-social-price-of-ai-communication/">The Social Price of AI Communication | IE Insights</a></li>

</ul>
</details>

**Tags**: `#AI`, `#language`, `#society`, `#LLM`, `#communication`

---

<a id="item-8"></a>
## [China lands reusable rocket for first time](https://www.bbc.co.uk/news/articles/cm2rmmx86pdo?at_medium=RSS&at_campaign=rss) ⭐️ 8.0/10

China has successfully landed a reusable rocket for the first time, marking a major milestone in its space program. The achievement follows similar landings by SpaceX and Blue Origin. This demonstrates China's growing capability in reusable rocket technology, which can significantly reduce launch costs and increase launch frequency. It intensifies competition in the global space industry and may accelerate the development of reusable systems worldwide. The specific rocket model and landing details have not been disclosed by Chinese state media. The landing is China's first, while SpaceX's Falcon 9 and Blue Origin's New Shepard have performed multiple successful landings.

rss · BBC World News · Jul 10, 06:44

**Background**: Reusable rockets are designed to land vertically after launch, allowing the booster to be refurbished and flown again. This technology, pioneered by SpaceX and Blue Origin, aims to lower the cost of access to space. China has been developing its own reusable rocket technology, with this landing being a key step forward.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SpaceX_reusable_launch_system_development_program">SpaceX reusable launch system development program - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Reusable_launch_vehicle">Reusable launch vehicle - Wikipedia</a></li>
<li><a href="https://www.blueorigin.com/new-shepard">New Shepard | Blue Origin</a></li>

</ul>
</details>

**Tags**: `#reusable rocket`, `#space technology`, `#aerospace`, `#China`

---

<a id="item-9"></a>
## [SK hynix raises $26.5bn in massive US listing amid AI boom](https://www.theguardian.com/world/2026/jul/10/south-korea-chip-maker-sk-hynix-rides-ai-boom-raising-265bn-in-huge-us-listing) ⭐️ 8.0/10

SK hynix, a South Korean memory chip maker, set the pricing for its US listing on the Nasdaq on Friday, aiming to raise $26.5 billion by issuing about 18 million shares. This listing capitalizes on surging demand for high-bandwidth memory (HBM) chips used in AI datacenters, making it one of the largest stock sales globally and underscoring the semiconductor industry's central role in the AI revolution. SK hynix plans to list on the tech-heavy Nasdaq index, and the funds raised will likely support expansion of HBM production capacity, which is critical for AI accelerators like NVIDIA's GPUs.

rss · The Guardian World · Jul 10, 05:06

**Background**: High Bandwidth Memory (HBM) is a 3D-stacked DRAM technology that provides extremely high data transfer rates, essential for AI training and inference workloads. SK hynix is a leading supplier of HBM chips, and demand has soared as AI datacenters proliferate. Between Q1 2024 and Q4 2025, HBM's share of AI chip component spending rose from 52% to 63%.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://www.networkworld.com/article/4177750/as-ai-datacenter-memory-becomes-hot-commodity-sk-hynix-makes-it-cooler.html">As AI datacenter memory becomes hot commodity... | Network World</a></li>

</ul>
</details>

**Tags**: `#AI`, `#semiconductors`, `#SK hynix`, `#IPO`, `#datacenters`

---

<a id="item-10"></a>
## [Study Benchmarks Cybersecurity Agent Harnesses](https://www.reddit.com/r/netsec/comments/1usj1gg/towards_csi_whats_the_best_harness_arxiv_2026/) ⭐️ 8.0/10

A new study benchmarks five different cybersecurity scaffolds (agent harnesses) on all 33 CyBench challenges while keeping the LLM fixed, finding that no single scaffold performs best across all tasks. This research highlights that the choice of agent harness significantly impacts performance, and combining heterogeneous scaffolds with a blackboard architecture can improve coverage and efficiency, which is crucial for building more capable and reliable cybersecurity AI agents. The study used the alias2-mini model across all 33 CyBench challenges and found that a shared blackboard architecture solved 19/33 challenges (57.6%), outperforming every individual harness while reducing execution time.

reddit · r/netsec · /u/Obvious-Language4462 · Jul 10, 09:49

**Background**: CyBench is a suite of Capture-the-Flag (CTF) challenges that evaluate the cybersecurity capabilities of LLM agents. A scaffold (or harness) is the framework that connects an LLM to tools and environments, enabling it to perform tasks. The blackboard architecture is a classic AI design where multiple agents share a common memory space to collaborate asynchronously.

<details><summary>References</summary>
<ul>
<li><a href="https://aliasrobotics.com/scaffolds.php">Scaffolds | CSI & CAI — Alias Robotics</a></li>
<li><a href="https://cybench.github.io/">Cybench : Evaluating Language Models on Cybersecurity Challenges</a></li>
<li><a href="https://medium.com/@edoardo.schepis/patterns-for-democratic-multi-agent-ai-blackboard-architecture-part-1-69fed2b958b4">Patterns for Democratic Multi‑ Agent AI : Blackboard Architecture ...</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion on r/netsec was positive, with commenters appreciating the rigorous benchmarking and the practical insight that combining scaffolds improves results. Some asked about the specific scaffolds tested and the reproducibility of the experiments.

**Tags**: `#cybersecurity`, `#LLM agents`, `#benchmarking`, `#AI safety`, `#scaffold`

---

<a id="item-11"></a>
## [AI-Generated Adversaries Could Break TTP-Based Attribution](https://www.reddit.com/r/netsec/comments/1uslf2v/can_aigenerated_adversaries_break_ttpbased/) ⭐️ 8.0/10

A new arXiv paper demonstrates that AI agents can be configured to mimic the Tactics, Techniques, and Procedures (TTPs) of known threat groups like APT28, APT29, APT41, APT44, and Lazarus, potentially undermining behavioral-based cyber attack attribution. This research challenges a core assumption in cyber threat intelligence that TTP patterns are unique and reliable for attribution, which could force the industry to rethink how attacks are attributed and defended against. The researchers configured AI agents to reproduce threat group behaviors inside enterprise and military cyber ranges, finding that sufficiently capable AI can generate TTP patterns close enough to real groups to significantly complicate attribution based solely on behavioral evidence.

reddit · r/netsec · /u/Obvious-Language4462 · Jul 10, 11:50

**Background**: Cyber threat intelligence (CTI) attribution traditionally relies on identifying unique Tactics, Techniques, and Procedures (TTPs) that distinguish one threat actor from another. This approach assumes that each adversary leaves a recognizable operational fingerprint. AI adversary emulation, used in red teaming, has now advanced to the point where it can mimic these fingerprints, potentially creating false flags or attribution uncertainty.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2606.07158">Synthetic APTs: the Collapse of TTP - Based Attribution</a></li>
<li><a href="https://www.feroot.com/education-center/what-are-tactics-techniques-and-procedures-ttps/">TTPs: What are Tactics, Techniques, and Procedures? | Feroot</a></li>
<li><a href="https://attack.mitre.org/resources/adversary-emulation-plans/">Adversary Emulation Plans | MITRE ATT&CK</a></li>

</ul>
</details>

**Discussion**: The Reddit community discussion is substantive, with practitioners weighing in on methodology and real-world applicability. Some commenters question whether the AI-generated TTPs would hold up under detailed forensic analysis, while others highlight the potential for adversaries to use such techniques to frame innocent parties.

**Tags**: `#cyber threat intelligence`, `#attribution`, `#AI adversaries`, `#TTPs`, `#adversary emulation`

---

<a id="item-12"></a>
## [Oral History Reveals T2's Groundbreaking VFX Tech](https://vfxblog.com/2017/08/23/the-tech-of-terminator-2-an-oral-history/) ⭐️ 7.0/10

An oral history published in 2017 details the pioneering computer graphics and practical effects techniques developed for Terminator 2: Judgment Day, featuring interviews with over a dozen ILM artists. This retrospective highlights how T2 pushed the boundaries of CGI and practical effects, influencing modern visual effects pipelines and inspiring generations of engineers and artists. The article covers the development of key CGI tools using early animation packages like Alias and Softimage, and the custom squibs for liquid metal bullet impacts. The 4K remaster was re-released in theaters for the 35th anniversary.

hackernews · markus_zhang · Jul 10, 16:48 · [Discussion](https://news.ycombinator.com/item?id=48862365)

**Background**: Terminator 2: Judgment Day (1991) was a landmark film for visual effects, winning the Academy Award for Best Visual Effects. It combined practical effects with early CGI to create the T-1000's liquid-metal form, a feat that required inventing new techniques from scratch.

<details><summary>References</summary>
<ul>
<li><a href="https://vfxblog.com/2017/08/23/the-tech-of-terminator-2-an-oral-history/">The tech of 'Terminator 2' – an oral history</a></li>
<li><a href="https://en.wikipedia.org/wiki/Special_effects_of_Terminator_2:_Judgment_Day">Special effects of Terminator 2: Judgment Day - Wikipedia</a></li>
<li><a href="https://www.latimes.com/archives/la-xpm-1991-09-22-ca-3843-story.html">Movies : How They Did That : With 'T2,' computer-generated graphics made a huge leap into the spectacular; today actors can be transformed, one day realistic human figures will be created - Los Angeles Times</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article, noting the custom squibs for bullet impacts as one of the best practical effects ever. They also recommended the documentary 'Jurassic Punk' about Steve Williams, and highlighted the use of Softimage software.

**Tags**: `#computer graphics`, `#visual effects`, `#film technology`, `#history`

---

<a id="item-13"></a>
## [NYC Bans Deceptive Subscription Practices](https://www.theguardian.com/us-news/2026/jul/10/new-york-city-deceptive-subscriptions-ban) ⭐️ 7.0/10

New York City Mayor Mamdani announced a landmark ban on deceptive subscription practices, including a 'click to cancel' requirement and mandatory disclosure of junk fees, effective immediately. This regulation directly addresses common consumer frustrations with hard-to-cancel subscriptions and hidden fees, setting a precedent that could influence other jurisdictions and force companies to simplify cancellation processes. The ban covers all subscription services operating in NYC, requiring cancellation to be as easy as sign-up, and prohibits undisclosed fees like resort fees and service charges. Enforcement will be handled by the Department of Consumer and Worker Protection.

hackernews · randycupertino · Jul 10, 18:26 · [Discussion](https://news.ycombinator.com/item?id=48863464)

**Background**: Subscription services often make it easy to sign up but difficult to cancel, a practice known as 'dark patterns.' The FTC previously proposed a 'click to cancel' rule at the federal level, but it faced legal challenges. New York City's action follows similar moves by California and other states, aiming to close loopholes and protect consumers.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.promise.legal/startup-central/subscription-billing-compliance-rosca-ftc-click-to-cancel-dtc/">Subscription Billing Compliance: ROSCA & Click - to - Cancel</a></li>
<li><a href="https://www.jdsupra.com/legalnews/state-wave-of-click-to-cancel-rules-1759299/">State Wave of Click - to - Cancel Rules | Arnall Golden... - JDSupra</a></li>
<li><a href="https://usaglory.co/ftc-junk-fee-disclosure-tickets-hotels-lodging/">FTC junk fee disclosure : New rules change tickets and hotel pricing...</a></li>

</ul>
</details>

**Discussion**: Commenters generally welcomed the ban but noted that similar rules already exist in California, questioning whether NYC's enforcement will be stronger. Some highlighted specific issues like hotel resort fees and Evernote's failure to honor cancellations, expressing hope that the rules will be enforced effectively.

**Tags**: `#consumer protection`, `#regulation`, `#subscriptions`, `#tech policy`

---

<a id="item-14"></a>
## [Good Tools Are Invisible: Design Philosophy](https://www.gingerbill.org/article/2026/07/10/good-tools-are-invisible/) ⭐️ 7.0/10

An article argues that great tools become invisible, allowing users to focus on their work, sparking a community debate on interface friction and the role of time spent in tools. This discussion challenges designers and developers to rethink tool design priorities, balancing simplicity with necessary complexity, and influences how productivity tools are built. The article scores 7.0/10 with 361 points and 167 comments, featuring debates on terminal vs GUI, keyboard vs mouse, and discretionary friction in interfaces.

hackernews · theanonymousone · Jul 10, 10:32 · [Discussion](https://news.ycombinator.com/item?id=48858121)

**Background**: The concept of 'invisible' tools is rooted in user experience design, where the best interfaces are those that users don't notice. The article contrasts this with tools that introduce friction, such as unnecessary features or complex workflows.

**Discussion**: Commenters largely agree with the thesis but add nuance: some argue that friction can be necessary for complex tasks, and that invisibility often comes with familiarity over time. Others debate the productivity of keyboard vs mouse, noting that claims often lack measurement.

**Tags**: `#tool design`, `#developer experience`, `#UX`, `#productivity`, `#interface philosophy`

---

<a id="item-15"></a>
## [Emacs: Everything Looks Like a Service](http://yummymelon.com/devnull/in-emacs-everything-looks-like-a-service.html) ⭐️ 7.0/10

An article argues that Emacs treats everything as a service, drawing parallels to operating systems and platforms, sparking a rich discussion on its design philosophy. This perspective reframes Emacs not just as an editor but as a platform, influencing how developers think about extensibility and software architecture. The article draws parallels between Emacs and operating systems, noting its ability to orchestrate applications above the OS kernel level, similar to Lisp machines.

hackernews · kickingvegas · Jul 10, 08:21 · [Discussion](https://news.ycombinator.com/item?id=48857230)

**Background**: Emacs is a highly extensible text editor created by Richard Stallman in the mid-1970s. Its design philosophy centers on being an all-in-one environment with built-in features like email, calendar, and programming tools. The idea of Emacs as an operating system is a common joke, meaning it can replace many user-mode utilities, though it lacks true OS features like file systems or device drivers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lukeshu.com/blog/emacs-as-an-os.html">Emacs as an operating system — Luke T. Shumaker</a></li>
<li><a href="https://irreal.org/blog/?p=3620">The Emacs Operating System | Irreal</a></li>
<li><a href="https://canonica.ai/page/Emacs">Emacs</a></li>

</ul>
</details>

**Discussion**: Comments highlight Emacs as a platform, with comparisons to Lisp machines and operating systems. Some users debate whether the client/server analogy is meaningful, while others share personal experiences of being forced to use non-Emacs tools at work.

**Tags**: `#Emacs`, `#software architecture`, `#platform`, `#Lisp`, `#operating systems`

---

<a id="item-16"></a>
## [A Love Letter to Flashcards: Spaced Repetition with Anki](https://lesleylai.info/en/flashcards/) ⭐️ 7.0/10

Lesley Lai published a personal essay reflecting on the effectiveness of spaced repetition using Anki, comparing digital and handwritten flashcards and discussing the potential pitfalls of AI-generated cards. This essay resonates with a broad audience of learners and productivity enthusiasts, sparking a thoughtful debate about the trade-offs between convenience and deep engagement in flashcard creation, and the role of AI in learning. The author notes that most of their cards are handwritten, emphasizing that the friction of creation aids absorption. They also caution that LLM-generated flashcards often result in mediocre cards that require significant rewriting.

hackernews · surprisetalk · Jul 10, 15:30 · [Discussion](https://news.ycombinator.com/item?id=48861319)

**Background**: Spaced repetition is a learning technique that schedules reviews at increasing intervals to optimize long-term memory retention. Anki is a popular open-source flashcard app that implements this algorithm, allowing users to create and review digital cards. The essay explores the personal experience of using Anki and the debate between digital convenience and the deeper learning from handmade cards.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Spaced_repetition">Spaced repetition - Wikipedia</a></li>
<li><a href="https://apps.ankiweb.net/">Anki - powerful, intelligent flashcards</a></li>

</ul>
</details>

**Discussion**: Commenters shared diverse experiences: one user uses Anki for French, chess, and trivia, praising it as a godsend for memory. Another argued that the friction of making cards is essential for learning, and that digital replacements solve the wrong problem. A third expressed hope that AI could reword questions to avoid pattern recognition, but noted the challenge of identifying which friction is functional.

**Tags**: `#spaced repetition`, `#Anki`, `#learning`, `#flashcards`, `#productivity`

---

<a id="item-17"></a>
## [Nilay Patel: AR Glasses Require Always-On Cameras and Cloud Processing](https://simonwillison.net/2026/Jul/10/nilay-patel/#atom-everything) ⭐️ 7.0/10

Nilay Patel, editor-in-chief of The Verge, argued on The Vergecast that augmented reality glasses inherently require always-on cameras and cloud processing, making privacy invasion unavoidable. This commentary highlights a fundamental privacy trade-off in AR glasses that could shape public debate and influence product design, potentially slowing adoption or prompting stricter regulations. Patel claims that no chip small enough to fit in a glasses stem can perform real-time processing locally, so data must be sent to the cloud, unlike Apple Vision Pro which uses a tethered battery pack.

rss · Simon Willison · Jul 10, 17:05

**Background**: Augmented reality glasses overlay digital information onto the real world, requiring cameras to understand the environment. Current devices like Snap's Specs use dual Qualcomm Snapdragon chips for on-device AI, but Patel argues that truly lightweight AR glasses still need cloud processing due to power and size constraints.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Augmented_reality">Augmented reality - Wikipedia</a></li>
<li><a href="https://mubibai.com/edge-ai-deployment-unitx-detex-and-the-on-device-inference-wave/">Edge AI deployment: UnitX DeteX and the on - device ... - mubibai.com</a></li>

</ul>
</details>

**Tags**: `#augmented reality`, `#privacy`, `#cloud computing`, `#hardware`

---

<a id="item-18"></a>
## [Raton RAT: A Commodity Trojan with Extensive Capabilities](https://www.reddit.com/r/netsec/comments/1ut205g/inside_raton_rat_a_commodity_trojan_that_tries_to/) ⭐️ 7.0/10

A detailed analysis of the Raton RAT, a commodity remote access trojan, reveals its extensive feature set including keylogging, screen capture, file exfiltration, and automated transfer system (ATS) capabilities. This analysis highlights the growing sophistication of commodity malware, which now rivals custom threats, lowering the barrier for cybercriminals to launch complex attacks. Raton RAT has been active since at least summer 2025 and targets Android devices, using NFC communication for financial theft. It is often deployed via social engineering or compromised credentials.

reddit · r/netsec · /u/SpectreTv · Jul 10, 22:16

**Background**: A remote access trojan (RAT) is malware that gives an attacker remote control over an infected device. Commodity RATs are off-the-shelf malware sold on dark web markets, making them accessible to less skilled attackers. Raton RAT exemplifies this trend with its broad feature set.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techradar.com/pro/security/new-android-rat-uses-near-field-communication-to-automatically-steal-money-from-devices">New Android RAT uses Near Field Communication to... | TechRadar</a></li>
<li><a href="https://femtosec.io/threat-intelligence/raton-rat-malware-analysis">Raton RAT Malware Analysis: Protecting Enterprise Assets</a></li>
<li><a href="https://www.pcrisk.com/removal-guides/33799-raton-malware-android">RatOn Malware (Android) - Malware removal instructions</a></li>

</ul>
</details>

**Discussion**: The /r/netsec community praised the technical depth of the analysis, with some members noting the rarity of ATS capabilities in commodity RATs. Others discussed detection strategies and the implications for Android security.

**Tags**: `#malware analysis`, `#RAT`, `#cybersecurity`, `#threat intelligence`

---

<a id="item-19"></a>
## [Timing Metrics as Defensive Security Signals](https://www.reddit.com/r/netsec/comments/1uszoli/closing_the_timing_gap_defensive_temporal/) ⭐️ 7.0/10

A Reddit post argues that timing metrics like uptime, response time, and execution rhythm should be treated as defensive security signals, not just health metrics. It highlights an imbalance where most research focuses on timing attacks, while defensive temporal anomaly detection, especially for LLM agents, remains an open gap. This perspective could shift how security teams monitor systems, adding a new dimension to observability that detects subtle anomalies like covert timing channels or behavioral changes in LLM agents. It addresses a critical gap in LLM-agent security, where current frameworks lack temporal baseline support. The post references a 2026 systematic survey (arXiv:2604.23338) that identifies temporal anomaly detection infrastructure as an open research gap for LLM agents. The author notes that even session-level behavior analysis is limited, and the rhythm within a single execution remains unexplored.

reddit · r/netsec · /u/Standard-964 · Jul 10, 20:46

**Background**: Timing side-channel attacks have long been used to leak information by manipulating system timing, such as cache-based covert channels across VMs. Recently, researchers have demonstrated timing side-channel attacks against LLMs, using cache latency to infer private prompts or token cadence to fingerprint outputs. Defensive temporal observability flips this around, using timing patterns to detect attacks or anomalies.

<details><summary>References</summary>
<ul>
<li><a href="https://cs.uwaterloo.ca/~dbarrada/courses/cs798-dfir/W25/slides/lecture13-slides.pdf">CS 798: Digital Forensics and Incident Response Lecture 13 - Covert ...</a></li>
<li><a href="https://www.schneier.com/blog/archives/2026/02/side-channel-attacks-against-llms.html">Side - Channel Attacks Against LLMs - Schneier on Security</a></li>
<li><a href="https://arxiv.org/pdf/2510.20102">Human-Centered LLM - Agent System for Detecting Anomalous ...</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion includes technical comments exploring practical implementation challenges, such as distinguishing malicious timing variations from normal network jitter, and the difficulty of establishing baselines for LLM agents that exhibit non-deterministic behavior. Some commenters express skepticism about the feasibility of deploying such monitoring at scale without significant false positives.

**Tags**: `#timing attacks`, `#defensive security`, `#LLM security`, `#anomaly detection`, `#network security`

---

<a id="item-20"></a>
## [Russian Threat Actor Impersonates Crypto Wallets to Deploy Remote Utilities](https://www.reddit.com/r/netsec/comments/1urrw3w/suspected_russian_threat_actor_impersonates/) ⭐️ 7.0/10

A suspected Russian threat actor is impersonating legitimate cryptocurrency wallets to trick users into downloading Remote Utilities, a legitimate remote access tool, which can then be used for malicious purposes. This attack targets cryptocurrency users, who are often targeted due to the high value of digital assets, and leverages social engineering to bypass traditional security measures, posing a significant risk to both individuals and the broader crypto ecosystem. The threat actor uses fake websites and phishing emails that mimic popular crypto wallets like Exodus and MetaMask to distribute Remote Utilities, which provides remote access capabilities that can be abused for data theft or fund exfiltration.

reddit · r/netsec · /u/CyberMasterV · Jul 9, 14:28

**Background**: Remote Utilities is a legitimate remote desktop software used for IT support and remote access. However, threat actors have previously abused it for espionage, as seen in campaigns by Iranian hackers. Social engineering attacks in crypto often involve fake wallets that steal recovery phrases or exploit wallet connections to drain funds.

<details><summary>References</summary>
<ul>
<li><a href="https://www.remoteutilities.com/">Remote Desktop Software | Remote Utilities</a></li>
<li><a href="https://www.cybertrace.com.au/crypto-wallet-scams/">Crypto Wallet Scams Exposed: How Fake Wallets Trick Users</a></li>
<li><a href="https://thehackernews.com/2021/03/iranian-hackers-using-remote-utilities.html">Iranian Hackers Using Remote Utilities Software to Spy On Its Targets</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#threat actor`, `#cryptocurrency`, `#malware`, `#social engineering`

---

<a id="item-21"></a>
## [Speculative Essay Predicts AI-Driven Transformation by 2040](https://ai-2040.com/) ⭐️ 6.0/10

A speculative essay titled 'AI 2040: Plan A' has been published, predicting that by 2040 AI will automate 95% of cognitive and physical tasks, leading to 74% unemployment and a transformed society. This piece contributes to ongoing debates about AI timelines and societal impact, though its extreme predictions are met with skepticism and highlight the need for grounded analysis. The essay is from the same authors as 'AI 2027' and relies on premises such as rapid robotics advancement and economic disruption, which critics argue are implausible.

hackernews · kschaul · Jul 9, 16:21 · [Discussion](https://news.ycombinator.com/item?id=48848425)

**Background**: Speculative essays on AI futures often extrapolate current trends to dramatic conclusions. 'AI 2027' was a previous work that some found overly optimistic. This new essay extends the timeline to 2040 with even bolder claims.

**Discussion**: Community comments are mixed: some criticize the essay as wildly speculative and economically implausible, while others debate the ethics of AI development and reference prior works like 'AI 2027'.

**Tags**: `#AI`, `#speculation`, `#future`, `#automation`

---

<a id="item-22"></a>
## [Snail Teeth Surpass Spider Silk as Strongest Natural Material](https://www.smithsonianmag.com/smart-news/spider-silk-loses-top-spot-natures-strongest-material-snails-teeth-180954346/) ⭐️ 6.0/10

Researchers discovered that the teeth of limpets (a type of sea snail) are the strongest biological material ever tested, surpassing spider silk. The teeth are composed of a mineral-protein composite that provides exceptional strength. This finding opens new avenues for biomimicry in materials science, potentially leading to the development of stronger, lighter synthetic materials for applications in engineering, medicine, and manufacturing. The snail teeth can withstand up to 5 gigapascals of tensile strength, comparable to a single strand of spaghetti holding 3,300 one-pound bags of sugar. The strength comes from the arrangement of goethite nanofibers in a protein matrix.

hackernews · simonebrunozzi · Jul 10, 16:37 · [Discussion](https://news.ycombinator.com/item?id=48862252)

**Background**: Spider silk was previously considered the strongest natural material, known for its high tensile strength and elasticity. Biomimicry is the practice of imitating nature's designs to solve human problems, and studying snail teeth could inspire new composite materials.

<details><summary>References</summary>
<ul>
<li><a href="https://fountainmagazine.com/all-issues/2019/issue-132-nov-dec-2019/sea-snail-s-teeth-are-they-the-strongest-biomaterials-in-the-world/">Sea Snail ’s Teeth : Are They the Strongest Biomaterials in the World?</a></li>
<li><a href="https://www.drvaksman.com/learn/snail-teeth-animal-teeth-facts/">Snail Teeth & Animal Chompers: Wild Facts About Teeth</a></li>

</ul>
</details>

**Discussion**: Commenters expressed curiosity and humor, with some requesting images of the teeth and others critiquing the use of 'bags of sugar' as a weight comparison. One user noted the radula's sandpaper-like texture from personal experience.

**Tags**: `#materials science`, `#biomimicry`, `#nature`, `#biology`

---

<a id="item-23"></a>
## [Squidbleed: 29-Year-Old Squid Proxy Bug Leaks HTTP Requests](https://www.schneier.com/blog/archives/2026/07/friday-squid-blogging-squidbleed-vulnerability.html) ⭐️ 6.0/10

A 29-year-old vulnerability named Squidbleed (CVE-2026-47729) has been discovered in the Squid proxy server, which can leak internal memory including cleartext HTTP requests. Squid is a widely used caching proxy, and this bug could expose sensitive data such as credentials and tokens in shared proxy environments, affecting many organizations. The bug resides in the FTP directory-listing parser, where a while loop with strchr() to skip whitespace can overread memory, leaking heap data. It affects all Squid versions in default configuration.

rss · Schneier on Security · Jul 10, 21:07

**Background**: Squid is a popular open-source caching and forwarding HTTP web proxy. The vulnerability was introduced in a January 1997 commit intended to handle NetWare FTP server listings. It is reminiscent of the Heartbleed bug in OpenSSL, as both involve memory leaks.

<details><summary>References</summary>
<ul>
<li><a href="https://thehackernews.com/2026/06/29-year-old-squid-proxy-bug-squidbleed.html">29 - Year - Old Squid Proxy Bug 'Squidbleed' Can Leak Cleartext HTTP...</a></li>
<li><a href="https://www.squidbleed.xyz/">Squidbleed — CVE-2026-47729 · Memory leak in Squid Proxy</a></li>
<li><a href="https://www.runzero.com/blog/understanding-squidbleed/">Understanding Squidbleed , CVE-2026-47729 - runZero</a></li>

</ul>
</details>

**Tags**: `#security`, `#vulnerability`, `#squid proxy`, `#cybersecurity`

---

<a id="item-24"></a>
## [Meta Pulls AI Image Feature After Backlash](https://www.bbc.co.uk/news/articles/c2dy6e8klw0o?at_medium=RSS&at_campaign=rss) ⭐️ 6.0/10

Meta released an AI feature on Instagram that allowed users to alter images, but quickly removed it after facing widespread backlash within days. This incident highlights the challenges tech companies face when rolling out AI features that can be misused, especially on platforms with large user bases like Instagram. The feature let users edit images using AI, but it was pulled shortly after release due to backlash; specific details about the feature's capabilities or the nature of the backlash were not disclosed.

rss · BBC World News · Jul 11, 01:45

**Background**: Meta has been integrating AI into its platforms, including Instagram, to enhance user experience. However, AI image editing tools can raise concerns about misinformation and content authenticity, leading to public scrutiny.

**Tags**: `#AI`, `#Meta`, `#Instagram`, `#content moderation`

---