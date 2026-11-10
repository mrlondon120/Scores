---
name: Game Night Scores
description: The family score pad, printed in teal and filled in pencil.
colors:
  accent: "#0e6b5c"
  accent-ink: "#ffffff"
  accent-soft: "#dff0eb"
  band-line: "rgba(255,255,255,.45)"
  bg: "#f7f8f7"
  surface: "#ffffff"
  sunk: "#f0f4f2"
  ink: "#1d2523"
  graphite: "#384140"
  muted: "#56645f"
  line: "#d3e4de"
  field-line: "#74867f"
  tile-red: "#c62f2f"
  tile-blue: "#1f5fbf"
  tile-orange: "#a35c00"
  tile-black: "#1d1d1d"
  bad: "#c23a2b"
  warn-bg: "#fdf3dc"
  warn-ink: "#6b4a00"
  accent-dark: "#2fae94"
  accent-ink-dark: "#03201a"
  accent-soft-dark: "#123029"
  band-line-dark: "rgba(3,32,26,.45)"
  bg-dark: "#0d1513"
  surface-dark: "#141d1b"
  sunk-dark: "#101917"
  ink-dark: "#e6edea"
  graphite-dark: "#d3dcd8"
  muted-dark: "#93a39e"
  line-dark: "#21392f"
  field-line-dark: "#61756c"
  tile-red-dark: "#f06b60"
  tile-blue-dark: "#72a3f3"
  tile-orange-dark: "#f2a744"
  tile-black-dark: "#ebe6da"
  bad-dark: "#f08a7e"
  warn-bg-dark: "#3a2f12"
  warn-ink-dark: "#f3d58c"
  timer-idle: "#0e1614"
  timer-run: "#0b2b25"
  timer-warn: "#3a2105"
  timer-up: "#4a100d"
  timer-paused: "#161d1b"
  timer-ring: "#3db49a"
  timer-ring-warn: "#f2a744"
  timer-ring-up: "#f06b60"
  timer-ring-paused: "#93a39e"
  timer-numeral-warn: "#ffd58a"
typography:
  display:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "2.1rem"
    fontWeight: 700
    lineHeight: 1.1
    fontVariation: "\"wdth\" 84"
  score-total:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "2rem"
    fontWeight: 700
    letterSpacing: "-0.01em"
    fontFeature: "\"tnum\" 1"
    fontVariation: "\"wdth\" 84"
  game-name:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 700
    letterSpacing: "-0.01em"
    fontVariation: "\"wdth\" 84"
  title:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.2rem"
    fontWeight: 700
    fontVariation: "\"wdth\" 84"
  timer-numeral:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "min(36vw, 24vh, 190px)"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "-0.02em"
    fontFeature: "\"tnum\" 1"
    fontVariation: "\"wdth\" 84"
  body:
    fontFamily: "Figtree, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.45
  player-name:
    fontFamily: "Figtree, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.1rem"
    fontWeight: 800
  sub:
    fontFamily: "Figtree, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "0.82rem"
    fontWeight: 600
  score-cell:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.02rem"
    fontWeight: 600
    fontFeature: "\"tnum\" 1"
    fontVariation: "\"wdth\" 84"
  label:
    fontFamily: "Oswald, Archivo, system-ui, sans-serif"
    fontSize: "0.74rem"
    fontWeight: 600
    letterSpacing: "0.08em"
rounded:
  stamp: "4px"
  tile-sm: "6px"
  tile: "7px"
  field: "8px"
  md: "10px"
  lg: "12px"
  sheet: "18px"
  pill: "999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "12px"
  lg: "14px"
  gutter: "16px"
  bar-reserve: "140px"
