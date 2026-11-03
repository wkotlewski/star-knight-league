# Star Knight League

A space-sports learning game for a 3rd grader. Build your ship, pick your crew, and win the Station Cup against the Eclipse Commander's Armor Troopers by solving math problems along the way.

Plays in any browser on a phone, tablet, or computer. No install, no login. Progress saves on each device.

## Play

Play it at **https://wkotlewski.github.io/star-knight-league/**

To host your own copy, turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). It will be at:

`https://wkotlewski.github.io/<repo-name>/`

On a phone or tablet, use **Add to Home Screen** so it opens like an app. After the first load it also works offline.

## What's in Chapter 1: The Station Cup

- **Create your Star Knight**: six diverse looks, your own name, and a blade color.
- **Hangar**: pick a ship frame (Swift Scout, Heavy Hauler, Star Cruiser), a cargo bay (Rescue Pod, Science Lab, Repair Drones, Sports Gear), paint, a droid buddy, and two crew members. Paint colors and droid heads unlock with credits.
- **The Station Cup**: a ladder of five teams (Armor Troopers, Moon Miners, Comet Crew, Nebula Nine, and the Eclipse Elite). Beat a team to unlock the next one.
- **Each match is one round each way**:
  - **Bat**: tap **Swing** when the ball reaches the glowing ring. When she's on base, she may get a chance to steal.
  - **Then she chooses Pitch or Catch** for the other team's turn.
    - **Pitch**: pick a Fastball, Curveball, or Changeup, then tap **Throw** when the marker is in the green.
    - **Catch**: move the glove Left, Middle, or Right to where the ball is going. Throw out runners who try to steal.
  - A tie plays one more round.
- **Math pops up at least once each turn** (batting, pitching, or catching), plus a few extra times depending on the grown-ups setting:
  - **Power Pitch** charges the blade bat.
  - **Steal the base** gets her runner in safe.
  - **Star Pitch** or **Call the pitch** throws a pitch that's very hard to hit.
  - **Steal alert** throws out a runner.

## Learning

Problems follow the California Common Core standards for grade 3:

| Skill | Examples |
| --- | --- |
| Multiplication & division | facts within 100, with a dot-array "Show me" hint |
| Add & subtract to 1,000 | 2- and 3-digit, with regrouping |
| Rounding | nearest 10 and nearest 100 |
| Fractions | name the shaded part of a bar |
| Area & perimeter | square-unit grids and labeled rectangles |
| Time | elapsed time to the nearest 5 minutes, with a clock |
| Two-step word problems | multiply, then add or subtract |

The game adapts: skills she misses show up more often, and missed problems come back later as practice. Wrong answers show the correct answer and a one-line explanation.

## Grown-ups corner

Press and hold the **Grown-ups** button on the title screen for 1.5 seconds to open it. It shows accuracy by skill and recently missed problems, and lets you:

- set the level (Easier, 3rd grade, Challenge)
- set how often math pops up (once per turn, once plus a few, or lots)
- turn skills on or off
- paste this week's spelling and vocabulary list (used by Hover-Soccer in Chapter 2)
- reset progress

## Coming next

| Chapter | Sport / mission | Learning |
| --- | --- | --- |
| 2. Meteor Storm | Hover-Soccer | spelling (from the weekly list) |
| 3. The Lost Signal | Zero-G Basketball | vocabulary and language arts |
| 4. Eclipse Ambush | Ship battle | mixed review |
| 5. The Missing Droid | Rescue mission | reading comprehension |

## Files

- `index.html`: the whole game (HTML, CSS, JavaScript; no build step)
- `sw.js`: offline cache
- `manifest.webmanifest`, `icon.svg`: home-screen app support

All characters, ships, and names are original designs.
