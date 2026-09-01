I build and operate production software end to end. Cross-platform systems that reach
**web, iOS and Android from a single codebase** — React&nbsp;/&nbsp;TypeScript and Flutter —
along with the backends, deployments and day-to-day operations behind them. Earlier work
in .NET&nbsp;/&nbsp;C# with EF Core, CQRS and multi-tenant data isolation.

I work with AI-assisted tooling daily, and treat reviewing what it produces as the part of
the job that matters: architectural fit, failure modes, and how the thing behaves in
production at 3am.

<img src="https://skillicons.dev/icons?i=ts,js,react,flutter,dart,tailwind,dotnet,cs,postgres,redis,docker,azure,firebase,linux&perline=14" alt="TypeScript, JavaScript, React, Flutter, Dart, Tailwind, .NET, C#, PostgreSQL, Redis, Docker, Azure, Firebase, Linux">

## Selected work

Source for these is private — each link goes to an architecture write-up explaining how it
is built and why.

#### [enTakvim](https://github.com/doguhanarslan/entakvim-case-study) — Clinic scheduling system · **in production**

`React 19` `TypeScript` `PocketBase` `Capacitor` `PWA`

Runs a psychology clinic's daily scheduling, client records and WhatsApp reminders.
One codebase serving web, iOS, Android and macOS from the same interface.

#### [Dreamluna](https://github.com/doguhanarslan/dreamluna-case-study) — AI dream analysis app · **on Google Play**

`Flutter` `Dart` `Firebase` `OpenAI` `GitHub Actions`

Offline-first sync, server-side OpenAI integration with prompt injection protection,
server-verified subscriptions, and CI/CD that publishes to the store on version tags.

#### [KlinikSaaS](https://github.com/doguhanarslan/kliniksaas-case-study) — Multi-tenant productisation & operations

`TypeScript` `React` `PocketBase` `Caddy` `systemd`

Per-clinic isolated instances behind a control plane, health-checked rolling releases,
encrypted off-site backups, and a watchdog that alerts only on state transitions.

#### [Planca](https://github.com/doguhanarslan/planca-case-study) — Multi-tenant appointment SaaS

`.NET` `C#` `EF Core` `PostgreSQL` `Redis` `Azure`

Tenant isolation enforced by EF Core global query filters rather than by remembering to
filter, CQRS with MediatR, Hangfire background jobs. Deployed to Azure Container Apps.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/doguhanarslan/) · arslandoguu@icloud.com