components:
  header-band:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.accent-ink}"
    typography: "{typography.game-name}"
    padding: "16px"
  tab:
    textColor: "{colors.muted}"
    padding: "10px 2px 9px"
    height: "44px"
  tab-active:
    textColor: "{colors.ink}"
  column-head:
    textColor: "{colors.accent}"
    typography: "{typography.label}"
    padding: "0 4px 6px"
  score-row:
    textColor: "{colors.ink}"
    typography: "{typography.player-name}"
    padding: "14px 4px"
  score-total:
    textColor: "{colors.graphite}"
    typography: "{typography.score-total}"
    padding: "0 8px"
  initial-box:
    textColor: "{colors.tile-black}"
    rounded: "{rounded.tile}"
    size: "2.1rem"
  initial-box-sm:
    rounded: "{rounded.tile-sm}"
    size: "1.7rem"
  button:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "10px 14px"
  button-small:
    rounded: "{rounded.md}"
    padding: "6px 12px"
    height: "44px"
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.accent-ink}"
    rounded: "{rounded.md}"
    padding: "10px 14px"
  button-bar:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.accent-ink}"
    rounded: "{rounded.lg}"
    padding: "16px"
  button-armed:
    backgroundColor: "{colors.bad}"
    textColor: "#ffffff"
    rounded: "{rounded.md}"
  input-field:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "10px 12px"
  segmented:
    backgroundColor: "{colors.sunk}"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
    padding: "4px"
  segmented-active:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.accent}"
  pad-section:
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    padding: "0 0 20px"
  history-row:
    textColor: "{colors.ink}"
    padding: "14px 4px"
  rounds-cell:
    textColor: "{colors.graphite}"
    typography: "{typography.score-cell}"
    padding: "10px 12px"
  rounds-total:
    backgroundColor: "{colors.bg}"
    textColor: "{colors.ink}"
    padding: "10px 12px"
  preset:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "7px 13px"
    height: "44px"
  preset-selected:
    backgroundColor: "{colors.accent-soft}"
    textColor: "{colors.accent}"
  sheet:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.sheet}"
    padding: "18px 16px"
  example-notice:
    textColor: "{colors.accent}"
    rounded: "{rounded.lg}"
    padding: "6px 6px 6px 14px"
  toast:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.bg}"
    rounded: "{rounded.lg}"
    padding: "10px 14px"
  timer-run:
    backgroundColor: "{colors.timer-run}"
    textColor: "#ffffff"
    typography: "{typography.timer-numeral}"
  timer-warn:
    backgroundColor: "{colors.timer-warn}"
    textColor: "{colors.timer-numeral-warn}"
  timer-up:
    backgroundColor: "{colors.timer-up}"
    textColor: "#ffffff"
  timer-paused:
    backgroundColor: "{colors.timer-paused}"
    textColor: "#ffffff"
---

# Design System: Game Night Scores

## Overview

**Creative North Star: "The Family Score Pad"**

The app is the score pad that lives in the game drawer: a printed form in one teal ink, filled in by hand in graphite pencil. Everything printed (the header band, the column heads, the rules under them, the active-tab underline) is teal. Everything written by the scorekeeper (totals, round values, player names) is graphite or ink. The leader's total is circled in pencil, and the circle is drawn again whenever the lead changes hands.

It is one narrow column, built to be held in one hand and glanced at from across the table. Rows and sections are separated by ruled lines, not boxed into cards: score rows, history entries, the Rounds grid and the settings sections in Players, Timer and History all sit directly on the pad. Players are marked with outlined initial boxes in the four tile colours (red, blue, orange, black), so a player can be found by colour before their name is read. Density is calm: a few ranked rows, very large tabular totals, and a pinned "+ Score a round" bar at the thumb.

The world rejects the stock card-list scoreboard: rounded white cards on grey, pill-shaped tabs, a filled highlight behind the leader. It avoids childish, busy, flashy or overly serious registers. It follows the phone's light and dark setting, with a manual override.

**Key Characteristics:**
- Printed teal for the form, graphite for the filled-in values, red pencil for negatives.
- One column, max 720px, 16px gutters, ruled rows and ruled sections; no boxed cards.
- Semi-condensed Archivo numerals (84% width) with tabular figures for every score.
- Oswald small-caps column heads in teal over a 2px teal rule.
- Outlined initial boxes in four tile colours.
- The pencil ring around the leader's total (and the winner's name, and the last winner in History) is the signature.
- Light pad (near-white) and night pad (deep green-black); the timer is always dark.

## Colors

One printed ink (teal) on a pale or deep-green pad, with graphite values and the four tile colours reserved for player marks.

