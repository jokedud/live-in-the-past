# live-in-the-past

An agent skill that simulates living inside a chosen past year in real time.

Pick any year — it asks on first run, no default — and it maps today's real month/day/time onto that year, then surfaces real dated events from that day: obscure local news, murders, small scandals, corporate seeds, incidents — the stuff the year-locked Twitter accounts dig up.

Two modes:

- **Digest** — a daily in-world briefing of what happened on this date in your year.
- **Natural mode** — casual pings like a friend texting breaking news ("yo guess what just happened…").

Hard rules: real dated events only, no future knowledge, obscure beats mainstream, multi-day stories unfold in order.

## Install

Drop `.devin/skills/live-in-the-past/` into a repo, or copy the `SKILL.md` into any agent skill directory. Then say "live in <year>" or just answer when it asks which year you want.

## Daily pings

Point a scheduled job/automation at a prompt like:

> Run live-in-the-past for year 2001, natural mode: find one real obscure event dated today in 2001 and tell me casually.
