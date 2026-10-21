## Hi, I'm Sanduni 👋

Undergraduate at the **University of Moratuwa**, looking for a **software engineering internship**.
I like building things end to end — backend services, mobile apps, and the documentation and CI that keep them honest.

📍 Sri Lanka &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/sanduni-liyanage-6w) &nbsp;·&nbsp; ✉️ [sanduniliyanage519@gmail.com](mailto:sanduniliyanage519@gmail.com)

---

### 🚀 Featured projects

**[Flaglane](https://github.com/SanduniLiyanage/flaglane)** — feature flags and remote configuration platform
Deploy a feature turned off, roll it out to a percentage of users, and switch it off in seconds without redeploying.
- In-process flag evaluation with stable user bucketing across restarts and redeploys
- Monotone percentage rollouts, attribute-based targeting, kill switch, append-only audit log
- Fail-safe SDK: if the server is unreachable, apps keep running on the last known ruleset
- Least-privilege PostgreSQL setup (schema owner vs. app role with no DDL rights), OpenAPI docs generated from source
- 400+ backend tests against real PostgreSQL (Testcontainers); a shared fixture runs the same cases through the Java engine and the TypeScript SDK

`Java 25` `Spring Boot 3` `PostgreSQL` `Flyway` `TypeScript SDK` `Docker`

**[Moneyora](https://github.com/SanduniLiyanage/Moneyora)** — offline-first personal finance app · **released, [v1.2.0 for Android](https://github.com/SanduniLiyanage/Moneyora/releases/latest)** · [v1.3.0 in testing](https://github.com/SanduniLiyanage/Moneyora/releases/tag/v1.3.0)
Builds a budget from your own spending history and reads receipts with on-device OCR, entirely on the phone.
- Money Plan Generator: classifies each category as fixed, variable or seasonal, adjusts for its trend, and produces confidence-scored budgets on-device
- Receipt scanner reads a receipt in stages and checks its items against the printed total; categories learn from the user's corrections
- Debts kept per person and netted, settled in one tap, optionally moving the account the money went through
- AES-256 encrypted database (SQLCipher), key held in Android Keystore / iOS Keychain
- Feature-first Clean Architecture, enforced on every push by a CI architecture-boundary checker
- Audited the project's specifications before coding and tracked every defect found in a public errata log
- 2,888 automated tests, 92.5% domain-layer coverage, 183 merged pull requests; five releases, the later ones shaped by tester feedback, signed and published by GitHub Actions

`Flutter` `Dart 3` `Riverpod` `SQLite / SQLCipher` `Google ML Kit` `GitHub Actions`

**[Waypoint Logistics](https://github.com/n1s1th/SynapX_WaypointLogistics)** — delivery operations platform (team SynapX, Tech-Triathlon 2026) · [live system](https://synap-x-waypoint-logistics-8thu.vercel.app/)
Role-based platform covering an order's whole journey: store request, depot allocation, dock loading, driver delivery and receipt.
- Built the Loader workspace end to end: dock queue, loading checklist, issue flags and truck release
- Offline mode for the dock: pages cached per run, actions queued in an outbox and synced when the connection returns
- Single sign-on for all five roles through Keycloak, with role-scoped workspaces

`Next.js` `TypeScript` `FastAPI` `PostgreSQL` `Keycloak` `Docker`

### 🤝 Team projects

- **[HRM System](https://github.com/insharp/hrm-system)** — modular HR platform with an applicant tracking system and an AI CV-screening microservice. `FastAPI` `Next.js` `PostgreSQL`
- **[Sentrio](https://github.com/Devmith0702/sentrio)** — agentic AI browser extension that detects social engineering aimed at Sri Lankan banking users. `JavaScript`

---

### 🛠️ Tech I work with

**Languages:** Java · Dart · TypeScript · JavaScript · C++ · Python · SQL<br>
**Backend:** Spring Boot · FastAPI · PostgreSQL · Flyway · Keycloak · REST / OpenAPI<br>
**Mobile & frontend:** Flutter · Riverpod · React · Next.js<br>
**Tooling:** Git · GitHub Actions · Docker

### 📈 Currently

- Testing Moneyora 1.3.0 with friends — debts kept per person, credit cards showing what's left to spend, and safer updates
- Building Flaglane's React dashboard
- Open to internship opportunities — feel free to reach out!
