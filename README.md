# Arunjay Agrawal

CS, Mathematics, and Data Science triple major at UW-Madison, graduating May 2028.
I like problems that need both the systems layer and the ML layer: backends, data pipelines, GPU kernels, and the RAG, agents, and LLM tooling on top.
I'm looking for a Summer 2027 SWE or AI engineering internship.

Portfolio: [arunjay.dev](https://arunjay.dev)

## Work in private repositories

Most of my job and lab work is in employer or university repositories, so I describe it here instead of linking it.

- **Wisconsin Surgical Outcomes Research Program (WiSOR), Software Engineer, 2026 - present.**
  A RAG system for thyroid cancer patients that checks each claim against curated clinical sources.
  It is evaluated against frontier models on a clinician-rated benchmark.
- **UW Tech Exploration Lab, Software Engineer Intern, 2026 - present.**
  A bilingual English/Spanish veterinary voice agent in Go for a 10-veterinarian dairy farm pilot, and the lab's FastAPI and Next.js management dashboard.
- **UW-Madison Data Science Institute, Undergraduate Research Fellow, 2026 - present.**
  Built the multi-speaker audio transcription tool for a qualitative research platform, and gave its research assistant sandboxed SQL access to an ontology knowledge graph.
- **RIA Advisory, AI Engineer Intern, summer 2026.**
  An agentic system that turns unstructured client input into cited business requirements documents.
  It uses GraphRAG over Qdrant and Neo4j and a LangGraph pipeline with a critic loop.
- **LogicPatterns, Software Engineer Intern, summer 2025.**
  An AI agent that turns natural-language prompts into live software architecture diagrams.

## Public projects

- [race-attention-kernel](https://github.com/Arunjay4213/race-attention-kernel) - fused CUDA kernels for RACE Attention (ICLR 2026), built at the CDIS & OpenAI Summer AI Lab.
  The reference causal path runs a 40 GB A100 out of memory at 131K tokens.
  The fused kernel runs a 2M-token causal forward in 14.7 ms on one H100, 165x faster than the chunked PyTorch baseline.
- [jobcrawl](https://github.com/Arunjay4213/jobcrawl) - watches company career boards at the source and emails a scored digest of new internship postings.
  It has run unattended since July 2026: 7,358 runs, 5,894 career boards on 14 applicant tracking systems plus company APIs, and about 872 million postings fetched.
  ETag conditional requests and per-host throttling keep it polite and cheap, dedupe catches reposts, and it notices when a posting closes.
  An LLM scores whatever gets past a regex prefilter.
- [mosh-rs](https://github.com/Arunjay4213/mosh-rs) - a Rust port of the mobile shell (mosh).
  It is wire-compatible with mosh 1.4 servers, adds a native Windows client and real scrollback, and is published on crates.io (`cargo install mosh`).
  It was built with AI coding agents under a written plan, and the plan, status log, and reviews are all in the repo.
- [Tripwire](https://github.com/Arunjay4213/Tripwire) - tests whether a tool-using AI agent can be hijacked by prompt injection before it ships.
  It runs 13 attacks, and plain Python (no LLM judge) checks whether the agent leaked a planted secret.
  Published on PyPI as `tripwire-eval`.
- [Cortexa](https://github.com/Arunjay4213/Cortexa) - observability for AI agent memory.
  It records which memories each response used, scores their influence, and traces every memory back to the interaction that created it.
- [Wattbot](https://github.com/Arunjay4213/Wattbot) - hybrid BM25 and dense retrieval for a UW-Madison Kaggle competition, 87% accuracy on 282 test questions.
- [CustomShell](https://github.com/Arunjay4213/CustomShell) - a POSIX shell in C11 with pipelines, redirection, and job control.
- [Monday](https://github.com/Arunjay4213/Monday) - vision-guided assisted grasping for people with upper motor neuron injury, using voice, a camera, a Claude grip planner, and electrical muscle stimulation.
  Built at StarkHacks 2026.
- [AI_Interviewer](https://github.com/Arunjay4213/AI_Interviewer) - an AI mock interviewer that also reads your body language from the webcam.
  3rd place at MadData 2025.
- [claude-mods](https://github.com/Arunjay4213/claude-mods) - four Claude Code mods written in TypeScript.
  They show context window use, plan quota burn rate, and per-turn cost on screen, and one stops the session past a budget you set.
- [shipwright](https://github.com/Arunjay4213/solari-cookbook/tree/main/shipwright) - an agent that builds a web app from one line of English, deploys it, tests it in a real browser, and fixes it until the tests pass.

## Contact

- Email: agrawal54@wisc.edu
- LinkedIn: [arunjay-agrawal-aab235322](https://www.linkedin.com/in/arunjay-agrawal-aab235322)
- Website: [arunjay.dev](https://arunjay.dev)
