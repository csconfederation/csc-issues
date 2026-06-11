# CSC Issue Tracker

This repository is the **public issue tracker** for [Counter-Strike Confederation (CSC)](https://playcsc.com). It is the right place to report bugs, request features, and ask questions about any CSC product — the website, stats, Discord bot, or league platform.

> **No code lives here.** Pull requests are not accepted. Use the Issues tab only.

---

## Before You Open an Issue

1. **Search first.** Your issue may already be reported. Use the search bar at the top of the [Issues](../../issues) page.
2. **One issue per report.** Don't bundle multiple bugs or requests into a single issue.
3. **Be specific.** Vague reports are hard to act on. The more detail you provide, the faster the team can help.

---

## How to Open an Issue

1. Go to the [**Issues**](../../issues) tab and click **New issue**.
2. Choose a template:
   - **Bug report** — something is broken or behaving incorrectly on the website, stats page, or Discord bot
   - **Game Server** — lag, high ping, packet loss, rubber banding, or stuttering on a CSC game server
   - **Feature request / Enhancement** — suggest a new feature or improvement
   - **Question** — ask how something works
3. Fill in the form fields and submit.

For quick questions, use the [#help channel on Discord](https://discord.com/channels/644377562516029460/644578759151976488) — it's usually faster.

---

## Example: What a Good Bug Report Looks Like

> **Title:** Gameday lobby shows "Waiting for players" after all 10 players have readied up
>
> **Where:** Website (playcsc.com)
>
> **What I expected:** The lobby to advance to the veto / map pick screen once all 10 players clicked Ready.
>
> **What actually happened:** The lobby stayed on "Waiting for players" indefinitely. Refreshing the page showed everyone as ready but nothing happened. A second player re-clicked Ready and it un-readied them instead of triggering the transition.
>
> **Steps to reproduce:**
> 1. Join a gameday lobby with 10 players queued
> 2. Have all 10 players click Ready
> 3. Observe — lobby does not advance
> 4. A second Ready click from any player de-readies them rather than nudging the lobby forward
>
> **When it started:** June 10 2026, around 8 PM EST — happened in at least two lobbies that night
>
> **Discord username:** playerone

What makes this good: it has a clear, specific title; explains expected vs. actual behavior; gives numbered reproduction steps; includes timing; and attaches a Discord username so the team can pull match context.

---

## Labels

| Label | Meaning |
|---|---|
| `bug` | Something is broken or behaving incorrectly |
| `enhancement` | A new feature or improvement to existing behavior |
| `question` | A question about how something works |
| `game-server` | Related to a CSC game server |
| `documentation` | A gap or error in docs or in-game instructions |
| `duplicate` | This issue has already been reported |
| `wontfix` | Acknowledged but out of scope or intentional |
| `invalid` | Not a valid issue (spam, user error, etc.) |

The team applies labels after triage — you don't need to set them yourself.

---

## What This Tracker Is Not For

For anything below, open a [ticket in Discord](https://discord.com/channels/644377562516029460/1431110723949297858) instead:

- **Account bans or punishment appeals**
- **Private or sensitive matters**

---

## Response Time

This is a volunteer-run league. The team triages issues as time allows. Upvoting an issue (👍 reaction on the first post) helps signal priority.
