<h1 align="center">Hi, I'm Cohen 👋</h1>

<p align="center">
  Backend developer from Germany 🇩🇪 — data-intensive production systems,<br>
  integrations and cloud infrastructure.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/cohen-dos-santos-imperial-40b821300">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:cohenimperial@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

## 🧑‍💻 About me

Backend developer working on data-intensive production systems, integrations and cloud
infrastructure. I came from Python and PHP, build production backends in C# / .NET, and
work on the JVM side in Java and Spring on an open-source energy data framework.

I'm especially interested in combining traditional software engineering with AI-assisted
workflows, retrieval systems and local language models. What keeps me curious is the part
most people skip: figuring out *why* a system actually behaves the way it does before
changing it — production diagnostics is my favourite kind of puzzle.

## 🛠️ What I'm working on

I work across the full backend data flow: ingestion, validation, asynchronous processing,
persistence, APIs and production diagnostics.

- **APIs and data models** — ASP.NET Core and EF Core, from the entity configuration and
  migration up to the endpoint contract.
- **Background workers and message queues** — job pipelines, consumers, retry and
  dead-letter behaviour, idempotency under multiple replicas.
- **Telemetry and time-series data** — high-volume measurement data, aggregation,
  interpolation and the repair of broken series.
- **Importers and external system integrations** — third-party APIs, device protocols and
  the tolerant-reader boundaries between them.
- **Docker, Azure and CI/CD** — building, deploying and promoting services across
  integration, test and production environments.
- **Observability and production diagnostics** — dashboards, structured logging and
  tracing an observed symptom back to the line of code or the row of data that caused it.

## 🤖 AI as an engineering tool

AI is a real part of how I work — not as a code generator I paste from, but as a set of
structured engineering workflows with verification built in.

### AI-assisted development

- Code analysis, refactoring and architecture planning
- Writing and reviewing implementation plans before writing code
- Debugging complex data and network flows
- Working with AI agents on narrow, explicit assignments — every result gets verified
- Architecture and production decisions stay with the human

### Retrieval and knowledge systems

I'm exploring how BM25, embeddings and hybrid retrieval can give AI agents reliable access
to project knowledge instead of relying on context windows alone.

The system I actually use daily is a several-hundred-page engineering wiki behind a hybrid
search: a lexical BM25 index and a vector index queried in parallel and fused by reciprocal
rank, with a deliberate fallback cascade — hybrid, then lexical, then plain grep — so a
failed backend degrades the answer instead of breaking the tool. Things I care about there:

- BM25 and classic full-text search, embedding-based semantic search, and why the two find
  different things
- Hybrid fusion, chunking, metadata and ranking
- Retrieval-Augmented Generation, and measuring it instead of eyeballing it
- Latency budgets and failure semantics — a retrieval call should always return something
- Local LLMs, personal knowledge systems and agent-assisted workflows

### AI infrastructure and experimentation

- Purpose-built MCP servers so an agent gets narrow, typed tools instead of one broad prompt
- A controlled write path into the knowledge base — versioned, hashed, recoverable
- Local models and local-first setups, with an agent control plane as the next step
- Deterministic tooling before LLM reasoning, wherever a script can decide it
- Evaluation over subjective prompt tweaking

## 🧩 Selected engineering topics

**Backend systems** — C#, .NET, ASP.NET Core and EF Core; Java 21, Spring Boot and Project
Reactor on the JVM side. REST APIs, workers, schedulers and reactive streams.

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)

**Data and messaging** — SQL Server, PostgreSQL, InfluxDB, RabbitMQ, Kafka, MQTT, data
imports and time series.

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat&logo=influxdb&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat&logo=mqtt&logoColor=white)

**Cloud and delivery** — Azure, Docker, GitHub Actions, CI/CD, monitoring and production
diagnostics.

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Search and AI** — Python, BM25, embeddings, vector search, hybrid retrieval, RAG, local
LLMs and AI agents.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat&logo=obsidian&logoColor=white)

## 🚀 Projects and experiments

