# Kaustubh Arora

Software engineer working on ML infrastructure and NLP tooling. Currently at ION Trading, previously at DRDO. I like bugs that sit between a model and the system it runs in.

## Merged upstream

Code of mine running in projects other people depend on.

| Project | What I changed |
|---|---|
| [stanfordnlp/stanza](https://github.com/stanfordnlp/stanza) · 7.9k★ | [#1693](https://github.com/stanfordnlp/stanza/pull/1693) Bounded the lemmatizer's results cache (LRU) and made it the default, so long-running pipelines stop growing without limit |
| | [#1692](https://github.com/stanfordnlp/stanza/pull/1692) Kept the cache off words a contextual lemmatizer decides, so `her` → `she`/`her` is still resolved by context after it has been seen before |
| [nextlevelbuilder/goclaw](https://github.com/nextlevelbuilder/goclaw) · 3.6k★ | [#1583](https://github.com/nextlevelbuilder/goclaw/pull/1583) Fixed agent deletion failing on an orphaned-vault path collision: a migration with a provenance column, a widened unique index, and an integration test that reproduces the collision |
| [Human-Agent-Society/reef](https://github.com/Human-Agent-Society/reef) · 7.6k★ | [#553](https://github.com/Human-Agent-Society/reef/pull/553) Harness `requires` kinds, so a program can declare the binary a release names |
| | [#714](https://github.com/Human-Agent-Society/reef/pull/714) Tell the model when a grounding document was cut short, instead of letting it end mid-sentence silently |
| [mex-memory/mex](https://github.com/mex-memory/mex) · 1.8k★ | [#196](https://github.com/mex-memory/mex/pull/196) Stopped targeted graph reads from re-auditing the whole store |

**Open:** [apache/tvm #20617](https://github.com/apache/tvm/pull/20617) — `ConvertLayout` segfaulted on `add(x, float32(1))` because layout inference dereferenced a null cast on the `PrimValue` operand. Reproduced from a no-LLVM build, fixed, regression test, CI green. · [SWE-bench #670](https://github.com/SWE-bench/SWE-bench/pull/670)

## Things I've built

- **[Auto-RCA](https://github.com/Kaustubh1235/Auto-RCA)** — alert fires → retrieve the matching historical RCA → extract a general SOP → run it with log-fetching tools → collect evidence. LLM-driven root-cause analysis for support teams.
- **[Vocat](https://github.com/Kaustubh1235/vocat)** — real-time voice conversation at sub-second latency: WebRTC → VAD → Whisper → streaming GPT-4 → Redis cache → ElevenLabs → WebRTC.
- **[AIEquity Traders](https://github.com/Kaustubh1235/MCP)** — a multi-agent trading-floor simulation where autonomous agents talk to local and remote MCP servers.
- **[BioGPT cancer-hallmark classifier](https://github.com/Kaustubh1235/BIO-SMALL-LANGUAGE-MODEL)** — a small biomedical language model fine-tuned for hallmark-of-cancer classification.
- **[ERA5 wind-speed LSTM](https://github.com/Kaustubh1235/era5_project)** — wind-speed prediction over time and altitude from ERA5 reanalysis data.
- **[NETOPTAI](https://github.com/Kaustubh1235/netoptai)** — phishing-site detection with the MLOps around it: MongoDB ingestion, training pipeline, deployment.
- **[Legally](https://github.com/Kaustubh1235/Legally-legal-advisor)** — an LLM legal assistant for Indian law, built for people who can't afford a lawyer for a first question.

## Background

- B.Tech, VIT Vellore — 8.5 / 10
- DRDO — research engineering
- ION Trading — software engineer, 2025 → now
- Co-founding something in developer tools. Quiet for now.

## Contact

kaustubharora082@gmail.com
