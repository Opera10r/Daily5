# Daily5

**A link queue with a hard limit of 5. Save less, read more.**

Daily5 is a minimalist reading queue that physically cannot grow beyond 5 items. If you want to add a 6th link, you have to finish and clear one first. No account, no sync, no excuses.

## The Problem

Pocket has 47,000 saved articles. The browser has 83 open tabs. The "read later" folder hasn't been opened since 2019. The problem isn't finding interesting content -- it's that you save everything and consume nothing. Daily5 fixes this with a hard cap of 5.

## How It Works

1. Paste a link, click ADD
2. Links appear as numbered slots (max 5)
3. Click a link to read it
4. Click DONE / CLEAR when finished
5. Queue full? Clear one to unlock a new slot

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Add link (when input focused) |
| `1`-`5` | Open link in slot N |
| `Shift+1`-`5` | Clear link in slot N |
| `Escape` | Clear input field |

## Features

- Hard 5-slot limit (the whole point)
- FIFO ordering -- first in, first to read
- Duplicate detection
- Auto-adds `https://` if you forget
- Time tracking ("added 2h ago")
- Stored in localStorage -- survives refresh, no server needed

## Privacy

100% client-side. No data leaves your browser. No cookies, no analytics, no accounts.

## License

MIT License - Raven's Gate Publishers LLC
