## Hi, I'm Sanduni 👋

Undergraduate at the **University of Moratuwa**, looking for a **software engineering internship**.
I like building things end to end — backend services, mobile apps, and the documentation and CI that keep them honest.

📍 Sri Lanka &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/sanduni-liyanage-6w) &nbsp;·&nbsp; ✉️ [sanduniliyanage519@gmail.com](mailto:sanduniliyanage519@gmail.com)

---

### 🚀 Featured projects

**[Flaglane](https://github.com/SanduniLiyanage/flaglane)** — feature flags and remote configuration platform<br>
Deploy a feature turned off, roll it out to a percentage of users, and switch it off in seconds without redeploying.
- In-process flag evaluation with stable user bucketing across restarts and redeploys
- Monotone percentage rollouts, attribute-based targeting, kill switch, append-only audit log
- Fail-safe SDK: if the server is unreachable, apps keep running on the last known ruleset
- React dashboard for flags, targeting rules, API keys and the audit trail, typed from the OpenAPI document the API generates from source
- Least-privilege PostgreSQL setup (schema owner vs. app role with no DDL rights) and per-key rate limiting
- Benchmarked: flag evaluation p99 under 4 µs in both the Java engine and the SDK; a change reaches running apps within 5 s
- 400+ backend tests against real PostgreSQL (Testcontainers); shared fixtures run the same cases through the Java engine and the TypeScript SDK

`Java 25` `Spring Boot 3` `PostgreSQL` `Flyway` `React` `TypeScript SDK` `Docker`

**[Moneyora](https://github.com/SanduniLiyanage/Moneyora)** — offline-first personal finance app · **released, [v1.2.0 for Android](https://github.com/SanduniLiyanage/Moneyora/releases/latest)** · [v1.3.0 in testing](https://github.com/SanduniLiyanage/Moneyora/releases/tag/v1.3.0)<br>
Builds a budget from your own spending history and reads receipts with on-device OCR, entirely on the phone.
- Money Plan Generator: classifies each category as fixed, variable or seasonal, adjusts for its trend, and produces confidence-scored budgets on-device
- Receipt scanner reads a receipt in stages and checks its items against the printed total; categories learn from the user's corrections
- Debts kept per person and netted, settled in one tap, optionally moving the account the money went through
- AES-256 encrypted database (SQLCipher), key held in Android Keystore / iOS Keychain
- Feature-first Clean Architecture, enforced on every push by a CI architecture-boundary checker
- Audited the project's specifications before coding and tracked every defect found in a public errata log
- 2,888 automated tests, 92.5% domain-layer coverage, 185 merged pull requests; five releases, the later ones shaped by tester feedback, signed and published by GitHub Actions

`Flutter` `Dart 3` `Riverpod` `SQLite / SQLCipher` `Google ML Kit` `GitHub Actions`

**[Waypoint Logistics](https://github.com/n1s1th/SynapX_WaypointLogistics)** — delivery operations platform (team SynapX, Tech-Triathlon 2026) · [live system](https://synap-x-waypoint-logistics-8thu.vercel.app/)<br>
Role-based platform covering an order's whole journey — store request, depot allocation, dock loading, driver delivery and receipt — with one Keycloak sign-in for all five roles.<br>
I built the frontend of the **Loader workspace**, the app the dock team uses to load and release trucks:
- Dock queue, loading checklist, issue flags, and truck release with undo
- Keeps working with the connection down: a service worker caches each run's pages, and actions wait in an IndexedDB outbox until they can sync
- Every write carries the plan version, so a stale plan or a reused ID comes back as a conflict instead of overwriting newer data

`Next.js` `TypeScript` `FastAPI` `PostgreSQL` `Keycloak` `Docker`

### 🤝 Team projects

- **[HRM System](https://github.com/Sachintha-dilshan49/hrm-system)** — modular HR platform with an applicant tracking system and an AI CV-screening microservice. I built its authentication (JWT with refresh tokens, TOTP two-factor sign-in, OTP password recovery, rate-limited auth endpoints), notifications and time tracking. `FastAPI` `Next.js` `PostgreSQL`
- **[Sentrio](https://github.com/Devmith0702/sentrio)** — agentic AI browser extension that detects social engineering aimed at Sri Lankan banking users. I built the extension's interface: the popup, the in-page warning overlay, and the threat and risk cards. `JavaScript` `React`
- **[Homeward](https://github.com/SanduniLiyanage/cg)** — an animated short in C++ and OpenGL that works 23 computer graphics concepts into one continuous scene, with the line, circle, fill and clipping algorithms written by hand. `C++` `OpenGL` `CMake`

---

### 🛠️ Tech I work with

**Languages:** Java · Dart · TypeScript · JavaScript · C++ · Python · SQL<br>
**Backend:** Spring Boot · FastAPI · PostgreSQL · Flyway · Keycloak · REST / OpenAPI<br>
**Mobile & frontend:** Flutter · Riverpod · React · Next.js<br>
**Testing & tooling:** JUnit · Testcontainers · Git · GitHub Actions · Docker

### 📈 Currently

- Testing Moneyora 1.3.0 with friends — debts kept per person, credit cards showing what's left to spend, and safer updates
- Finishing Flaglane v0.1: a public deployment, and multi-instance propagation over PostgreSQL `LISTEN`/`NOTIFY`
- Open to internship opportunities — feel free to reach out!
