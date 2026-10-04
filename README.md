## Nilesh Charan

Final year at NIT Trichy, Instrumentation and Control with a CS minor.

Last summer I interned at **Capital One**, building a LangGraph multi-agent pipeline that
reads a service codebase and proposes observability rules. Most of that work turned out to
be reliability engineering rather than prompting: compression to fit a token ceiling,
retries and fail-open fallbacks, and schema validation on every model response.

Right now I'm interested in real-time systems, LLM agents that have to be trustworthy,
and the general problem of making unreliable components behave.

### Things I've built

| Project | What it is |
|---|---|
| [LynxGPT](https://github.com/nileshcharan24/LynxGPT) | A LangGraph routing agent over three backends: RAG on Postgres + pgvector, question paper search, resume matching. FastAPI, Redis, MongoDB. |
| [Hospital Readmission](https://github.com/nileshcharan24/Hospital-Readmission) | Feature-tokenizer transformer written from scratch in PyTorch, with a leakage-safe staged data pipeline over 101,766 records. |
| [Fixit](https://github.com/nileshcharan24/fixit-project) | Full stack service request platform. React, Express, MongoDB, with real-time updates over Redis and WebSockets. |
| [NAND FTL Simulator](https://github.com/nileshcharan24/nand-ftl) | A flash translation layer in C: page/block/hybrid mapping, garbage collection, wear levelling, power-loss recovery. 65 tests, 673k assertions. |

**Stack:** Python, JavaScript, C, C++ · FastAPI, Node, Express · LangGraph, PyTorch ·
Postgres, MongoDB, Redis · Git, Linux

Reachable at nileshcharan.s@gmail.com