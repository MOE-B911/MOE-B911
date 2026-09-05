# MOE-B911 — MKB GitHub map

Private account for Mohammed Khaled Bajeri (MKB). Repos are categorized by **topic**, not dumped in one pile.

## Categories

| Topic | Meaning | Repos |
| --- | --- | --- |
| `active` + `command-hub` | Live personal OS | [`mkb-command-hub`](https://github.com/MOE-B911/mkb-command-hub) |
| `vault` + `identity` | Vault / envelope index apps | [`envelope-vault-index`](https://github.com/MOE-B911/envelope-vault-index) |
| `stub` + `scaffold` | Boilerplate only — not live systems | [`THE-BOT`](https://github.com/MOE-B911/THE-BOT) |

## Repo roles (short)

1. **mkb-command-hub** — Personal operating system (Next.js + Supabase). Primary active codebase.
2. **envelope-vault-index** — Envelope / vault index (Vite + Supabase). Identity track. Do not commit `.env`.
3. **THE-BOT** — Empty bot scaffold. Not an identity vault. Keep as stub until a real bot lives here.

## Not on this GitHub account (local `~/Developer`)

| Folder | Status |
| --- | --- |
| `stationery-chest` | Local only (no git remote) |
| `vlrs` | Local git, no GitHub remote |
| `OmniRoute` | Upstream clone (`diegosouzapw/OmniRoute`) — not MKB-owned |
| `claude-plugins-official` | Upstream Anthropic clone — not MKB-owned |

## Rules

- New MKB code gets a **topic** on day one (`active`, `vault`, `brand`, `fab`, `ops`, `stub`).
- Never commit `.env` / tokens. Use `.env.example` only.
- Upstream clones stay upstream — do not rewrite history as MOE-B911 unless forking intentionally.
- Author credit: **MKB** internally / **Mohammed Khaled Bajeri** on external surfaces.

_Last organized: 2026-09-04 (DISPATCH)._
