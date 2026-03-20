# Mayank

Backend engineer with a thing for embedded systems and developer tooling.

I work across the full depth of the stack — TypeScript APIs, Python backends, and C++ firmware when the job calls for talking directly to hardware. I'm currently deep into AI tooling, specifically MCP (Model Context Protocol) and RAG systems.

---

### Projects

**[Adaptive-RAG](https://github.com/mac146/Adaptive-RAG)** `Python` `FastAPI` `Qdrant` `BM25`

A structure-aware RAG system that actually thinks before it retrieves. It parses PDFs, DOCX, and Markdown, detects document structure and sections, then picks a retrieval strategy based on both the document layout and the question type. Retrieval is hybrid — Qdrant for vector search, BM25 for keyword — followed by cross-encoder reranking before the LLM ever sees the context. Most RAG implementations skip all of this and just do nearest-neighbour on the whole doc. This one doesn't.

**[IssueWatcher](https://github.com/mac146/IssueWatcher)** `TypeScript` `MCP` `Node.js`

Monitors all your starred GitHub repos for new issues, runs each one through an LLM, and sends you an email with a plain-english summary and a suggested fix. Built on MCP so you can swap the underlying model or add new sources (JIRA, HackerNews, Reddit) without touching the core logic. One of those tools I built because I actually wanted it.

**[FastPay](https://github.com/mac146/fastpay)** `Python` `FastAPI` `MongoDB`

REST API for a digital wallet and transaction system. Users, wallets, cross-user transactions — full CRUD with auto-generated Swagger docs at `/docs`. Uses PyMongo directly, no ORM. Proper `.gitignore`, `requirements.txt`, and project structure from the start.

**[soccer-bot](https://github.com/mac146/soccer-bot)** `C++` `Arduino` `PlatformIO`

Autonomous robot built on Arduino Nano (ATmega328), written in C++ with PlatformIO. Proper layout — `src/`, `include/`, `lib/`, `test/`. Different problem space from web work entirely: no stack traces, no hot reload, just hardware doing what the code says or not.

---

### Stack

```
Languages   TypeScript · Python · C++ · JavaScript . C
Backend     FastAPI · Node.js · MongoDB · PyMongo
RAG/AI      Qdrant · BM25 · cross-encoder reranking · LLM APIs · MCP
Frontend    React · CSS
Embedded    Arduino Nano · ATmega328 · PlatformIO
Tooling     GitHub REST API · Nodemailer · Swagger UI · uvicorn
```

---

### Stats

![](https://github-readme-stats.vercel.app/api?username=mac146&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=mac146&layout=compact&theme=tokyonight&hide_border=true)

---

27 repos &nbsp;·&nbsp; India, UTC +05:30 &nbsp;·&nbsp; open to collabs and interesting problems