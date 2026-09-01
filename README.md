<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/doguhanarslan/doguhanarslan/main/hero-dark.svg">
  <img src="https://raw.githubusercontent.com/doguhanarslan/doguhanarslan/main/hero-light.svg" width="880" alt="One codebase, shipped to web, iOS, Android and macOS">
</picture>

I build things that have to work in a browser and on a phone at the same time, and keep
working after launch.

Right now that's a scheduling system a psychology clinic runs on every day, a dream-journal
app on Google Play, and the multi-tenant rebuild of the first one. Before those, a few years
of .NET and C#.

The part I underestimated early on was everything that comes after deploy — the backup that
quietly stopped running, the alert channel everyone muted because it fired too often, the
reminder that never arrived because a phone number had a space in it. Most of what I know
now came from those. I work with Claude Code daily and read what it writes before it ships.

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
