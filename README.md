# Damyan Deshev

I build local-first AI systems that make model behavior inspectable: exact recall, evidence logs, token-level diagnostics, benchmark harnesses, and deterministic product workflows.

Most of my work sits at the edge between infrastructure, retrieval, model evaluation, and small tools that solve real problems without turning into platforms for their own sake.

## AI Systems And Evaluation

- [ariadne](https://github.com/damyan-deshev/ariadne) - local-first AI workbench built from an Open WebUI fork. It focuses on long-chat continuity, exact recall, evidence-first retrieval, personas, Kokoro TTS, local corpus workflows, and practical `llama.cpp` debugging.

- [logit_snake](https://github.com/damyan-deshev/logit_snake) - token inspection lab for local model runs. It visualizes logprobs, decoder risk, embeddings, branching, replay/diff behavior, and claim-level consistency experiments.

- [vera](https://github.com/damyan-deshev/vera) - local research agent runtime with a Docker sandbox, shell-based tools, evidence logs, verifier loops, and explicit unresolved states when evidence is insufficient.

- [damyan-bench](https://github.com/damyan-deshev/damyan-bench) - benchmark harness for OpenAI-compatible endpoints, including local servers. It covers coding, structured output, tool-use, boundary behavior, and operator-style tasks.

- [simon](https://github.com/damyan-deshev/simon) - local voice assistant with STT/TTS, FTS5 memory, ChatGPT archive recall, Android client support, image input, and explicit tests for long-context recall behavior.

## Product Systems

- [myroll](https://github.com/damyan-deshev/myroll) - local-first GM workspace for tabletop RPG campaigns. It separates private preparation from explicit player-facing publishing, with maps, fog, tokens, scene state, and export/restore workflows.

- [tavichka](https://github.com/damyan-deshev/tavichka) - mobile-first recipe search with deterministic filters, USDA nutrition mapping, smart tags, and in-memory indexes. The public repo includes code and maintenance scripts, not the production recipe database or generated images.

- [gymorpay](https://github.com/damyan-deshev/gymorpay) - commitment enforcement app with signed Android check-ins, VLM proof review, default-deny state transitions, idempotent daily penalties, and local SQLite state.

- [smallpie](https://github.com/damyan-deshev/smallpie) - privacy-first meeting capture pipeline with local transcription, diarization cleanup, live notes, scoped session credentials, and email-ready summaries.

- [dalimistiga](https://github.com/damyan-deshev/dalimistiga) - browser-only Bulgarian retirement calculator with NOI formulas, inflation modeling, safe-withdrawal scenarios, and regression tests around legal edge cases.

## Research Tooling And Data

- [ssl-pinning-toolkit](https://github.com/damyan-deshev/ssl-pinning-toolkit) - authorized Android TLS inspection toolkit for visibility into potential attack surface in modern mobile apps: Frida hooks, native-library fingerprints, signature windows, and repeatable test protocols.

- [data-deduplicator](https://github.com/damyan-deshev/data-deduplicator) - semantic deduplication reference implementation using embeddings, TF-IDF anchor vetoes, Jaccard checks, and graph clustering instead of plain cosine similarity.

- [hob-junter](https://github.com/damyan-deshev/hob-junter) - local/cloud LLM job matching system that scores roles against CV evidence, deduplicates listings, red-teams strong matches, and exports review queues.

[LinkedIn: Damyan Deshev](https://www.linkedin.com/in/damyan-deshev/)
