# Prince of Persia: Shadow Self

> *"The dungeon doesn't reset. It remembers."*

A browser-based platformer where every death leaves a ghost behind. The corridors fill with shadows of your failed attempts — each one walking the exact path where you went wrong.

Built with vanilla JavaScript and HTML5 Canvas. No frameworks, no build step. Open the file and play.

## The Story

Jaffar has imprisoned the Princess. She has minutes to live.

You are the Prince. Fight through the dungeon, defeat the guards, escape before time runs out.

But every time you fail, you leave something behind.

## The Shadow Self Mechanic

Every death records your exact movement path. On your next life, that recording replays as a translucent blue ghost — your Shadow Self — walking the same route you did.

Die three times, and three shadows haunt the corridors. All walking the paths where you failed. All reminding you of every mistake.

Your failures become the atmosphere. Don't become a shadow.

## How To Play

| Key | Action |
|---|---|
| `←` `→` | Move left and right |
| `↑` | Jump |
| `Z` | Slash sword |
| `↓` (near lever) | Pull lever to open gate |
| `Esc` | Return to title screen |

## Objective

- Find the lever — pull it to open the gate
- Fight or avoid the guards
- Reach the gate before the timer runs out
- Escape both levels to save the Princess

## Levels

### Level 1 — The Dungeon (1:30)
- One patrolling guard with reactive chase AI
- One spike pit to cross
- Three floating platforms
- Find the lever, open the gate, escape

### Level 2 — The Palace (2:00)
- Two guards, faster and more aggressive
- Two spike pits with deeper drops
- A climbing staircase of narrow platforms
- Two moving platforms that test your timing
- Every second counts — escape to save the Princess

## Features

- **Shadow recording** — your deaths replay as transparent ghosts on subsequent runs
- **Reactive guard AI** — guards detect you within range and chase, returning to patrol when you escape
- **Moving platforms** — timing-based traversal in Level 2
- **Screen shake, blood particles, squash-and-stretch** animation for game feel
- **Dynamic torch lighting** with flickering radial gradients
- **Procedural sound effects** via the Web Audio API (no sound files needed)
- **Cinematic intro, death, and victory screens** with ornate gold typography

## How To Run

1. Clone or download this repository
2. Make sure `music.mp3` is in the project folder
3. Open `index.html` in any modern browser
4. Press `Enter` to begin

That's it. No npm install, no build step, no server required.

## Built With

- HTML5 Canvas
- Vanilla JavaScript — no libraries
- Web Audio API — sound effects
- Google Fonts (Cinzel, Cinzel Decorative) — typography
- [Kilo Code](https://kilocode.ai/) — AI-assisted development
- Claude AI — game design and architecture

## File Structure

```
.
├── index.html       # The entire game (HTML, CSS, JS in one file)
├── music.mp3        # Background music
└── README.md
```

## License

Free to fork, modify, and use. A credit back is appreciated but not required.

---

*"Your shadow stays behind when you die."*
*"How many ghosts will you leave?"*
