# Anthony Zhou

Software engineer finishing a B.S. in Information Science at the University of Maryland in May 2027. I build backend services and the data work around them, mostly in Java, TypeScript, Python and PostgreSQL. I'm looking for a 2027 new grad software engineering role in Boston, the DC area or New York.

[anthony-zhou.com](https://www.anthony-zhou.com) · [LinkedIn](https://www.linkedin.com/in/anthony--zhou) · azhou112@terpmail.umd.edu

## Projects

**[p2p-ledger](https://github.com/developer-az/p2p-ledger)** · Java, Spring Boot, PostgreSQL, Kafka / AWS SQS, TypeScript · [assistant demo](https://ledger.anthony-zhou.com)

A double-entry payments API. Transfers are idempotent, both account rows are locked in id order so opposite transfers can't deadlock, and Postgres triggers reject a ledger that doesn't balance or an entry that gets edited. Events leave through a transactional outbox, so a rolled-back transfer never publishes one. A k6 load test ran the JVM out of memory at 500 req/s on a 512 MB container, which is why the service now sheds load with a fast 503. The README walks through each of these trade-offs. A TypeScript assistant answers account questions through LLM tool calls that are bound to the signed-in account in code.

**[Racket Form](https://racketform.anthony-zhou.com)** · Next.js, TypeScript, React Three Fiber, Supabase

A tennis stroke viewer and gear catalog. It pulls racket specs, tour usage and product media into one catalog behind Next.js API routes and scores each setup from measured specs instead of marketing ratings. Strokes play on 3D skeletal models. I fixed the animation math that flipped the elbow mid-swing and synced player profiles to Supabase with local-first storage.

**[UMD Tennis Court Alerts](https://github.com/developer-az/tennis-court-reserve-umd)** · Next.js, TypeScript, Upstash Redis, Resend, Vercel

Emails you when a court opens on UMD's booking system. A scheduled job checks availability and alerts verified addresses, with one-click unsubscribe in every email. Typecheck, unit tests and the build run in CI on every push to main.

## Work

- **Software Engineering Intern, Kin2College** (Summer 2026). Built Express REST APIs with JWT auth and role-based access for a nonprofit that supports students from kinship and foster care through college, plus the deadline reminder emails, run by a daily Postgres job with a send log so no email goes out twice. Found a gap in the existing code that let the browser write data directly and moved those writes behind server-side database functions. Set up GitHub Actions CI and branch protection.
- **Software Engineer Intern, Development Monitors** (Summer 2025). Built a QGIS plugin in Python that maps buildings and waterways from satellite and drone imagery into PostgreSQL, and the pipelines that feed it.
- **Software Development Intern, allBETs** (2025). Owned testing of payment and fraud edge cases across web and mobile before the iOS launch, and wrote Solidity contract logic.
- **Undergraduate Course Aide, INST346** (Computer Networking and Systems). I help students debug Linux over SSH, PowerShell scripts and Wireshark captures.

I use Claude Code, Cursor and Copilot every day. Their changes go through the same review, tests and CI as anyone else's before they merge.

## Stack

Java · TypeScript · JavaScript · Python · SQL · Spring Boot · Node.js / Express · React / Next.js · PostgreSQL / Supabase · Docker · GitHub Actions · Linux
