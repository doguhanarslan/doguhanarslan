## Doğuhan Arslan

I build and operate production software end to end — multi-tenant backends in **.NET / C#**
with EF Core, and **React / TypeScript** interfaces that ship to web, iOS and Android from a
single codebase.

I work with AI-assisted tooling daily, and treat reviewing what it produces as the part of
the job that matters: architectural fit, failure modes, and how the thing behaves in
production at 3am.

Ankara, Türkiye.

---

### Selected work

Source for these is private. Each link goes to an architecture write-up explaining how it
is built and why.

**[Planca](https://github.com/doguhanarslan/planca-case-study)** — Multi-tenant appointment SaaS · `.NET` `C#` `EF Core` `PostgreSQL`
Tenant isolation enforced by EF Core global query filters rather than by remembering to
filter, CQRS with MediatR, Hangfire background jobs, Docker Compose.

**[enTakvim](https://github.com/doguhanarslan/entakvim-case-study)** — Clinic scheduling system · **in production** · `React 19` `TypeScript` `PocketBase`
Runs a psychology clinic's daily scheduling, client records and WhatsApp reminders. One
codebase serving web, iOS, Android and macOS.

**[KlinikSaaS](https://github.com/doguhanarslan/kliniksaas-case-study)** — Multi-tenant productisation & operations · `TypeScript` `Caddy` `systemd`
Per-clinic isolated instances, health-checked rolling releases, encrypted off-site backups,
and a watchdog that alerts only on state transitions.

**[Dreamluna](https://github.com/doguhanarslan/dreamluna-case-study)** — AI dream analysis app · **on Google Play** · `Flutter` `Firebase` `OpenAI`
Server-side OpenAI integration with prompt injection protection, offline-first sync,
server-verified subscriptions, CI/CD publishing to the store on version tags.

---

### Stack

| | |
|---|---|
| **Backend** | .NET · C# · ASP.NET Core Web API · EF Core · MediatR · Hangfire · PostgreSQL · Redis · SQLite |
| **Frontend** | React · TypeScript · Redux Toolkit · RTK Query · Tailwind CSS · Vite |
| **Mobile** | Flutter · Dart · Capacitor · PWA |
| **Infra** | Docker · GitHub Actions · Linux · Caddy · systemd · Firebase / GCP |
| **Practice** | Clean Architecture · CQRS · DDD · Multi-tenant SaaS · REST |

---

[LinkedIn](https://www.linkedin.com/in/doguhanarslan/) · arslandoguu@icloud.com
