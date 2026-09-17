# Poker Tracker

Live site: https://hellomate2.github.io/poker-tracker/

- `Poker Tracker.xlsx` is the source of truth. Edit it, then run `python3 sync.py` and commit.
- `data/sessions.js` is generated from the spreadsheet and feeds the site.
- `index.html` renders the summary, running-total chart, and session log. No build step.
