# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users
The owner, keeping score on his phone at the table during family game nights at home. One person holds the phone and enters scores for everyone; the rest of the table glances at it between hands.

## Product Purpose
Game Night Scores replaces pen-and-paper or a notes app for scoring card and tile games. Success means scoring never slows the game down: a round is entered in seconds, the leader is obvious at a glance, and past nights are there to look back on.

## Positioning
One small scorekeeper built around how a game night actually runs: fast round entry mid-game, rules that flex to whatever is on the table (highest or lowest wins, teams, who went out), a turn timer with sound to keep play moving, and history that carries standings across nights.

## Operating Context
- Used on a phone, held in one hand at a table, often mid-conversation and between hands.
- Games named in the app as examples: Uno, Rummikub.
- Screen is kept awake (Wake Lock) while the timer runs.
- Installable to the home screen as "Game Night" (web app manifest, icons in `icons/`), runs standalone.
- Follows the phone's light/dark setting.

## Capabilities and Constraints
- Static site: `index.html` plus `manifest.webmanifest`, `icons/` and `sounds/`. No build step, no framework.
- Hosted on GitHub Pages; must keep working as a static site there.
- Data saved on the device in both localStorage and IndexedDB so it survives closing the home-screen app; no accounts, no server, no sync between devices.
- Views: Scores, Rounds, Players, History, Timer.
- Score a round; tap a round to edit or delete it; two-tap confirm on destructive actions.
- Win condition toggles between highest and lowest score; ties are handled.
- Teams supported (players can be on a team or not).
- "Who went out" can be recorded per round.
- New game keeps players; finished games archive to History with standings.
- A sample game loads first so a new user sees how it works, with a "Start fresh" action.
- Turn timer with tap-to-restart, pause/resume, time's-up alert and sounds; sound can be turned on/off.
- New game picker: choose players, set up teams, untick all; play again after End game.

## Evidence on Hand
- `index.html` is the whole app logic and UI.
- Timer sounds in `sounds/`: tick1, tick2, tock1, tock2, beep, timeup (mp3).
- Home-screen icons in `icons/` (192, 512, apple-touch, favicon).
- No testimonials, users beyond the owner's family, or usage data. Do not fabricate any.

## Product Principles
1. Never slow the game down: every common action works one-handed in a couple of taps.
2. Readable across the table: the current leader and totals are legible at a glance.
3. Flexible to the game, not tied to one: rules are settings, not assumptions.
4. Remember the nights: history and standings are part of the product, not an afterthought.
5. Stay a simple static page that just works on GitHub Pages.
