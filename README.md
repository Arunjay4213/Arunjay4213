# Arunjay Agrawal

CS, Mathematics, and Data Science triple major at UW-Madison, graduating May 2028.
I like problems that need both the systems layer and the ML layer: backends, data pipelines, GPU kernels, and the RAG, agents, and LLM tooling on top.
I'm looking for a Summer 2027 SWE or AI engineering internship.

Portfolio: [arunjay.dev](https://arunjay.dev)

## Selected projects

- [mosh-rs](https://github.com/Arunjay4213/mosh-rs) - the mobile shell (mosh) rewritten in Rust.
  It is wire-compatible with mosh 1.4 servers, adds a native Windows client and real scrollback, and is published on crates.io (`cargo install mosh`).
  It was built with AI coding agents under a written plan, and the plan, status log, and reviews are all in the repo.
- [race-attention-kernel](https://github.com/Arunjay4213/race-attention-kernel) - fused CUDA kernels for RACE Attention (ICLR 2026), built at the CDIS & OpenAI Summer AI Lab.
  The reference causal path runs a 40 GB A100 out of memory at 131K tokens.
  The fused kernel runs a 2M-token causal forward in 14.7 ms on one H100, 165x faster than the chunked PyTorch baseline.
- [Tripwire](https://github.com/Arunjay4213/Tripwire) - finds out whether a tool-using AI agent can be hijacked by prompt injection before it ships.
  It runs 13 attacks and checks for a leaked planted secret in plain Python, with no LLM judge.
  Published on PyPI as `tripwire-eval`.
- [claude-mods](https://github.com/Arunjay4213/claude-mods) - four Claude Code mods written in TypeScript.
  They show context window use, plan quota burn rate, and per-turn cost on screen, and one stops the session past a budget you set.
- [doordash-deal-scanner](https://github.com/Arunjay4213/doordash-deal-scanner) - an unattended agent that finds the cheapest all-in meal nearby every day, built on the official DoorDash CLI.
  Its fee model reproduces DoorDash's own checkout quotes to within about a cent.
- [Cortexa](https://github.com/Arunjay4213/Cortexa) - observability for AI agent memory.
  It records which memories each response used, scores their influence, and traces every memory back to the interaction that created it.
- [shipwright](https://github.com/Arunjay4213/solari-cookbook/tree/main/shipwright) - an agent that builds a web app from one line of English, deploys it, tests it in a real browser, and fixes it until the tests pass.
- [Monday](https://github.com/Arunjay4213/Monday) - vision-guided assisted grasping for people with upper motor neuron injury, using voice, a camera, a Claude grip planner, and electrical muscle stimulation.
  Built at StarkHacks 2026.
- [CustomShell](https://github.com/Arunjay4213/CustomShell) - a POSIX shell in C11 with pipelines, redirection, and job control.
- [Wattbot](https://github.com/Arunjay4213/Wattbot) - hybrid BM25 and dense retrieval for a UW-Madison Kaggle competition, 87% accuracy on 282 test questions.
- [AI_Interviewer](https://github.com/Arunjay4213/AI_Interviewer) - AI mock interviewer that also reads body language from the webcam.
  3rd place at MadData 2025.

## Work in private repositories

Most of my job and lab work lives in employer or university repositories, so it is described here rather than linked.

- **Wisconsin Surgical Outcomes Research Program (WiSOR), Software Engineer, 2026 - present.**
  A RAG system for thyroid cancer patients that checks each claim against curated clinical sources, evaluated against frontier models on a clinician-rated benchmark.
- **UW Tech Exploration Lab, Software Engineer Intern, 2026 - present.**
  A bilingual English/Spanish veterinary voice agent in Go for a 10-veterinarian dairy farm pilot, and the lab's FastAPI and Next.js management dashboard.
- **UW-Madison Data Science Institute, Undergraduate Research Fellow, 2026 - present.**
  Built the multi-speaker audio transcription tool for a qualitative research platform, and gave its research assistant sandboxed SQL access to an ontology knowledge graph.
- **RIA Advisory, AI Engineer Intern, summer 2026.**
  An agentic system that turns unstructured client input into cited business requirements documents, using GraphRAG over Qdrant and Neo4j and a LangGraph pipeline with a critic loop.
- **LogicPatterns, Software Engineer Intern, summer 2025.**
  An AI agent that turns natural-language prompts into live software architecture diagrams.
- **jobcrawl.**
  A personal pipeline that polls about 540 company career boards every 10 minutes and scores new postings with Claude.
  The code is private because it holds my application data; there is a [write-up](https://arunjay.dev/jobcrawl/).

## Contact

- Email: agrawal54@wisc.edu
- LinkedIn: [arunjay-agrawal-aab235322](https://www.linkedin.com/in/arunjay-agrawal-aab235322)
- Website: [arunjay.dev](https://arunjay.dev)