### Primary
- **Printed Teal** (`accent`; night: `accent-dark`): the only brand colour. It fills the header band and the status-bar strip above it, the primary buttons and the bottom "+ Score a round" bar. It draws every printed line: column-head text and the 2px rule under it, section-head rules, the History list's top rule, table head rules and the Rounds total rule, the active-tab underline, the focus outline, the selected-chip border, the dashed example notice, the stamp-style round-type tag, the pencil ring, the text caret, and win marks (the "went out" mark, the winning total in the round sheet's winner line, first place in standings). The win role (`--good`) is an alias of this teal in both themes, not a separate green. In dark mode it lightens to a brighter teal so the band and rules read on the night pad.
- **Band Ink** (`accent-ink`; night: `accent-ink-dark`): text on teal. White on the light pad; near-black green on the night pad, where the teal is light.
- **Teal Wash** (`accent-soft`; night: `accent-soft-dark`): the faint teal fill behind selected chips, presets and the winner line, the 2px focus halo on fields, and text selection (with Ink text).
- **Band Rule** (`band-line`; night: `band-line-dark`): translucent hairline for outlined controls sitting on the band, such as the New game button and the game-name underline on hover/focus.

### Secondary: the four tile colours
Player marks only. A player's colour index (mod 4) picks one of these for the outline and letter of their initial box.
- **Tile Red** (`tile-red` / `tile-red-dark`)
- **Tile Blue** (`tile-blue` / `tile-blue-dark`)
- **Tile Orange** (`tile-orange` / `tile-orange-dark`)
- **Tile Black** (`tile-black` / `tile-black-dark`): black on the light pad, warm bone on the night pad.

### Tertiary: semantic
- **Red Pencil** (`bad` / `bad-dark`): negative totals and values, the "−" sign toggle when active, danger text and the armed (second-tap) state of destructive buttons.
- **Notice Amber** (`warn-bg` / `warn-ink` and their dark pairs): warning boxes only.

### Neutral
- **Pad** (`bg` / `bg-dark`): the page ground. Near-white on light; deep green-black on dark.
- **Sheet White** (`surface` / `surface-dark`): raised paper for sheets, fields, outlined buttons, chips, presets and selected segments.
- **Sunk** (`sunk` / `sunk-dark`): recessed track behind segmented controls, and Rounds row hover.
- **Ink** (`ink` / `ink-dark`): headings, names, active tab text, the Rounds Total row, selected text, the toast background.
- **Graphite** (`graphite` / `graphite-dark`): the "pencil" for filled-in numbers: score totals and table cells.
- **Muted** (`muted` / `muted-dark`): the "N behind" line, hints, meta, rank numbers, inactive tabs.
- **Rule** (`line` / `line-dark`): ruled row and section separators, the tab baseline, table row rules, dashed empty states and the dashed rule inside an opened history entry.
- **Field Rule** (`field-line` / `field-line-dark`): the darker stroke for text fields and the sign toggle, so inputs read as writable.

### Turn timer
The full-screen timer has its own fixed dark palette in both themes. The ground is a radial glow of the ring colour (22% mixed in) fading to the state background. Idle `timer-idle`, running `timer-run` with ring `timer-ring`, last seconds `timer-warn` with ring `timer-ring-warn` and amber numerals `timer-numeral-warn`, time's up `timer-up` with ring `timer-ring-up` and a pulsing numeral, paused `timer-paused` with ring `timer-ring-paused`. The background cross-fades over 0.25s between states.

### Named Rules
**The One Ink Rule.** Printed parts of the form (band, heads, rules, underline, ring, focus, caret, selection) and win marks are teal and only teal. There is no second brand or success colour; nothing else on the pad gets a brand colour.

**The Pencil Rule.** Numbers the scorekeeper wrote are graphite. Negatives switch to red pencil. Totals are never teal and never sit on a coloured fill.

**The Tile Colours Are Names Rule.** The four tile colours mark players and nothing else. They never carry status, ranking or emphasis.

## Typography

**Display Font:** Archivo variable (with system-ui, -apple-system, Segoe UI, sans-serif), set semi-condensed (`font-stretch: 84%`) wherever it carries a heading or a number.
**Body Font:** Figtree variable (with system-ui, -apple-system, Segoe UI, sans-serif).
**Label Font:** Oswald 600 (with Archivo, system-ui), uppercase and tracked.

