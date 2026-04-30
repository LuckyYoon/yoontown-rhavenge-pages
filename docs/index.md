# YOONTOWN RHAVENGE

> **WARNING:** This game contains flashing lights which may not be suitable for photosensitive epilepsy.

**[Play Now (Installation)](#installation)** · **[Download](#download)** · **[GitHub](https://github.com/olincollege/yoontown-rhavenge)**

## About the Game

Yoontown Rhavenge is a top-down **bullet hell** boss-rush game inspired by the manic shooter genre. You play as **Gilbert**, an unlikely hero armed with nothing but a slingshot, who must face the fearsome **Rhavenger of Yoontown** — a multi-phase boss that grows more ruthless with every hit it takes.

The core goal is pure survival: dodge an escalating storm of projectiles, find openings to fire back, and outlast the boss through both of its distinct phases. Every sprite, soundtrack, and attack pattern was crafted from scratch for this game.

Built in **Python 3.14** using the [pygame-ce](https://github.com/pygame-community/pygame-ce) community library.

---

## Screenshots

### Phase 1

![The Rhavenger of Yoontown in Phase 1](https://github.com/olincollege/yoontown-rhavenge/raw/main/images/phase-1.png)

The Rhavenger opens the fight with its initial set of attack patterns. Learn the rhythm — and stay alive.

### Phase 2

![The Rhavenger of Yoontown in Phase 2](https://github.com/olincollege/yoontown-rhavenge/raw/main/images/phase-2.png)

Deal enough damage and the Rhavenger transforms, unlocking faster, denser projectile patterns that demand even sharper reflexes.

---

## Controls

| Input | Action |
|---|---|
| `W` `A` `S` `D` | Move Gilbert in 2D space |
| `Space` | Fire Gilbert's slingshot |

> The game involves certain audio cues which may effect the gameplay experience. The use of audio devices such as headphones is recommended..

---

## Unique Features

- **Two-Phase Boss Fight** - At a health threshold the Rhavenger transforms entirely, introducing new attack patterns and escalating difficulty.
- **Original Soundtrack** - Music for the game was composed from scratch specifically for this game.
- **Hand-Crafted Sprites** - Every sprite and animation was created exclusively for Yoontown Rhavenge all original pixel art.
- **Bullet Hell Patterns** - Inspired by the manic shooter genre, the boss fires complex, patterned projectile arrangements that reward reading and memorization.
- **Simple Controls** - WASD and Spacebar. Zero barrier to entry; the challenge comes entirely from the game.
- **Clean Architecture** - Code is split across focused modules: `ytr_classes.py` for game objects, `ytr_config.py` for tunable constants, and a full unit-test suite in `ytr_unittests.py`.

---

## Installation

Running **Python 3.14** is recommended. The game should work on earlier Python 3 versions, but switch to 3.14 if you run into any issues.

**Step 1 — Install Python 3.14**

Download from the official Python site:
[https://www.python.org/downloads/release/python-3144/](https://www.python.org/downloads/release/python-3144/)

**Step 2 — Clone the repository**

```bash
git clone https://github.com/olincollege/yoontown-rhavenge
```

**Step 3 — Install pygame-ce**

```bash
pip install pygame-ce
```

On Windows you may need to use:

```bash
py -m pip install pygame-ce
```

**Step 4 — Run the game**

```bash
cd yoontown-rhavenge
python yoontown_rhavenge.py
```

For full details, see the [README on GitHub](https://github.com/olincollege/yoontown-rhavenge/blob/main/README.md).

---

## Download

| Option | Link |
|---|---|
| Download ZIP | [yoontown-rhavenge.zip](https://github.com/olincollege/yoontown-rhavenge/archive/refs/heads/main.zip) |
| Clone via Git | `git clone https://github.com/olincollege/yoontown-rhavenge` |
| Browse source | [github.com/olincollege/yoontown-rhavenge](https://github.com/olincollege/yoontown-rhavenge) |
| Full README | [README.md](https://github.com/olincollege/yoontown-rhavenge/blob/main/README.md) |

---

## The Team

Yoontown Rhavenge was created as a software design project at [Olin College of Engineering](https://www.olin.edu), a small, hands-on engineering school in Needham, Massachusetts.

Contributors can be found on the [GitHub contributors page](https://github.com/olincollege/yoontown-rhavenge/graphs/contributors). All sprites, audio, and code were built from scratch by the project team.

---

## Attribution

All game content — sprites, audio, and levels — was created from scratch. The following open-source tools and resources made the project possible:

- **[Python 3.14](https://www.python.org)** — The programming language Yoontown Rhavenge is written in.
- **[pygame-ce (Community Edition)](https://github.com/pygame-community/pygame-ce)** — The multimedia library handling graphics, input, and audio.
- **[Bullet Hell genre](https://en.wikipedia.org/wiki/Bullet_hell)** — The manic shooter subgenre that inspired the game's design and attack patterns.
- **[Olin College of Engineering](https://www.olin.edu)** — Developed as part of the Software Design course curriculum.

---

*Made at Olin College of Engineering*