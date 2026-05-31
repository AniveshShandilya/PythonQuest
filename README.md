# Python Quest

**Learn Python by playing.** A single-file, fully offline browser game that turns learning Python into a quest - 1000 levels, 20 worlds, and a short read whenever you get stuck. No installs, no logins, no ads.

**Version:** 2.1

---

## What it is

Python Quest is a browser game for anyone who wants to actually *learn* Python rather than just watch tutorials scroll by. You solve real Python riddles, the game runs your code for real (in the browser), and every correct answer comes with a plain-English explanation of *why* it works. Stuck? The game hands you a short, original read on the concept before nudging you forward.

It runs entirely in a single HTML file. Open it in any modern browser - desktop or mobile - and play.

---

## Features

- **1000 procedurally generated levels** across **20 worlds** and **28 question archetypes**, so the path stays fresh from your first `print()` to object-oriented programming.
- **Real Python, in the browser.** Your code is executed for real using Pyodide - no server, no setup.
- **Learn on success.** Every correct answer explains the logic behind the solution, not just a tick.
- **Help when you are stuck.** After a few tries the game surfaces a short original read on the concept, then offers hints.
- **Three difficulty tiers** - Basic, Intermediate and Advanced - including OOP riddles (classes, objects, inheritance).
- **Fully offline.** After the engine loads once, the game itself needs no internet.
- **Mobile friendly.** Plays in Safari and Chrome on a phone, not just a laptop.
- **No ads, no tracking, no accounts.** Your progress is saved locally in your own browser.

---

## How to play

1. Open the game file in a browser (see **Run it** below).
2. Read the riddle, type your Python into the editor.
3. Run your code - the game checks the result.
4. Get it right and you earn stars and XP, plus an explanation of the logic.
5. Get it wrong a few times and the game offers a short read and hints to get you unblocked.

Your progress is stored locally in the browser (under the key `pyquest_progress_v2`), so you can close the tab and pick up where you left off on the same device.

---

## Run it

### Option A - just open the file
Download `index.html` (the game) and open it in any modern browser. That is it.

> First load needs the internet once, to fetch the Python engine (Pyodide) from its CDN. After that, the game runs offline.

### Option B - host it on GitHub Pages (shareable link)
1. Create a new **public** repository on GitHub.
2. Upload the game file and rename it to **`index.html`**.
3. Go to **Settings → Pages**, set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)**, and **Save**.
4. After about a minute you get a live link: `https://YOUR-USERNAME.github.io/YOUR-REPO/`
5. Open that link in Safari or Chrome on any device, including a phone.

### Option C - Netlify Drop (fastest)
Go to **app.netlify.com/drop**, drag the HTML file in, and you get a shareable URL in seconds - no repo needed.

---

## How it works

- **Single file.** Everything - layout, styling, game logic and content generation - lives in one HTML file. Nothing to build or compile.
- **Pyodide** runs CPython in the browser via WebAssembly, so the code you write is genuinely executed.
- **Procedural generation.** A seeded generator combines 28 question archetypes across the worlds to produce 1000 levels, with a boss challenge at regular intervals.
- **Local storage.** Stars, XP and progress are saved in your browser only - nothing leaves your device.

---

## Browser support

- **Desktop:** latest Chrome, Edge, Firefox and Safari.
- **Mobile:** Safari and Chrome on iOS and Android.

> On iPhone, a *local* `.html` file will not open straight into Safari (an iOS limitation). Host it (Option B or C) and open the link, or use a local-HTML viewer app such as Documents by Readdle.

---

## Privacy

- No accounts, no sign-in.
- No ads, no analytics, no tracking.
- Progress is saved only in your own browser's local storage.

---

## What's new in 2.1

- Added **object-oriented programming** riddles (classes, objects, inheritance) - 28 archetypes in total.
- **Learn on success** - every correct answer now explains the code logic.
- Smarter **attempt counter** so re-running identical code does not unfairly burn a try, with a guided learning gate after repeated misses.
- **Mobile browser compatibility** improvements.
- Anime-style backdrops and visual polish.
- Passed an internal **cybersecurity review** and a full **QA pass across all 1000 levels**.

---

## Credits

Created by **Anivesh Shandilya**, built with AI alongside.

Happy Learning.
