# xletterate-game
xletterate-game
# XLetterate Game Tracker

Static site for tracking wins in XLetterate game via GitHub Pages.

## Live Pages
- [Landing/Leaderboard](https://xLetterate.github.io/xletterate-game/)
- [User Wins Example](https://xLetterate.github.io/xletterate-game/wins/xuser1)

## Data Management
- All wins in `data/plays.json` (array of objects: {user_handle, play_date, guesses, time_sec}).
- To add: Use local script `append-win.js` or edit manually → commit/push.
- Script: Run `node append-win.js --handle xuser1 --date 2026-02-24 --guesses 3 --time 182`.

## Development
- Client-side JS handles filtering/sorting.
- Test locally: Clone repo, open HTML files in browser.

## TODO
- [ ] Add more features (e.g., all-time leaderboard).
