# Nikolai's Game

A tiny touch game for a one-year-old. Tap the cat, the bear or the car — each
one hops and makes a sound.

![The game](docs/tasks/task-002-bolshie-knopki/mockups/01-gorizontalno.png)

## Play

Open `index.html` in any modern browser. No server, no installation, no
internet connection needed.

Online version: **https://zik69.github.io/nikolai-game/**

## What is inside

- **One file.** Everything — pictures, sounds, code — lives in `index.html`.
- **Works offline.** There is not a single link to the internet, so nothing can
  fail to load. A strict Content-Security-Policy stops the page from making any
  network request at all, even by accident.
- **Big targets.** A button is a whole grid cell. On a 320 px phone the
  smallest one is still 243 × 163 px.
- **Two layouts.** Landscape keeps the three characters in a row; portrait
  stacks them, full width.
- **Real sounds, no files.** The meow, the growl and the horn are synthesized
  with the Web Audio API.
- **Safe for small hands.** No scrolling, no pinch zoom, no double-tap zoom,
  no long-press menu, no text to read.
- **Parent lock.** A faint dot in the top-left corner opens after a three-second
  hold: sound on/off, play time (5/10/15/30 minutes), exit with confirmation.
  The panel closes itself after 30 seconds.
- **Gentle time limit.** When the time is up, a calm night screen appears and
  taps stop working. Only an adult can bring the game back.
- **Peekaboo.** Tap a character and it vanishes with a little puff, then pops
  back with a two-note “ku-ku”.
- **Bubbles.** A second game: thirteen slow bubbles float up, pop on touch with
  a soft sound and come back from the bottom. An adult switches games in the
  parent panel.
- **Colour sky.** A third game: touch anywhere and the sky and sun fade through
  five gentle palettes with a quiet chime.
- **Finger drawing.** A fourth game: thick, bright, multi-colour strokes follow
  the finger; only an adult can clear the canvas.
- **Musical animals.** A fifth game: five animals sing notes from a pentatonic
  scale, so any combination sounds pleasant.
- **Clapping.** A sixth game: two big hands clap out a calm “two claps and a
  pause” rhythm, and a tap anywhere adds a clap.
- **Big and small.** A seventh game: drag each bear into the matching house.
  A wrong drop simply sends the bear back — no scores, no “wrong”.
- **No ads, no tracking, no accounts.** Nothing leaves the device.
- **Fullscreen button.** One tap in the parent panel hides the browser UI.
  If the browser refuses, a short card explains the two reliable ways to lock
  the game on an iPad.

## On an iPad

Open the online link in Safari, or save `index.html` to the Files app and open
it from there. Sound starts on the very first tap, which is what iOS requires.

**Fullscreen.** iPadOS 16.4 and later lets a web page go fullscreen from the
parent panel. A small close cross stays in the corner — the site cannot remove
it. For a real child lock use one of these:

- **Add to Home Screen** — Safari → Share → Add to Home Screen. The game opens
  without browser chrome.
- **Guided Access** — Settings → Accessibility → Guided Access. Triple-click
  the side button in the game; the child cannot leave until you enter the code.

## Project documents (in Russian)

- `docs/ROADMAP.md` — the plan, written as user stories.
- `docs/CHANGELOG.md` — what has been done so far.
- `docs/tasks/` — one folder per task, with a plain-language description and a
  ready-to-use prompt for an AI assistant.

## Roadmap in one line

All P0 tasks are done, plus peekaboo, bubbles, the colour-changing sky, finger
drawing, musical animals, clapping and size sorting. Next: a quiet bedtime
screen.