All three are self-hosted from `fonts/` under the SIL Open Font License; Archivo and Figtree are preloaded.

**Character:** Archivo's narrowed numerals look like a printed score form; Figtree keeps names and hints friendly and plain; Oswald supplies the condensed small-caps of a pre-printed column head.

### Hierarchy
- **Display** (Archivo 700, 2.1rem, 1.1, 84% width): the game-over heading (the winner's name, or "It's a tie"), circled in pencil.
- **Score total** (Archivo 700, 2rem, −0.01em, tabular, 84% width, graphite): the per-row total on the Scores board. The largest repeated text on the pad.
- **Game name** (Archivo 700, 1.5rem, −0.01em, 84% width): the editable game title in the header band.
- **Title** (Archivo 700, 1.2rem, 84% width): pad-section heads (h2), set over a 2px teal rule.
- **Score cell** (Archivo 600, 1.02rem, tabular, 84% width, graphite): every score cell in the Rounds grid; the Total row is the same at weight 800 in Ink.
- **Numerals in place** (Archivo 600–700, 1.15–1.5rem, tabular, 84% width): round-entry inputs, timer setting inputs, history standings.
- **Timer numeral** (Archivo 700, min(36vw, 24vh, 190px), line-height 1, −0.02em, tabular): the countdown; drops to min(24vw, 16vh, 130px) for long values.
- **Body** (Figtree 400, 16px, 1.45): base text.
- **Player name** (Figtree 800, 1.1rem): names on the board; other lists use Figtree 700.
- **Sub** (Figtree 600, 0.82rem, muted): the "N behind" / "Leading" line under a name, and other second lines.
- **Label** (Oswald 600, 0.74–0.76rem, 0.08em, uppercase, teal): column heads, table heads, form labels naming the block below, the "Lowest wins" chip and round-type tags. A label suffix ("· optional", "· 4 picked") drops to Figtree 600, sentence case, Muted.
- **Round number** (Oswald 600, Muted): the first column of the Rounds grid.

### Named Rules
**The Tabular Rule.** Every score, total, rank and timer value uses tabular figures, so columns of numbers line up like a ruled form.

**The Narrow Numeral Rule.** Archivo is always set at 84% width when it is used for headings or numbers. It never appears at full width.

## Layout

A single column, max-width 720px, centred, with a 16px side gutter that grows to the device's safe-area inset when larger. The page reserves 140px at the bottom for the pinned "+ Score a round" bar, which sits over a gradient fade from the pad colour (70%) to transparent.

Top to bottom: the teal header band runs edge to edge (it cancels the wrapper's gutters and top padding, and the status-bar strip above it is teal too); an optional dashed example notice; the sticky underline tab row (Scores, Rounds, Timer, Players, History) spread across the full width; then the active panel with 14px top padding.

Spacing steps are small and repeated: 4px, 6px, 8px, 10px, 12px and 14px for gaps and padding; 16px for gutters and band padding; 18px for sheet padding. Board rows are 14px tall-padding with 4px side insets, 12px gaps between rank, initial box, name and total.

Bottom sheets (round entry, New game) rise from the bottom edge, max-width 600px and up to 92% of the viewport height, over a 50% green-black scrim. The game-over card is the same sheet centred, max-width 440px. Settings in Players, Timer and History are ruled pad sections stacked with 18px between them. The sheet's last action row is sticky at its bottom edge. Touch targets are at least 44px; sheet actions are 52px.

## Elevation & Depth

The pad is flat. Depth comes from the ruled form and from sheets of paper laid over it, not from shadows. Rows, column heads, tabs, sections and tables carry no shadow. Shadows appear only on the few elements that sit physically above the pad.

### Shadow Vocabulary
- **Sheet action lip** (`box-shadow: 0 -10px 12px -10px rgba(0,0,0,.18)`): the soft upper edge on a sheet's sticky action row, showing that content scrolls under it.
- **Selected segment** (`box-shadow: inset 0 0 0 1.5px accent`): the chosen option in a segmented control is a Sheet White tab outlined in teal, flat, with no drop shadow.
- **Field focus halo** (`box-shadow: 0 0 0 2px accent-soft`): with the teal border on a focused field.
- **Selected ring** (`box-shadow: inset 0 0 0 1px accent`): doubles the 1px teal border on a selected went-out chip or timer preset.
- **Scrim** (`background: rgba(5,12,10,.5)`): behind every sheet.

### Named Rules
**The Flat Pad Rule.** Nothing on the pad casts a shadow. Only sheets (and a sheet's sticky action row) are lifted. Selection is shown with teal outlines, never with a shadow.

## Shapes

Gently squared paper shapes. The pad itself has no corners: score rows, history entries, settings sections and the Rounds grid are 0-radius strips divided by rules, with no outer box. The only bordered container left on the pad is the dashed empty state (10px). Buttons, segmented controls and went-out chips are 10px; text fields, the sign toggle and timer presets 8px; initial boxes 7px (6px small); the round-type stamp 4px; the example notice, toast and bar button 12px; sheets 18px on their top corners only. The pill shape (999px) is kept only for the small printed "Lowest wins" chip. Timer controls are 58px outlined circles.

Line weights carry meaning. 1px is a ruled separator. 1.5px outlines an initial box, the selected segment, the dashed example notice and the dashed empty state. 2px is a printed rule: teal under column heads, section heads, table heads and the Rounds total row, and above the History list; Rule-coloured for the tab baseline. 3px is the active-tab underline. Dashed lines mean "not real yet" or "tucked inside": the example notice, empty states, and the 1px dashed rule above an opened history entry's details.

## Components

### Header band
The printed top of the pad. A full-bleed teal band (Printed Teal background, Band Ink text, 16px padding) holding the editable game name on the left (Game name type, transparent field with a 2px dashed underline that appears in Band Rule on hover/focus) and an outlined "New game" button on the right (transparent, Band Rule border, inherits band text colour). The status-bar strip above it is filled teal to match.

### Example notice
A dashed reminder that the sample game is loaded: transparent ground, 1.5px dashed teal border, 12px radius, teal bold text, with an outlined teal "Start fresh" button. Shown only while the example is loaded.

### Navigation: underline tabs
Five equal tabs across a 2px Rule baseline. Tabs are transparent, 0-radius, at least 44px tall, Figtree 700 at 0.9rem in Muted. The selected tab turns Ink and gets a 3px teal underline that sits on the baseline (pulled down 2px). The row is sticky under the safe-area top on the Pad background.

### Column heads
The pre-printed head of the board: `#`, `Player · N rounds` (or `Team`), and `Total`, in the Label style in teal, over a 2px teal rule with 6px bottom padding. When lowest score wins, an outlined teal "Lowest wins" chip sits in the head.

### Ruled score rows
Each player or team is a transparent strip with a 1px Rule bottom border and 14px vertical padding: rank (Oswald 600, ~1rem, Muted, centred in a 1.6rem column), the initial box, the name (Player name type) with a Sub line under it ("Leading", "Tied for the lead", or "N behind"), and the total on the right (Score total type in Graphite, Red Pencil when negative). The leader row has no fill, border or badge; the pencil ring alone marks it. Team rows add a line of member initial boxes (small) and names below, indented 2.4rem.

### Outlined initial boxes
A player's mark: a transparent 2.1rem square, 7px radius, 1.5px outline and letter both in that player's tile colour, Archivo 700 at 1rem. When two saved players share an initial, the box shows two letters at a smaller size. Small (1.7rem, 6px radius) inside team member lists, the round sheet and history. On the game-over card, 3.4rem, 10px radius, 2px outline, dropped in one by one with a slight tilt and bounce.

### The pencil ring (signature)
A hand-drawn loop around the leader's total, around the heading of the game-over card (the winner's name, or "It's a tie"), and around the last winner's name in History's All nights line. It is an inline SVG path in Printed Teal, 2.4px round-capped stroke, non-scaling, stretched to the number's box with a little overhang (14px each side, 9px top and bottom on the board). When the lead changes (or on first render with rounds), the stroke draws itself over 0.7s (`cubic-bezier(.5,0,.3,1)`, 0.1s delay). When the lead is unchanged, it is shown already drawn. On the game-over card it always draws; in All nights it is shown already drawn (2px/4px overhang around an inline name). With reduced motion it is always shown complete. Ties ring every tied leader.

### Buttons
- **Shape:** 10px radius, 1px border, Figtree 700 at 0.95rem, 10px 14px padding; nudges down 1px when pressed.
- **Default:** Sheet White with a Rule border.
- **Primary:** Printed Teal fill and border, Band Ink text.
- **Bottom bar:** the full-width primary "+ Score a round", 16px padding, 12px radius, Archivo 700 at 1.1rem (84% width). The timer's Start button is the same at 18px padding and 1.2rem.
- **Small:** 6px 12px padding, 0.88rem, 44px minimum height.
- **Ghost / Link:** transparent; the link variant is Muted, underlined with a 3px offset.
- **Danger and armed:** destructive buttons show Red Pencil text, and on the first tap become armed (Red Pencil fill, white text) waiting for a confirming second tap.
- **Disabled:** 45% opacity.
- **Focus:** a 3px teal outline, 2px offset, on every focusable element.

### Segmented control
A Sunk track (10px radius, 4px padding and gap) of transparent Muted options. The selected option becomes a flat Sheet White tab with teal text and a 1.5px inset teal outline (no shadow). Two options by default, three for the Display setting.

### Display setting (Auto / Light / Dark)
A ruled section in Players headed "Display" with a three-way segmented control and a hint that restates the choice ("Follows your phone's light or dark setting.", "Always dark, whatever the phone is set to.", "Always light, whatever the phone is set to."). Auto removes the `data-theme` attribute so the dark tokens apply through `prefers-color-scheme`; Light and Dark set `data-theme` on the root, which forces the matching token set. The browser theme colour follows: Printed Teal on light, the night teal on dark.

### Inputs / Fields
- **Style:** Sheet White ground, 1px Field Rule border, 8px radius, 10px 12px padding.
- **Focus:** the border turns Printed Teal with a 2px Teal Wash halo; no outline.
- **Round entry:** each player row in the round sheet has a sign toggle (2.8rem square, 8px radius, Field Rule border, Archivo 700 at 1.3rem; filled Red Pencil with white text when set to minus) and a right-aligned 5.5rem Archivo 600 numeric field, with the player's running total shown beneath the name.
- **Checkboxes** use the teal accent colour, 1.4rem, with a 44px hit area.

### Chips and tags
- **Who went out** chips: Sheet White, 1px Rule border, 10px radius, carrying a small initial box; selected adds a teal border, a 1px inset teal ring and a Teal Wash fill.
- **Timer presets** are form boxes, not pills: Sheet White, 1px Field Rule border, 8px radius, tabular figures, 44px minimum height; selected takes a teal border, 1px inset teal ring, Teal Wash fill and teal text.
- **Printed chip** ("Lowest wins"): outlined pill, Label type.
- **Round-type stamp** (Rummikub / Points in the rounds table): transparent, 1px teal outline, 4px radius, Label type at 0.7rem.

### Rounds grid (Rounds and history)
A ruled grid written straight on the pad, with no outer box, horizontally scrollable. Head cells are Label type in teal over a 2px teal rule. Score cells are the Score cell style (Archivo 600, 84% width, tabular) in Graphite, each row closed by a 1px Rule; round numbers in the first column are Oswald in Muted. The first column sticks to the left on the Pad ground so it stays legible while scrolling. The Total row sits on the Pad ground in Archivo 800, Ink, over (closed by) a 2px teal rule. Rows are tappable to edit (Sunk on hover). "Went out" values show in teal.

### Pad sections (Players, Timer, History)
Settings and groups are ruled sections of the pad, not cards.
- **Shape:** transparent, no border, no radius; 20px bottom padding closed by a 1px Rule; 18px between sections; 10px gap inside.
- **Section head:** the Title (h2, Archivo 700 at 1.2rem, 84% width) over a 2px teal rule with 7px padding beneath; when the head row carries a button, the rule runs under the whole row.
- **Empty state:** the one bordered element left: transparent with a 1.5px dashed Rule border, 10px radius, centred Muted text and one primary action.

### History
- **List:** opens with a 2px teal rule. Each past game is a ruled row (transparent, 1px Rule bottom border, 14px 4px padding): game name in Archivo 700 at 1.1rem, date in Muted, the winner line with the winner in teal, and a chevron that turns 90° when open. Opening a row reveals standings and its Rounds grid below a 1px dashed Rule.
- **All nights:** a collapsible pad section. The heading itself is the toggle button (full width, 44px minimum, chevron at the right, rotates 90° when open, `aria-expanded`). The "Last winner: <name>" line stays visible whether open or closed, with the name ringed in pencil, plus "N in a row" for a streak; a tied last game reads "The last game was a tie." Open/closed is saved with the rest of the data (open by default). The body lists win counts per player with first place in teal and a counted-games hint.

### Game-over card
The sheet centred as a card (max-width 440px, 18px radius, 24px top padding). The player's outlined initial boxes drop in (3.4rem), then the heading rises in: the winner's name in Display type, circled in pencil, with "N points" (and "lowest score wins" when set) beneath in Muted. A tie makes "It's a tie" the circled heading, with the tied names joined by "&" and their points beneath. There is no separate "Winner" label above the heading. Final standings follow under a "Final scores" label.

### Sheets
Bottom sheets in Sheet White, 18px top radius, 18px/16px padding with safe-area insets, 14px gap between blocks, a sticky action row with the sheet action lip. The round sheet's winner line is a Teal Wash strip (12px radius) with the winning total in Archivo, teal. Sheets have no coloured top edge; the rounded top corners and the scrim are their only frame.

### Toast
An Ink rectangle (12px radius) with Pad-coloured text, floating above the bottom bar (or at the top when the bottom is busy). Its Undo action is underlined, extra-bold, in Teal Wash.

### Turn timer
A full-screen dark overlay with two rows of three 58px outlined circular controls (stop, pause, mute; 2.5px white border at 85%), one at the top and a mirrored one at the bottom so either player can reach them. The centre is a tap-to-restart dial: a 5px track at 14% white and a round-capped progress arc in the state ring colour, sized min(80vw, 52vh, 420px), around the Timer numeral. The dial does a quick 0.22s scale-in on each tap. The state colours are in Colors › Turn timer. Time's up pulses the numeral (1s, to 45% opacity). A status line in Archivo 700 at 1.6rem sits below the dial.

## Do's and Don'ts

### Do:
- **Do** draw every printed element (band, heads, section rules, active underline, ring, focus, caret, selection wash) and every win mark in Printed Teal; there is no separate success green.
- **Do** write numbers in Graphite, with tabular figures, in Archivo at 84% width; switch to Red Pencil for negatives.
- **Do** write lists, settings sections, history entries and the Rounds grid directly on the pad, separated by 1px Rule lines and headed by a 2px teal rule.
- **Do** mark players with outlined initial boxes in their tile colour (colour index mod 4).
- **Do** mark the leader, the game-over heading and the last winner with the pencil ring only, redrawn when the lead changes and shown complete under reduced motion.
- **Do** put column and table heads in Oswald 600 uppercase at 0.08em tracking, teal, over a 2px teal rule.
- **Do** define every colour as a token in both the light block and the two dark blocks (`prefers-color-scheme` without `data-theme="light"`, and `data-theme="dark"`).
- **Do** keep touch targets at least 44px and keep the primary action in the pinned bottom bar.

### Don't:
- **Don't** box rows, sections, history entries or tables into rounded bordered cards, or use pill-filled tabs; that is the stock scoreboard this world replaces.
- **Don't** highlight the leader with a fill, a border, a badge or a shadow; the ring is the only leader mark.
- **Don't** use the tile colours for status, emphasis or anything other than identifying a player.
- **Don't** add shadows to anything on the pad, or use a shadow to show selection; only sheets lift, and selected options are outlined in teal.
- **Don't** set Archivo at full width or use proportional figures for scores.
- **Don't** fill tile boxes solid or give them the old raised tile edge; they are outlined in pencil.
