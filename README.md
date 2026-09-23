# Uditanshu Tomar

Software engineer focused on distributed systems, AI infrastructure, and developer tools.

Foster City, California · Open to software engineering roles

[Email](mailto:uditanshutomar21@gmail.com) · [LinkedIn](https://www.linkedin.com/in/uditanshutomar)

## What I work on

At **Signadot (YC W20)**, I work as a Developer Relations Engineer on contract. I investigate integration requests, build supporting tools, troubleshoot Kubernetes workflows, and turn working integrations into official tutorials. I previously interned with the team.

At **Custosa**, I am a Software Engineer (Founder), building runtime security controls for AI agents. My work includes inspecting prompts and tool activity, preserving content provenance, and handling uncertain requests through human approval.

## Selected engineering work

- **[FastDuan](https://github.com/uditanshutomar/FastDuan)** · C++20, OpenMP  
  Parallel shortest-path engine with adaptive delta-stepping and a thread-local slab allocator. Recorded Apple M3 benchmarks show a **3.08x speedup** over the included parallel reference on RMAT-20 and **100 MTEPS** on RMAT-24 with 268 million edges. [Benchmarks and reproduction steps](https://github.com/uditanshutomar/FastDuan#performance)

- **[Distributed Stream Processing Platform](https://github.com/uditanshutomar/stream-processing-platform)** · Python, Kafka, gRPC, RocksDB, Kubernetes  
  Flink-inspired course project with JobManager and TaskManager coordination, distributed checkpointing, state recovery, and Docker/GKE deployment. The repository includes architecture notes and local run instructions.

- **[Custosa agent security proxy](https://github.com/uditanshutomar/CustosaXopenclaw)** · Python, WebSockets, HTTP  
  Public implementation of runtime controls for OpenClaw: prompt-injection checks, Unicode normalization, tool-risk policies, and Telegram approval for uncertain requests.

- **[GenEC](https://github.com/uditanshutomar/genec)** · Python, Java, Eclipse JDT, LLMs  
  Ongoing collaborative research on Extract Class refactoring. Combines static analysis and Git-history mining with constrained LLM reasoning, deterministic transformations, and verification before presenting suggestions.

- **[Boxoffice runtime verification](https://github.com/uditanshutomar/boxoffice-runtime-review)** · Node.js, PostgreSQL, Redis, Kubernetes  
  A seat-reservation demo with deliberate regressions, sandbox workflows, and tests covering retries, concurrent reservations, dependency failures, and runtime evidence.

## Published Signadot tutorials

I independently developed and authored these integrations:

- [Testing Dapr Services with Signadot Sandboxes](https://www.signadot.com/docs/tutorials/testing-dapr-services): request routing across Dapr service invocation and pub/sub while preserving sidecar mTLS
- [Diagnose Failing Tests with Signadot and CodeRabbit](https://www.signadot.com/docs/tutorials/coderabbit-signadot-failing-tests): sandbox-per-PR testing with GitHub Actions and Playwright, followed by diagnosis and verification of repairs

## Background

M.S. in Computer Science, Artificial Intelligence Specialization, **University of Colorado Boulder**, May 2026. Previously worked on backend systems at BharatPe, Slash (SlashPay), and Ford Smart Mobility.

Winner of **American Express CodeStreet '20** among 6,000+ teams; **NSF T3-CIDERS Fellow**; hackathon judge at **CalHacks 12 and MHacks**.

## Technologies

**Languages:** Python, Go, Java, C++, SQL, TypeScript, JavaScript  
**Systems and infrastructure:** Kubernetes, Docker, Helm, Kafka, gRPC, GitHub Actions, AWS, Google Cloud  
**Backend and AI:** Spring Boot, FastAPI, PostgreSQL, Redis, RocksDB, PyTorch, MCP
