[README (2).md](https://github.com/user-attachments/files/31683569/README.2.md)
<div align="center">

# RAGHAV MALANI

<code>C++ · Python · Kotlin · AI</code>

<i>building stuff · breaking stuff · shipping stuff · doing a bit of CP on the side ⚔️</i>

<br>

[![GitHub](https://img.shields.io/badge/GitHub-Ragh234-0d1117?style=for-the-badge&logo=github&logoColor=39FF14)](https://github.com/Ragh234)
![Status](https://img.shields.io/badge/status-shipping-0d1117?style=for-the-badge&logoColor=39FF14&color=0d1117&labelColor=0d1117)

</div>

<br>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=15&duration=2200&pause=900&color=39FF14&center=true&vCenter=true&multiline=true&repeat=true&width=560&height=200&lines=%24+whoami;raghav%40github%3A~%24+.%2Fabout;%3E+CS+student%2C+LNMIIT;%3E+builder+of+random+things;%3E+AI+%2F+backend+%2F+Android;%3E+competitive+programming+enjoyer;%3E+professional+%22one+more+feature%22+dev;status%3A+coding..." alt="Terminal typing animation" />
</p>

<br>

## `~/currently`

```text
> exploring RAG pipelines and how to make retrieval actually reliable
> wiring up multi-agent systems that argue with each other before deciding anything
> shipping backend + Android side quests faster than I finish the last one
> half-building something new at 1am on a "quick idea"
> probably in the middle of a hackathon or about to be
```

<br>

## `~/projects`

The ones I'd actually defend in a technical interview.

<br>

### 🧠 `codebase-intelligence-rag`

**A code-aware RAG system that answers grounded questions about GitHub repos — with exact file/line citations.**

`Python` `Tree-sitter` `BM25` `FastEmbed` `NetworkX` `Streamlit`

Vector search alone misses exact identifiers and symbols, so this fuses semantic retrieval with BM25 lexical search via reciprocal rank fusion, parses code with Tree-sitter into functions/classes/calls, and expands context through a lightweight code graph before reranking. Runs fully local — no OpenAI key required to index or retrieve.

🔗 [github.com/Ragh234/codebase-intelligence-rag](https://github.com/Ragh234/codebase-intelligence-rag)

<br>

### 🤖 `MarketMind AI` — `TRADING_AGENT`

**A multi-agent market analysis system: five agents argue in parallel, one synthesizes the verdict.**

`Python` `LangGraph` `Groq` `yfinance` `Streamlit`

Price, sentiment, on-chain, macro, and risk agents fan out from a single LangGraph node, run concurrently, and merge into a synthesis agent that produces a bullish/bearish/neutral call with a confidence score and reasoning. Basically a small committee that has to actually agree before it says anything.

🔗 [github.com/Ragh234/TRADING_AGENT](https://github.com/Ragh234/TRADING_AGENT)

<br>

### 💹 `FinOS`

**A multi-tenant financial operating system — ERP, accounting, and collections in one platform.**

`Next.js` `NestJS` `PostgreSQL` `Redis` `BullMQ`

Double-entry accounting, invoice → payment → reconciliation flows, a transactional outbox for reliable event publication, and idempotency keys so financial APIs survive retries and duplicate requests without double-charging anyone. The unglamorous plumbing that makes finance software trustworthy.

🔗 [github.com/Ragh234/FinOS](https://github.com/Ragh234/FinOS)

<br>

### 🔎 `RazorRecon`

**An AI finance controller for payment reconciliation — deterministic math, LLM only for explaining exceptions.**

`Python` `Streamlit` `Gemini`

Reconciliation logic (ID matching, settlement linkage, fees, refunds, duplicates) stays fully deterministic against a 540-payment benchmark; an LLM investigator is boxed in with read-only tools to explain *why* something didn't match — never to touch the numbers. Live demo included, because a project that only runs on localhost doesn't count.

🔗 [github.com/Ragh234/RazorRecon](https://github.com/Ragh234/RazorRecon) · [live demo](https://razorrecon-sqdzzsbxwdkzpokgn28xpp.streamlit.app/)

<br>

### 📱 `CoinTrack`

**A crypto market + portfolio tracker, built the "actually maintainable" way.**

`Kotlin` `Jetpack Compose` `MVVM` `Room` `Hilt`

Clean Architecture end to end: Compose UI → ViewModel → use cases → repository → Room/Retrofit. Live INR pricing, offline caching, a persistent watchlist, and real profit/loss tracking on portfolio holdings — not just a coin-price wrapper.

🔗 [github.com/Ragh234/CoinTrack](https://github.com/Ragh234/CoinTrack)

<br>

### 🛒 `KeywordIQ`

**A full-stack Amazon keyword research SaaS with a homegrown ranking algorithm.**

`React` `Node.js` `FastAPI` `scikit-learn` `MongoDB`

Node/Express handles auth and the client gateway; a Python/FastAPI microservice scrapes live listings and scores keywords on a weighted mix of frequency, TF-IDF significance, and rank position — instead of just counting occurrences like everyone else's version of this tool.

🔗 [github.com/Ragh234/KeywordIQ](https://github.com/Ragh234/KeywordIQ)

<br>

## `~/side-quest`

```text
⚔️ competitive programming

C++ · DSA · algorithms
one more problem before sleep
```

<br>

## `~/toolbox`

```text
LANGUAGES
C++ · Python · Kotlin · TypeScript · Java

AI / ML
RAG · LangGraph · LLMs (Gemini, Groq) · Embeddings · NLP · Computer Vision (YOLOv8)

BACKEND / DATA
FastAPI · NestJS · Express.js · PostgreSQL · MongoDB · Redis · Qdrant · REST APIs

APP DEVELOPMENT
Android · Jetpack Compose · Room · MVVM · Hilt

TOOLS
Git · GitHub Actions · Docker · Streamlit
```

<br>

## `~/stats`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ragh234&show_icons=true&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=39FF14&icon_color=39FF14&text_color=c9d1d9" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ragh234&layout=compact&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=39FF14&text_color=c9d1d9" alt="Top languages" height="165" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ragh234/Ragh234/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ragh234/Ragh234/output/snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/Ragh234/Ragh234/output/snake.svg" />
  </picture>
</p>

<br>

## `~/connect`

Interested in AI/RAG systems, backend engineering, Android, or the next hackathon idea that probably isn't sleep-schedule-friendly. Reach out on [GitHub](https://github.com/Ragh234).

<br>

```text
raghav@github:~$ git status
On branch main
Changes not staged for commit:
        modified:   side-projects/
        modified:   sleep-schedule/
        untracked:  three-new-ideas-from-tonight/

nothing to commit, everything to build.
```

<div align="center">

**⚔️ ship it, then fix it, then ship it again.**

</div>