**[EDDIE](https://github.com/eddie-energy/eddie)** *(open source)* — the European
Distributed Data Infrastructure for Energy: a permission-based framework that gives energy
companies a single way to reach metering data across ~13 national grid operators. I work on
the German region connector — mapping provider data into CIM market documents
([#2475](https://github.com/eddie-energy/eddie/pull/2475)), historical-data polling
([#2347](https://github.com/eddie-energy/eddie/pull/2347)) and future-data polling
([#2329](https://github.com/eddie-energy/eddie/pull/2329)). The interesting part is the
outbound design: a connector never publishes to a topic itself, it just exposes a
`Flux<Envelope>` and the framework fans it out to Kafka, REST and AMQP at once. Java 21,
Spring Boot, Project Reactor, PostgreSQL, event sourcing over a transactional outbox.

**[Video Downloader](https://github.com/PappenHeim10/videoDownloader)** — an asynchronous
desktop app for downloading HLS streams. The interesting decision was separating the
site-specific scraping from the download engine: a client adapter only has to resolve an
`.m3u8` URL, and the core handles concurrent segment fetching, resumable state and
remuxing into MP4. Python, PySide6 and `qasync`, so the UI stays responsive while hundreds
of segments are in flight.

**Vault Control & Agent Control Plane** *(private, local-first)* — my own knowledge system
and the tooling around it. The problem: AI agents lose everything between sessions and
re-derive the same context over and over. The answer is a controlled write path into an
Obsidian vault — every change versioned, content-hashed and recoverable after a crash —
plus hybrid retrieval over it, so an agent looks knowledge up instead of carrying it in a
context window. Exposed to my tools as MCP servers. Everything runs locally by design.

**Game engines and reverse engineering** *(private)* — where I go when I want to work close
to the machine. A clean-room study of a 2000s fighting game's data format: the container
cipher decoded from public community research only, a Kotlin pipeline that normalises the
asset files into canonical JSON, and a C++17 engine model with a deterministic
fixed-timestep tick loop under test (no original assets redistributed). Alongside it a 2D
sidescroller in Godot / GDScript — the same problems, from the other end.

**[Musikplayer](https://github.com/PappenHeim10/Musikplayer)** — a local-first desktop
music player built with Electron: pick a folder, stream your tracks through a warm
hi-fi-console UI. The renderer never touches the file system — a small HTTP server in the
main process exposes the library and streams audio with range support, which keeps
`contextIsolation` on and `nodeIntegration` off.

## 🌟 Beyond code

Outside work I spend time on chess, psychological manga, music software and experiments
around local AI and personal knowledge systems. I enjoy projects that sit somewhere between
engineering, curiosity and everyday usefulness.

- ♟️ Chess — and learning systematically from my own games
- 📚 Psychological manga and character-driven stories
- 🎵 Music and local media libraries
- 🎮 Game engines, from tick loops to binary asset formats
- 🤖 Local AI models and personal automation
- 🧠 Knowledge management, Obsidian and second-brain systems
- 🏙️ An interest in flexible, location-independent ways of working

## 🧭 How I approach engineering

I prefer evidence over assumptions: inspect the real data flow, isolate the uncertainty,
make the smallest useful change and verify it against observable behaviour.

- Investigate what the system actually does before theorising about it
- Replace assumptions with measurements and tests
- Prefer small, verifiable changes over large rewrites
- Plan the failure case and the rollback, not just the happy path
- A green step is not a passing test — check that the check actually ran
- Never take an AI result at face value; verify it like any other claim
- Document knowledge so it can still be found months later

## 📚 Current learning focus

An honest split between what I use in production and what I'm still learning:

- **Using in production:** C# / .NET backends, EF Core, SQL Server, RabbitMQ, MQTT,
  time-series data, Azure, Docker and CI/CD; Java / Spring and Kafka-backed event streams
  on the EDDIE side
- **Currently learning:** Azure architecture and DevOps (AZ-204) and Azure SQL
  administration (DP-300), cloud and networking fundamentals in more depth, robust RAG and
  agent systems, retrieval evaluation and ranking, distributed systems and observability

## 📬 Contact

- 💼 [LinkedIn](https://www.linkedin.com/in/cohen-dos-santos-imperial-40b821300)
- ✉️ [cohenimperial@gmail.com](mailto:cohenimperial@gmail.com)

Happy to talk about backend data flows, time-series and telemetry systems, retrieval and
RAG, or local-first AI tooling.
