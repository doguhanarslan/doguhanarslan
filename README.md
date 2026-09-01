I build software that runs unattended and has to keep running: a scheduling system a
psychology clinic uses every day, an app on Google Play, and the multi-tenant rebuild of
the first one.

Most of what I know came from things that failed quietly rather than loudly — a backup
that stopped and told nobody, an alert channel muted because it fired too often, a
reminder the WhatsApp API accepted and never delivered because a phone number had a space
in it. A service that restarts itself also hides that it has been crashing for weeks.

So the half of the work I care about is what happens after deploy. React and TypeScript on
the web, Flutter on mobile; .NET and C# before that. I use Claude Code daily and read what
it writes.

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
