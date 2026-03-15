![GitHub stars](https://img.shields.io/github/stars/haidrsalam1/PhD-in-computer-science-degree?style=flat-square)
![Last commit](https://img.shields.io/github/last-commit/haidrsalam1/PhD-in-computer-science-degree?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

# Self-Study PhD in Computer Science

PhD-in-computer-science-degree



> [!info] Overview A complete 6-year self-study curriculum modeled on PhD requirements from **MIT, Stanford, CMU, and Berkeley**. Contains **120+ resources** organized as both a semester-by-semester plan and a topic-based reference. Assumes completion of [[Teach Yourself CS]] (TYCS) as prerequisite.

> [!tip] How to use this in Obsidian
> 
> - Check off items as you complete them using `- [ ]`
> - Create linked notes for each course/book as you study them
> - Use the Dataview plugin to track progress across semesters
> - Tag your reading notes with `#phd-curriculum` to link back here

---

## How This Maps to Real PhD Programs

|University|Structure|
|---|---|
|**CMU**|5 breadth courses (algorithms, AI, systems, PL, software systems) + electives + research|
|**Stanford**|Courses from 4 breadth areas (Formal Foundations, Learning & Modeling, Systems, People & Society), B+ minimum|
|**Berkeley**|Preliminary oral exam by semester 3, qualifying exam by semester 6|
|**MIT**|4 graduate courses across 3 groups, master's thesis, Research Qualifying Exam|

> [!note] Your TYCS Foundation SICP, Skiena's algorithms, OSTEP, Kurose/Ross networking, Crafting Interpreters, Kleppmann's DDIA, MIT 6.042 math — equivalent to a strong undergraduate CS degree.
> 
> **Gaps to fill:** no graduate-level theory of computation, no formal methods, no AI/ML, no security, no type theory, limited math maturity in optimization/probability, no research experience.

---

## Year 1 — Building Graduate Breadth

> [!abstract] Goal One rigorous course in each major area + mathematical foundations. **40–50 hours/week.**

### Semester 1 (Fall)

#### Course 1 — Graduate Algorithms

`12 weeks · 15 hrs/week`

- [ ] MIT 6.854 Advanced Algorithms — [Lecture Videos (Moitra, 2016)](https://people.csail.mit.edu/moitra/854.html)
    - Hashing, dimensionality reduction, max flow, LP, SDP, approximation algorithms
- [ ] [Jeff Erickson — _Algorithms_](https://jeffe.cs.illinois.edu/teaching/algorithms/) (free textbook, supplement)
- [ ] Complete all 6 problem sets from [MIT OCW Fall 2008](https://ocw.mit.edu/courses/6-854j-advanced-algorithms-fall-2008/)

#### Course 2 — Machine Learning Foundations

`12 weeks · 15 hrs/week`

- [ ] Kevin Murphy — _Probabilistic ML: An Introduction_ (free PDF at probml.github.io), Chapters 1–15
- [ ] [Stanford CS229 lecture notes](https://cs229.stanford.edu/main_notes.pdf)
- [ ] Deisenroth et al. — [_Mathematics for Machine Learning_](https://mml-book.github.io/) (free, prerequisite)
- [ ] Boyd & Vandenberghe — [_Convex Optimization_](https://web.stanford.edu/~boyd/cvxbook/) Chapters 1–5 (free)

#### Course 3 — Systems Security

`12 weeks · 10 hrs/week`

- [ ] MIT 6.858 Computer Systems Security (Fall 2014, full OCW — 23 lectures + labs)
- [ ] Ross Anderson — [_Security Engineering_ 3rd ed.](https://cl.cam.ac.uk/archive/rja14/book.html) Part I (free PDF)
- [ ] [pwn.college](https://pwn.college/) — binary exploitation practice
- [ ] Complete buffer overflow + web security labs

---

### Semester 2 (Spring)

#### Course 4 — Programming Language Theory

`14 weeks · 15 hrs/week`

- [ ] Benjamin Pierce — _Types and Programming Languages_ (TAPL) (~$80)
    - Untyped/simply typed lambda calculus, subtyping, recursive types, System F
- [ ] [_Software Foundations_ Vol. 1: Logical Foundations](https://softwarefoundations.cis.upenn.edu/) (free)
    - Interactive Coq/Rocq proof exercises

#### Course 5 — Complexity Theory

`14 weeks · 12 hrs/week`

- [ ] Arora & Barak — [_Computational Complexity: A Modern Approach_](https://theory.cs.princeton.edu/complexity/book.pdf) Part I (free PDF)
    - P, NP, coNP, polynomial hierarchy, space complexity, circuits, randomized computation, interactive proofs
- [ ] Work through exercises (300+ with hints)

#### Course 6 — Deep Learning

`14 weeks · 13 hrs/week`

- [ ] Goodfellow, Bengio & Courville — [_Deep Learning_](https://deeplearningbook.org/) Parts I & II (free)
- [ ] [Stanford CS231n course notes](https://cs231n.github.io/)
- [ ] [fast.ai Practical Deep Learning](https://course.fast.ai/) (free)
- [ ] Build real models in PyTorch (CNNs from scratch, backpropagation)

---

## Year 2 — Deepening to Qualifying-Exam Level

> [!abstract] Goal Take each pillar deeper. Start paper reading.

### Semester 3 (Fall)

#### Course 7 — Advanced OS & Kernel Internals

`14 weeks · 15 hrs/week`

- [ ] [MIT 6.S081 Operating System Engineering](https://pdos.csail.mit.edu/6.828/2021/schedule.html) — 11 xv6 RISC-V labs
- [ ] Robert Love — _Linux Kernel Development_ 3rd ed. (~$50)
- [ ] Build and submit a Linux kernel module
- [ ] Read: Klein et al. "seL4 Formal Verification" (2009)

#### Course 8 — Natural Language Processing

`14 weeks · 13 hrs/week`

- [ ] Jurafsky & Martin — [_Speech and Language Processing_ 3rd ed.](https://web.stanford.edu/~jurafsky/slp3/) (free draft)
- [ ] [Stanford CS224n](https://web.stanford.edu/class/cs224n/) lecture videos on YouTube
- [ ] **Landmark papers (read in order):**
    - [ ] Mikolov et al. — "Word2Vec" (2013)
    - [ ] Bahdanau et al. — "Attention for NMT" (2015)
    - [ ] Vaswani et al. — "Attention Is All You Need" (2017)
    - [ ] Devlin et al. — "BERT" (2019)
    - [ ] Brown et al. — "GPT-3" (2020)

#### Course 9 — Distributed Systems Deep Dive

`14 weeks · 12 hrs/week`

- [ ] [MIT 6.5840](https://pdos.csail.mit.edu/6.824/schedule.html) — all 4 labs (MapReduce, Raft, KV store, sharded KV)
- [ ] Read all papers on the syllabus (MapReduce, GFS, Paxos, Raft, ZooKeeper, Spanner, PBFT, Bitcoin…)
- [ ] van Steen & Tanenbaum — _Distributed Systems_ (free PDF at distributed-systems.net)
- [ ] Read: Lamport "Time, Clocks, and the Ordering of Events" (1978)
- [ ] Read: Fischer/Lynch/Patterson "FLP Impossibility" (1985)

---

### Semester 4 (Spring)

#### Course 10 — Applied Cryptography

`14 weeks · 13 hrs/week`

- [ ] Dan Boneh — Cryptography I on Coursera (free audit)
- [ ] Boneh & Shoup — [_A Graduate Course in Applied Cryptography_](https://toc.cryptobook.us/) (free, 818 pages)
- [ ] Katz & Lindell — _Introduction to Modern Cryptography_ 3rd ed. (~$80)
- [ ] Practice on [CryptoHack](https://cryptohack.org/)

#### Course 11 — Advanced Compilers & Program Analysis

`14 weeks · 14 hrs/week`

- [ ] [Stanford CS143 Compilers](https://online.stanford.edu/courses/soe-ycscs1-compilers) on edX (free)
- [ ] [LLVM Kaleidoscope Tutorial](https://releases.llvm.org/3.6.2/docs/tutorial/LangImpl1.html) — SSA, IR, JIT, optimization
- [ ] Cooper & Torczon — _Engineering a Compiler_ (~$80)
- [ ] Read: Cytron et al. "Efficiently Computing SSA Form" (1991)
- [ ] Explore: [Stanford CS243 Program Analysis](https://suif.stanford.edu/~courses/cs243/)

#### Course 12 — Reinforcement Learning

`14 weeks · 13 hrs/week`

- [ ] Sutton & Barto — [_RL: An Introduction_](https://incompleteideas.net/book/the-book-2nd.html) Chapters 1–13 (free)
- [ ] [David Silver UCL RL Course](https://davidstarsilver.wordpress.com/teaching/) — 10 lectures on YouTube
- [ ] Implement Q-learning, SARSA, policy gradient from scratch
- [ ] [Berkeley CS285 Deep RL](https://www2.eecs.berkeley.edu/Courses/CS285/) (Sergey Levine)
- [ ] **Papers:** DQN (Mnih 2015), AlphaGo (Silver 2016), PPO (Schulman 2017)

---

### ✅ Year 2 Milestone: Breadth Qualifying Exam

> [!warning] Self-Assessment Checkpoint Administer yourself these exams modeled on real PhD qualifying exams.

- [ ] **Algorithms & Complexity** — Solve 5/8 problems from the UIUC Theory Qualifying Exam archive within 5 hours
- [ ] **Systems** — Write a technical report analyzing a distributed systems paper you haven't read (72-hour limit, Stanford format)
- [ ] **AI/ML** — Implement a Transformer from scratch in PyTorch, train it, write a 5-page report with math justification
- [ ] **Security** — Achieve yellow belt on pwn.college; 20+ challenges across binary exploitation, RE, and crypto
- [ ] **PL** — Prove type safety (progress + preservation) for a simple type system in Coq using Software Foundations

---

## Year 3 — Specialization Depth

> [!abstract] Goal Transition from coursework to research-oriented study. Choose **one primary** and **one secondary** specialization.

### Semester 5 (Fall)

#### Advanced Security Specialization

`15 hrs/week`

- [ ] Anderson — _Security Engineering_ Parts II–III (access control, security economics, API security)
- [ ] Goldreich — _Foundations of Cryptography_ Vol. 1 (one-way functions, ZK proofs)
- [ ] Compete in 3+ CTFs via [CTFtime.org](https://ctftime.org/)
- [ ] Complete OverTheWire wargames (Bandit → Behemoth)

#### Formal Methods & Verification

`12 hrs/week`

- [ ] [_Software Foundations_](https://softwarefoundations.cis.upenn.edu/) Volumes 3–5 (Verified Functional Algorithms, QuickChick, Verifiable C)
- [ ] TLA+ — Lamport's video course + [learntla.com](https://learntla.com/)
- [ ] Chlipala — [_Certified Programming with Dependent Types_](http://adam.chlipala.net/cpdt/) (free)

#### Paper Reading Group (self-directed)

`6 hrs/week`

- [ ] Read 2 papers/week from: IEEE S&P, USENIX Security, CCS, NDSS, OSDI, SOSP
- [ ] Use Keshav's "How to Read a Paper" method (3-pass approach)
- [ ] Maintain a research notebook in Obsidian

---

### Semester 6 (Spring)

#### Probabilistic Graphical Models

`12 hrs/week`

- [ ] [Stanford CS228 notes](https://ermongroup.github.io/cs228-notes/) (free)
- [ ] Koller & Friedman — _Probabilistic Graphical Models_ (~$90)
- [ ] Wainwright & Jordan — variational inference monograph (free)

#### Parallel & Concurrent Programming

`13 hrs/week`

- [ ] Herlihy & Shavit — _The Art of Multiprocessor Programming_ (~$70)
- [ ] [CMU 15-418 Parallel Architecture & Programming](https://www.cs.cmu.edu/~418/) (free lectures + assignments)
- [ ] Paul McKenney — _Is Parallel Programming Hard?_ (free, Linux kernel concurrency)

#### Advanced Complexity Theory

`10 hrs/week`

- [ ] Arora & Barak Parts II–III (circuit lower bounds, PCP theorem, derandomization, quantum computing)
- [ ] Goldreich — _Computational Complexity: A Conceptual Perspective_ (alternative perspective)

---

### ✅ Year 3 Milestone: Depth Qualifying Exam

> [!warning] Self-Assessment Checkpoint Modeled on Berkeley's preliminary exam — a 30-minute oral presentation.

- [ ] Select 3 papers in your specialization area
- [ ] Study to the point of reconstructing every proof and critiquing every design decision
- [ ] Record a 30-minute presentation covering contributions, strengths/weaknesses, open questions
- [ ] Write a 10-page survey connecting the papers to broader themes

---

## Year 4 — Research Preparation

### Semester 7 (Fall)

#### Research-Level Security

`15 hrs/week`

- [ ] Read recent best papers from USENIX Security 2024–2025, IEEE S&P 2025, CCS 2025
- [ ] Choose a sub-area: binary analysis, network security, crypto protocols, OS security, or web security
- [ ] Write 1-page critical review per paper
- [ ] Software Foundations Volume 7 (Security Foundations)

#### Advanced Algorithms — Specialized Topics

`12 hrs/week`

Choose one track:

- [ ] Motwani & Raghavan — _Randomized Algorithms_ (~$60)
- [ ] OR Williamson & Shmoys — [_Design of Approximation Algorithms_](https://designofapproxalgs.com/) (free PDF)
- [ ] Erik Demaine — [MIT 6.851 Advanced Data Structures](https://ocw.mit.edu/courses/6-854j-advanced-algorithms-fall-2008/) (full OCW videos)

#### Advanced PL Theory

`10 hrs/week`

- [ ] Pierce — _ATTAPL_ (Advanced Topics in Types and PL) — chapters on dependent types, linear types, effect types (~$70)
- [ ] Harper — _Practical Foundations for Programming Languages_ (PFPL) (~$65)
- [ ] OPLSS recorded lectures (Oregon PL Summer School, free)
- [ ] [CMU 15-312 Foundations of PL materials](https://www.andrew.cmu.edu/course/15-312/)

---

### Semester 8 (Spring)

#### Independent Research Project I

`20 hrs/week`

- [ ] Read 15–20 papers in chosen area
- [ ] Identify a gap
- [ ] Design a solution
- [ ] Implement it
- [ ] Write a conference-style paper (8–12 pages)

#### Advanced Topics Electives (choose 1–2)

`13 hrs/week`

- [ ] **Information Theory** — MacKay, [_Information Theory, Inference, and Learning Algorithms_](http://www.inference.org.uk/mackay/itila/) (free)
- [ ] **Advanced Databases** — [CMU 15-721](https://15721.courses.cs.cmu.edu/spring2024/) (Andy Pavlo, all lectures free on YouTube)
- [ ] **AI Safety** — Christiano et al. "RLHF" (2017), Hubinger et al. "Sleeper Agents" (2024), Greenblatt et al. "AI Control" (2024)
- [ ] **Abstract Interpretation** — Rival & Yi, _Intro to Static Analysis_ (~$60) or [MIT 16.399](http://web.mit.edu/16.399/www/)

---

### ✅ Year 4 Milestone: Thesis Proposal Equivalent

> [!warning] Self-Assessment Checkpoint Write a 20-page research proposal (Stanford's qual format).

- [ ] Survey your sub-field (8–10 pages of related work)
- [ ] Identify 2–3 open problems
- [ ] Propose concrete approaches to one
- [ ] Include preliminary results or proof-of-concept
- [ ] Outline a 2-year research plan
- [ ] Get external review (academic communities, Discord, email researchers)

---

## Years 5–6 — Research and Independent Scholarship

> [!abstract] Goal Produce original work, read at the frontier, develop expertise beyond any textbook.

### Research Reading Lists by Area

#### Systems & Security Frontier

Follow: USENIX Security, IEEE S&P, ACM CCS, NDSS, OSDI, SOSP, EuroSys, USENIX ATC

**Hot topics:** verified systems software (seL4, IronFleet, CertiKOS), fuzzing for vulnerability discovery, side-channel attacks, post-quantum crypto migration, confidential computing (TEEs), AI-assisted security analysis

#### Theory Frontier

Follow: STOC, FOCS, SODA, CCC, ITCS

**Hot topics:** circuit complexity lower bounds, fine-grained complexity, algorithmic fairness theory, quantum complexity, P vs NP barrier approaches

#### AI/ML Frontier

Follow: NeurIPS, ICML, ICLR, ACL, EMNLP, CVPR

- [ ] Murphy — _Probabilistic ML: Advanced Topics_ Vol. 2 (free) — diffusion models, causal inference, Bayesian deep learning

**Hot topics:** mechanistic interpretability, scaling laws, efficient fine-tuning (LoRA, QLoRA), multimodal models, reasoning in LLMs

#### PL/SE Frontier

Follow: POPL, PLDI, ICFP, OOPSLA, ICSE, FSE

- [ ] Pierce — ["Great Works in Programming Languages"](https://www.cis.upenn.edu/~bcpierce/courses/670Fall04/GreatWorksInPL.shtml) reading list

**Hot topics:** gradual typing, effect systems, Rust ownership formalization, verified compilation (CompCert, CakeML), LLM-assisted program synthesis

---

### Independent Research Projects (complete 2–3)

- [ ] Project 1: _________________________________
- [ ] Project 2: _________________________________
- [ ] Project 3: _________________________________
- [ ] Submit at least one paper to a workshop or conference
- [ ] Open-source all implementations
- [ ] Build a personal research website

---

### ✅ Year 5 Milestone: Dissertation Defense Equivalent

> [!warning] Final Assessment Modeled on Berkeley's qualifying exam format.

- [ ] Prepare a 50-minute research talk (15 min survey + 25 min contributions + 10 min future work)
- [ ] Record and share publicly
- [ ] Write a 50+ page dissertation-equivalent document combining your research projects

---

## Research Project Ideas

### Systems & Security

> [!example] Project Ideas
> 
> 1. **Verified microkernel component** — Build in Coq, compare performance to unverified equivalent
> 2. **Novel fuzzing framework** — Target Linux kernel use-after-free vulnerabilities, benchmark against Syzkaller
> 3. **eBPF-based IDS** — Detect novel attack patterns in real-time network traffic, benchmark against Suricata/Snort
> 4. **Distributed consensus verification** — Model-check a real implementation with TLA+, find bugs

### Theory

> [!example] Project Ideas
> 
> 1. **Approximation algorithms empirical study** — Implement for NP-hard problem, compare theoretical vs practical performance
> 2. **New streaming algorithm** — Design for a graph problem, prove space/approximation tradeoffs
> 3. **Mechanized proof** — Formalize an un-mechanized complexity result in Lean 4 or Coq

### AI/ML

> [!example] Project Ideas
> 
> 1. **Arabic NLP** — Fine-tune open LLM for Arabic tasks (leverage bilingual background; underserved research area)
> 2. **Mechanistic interpretability** — Extend activation patching on a small Transformer, produce novel insights
> 3. **RL comparison study** — Build agent for novel environment, compare model-based vs model-free

### PL/SE

> [!example] Project Ideas
> 
> 1. **Language with novel type system** — Design linear types for memory safety, prove type safety in Coq, compile via LLVM
> 2. **Static analysis security tool** — Find C vulnerabilities via abstract interpretation, evaluate on real CVEs
> 3. **Verified compiler** — Implement for a language subset using CompCert methodology

---

## Complete Resource Compendium

### Systems & Security

|Resource|Type|Free?|When|
|---|---|---|---|
|MIT 6.858 Computer Systems Security|Course|✅|Y1S1|
|_Security Engineering_ 3e — Anderson|Book|✅ PDF|Y1–3|
|[pwn.college](https://pwn.college/)|Platform|✅|Y1–4|
|Boneh Cryptography I (Coursera)|Course|✅ audit|Y2S4|
|Boneh & Shoup — _Applied Cryptography_|Book|✅ PDF|Y2S4|
|MIT 6.S081 OS Engineering|Course|✅|Y2S3|
|_Linux Kernel Development_ — Love|Book|❌ ~$50|Y2S3|
|MIT 6.5840 Distributed Systems|Course|✅|Y2S3|
|_Distributed Systems_ — van Steen & Tanenbaum|Book|✅ PDF|Y2S3|
|CMU 15-721 Advanced Databases (Pavlo)|Course|✅ YouTube|Y4|
|Katz & Lindell — _Modern Cryptography_ 3e|Book|❌ ~$80|Y2S4|
|_Linux Programming Interface_ — Kerrisk|Reference|❌ ~$70|Y2–6|
|[CryptoHack](https://cryptohack.org/)|Platform|✅|Y2+|
|[OverTheWire Wargames](https://overthewire.org/)|Platform|✅|Y1+|
|Goldreich — _Foundations of Cryptography_ 1–2|Book|❌ ~$60/vol|Y3|

### Theory of Computation & Algorithms

|Resource|Type|Free?|When|
|---|---|---|---|
|MIT 6.854 Advanced Algorithms (Moitra)|Course|✅|Y1S1|
|Erickson — _Algorithms_|Book|✅ CC-BY|Y1S1|
|Arora & Barak — _Computational Complexity_|Book|✅ draft PDF|Y1–3|
|MIT 6.851 Advanced Data Structures (Demaine)|Course|✅ OCW|Y4|
|Motwani & Raghavan — _Randomized Algorithms_|Book|❌ ~$60|Y4|
|Williamson & Shmoys — _Approximation Algorithms_|Book|✅ PDF|Y4|
|_Software Foundations_ Vols. 1–7|Book|✅|Y1–4|
|TLA+ (Lamport video course + learntla.com)|Tools|✅|Y3|
|MacKay — _Info Theory, Inference & Learning_|Book|✅|Y4|

### AI & Machine Learning

|Resource|Type|Free?|When|
|---|---|---|---|
|Murphy — _Probabilistic ML: Introduction_|Book|✅ PDF|Y1S1|
|Murphy — _Probabilistic ML: Advanced Topics_|Book|✅ PDF|Y3–5|
|Stanford CS229 lecture notes|Course|✅|Y1S1|
|Goodfellow et al. — _Deep Learning_|Book|✅ HTML|Y1S2|
|Stanford CS231n|Course|✅|Y1S2|
|fast.ai Practical Deep Learning|Course|✅|Y1S2|
|Stanford CS224n NLP|Course|✅ YouTube|Y2S3|
|Jurafsky & Martin — _SLP_ 3e|Book|✅ draft|Y2S3|
|Sutton & Barto — _RL: An Introduction_|Book|✅ PDF|Y2S4|
|David Silver UCL RL Course|Course|✅ YouTube|Y2S4|
|Berkeley CS285 Deep RL (Levine)|Course|✅ YouTube|Y2S4|
|Stanford CS228 PGM notes|Course|✅|Y3S6|
|Koller & Friedman — _PGM_|Book|❌ ~$90|Y3|
|Hastie et al. — _Elements of Statistical Learning_|Book|✅ PDF|Y1–2|
|Bishop — _Pattern Recognition and ML_|Book|✅ PDF|Y1–2|
|_Mathematics for Machine Learning_ — Deisenroth|Book|✅|Y1|
|Boyd & Vandenberghe — _Convex Optimization_|Book|✅|Y1|

### Software Engineering & Programming Languages

|Resource|Type|Free?|When|
|---|---|---|---|
|Pierce — _TAPL_|Book|❌ ~$80|Y1S2|
|_Software Foundations_ series (7 vols.)|Book|✅|Y1–4|
|Harper — _PFPL_|Book|❌ ~$65|Y4|
|Pierce — _ATTAPL_|Book|❌ ~$70|Y4|
|Stanford CS143 Compilers (edX)|Course|✅|Y2S4|
|LLVM Kaleidoscope Tutorial|Tutorial|✅|Y2S4|
|Cooper & Torczon — _Engineering a Compiler_|Book|❌ ~$80|Y2S4|
|CMU 15-418 Parallel Architecture|Course|✅|Y3S6|
|Herlihy & Shavit — _Art of Multiprocessor Programming_|Book|❌ ~$70|Y3S6|
|Chlipala — _CPDT_|Book|✅|Y3S5|
|OPLSS recorded lectures|Lectures|✅|Y4+|
|CMU 15-312 Foundations of PL|Course|✅|Y3–4|
|Rival & Yi — _Intro to Static Analysis_|Book|❌ ~$60|Y4|

---

## 30 Landmark Papers

> [!note] Reading Instructions Read these across Years 2–4. Write a 1-page critical summary of each in Obsidian and link them back here.

### Systems (10)

- [ ] Ritchie & Thompson — "The UNIX Time-Sharing System" (1974)
- [ ] Lamport — "Time, Clocks, and the Ordering of Events" (1978)
- [ ] Thompson — "Reflections on Trusting Trust" (1984)
- [ ] Clark — "Design Philosophy of the DARPA Internet Protocols" (1988)
- [ ] Fischer/Lynch/Patterson — "FLP Impossibility" (1985)
- [ ] Castro & Liskov — "Practical BFT" (1999)
- [ ] DeCandia et al. — "Dynamo" (2007)
- [ ] Klein et al. — "seL4" (2009)
- [ ] Corbett et al. — "Spanner" (2012)
- [ ] Ongaro & Ousterhout — "Raft" (2014)

### Theory (3)

- [ ] Cook — "The Complexity of Theorem-Proving Procedures" (1971)
- [ ] Arora et al. — "PCP Theorem" (1998)
- [ ] Shor — "Algorithms for Quantum Computation" (1994)

### AI/ML (10)

- [ ] Goodfellow et al. — "Generative Adversarial Nets" (2014)
- [ ] Mnih et al. — "DQN" (2015)
- [ ] He et al. — "Deep Residual Learning" (2016)
- [ ] Silver et al. — "Mastering the Game of Go" (2016)
- [ ] Vaswani et al. — "Attention Is All You Need" (2017)
- [ ] Devlin et al. — "BERT" (2019)
- [ ] Brown et al. — "GPT-3" (2020)
- [ ] Ho et al. — "Denoising Diffusion Probabilistic Models" (2020)
- [ ] Ouyang et al. — "InstructGPT / RLHF" (2022)

### PL/SE (7)

- [ ] Hoare — "An Axiomatic Basis for Computer Programming" (1969)
- [ ] Parnas — "On the Criteria To Be Used in Decomposing Systems into Modules" (1972)
- [ ] Milner — "A Theory of Type Polymorphism in Programming" (1978)
- [ ] Damas & Milner — "Principal Type Schemes for Functional Programs" (1982)
- [ ] Wadler — "Theorems for Free!" (1989)
- [ ] Moggi — "Computational Lambda-Calculus and Monads" (1989)
- [ ] Cytron et al. — "Efficiently Computing SSA Form" (1991)

---

## Practical Advice

> [!tip] Time Management A real PhD student works 50–60 hrs/week. At 40 hrs consistently → 6 years. At 20 hrs → 8–10 years. **Track your hours.**

> [!tip] Build in Public Create a GitHub repo documenting progress, implementations, and paper summaries. Start a blog in English (and optionally Arabic). If you can't explain it clearly in writing, you don't understand it.

> [!tip] Arabic Bilingual Advantage Arabic NLP research is significantly underserved. Projects involving Arabic language models, Arabic cybersecurity resources, or cross-lingual transfer learning have genuine research value and lower competition.

> [!tip] Connect with Researchers Attend virtual seminars (MIT CSAIL, Stanford CS talks — all streamed free). Join Discord/Slack communities. Email researchers whose papers you've deeply studied.

> [!tip] Free Compute Google Colab for GPU access. Cloud provider research credits. For systems work, your Linux machine is sufficient for kernel dev, CTF practice, and compiler projects.

---

> [!summary] Total Estimated Hours **9,000–12,000 hours** — comparable to a top-4 PhD program. The critical habit is **consistent deep work on hard problems**. Solve exercises. Implement algorithms. Read papers critically. Write about what you learn. Build real systems. The gap between reading about Raft and implementing Raft from scratch is the gap between a student and a researcher.