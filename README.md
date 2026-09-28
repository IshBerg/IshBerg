## AI Product Builder

I take products from idea to pilot-ready: I define the product, design the system and set the rules it works by; AI models write the code, and I specify, review and verify it.

My main project is **YAKKI**, an English-learning platform for children who don't have English at home: an Android app on Google Play, a web client and a Rust backend in production, with AI content generation in 10 languages. I have been building AI systems since February 2025 and YAKKI since December 2025, running a fleet of AI coding agents.

### What I focus on

Making AI deliver reliably in production, not just in a demo:

- **Independent multi-model review.** Architecture decisions are reviewed by several AI models before implementation.
- **Quality gates that are proven to fail.** Every automated gate is checked against a control case before it is trusted; baselines can only improve (ratchets).
- **Anti-hallucination engineering.** Independent judge models on random samples with an acceptance threshold, verification by data provenance rather than by what an agent reports, and a system manifest that agents may not contradict.
- **Programmatic UI control.** Every UI element has a programmatic interface; coordinate taps are banned by a commit gate, so device tests are reliable.
- **Dynamic learner-language UI.** Interface language chosen per student by the teacher, 10 languages including RTL and Amharic, one string catalog with translation provenance.

### Public work

| Project | What it is |
|---|---|
| [yakki-claude-skills](https://github.com/YakkiEdu/yakki-claude-skills) | Claude Code skills extracted from YAKKI: multi-model committee reviews, task tracking, agent coordination, runbooks |
| [yakki-chat](https://github.com/YakkiEdu/yakki-chat) | Android client and Node.js WebSocket server to follow and steer AI coding agents from a phone |
| [LangChainAssistant](https://github.com/IshBerg/LangChainAssistant) | My first multi-model review committee (July 2025): one model writes code, another reviews it, with retrieval over project docs |
| [smartrag2](https://github.com/IshBerg/smartrag2) | Prototype of a hybrid on-device RAG library for Android: SQLite, knowledge graph, FTS5 and a Rust vector index |

### Background

Publishing (the full cycle, from choosing books to print and distribution), then years in retail management. Studied applied mathematics; learned programming the classic way (Fortran, Pascal, BASIC).

**Stack I direct:** Kotlin and Jetpack Compose, Rust (Axum), TypeScript and React, Python; Claude, GPT, Gemini, Grok.

### Looking for

A product role in a small team or AI startup: taking AI products from idea to something that works reliably for real users. Based in Haifa, Israel; hybrid or remote.

[LinkedIn](https://www.linkedin.com/in/ish-berg-79b713313/)
