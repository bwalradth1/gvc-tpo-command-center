# GVC TPO Command Center

Internal broker operating system (not the marketing website).

## Open locally
Open `index.html` in a desktop browser, or:
`python3 -m http.server 8765` from this folder, then visit http://127.0.0.1:8765/

## Data
All state persists in browser localStorage (`gvc-tpo-command-center-v1`).
First load seeds 18 Active approved wholesale shops (Optimal Blue Active book). Pending shops are not included. Export/Import/Reset are in the header. A saved book that is not exactly 18 Active shops is replaced by this seed.

## Views
Today, Updates, Door-kick, Shops, Fast Lane, Rooms, Rhythm, Campaigns, Feedback, Scoreboard.

## Door-kick SAMPLE rates
Door-kick emails must never invent GVC live locks: rate/points cells default to Secondary/lock-desk tokens (e.g. `{{CONV30_RATE}}`) and are labeled “Paste from Secondary / lock desk — not Sales Desk Matrix.” Guideline-door bullets may carry longer-lived SAMPLE Matrix cues (loan limits, overlays) but are editable copy only—always lock with Secondary, and treat timestamps + the compliance footer as mandatory before anything leaves the composer.
