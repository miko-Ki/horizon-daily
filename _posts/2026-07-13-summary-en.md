---
layout: default
title: "Horizon Summary: 2026-07-13 (EN)"
date: 2026-07-13
lang: en
---

> From 182 items, 14 important content pieces were selected

---

1. [vLLM v0.25.0: Model Runner V2 Default, PagedAttention Removed](#item-1) ⭐️ 9.0/10
2. [Fields Medalist Terry Tao Uses LLM Coding Agents for Apps](#item-2) ⭐️ 8.0/10
3. [Claude Code vs OpenCode: Token Overhead Comparison](#item-3) ⭐️ 8.0/10
4. [George Hotz: LLMs Create Value, But Frontier Labs Won't Capture It](#item-4) ⭐️ 8.0/10
5. [Realtek Driver Flaw Enables User-Mode DMA Abuse](#item-5) ⭐️ 8.0/10
6. [Scanning Malicious Sites with Arbitrary VPN Tunnels (Part 2)](#item-6) ⭐️ 8.0/10
7. [Chromium 148 Math.tanh Enables OS Fingerprinting](#item-7) ⭐️ 7.0/10
8. [Migrating AI Agent to GPT-5.6: 2.2x Faster, 27% Cheaper](#item-8) ⭐️ 7.0/10
9. [LLM Agents Should Never Be Directly Responsible Individuals](#item-9) ⭐️ 7.0/10
10. [Indian Scientists Create Detailed Brainstem Atlas](#item-10) ⭐️ 7.0/10
11. [Tiny Emulators: Cycle-Accurate 8-Bit Computer Emulators](#item-11) ⭐️ 6.0/10
12. [Reclaiming Deep Reading in a Distracted Age](#item-12) ⭐️ 6.0/10
13. [Anthropic Extends Fable 5 Access Amid Compute Constraints](#item-13) ⭐️ 6.0/10
14. [Australia Mandates Antisemitism, Islamophobia Definitions at Universities](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [vLLM v0.25.0: Model Runner V2 Default, PagedAttention Removed](https://github.com/vllm-project/vllm/releases/tag/v0.25.0) ⭐️ 9.0/10

vLLM v0.25.0 makes Model Runner V2 the default execution path for all dense models and removes the legacy PagedAttention implementation. It also introduces new models like LLaVA-OneVision-2 and GLM-5, a Streaming Parser Engine, and universal speculative decoding for heterogeneous vocabularies. This release marks a major architectural shift for vLLM, streamlining the codebase and improving performance for production LLM deployments. The removal of PagedAttention and the default adoption of Model Runner V2 simplify maintenance and enable future optimizations. Model Runner V2 now supports EVS, realtime embeddings, prefix caching for Mamba hybrid models, and dynamic speculative decoding with full CUDA graphs. The Transformers modeling backend has become as fast as native vLLM, and the release includes 558 commits from 232 contributors.

github · khluu · Jul 11, 20:06

**Background**: vLLM is a high-throughput, memory-efficient inference engine for large language models. PagedAttention was its original attention algorithm that reduced memory waste by managing KV cache in pages, but the newer Model Runner V2 architecture offers better performance and flexibility. CUDA graphs are a technique to reduce kernel launch overhead by capturing a sequence of GPU operations into a single graph.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/vllm-project/vllm/releases">Releases · vllm -project/ vllm</a></li>
<li><a href="https://en.wikipedia.org/wiki/PagedAttention">PagedAttention - Wikipedia</a></li>
<li><a href="https://docs.vllm.ai/en/latest/design/paged_attention/">Paged Attention - vLLM</a></li>

</ul>
</details>

**Tags**: `#vLLM`, `#LLM inference`, `#release`, `#performance`, `#open source`

---

<a id="item-2"></a>
## [Fields Medalist Terry Tao Uses LLM Coding Agents for Apps](https://terrytao.wordpress.com/2026/07/11/old-and-new-apps-via-modern-coding-agents/) ⭐️ 8.0/10

Terry Tao, a Fields Medalist, shared his experience using LLM-powered coding agents to build interactive visualizations and apps, noting significant productivity gains while emphasizing the need for careful oversight. This demonstrates that even top-tier mathematicians are adopting AI-assisted coding for non-trivial tasks, signaling a broader shift in software development practices and highlighting the growing maturity of LLM coding agents. Tao used guided interaction with LLM agents to generate visualizations that supplement his research papers, noting that while the code is not mission-critical, the downside risk is acceptable. The community discussion includes 120 comments with diverse perspectives on AI-assisted coding.

hackernews · subset · Jul 12, 11:09 · [Discussion](https://news.ycombinator.com/item?id=48880170)

**Background**: LLM coding agents are AI tools that use large language models to assist with software development tasks such as writing, editing, and debugging code. Recent benchmarks show rapid progress in models like Claude Code, GitHub Copilot, and open-source agents like OpenCode, which has over 172,000 stars on GitHub.

<details><summary>References</summary>
<ul>
<li><a href="https://benchlm.ai/coding">Best LLMs for Coding — July 2026 Leaderboard | BenchLM.ai</a></li>
<li><a href="https://www.morphllm.com/best-ai-coding-agents-2026">Best AI Coding Agents (June 2026): Scored Leaderboard</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_AI-assisted_software_development_tools">List of AI-assisted software development tools - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed a range of views: some highlighted the productivity boost for creating visualizations in education, while others humorously noted that even a Fields Medalist now faces the same struggles with AI tools as everyone else. The overall sentiment is positive but cautious, agreeing that LLM coding agents are useful tools but not to be trusted blindly.

**Tags**: `#AI-assisted coding`, `#LLM agents`, `#software development`, `#visualization`, `#education`

---

<a id="item-3"></a>
## [Claude Code vs OpenCode: Token Overhead Comparison](https://systima.ai/blog/claude-code-vs-opencode-token-overhead) ⭐️ 8.0/10

A study found that Claude Code sends approximately 33,000 tokens as overhead before processing a user prompt, while OpenCode sends only about 7,000 tokens, making Claude Code roughly 4.7 times less token-efficient. This token inefficiency directly translates to higher costs for users, especially for heavy users of agentic coding tools, and raises concerns about monetization strategies by Anthropic. The study measured token usage at the API boundary between the coding agent and Anthropic's endpoint, capturing all requests and usage blocks. The overhead includes system prompts, tool definitions, and cache management.

hackernews · systima · Jul 12, 18:25 · [Discussion](https://news.ycombinator.com/item?id=48883275)

**Background**: Agentic coding tools like Claude Code and OpenCode use large language models to assist with software development tasks. They send system prompts and tool definitions along with each user request, which contributes to token overhead. Token usage directly impacts cost, as users are billed per token.

<details><summary>References</summary>
<ul>
<li><a href="https://systima.ai/blog/claude-code-vs-opencode-token-overhead">Claude Code Sends 4.7x More Tokens Than... | Systima Blog</a></li>
<li><a href="https://www.neura.market/blog/claude-code-sends-33k-tokens-before-reading-your-prompt-opencode-sends">Claude Code Sends 33K Tokens Before Reading Your... | Neura Market</a></li>
<li><a href="https://www.truefoundry.com/blog/opencode-token-usage-how-it-works-and-how-to-optimize-it">OpenCode Token Usage: How It Works and How to Optimize It</a></li>

</ul>
</details>

**Discussion**: Community comments highlight that sub-agents in Claude Code can burn tokens rapidly, and some users suspect Anthropic intentionally inflates token usage to drive subscriptions. Others note that token inefficiency is not unique to Claude Code, as other tools also show aggressive tool calls.

**Tags**: `#AI coding tools`, `#token efficiency`, `#Claude Code`, `#OpenCode`, `#cost analysis`

---

<a id="item-4"></a>
## [George Hotz: LLMs Create Value, But Frontier Labs Won't Capture It](https://geohot.github.io//blog/jekyll/update/2026/07/12/i-love-llms.html) ⭐️ 8.0/10

George Hotz published a blog post arguing that while LLMs generate immense value, frontier AI labs like OpenAI and Anthropic will fail to capture that value due to commoditization and open-source alternatives. This critique challenges the high valuations of frontier labs and highlights a potential shift in value capture from proprietary models to open-source ecosystems, affecting investors, developers, and the future of AI commercialization. Hotz points out that open-source models are only 3–6 months behind proprietary ones, and that productivity gains from LLMs are not translating into visible new software because they are used privately in homelabs and one-off scripts.

hackernews · therepanic · Jul 12, 18:31 · [Discussion](https://news.ycombinator.com/item?id=48883343)

**Background**: LLMs (Large Language Models) are AI models trained on vast text data to generate human-like text. Frontier labs are leading AI research organizations like OpenAI, Anthropic, and Google DeepMind. Commoditization occurs when advanced models become widely available and interchangeable, often through open-source releases, reducing the competitive advantage of proprietary models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/commoditization-ai-models-implications-innovation-siddharth-bhalsod-seimf">The Commoditization of AI Models : Implications for Innovation</a></li>
<li><a href="https://intelligence.org/2025/06/11/so-you-want-to-work-at-a-frontier-ai-lab/">So You Want to Work at a Frontier AI Lab - Machine Intelligence Research Institute</a></li>
<li><a href="https://www.ability.ai/blog/ai-model-commoditization-guide">AI model commoditization : a guide for COOs | Ability AI | Ability. ai</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree with Hotz, noting that productivity gains are real but hidden in private use, and that the balance of open source contributions may shift as forking becomes easier. Some express concern about the future of open source, while others report that newer models like Sonnet 4 and Opus 4.5 feel like step changes, suggesting uncertainty about timelines.

**Tags**: `#LLMs`, `#AI hype`, `#open source`, `#value capture`, `#productivity`

---

<a id="item-5"></a>
## [Realtek Driver Flaw Enables User-Mode DMA Abuse](https://www.reddit.com/r/netsec/comments/1uuquzx/vulnerability_in_realtek_driver_allows_dma/) ⭐️ 8.0/10

A vulnerability in a Realtek driver allows unprivileged user-mode applications to program the DMA controller, enabling arbitrary physical memory reads and writes without requiring additional hardware or drivers. This vulnerability bypasses kernel memory protections, potentially allowing attackers to read sensitive data or corrupt system memory from user mode, posing a severe security risk to affected systems. The flaw specifically targets a Realtek driver that exposes DMA controller programming interfaces to user mode, violating the principle of least privilege. No additional hardware is needed, making exploitation straightforward.

reddit · r/netsec · /u/zwclose · Jul 12, 20:39

**Background**: Direct Memory Access (DMA) allows peripherals to transfer data directly to/from memory without CPU intervention, improving performance. Typically, DMA controllers are only accessible from kernel mode to prevent abuse. User-mode DMA attacks, like those via Thunderbolt or FireWire, usually require physical access or special hardware. This vulnerability removes those barriers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DMA_attack">DMA attack - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Direct_memory_access">Direct memory access - Wikipedia</a></li>
<li><a href="https://learn.microsoft.com/en-us/windows-hardware/drivers/kernel/dma-programming-techniques">DMA Programming Techniques - Windows drivers | Microsoft Learn</a></li>

</ul>
</details>

**Tags**: `#vulnerability`, `#DMA`, `#Realtek`, `#security`, `#driver`

---

<a id="item-6"></a>
## [Scanning Malicious Sites with Arbitrary VPN Tunnels (Part 2)](https://www.reddit.com/r/netsec/comments/1uto85z/scanning_malicious_websites_with_arbitrary_number/) ⭐️ 8.0/10

The author details a method to create an arbitrary number of VPN tunnels and route traffic through them to scan malicious websites, building on a previous part that established the basic infrastructure. This technique enables security researchers to evade IP-based blocking and geo-restrictions when analyzing malicious websites, improving the effectiveness of threat intelligence gathering. The implementation uses Linux network namespaces and WireGuard to create isolated tunnels, allowing each scan to appear from a different IP address without requiring multiple physical VPN subscriptions.

reddit · r/netsec · /u/moonlightelite · Jul 11, 16:13

**Background**: VPN tunnels encrypt and route traffic through remote servers, masking the user's IP address. Malicious websites often block or serve different content based on the visitor's IP or location. By chaining multiple VPN tunnels, researchers can rotate IPs and bypass these restrictions.

<details><summary>References</summary>
<ul>
<li><a href="https://discounttimu.substack.com/p/scanning-malicious-websites-with">Scanning malicious websites with 'infinite' number of VPN ...</a></li>
<li><a href="https://thenote.app/post/en/scanning-malicious-websites-with-arbitrary-number-of-vpn-tunnels-part-2-4bkepam8mc">Scanning malicious websites with arbitrary number of VPN ...</a></li>

</ul>
</details>

**Discussion**: The r/netsec community praised the technical depth and practicality of the approach, with some users discussing potential improvements and caveats such as VPN provider reliability and legal considerations.

**Tags**: `#VPN`, `#malware analysis`, `#network security`, `#web scanning`

---

<a id="item-7"></a>
## [Chromium 148 Math.tanh Enables OS Fingerprinting](https://scrapfly.dev/posts/browser-math-os-fingerprint/) ⭐️ 7.0/10

Since Chromium 148, the Math.tanh function produces different bit-level results across operating systems due to underlying math library differences, allowing websites to infer the user's OS by comparing tanh outputs. This new fingerprinting vector undermines privacy protections like user-agent spoofing, as it exposes OS information even when headers are altered, and highlights the need for standardized transcendental function implementations across browsers. The fingerprinting works by calling Math.tanh with specific inputs and comparing the results to known OS-specific outputs; the differences stem from varying math libraries (e.g., glibc on Linux, MSVCRT on Windows, libm on macOS).

hackernews · joahnn_s · Jul 12, 21:12 · [Discussion](https://news.ycombinator.com/item?id=48884853)

**Background**: Browser fingerprinting is a technique used by websites to identify users by collecting device and browser configuration details via JavaScript. Math.tanh is a hyperbolic tangent function available in JavaScript's Math object. Chromium is the open-source browser engine underlying Google Chrome and many other browsers.

<details><summary>References</summary>
<ul>
<li><a href="https://scrapfly.dev/posts/browser-math-os-fingerprint/">Your Browser Does Math Differently on Every OS, and Anti-Bot Systems Read the Bits · scrapfly.dev</a></li>
<li><a href="https://news.ycombinator.com/item?id=48884853">Since Chromium 148, Math.tanh is now fingerprintable to link underlying OS | Hacker News</a></li>
<li><a href="https://fingerprint.com/blog/browser-fingerprinting-techniques/">Browser Fingerprinting Techniques : 6 Top Methods Explained</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the technique may also fingerprint browser version ranges, and some criticized the article's AI-generated nature and the company's motives, suggesting it was written to pressure fixes for scraping benefits. Others pointed out that even Tor Browser has given up on OS obfuscation due to too many fingerprinting vectors.

**Tags**: `#browser fingerprinting`, `#privacy`, `#Chromium`, `#JavaScript`, `#operating system`

---

<a id="item-8"></a>
## [Migrating AI Agent to GPT-5.6: 2.2x Faster, 27% Cheaper](https://ploy.ai/blog/migrating-a-production-ai-agent-to-gpt-5-6) ⭐️ 7.0/10

Ploy.ai migrated its production AI agent from previous models to GPT-5.6, achieving a 2.2x speedup and 27% cost reduction while maintaining or improving quality. This real-world migration demonstrates significant performance and cost benefits for production AI agents, encouraging other companies to upgrade and optimize their LLM deployments. The agent builds and edits marketing websites, involving planning, code reading, component writing, image generation, and self-screening. The migration required minimal code changes, often just a one-line model name update.

hackernews · brryant · Jul 12, 17:13 · [Discussion](https://news.ycombinator.com/item?id=48882716)

**Background**: GPT-5.6 is a family of large language models released by OpenAI in July 2026, with variants Luna, Terra, and Sol. It offers improved capabilities in coding, science, and cybersecurity, and is designed for enterprise use.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6">GPT-5.6</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT‑5.6 Sol: a next-generation model - OpenAI</a></li>
<li><a href="https://www.nytimes.com/2026/07/09/technology/openai-sol-ai.html">OpenAI Releases GPT-5.6 Sol, Its Most Powerful AI Model Yet</a></li>

</ul>
</details>

**Discussion**: Commenters noted the LLM-like writing style in the article, with some skepticism about the claimed numbers. Others shared similar positive experiences with GPT-5.6 upgrades, while some questioned consistency and prompt engineering changes.

**Tags**: `#AI`, `#LLM`, `#GPT-5.6`, `#production`, `#cost optimization`

---

<a id="item-9"></a>
## [LLM Agents Should Never Be Directly Responsible Individuals](https://simonwillison.net/2026/Jul/12/directly-responsible-individuals/#atom-everything) ⭐️ 7.0/10

Simon Willison argues that LLM-powered agents should never be considered Directly Responsible Individuals (DRIs) because accountability is uniquely human. This argument challenges the trend of delegating decision-making to AI agents, emphasizing that machines cannot be held accountable for outcomes, which is critical for organizational governance and ethical AI deployment. Willison references the GitLab handbook's definition of DRI, which originated at Apple, and cites IBM's 1979 training slide stating that a computer must never make a management decision because it cannot be held accountable.

rss · Simon Willison · Jul 12, 23:57

**Background**: Directly Responsible Individual (DRI) is a concept popularized at Apple and adopted by companies like GitLab, referring to the single person ultimately accountable for a project's success or failure. As LLM-powered agents become more autonomous, questions arise about who is responsible when they make mistakes. Willison's post connects this classic management principle to modern AI accountability debates.

<details><summary>References</summary>
<ul>
<li><a href="https://handbook.gitlab.com/handbook/people-group/directly-responsible-individuals/">Directly Responsible Individuals ( DRI ) | The GitLab Handbook</a></li>
<li><a href="https://tettra.com/article/directly-responsible-individuals-guide/">Directly Responsible Individuals : The What, How and Why of DRIs</a></li>

</ul>
</details>

**Tags**: `#management`, `#AI accountability`, `#LLM agents`, `#organizational design`

---

<a id="item-10"></a>
## [Indian Scientists Create Detailed Brainstem Atlas](https://www.bbc.co.uk/news/articles/cg53l737v1qo?at_medium=RSS&at_campaign=rss) ⭐️ 7.0/10

Indian scientists have developed a comprehensive brainstem atlas, providing an unprecedented map of one of the brain's least understood regions. This atlas could significantly advance neuroscience research and medical understanding of conditions like Parkinson's disease, where brainstem neurons are affected. The atlas maps the brainstem at a detailed level, potentially including single-cell resolution, and is expected to aid in identifying key neurons lost in neurodegenerative diseases.

rss · BBC World News · Jul 13, 00:08

**Background**: The brainstem controls essential life functions such as heart rate, breathing, and sleep. Despite its importance, it has been poorly mapped compared to other brain regions. This new atlas fills a critical gap in neuroscience.

<details><summary>References</summary>
<ul>
<li><a href="https://neurosciencenews.com/brainstem-neurodevelopment-map-29892/">BrainSTEM Atlas Maps Every Cell of the... - Neuroscience News</a></li>
<li><a href="https://www.verywellhealth.com/brainstem-anatomy-5095691">verywellhealth.com/ brainstem -anatomy-5095691</a></li>

</ul>
</details>

**Tags**: `#neuroscience`, `#brain mapping`, `#scientific research`, `#India`

---

<a id="item-11"></a>
## [Tiny Emulators: Cycle-Accurate 8-Bit Computer Emulators](https://floooh.github.io/tiny8bit-preview/index.html) ⭐️ 6.0/10

A collection of tiny, cycle-accurate emulators for 8-bit computers has been released, allowing games to load instantly in a web browser. This project demonstrates that pin-level emulation can be achieved in JavaScript, enabling instant loading of classic games that originally took minutes from tape. The emulators use a pin-level emulation model where each component's behavior is self-contained and modular, communicating via explicitly defined interfaces.

hackernews · naves · Jul 12, 20:23 · [Discussion](https://news.ycombinator.com/item?id=48884395)

**Background**: Cycle-accurate emulation means the emulator synchronizes components at the clock cycle level, ensuring behavior matches the original hardware precisely. This is computationally intensive but provides high accuracy. The project focuses on 8-bit computers like the ZX Spectrum, which used tape loading that was notoriously slow.

<details><summary>References</summary>
<ul>
<li><a href="https://emulation.gametechwiki.com/index.php/Emulation_accuracy">Emulation accuracy - Emulation General Wiki</a></li>
<li><a href="https://retrocomputing.stackexchange.com/questions/1191/what-exactly-is-a-cycle-accurate-emulator/1199">emulation - What exactly is a cycle - accurate emulator ?</a></li>

</ul>
</details>

**Discussion**: Community comments are positive, with users praising the instant loading and pin-level emulation model. One user noted that some games have unexpectedly high volume, and another pointed out the project is at least 8 years old.

**Tags**: `#emulation`, `#retrocomputing`, `#8-bit`, `#javascript`

---

<a id="item-12"></a>
## [Reclaiming Deep Reading in a Distracted Age](https://substack.magazinenongrata.com/p/how-i-learned-to-read-again) ⭐️ 6.0/10

The author reflects on losing the ability to read deeply due to digital distractions and shares a personal journey of reclaiming focused reading through deliberate practice. This essay highlights a widespread cognitive shift from deep reading to skimming, affecting critical thinking and attention spans, and offers a path to recovery. The author notes that reading peak occurred around age 11-12, echoing Mortimer Adler's observation that reading instruction stagnates after 6th grade. Community comments reference Paul Graham's assertion that deep reading is essential for clear thinking and writing.

hackernews · georgex7 · Jul 12, 18:22 · [Discussion](https://news.ycombinator.com/item?id=48883238)

**Background**: Deep reading involves sustained, focused attention to extract meaning and engage critically with text, contrasting with the skimming and scanning common on screens. The rise of digital media has been linked to reduced attention spans and shallower comprehension.

**Discussion**: Commenters share personal struggles with screen addiction and ADHD, and discuss strategies for deep reading. Some reference Paul Graham and Mortimer Adler to emphasize the importance of reading instruction and the link between reading, writing, and thinking.

**Tags**: `#reading`, `#digital distraction`, `#attention`, `#self-improvement`

---

<a id="item-13"></a>
## [Anthropic Extends Fable 5 Access Amid Compute Constraints](https://simonwillison.net/2026/Jul/12/bump/#atom-everything) ⭐️ 6.0/10

Anthropic has extended Claude Fable 5 access on all paid plans through July 19, 2026, due to compute constraints, while OpenAI removed usage limits for GPT-5.6 Sol on Plus, Business, and Pro plans. This highlights the competitive pressure between Anthropic and OpenAI, with OpenAI gaining users due to unrestricted access to GPT-5.6 Sol, while Anthropic's uncertainty around Fable 5 availability may drive users away. Fable 5 users can use up to half of their weekly usage limit on the model, then switch to another model or use credits. OpenAI's GPT-5.6 Sol is also becoming more efficient, reducing usage consumption.

rss · Simon Willison · Jul 12, 21:20

**Background**: Claude Fable 5 is Anthropic's most powerful generally available AI model, released on June 9, 2026, and is a Mythos-class conversational model. GPT-5.6 Sol is OpenAI's latest flagship model, achieving state-of-the-art results across coding, science, and cybersecurity. Both models represent the frontier of large language models, competing for users and compute resources.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT‑5.6 Sol: a next-generation model - OpenAI</a></li>
<li><a href="https://openai.com/index/gpt-5-6/">GPT‑5.6: Frontier intelligence that scales with your ambition</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Anthropic`, `#Claude`, `#GPT-5`, `#compute constraints`

---

<a id="item-14"></a>
## [Australia Mandates Antisemitism, Islamophobia Definitions at Universities](https://www.theguardian.com/australia-news/2026/jul/12/new-anti-racism-standard-will-force-australian-universities-to-use-definitions-of-antisemitism-and-islamophobia-ntwnfb) ⭐️ 6.0/10

Starting next year, Australian universities will be legally required to adopt specific definitions of antisemitism, Islamophobia, and racism against Aboriginal and Torres Strait Islander people under a new anti-racism standard. This policy aims to combat discrimination on campuses by providing clear, legally enforceable definitions, potentially affecting how universities handle complaints and free speech debates. The standard also requires universities to create a transparent complaints process and issue guidance to students and staff. The definitions are expected to align with the IHRA working definition of antisemitism and similar frameworks for Islamophobia.

rss · The Guardian World · Jul 12, 12:00

**Background**: The IHRA definition of antisemitism, adopted in 2016, includes 11 illustrative examples, some of which relate to criticism of Israel, sparking debate over free speech. Islamophobia is generally understood as prejudice or hostility against Muslims. The new standard emerges amid a royal commission into antisemitism and social cohesion in Australia.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/australia-news/2026/jul/12/new-anti-racism-standard-will-force-australian-universities-to-use-definitions-of-antisemitism-and-islamophobia-ntwnfb">Australian universities will be required to adopt... | The Guardian</a></li>
<li><a href="https://en.wikipedia.org/wiki/IHRA_definition_of_antisemitism">IHRA definition of antisemitism</a></li>
<li><a href="https://www.timeshighereducation.com/news/new-standards-become-law-australia">New standards become law in Australia</a></li>

</ul>
</details>

**Tags**: `#policy`, `#education`, `#social issues`, `#Australia`

---