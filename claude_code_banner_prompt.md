# Task: Add a site-wide "currently booking" status banner

This is a Jekyll site using the Minimal Mistakes theme. Add a slim,
dismissible banner that appears at the top of every page, above or
directly below the main nav, indicating current booking availability.

## Step 0 — Investigate before changing anything

- Find `_layouts/default.html` (or whatever layout all pages inherit
  from) to identify the correct injection point — likely right after
  `<body>` opens, or immediately before/after the existing masthead/nav
  include, so it appears above the fold on every page.
- Check `_config.yml` for how other site-wide text/settings are stored,
  so the banner text can follow the same convention (I want to be able
  to update the month/quarter text later by editing a config value or
  small data file, not by editing HTML directly each time).
- Confirm there's no existing banner/alert include already in the theme
  I should reuse instead of building from scratch.

## Step 1 — Banner content & styling

- Text: "Currently booking for [Month/Quarter]" — pull the actual value
  from a config/data field (e.g. `_config.yml` under a key like
  `booking_status_text`, or a small `_data/booking.yml` file) rather
  than hardcoding it in the HTML, so I can update it myself later
  without touching template files.
- Include a short call-to-action inline in the banner, e.g. "Schedule a
  call →" linking to the existing discovery call scheduler:
  `https://scheduler.zoom.us/jessica-hayden-i79emd/free-discovery-call`
- Styling: full-width, slim bar (not tall — shouldn't push content down
  much). Use an accent color that stands OUT from the site's existing
  navy/white/teal palette rather than blending in — check the existing
  custom CSS (`_includes/head/custom.html`) for the current palette
  variables (navy #1E3A5F-ish, teal #1E88A8-ish, from recent Services/
  Portfolio work) and choose something that contrasts against both,
  e.g. a warm accent (amber/gold) — propose a specific hex and show me
  before finalizing if there's any ambiguity.
- Include a small "X" dismiss button on the right side of the banner.

## Step 2 — Dismiss behavior (localStorage, message-aware)

- On dismiss click, hide the banner and store the dismissal in
  `localStorage`, keyed to the CURRENT banner text/value (not just a
  generic "dismissed: true" flag) — e.g. store the exact booking status
  string that was dismissed.
- On page load, only show the banner if either (a) nothing is stored in
  localStorage yet, or (b) the stored dismissed value no longer matches
  the current banner text. This way, when I update the booking text
  later (new month), the banner automatically reappears for everyone,
  even people who dismissed the old version — it only stays hidden if
  the message hasn't changed since they last dismissed it.
- Banner should NOT reappear on every single page navigation within the
  same visit once dismissed for the current message — persist via
  localStorage (not sessionStorage) so it stays dismissed across visits
  too, until the message itself changes.

## Constraints

- Make the file edits directly in the working directory — do NOT run
  `git add`, `git commit`, or `git push`. I'll review and commit myself.
- Don't modify any existing page content, only add the new banner
  include/partial and its injection point in the layout.
- Keep the JS vanilla (no new dependencies/libraries) — this is a
  static Jekyll site, keep it lightweight.
- When done, tell me exactly which config/data file and key to edit
  when I want to update the booking month/quarter text in the future,
  and give me a summary of every file changed.
