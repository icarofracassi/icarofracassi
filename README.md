# Hey, I'm Ícaro 👋

Electrical Engineering student turned developer — not a pivot, just the natural next step for someone who's always been building things.

Currently an intern at SAP, where I split my time between product support and building internal tools that actually make people's work easier. I also founded a small citizen developer group within our team to formalize that effort.

---

## What I work on

Most of my projects start with a problem I keep bumping into. Then I build something. Then other people start using it.

- **Browser extensions** for standardizing technical workflows across global teams
- **Productivity tools** that have racked up hundreds of downloads and touched tens of thousands of support cases
- **AI-assisted tooling** for semi-automated classification and case routing
- **Side projects** like a full-stack football statistics tracker with a 14-table PostgreSQL schema, materialized caches, RBAC, and time-travel roster reconstruction — because scope creep is a feature

The pattern: find friction → remove it → ship it.

---

## Before software

I worked four years and half as an Electrical Engineering Designer. I was already automating things — Excel/Sheets workflows, project standards, sizing calculations. I also self-taught specialized technical areas and went from "we depend on contractors for this" to "we now have in-house specialized people."

Same instinct, different domain.

---

## Stack

```
Languages     JavaScript · Python · HTML · CSS · SQL (PostgreSQL)
Certs         CS50 (Harvard) · Claude Code in Action (Anthropic)
Studying      B.Sc. Electrical Engineering — Unisinos (2022–2028)
```

---

## Arnica F.Q. — CS50x Final Project
 
My CS50x final project was a full-stack football match tracker built for a real group of friends who play and record their games but had no way to keep statistics or revisit highlights. So I built one.
 
The app handles the full lifecycle of a match: attendance, roster assignment, substitutions, goals, assists, fouls — each event stamped with a video timestamp. The game page embeds the YouTube footage alongside a live roster sidebar that updates as the video plays, showing exactly who's on the field at any given moment. Clicking any event seeks the player to that exact second.
 
The part I'm most proud of is the roster sync. Player state is materialized at every substitution boundary into a `roster_snapshots` table, so the frontend only needs a binary search against the current timestamp — fast enough to run on every poll cycle. It also animates entries in green and exits in red, which makes substitutions feel alive.
 
Other things worth mentioning: a 14-table schema with cascading FK relationships, a `player_stats_cache` with invalidation on roster changes, an `arrived_at` field on presences so late arrivals don't get false bench time attributed to before they showed up, and a global search that joins across every participant in every event type.
 
The project is live at [arnicafutebolquase.app](https://www.arnicafutebolquase.app) · [Video demo](https://www.youtube.com/watch?v=ObAuJqqad9U)


---

## How I work

At some point I started hitting real problems — branch chaos, tangled state, code that only I could navigate. So I solved them my own way, and later found out those solutions already had names: gitflow, state management patterns, layered architecture.
I think that's a good sign. These abstractions exist because everyone runs into the same walls, and understanding why a pattern was invented — what pain it was designed to absorb — is the part I actually care about. The recipe is just a shortcut to that answer.

---

## Currently

- 🛠 Building at "S4DEV" Citizen Developer group at SAP 
- 📐 Studying EE
  
---

📍 São Leopoldo, Brazil &nbsp;·&nbsp; 🇧🇷 PT / 🇺🇸 EN (C1)
