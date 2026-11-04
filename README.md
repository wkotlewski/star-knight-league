# Star Knight League

A space-sports learning game for a 3rd grader. Build your ship, pick your crew, and win the Station Cup against the Eclipse Commander's Armor Troopers by solving math problems along the way.

Plays in any browser on a phone, tablet, or computer. No install, no login. Progress saves on each device.

## Play

Play it at **https://wkotlewski.github.io/star-knight-league/**

To host your own copy, turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). It will be at:

`https://wkotlewski.github.io/<repo-name>/`

On a phone or tablet, use **Add to Home Screen** so it opens like an app. After the first load it also works offline.

## Chapters

Pick a chapter from the title screen. **Play** continues the last chapter she played.

### Chapter 1: The Station Cup (Asteroid Baseball · math)

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

### Chapter 2: Meteor Storm (Hover-Soccer · spelling)

- **The Hover Cup**: the same five teams, on an ice-moon soccer field. A meteor storm knocked out the station's shields, and every win earns a shield crystal.
- **Each match is three turns each way**:
  - **Attack**: tap Left, Middle, or Right to dodge defenders. A red arrow warns when a defender is about to move. At the top, tap **Shoot** when the aim arrow points at a corner.
  - **Then she chooses Goalie or Defender** for the other team's three turns.
    - **Goalie**: watch which way the kicker leans, then dive Left, Middle, or Right.
    - **Defender**: stay in front of the striker to tackle the ball.
  - A tie goes to a penalty shootout.
- **A spelling word pops up at least once each half**, plus extras depending on the grown-ups setting:
  - **Defender closing in!** gives hover boots that jump the next tackle.
  - **Meteor Kick** makes the goalie much slower.
  - **Super Save** shows where their shot is going.
  - **Slide tackle** makes her tackle reach wider.
- **Spelling words** come from the weekly list in the Grown-ups corner when there is one, otherwise from a built-in bank of about 90 grade-3 words. The bank covers vowel teams, r-controlled vowels, silent letters, -ed/-ing, plurals, compound words, prefixes and suffixes, and homophones. Each word comes with a sentence. **Hear it** reads the word aloud, and **Peek** flashes it for two seconds. She taps letter tiles (with a few decoys) or picks the right spelling from four choices. Missed words come back later.

### Chapter 3: The Lost Signal (Zero-G Basketball · vocabulary)

- **The Hoops League**: the same five teams on a floating court with a drifting hoop. The station's radio dish lost its signal, and every win earns a decoder chip.
- **Each match is three turns each way**:
  - **Shoot**: tap **3 pts**, **2 pts**, or **Close** to move between three spots while a defender shifts to guard her (a red arrow warns before it moves). Shoot from an open spot for a big green zone; a guarded shot gets a smaller one. A shot clock keeps it moving. Then tap **Shoot** again when the marker is in the green.
  - **Then she chooses Block or Steal** for the other team's three turns.
    - Their player moves between the same three spots. She taps **Left**, **Middle**, or **Right** to stay in front of them. If she's out of position, they get an open shot.
    - **Block**: tap Block right when the ball leaves their hands. Tougher teams use pump fakes.
    - **Steal**: tap Steal when the dribble hits the glowing ring on the floor.
  - A tie goes to overtime.
- **A word question pops up at least once each half**, plus surprises:
  - **Laser Shot** makes the green zone bigger.
  - **Double-team!** passes to an open teammate for a layup.
  - **Super Block** and **Quick Hands** give her more time.
  - **Loose ball!** grabs the ball right away.
- **About 90 questions** aligned to California grade 3 language standards (L.3.1, L.3.4, L.3.5): word meanings, context clues, synonyms, antonyms, prefixes and suffixes (re-, un-, pre-, mis-, dis-, -less, -ful, -er, -ly), homophones (their/there/they're, to/two/too and more), parts of speech, irregular past-tense verbs, and comparing with -er/-est. Wrong answers explain the rule, missed questions come back later, and weaker skills come up more often.

### Unlocking

- **Teams** unlock by winning: beat a team to open the next one. Locked teams say which team to beat.
- **Hangar items** (paint colors, droid heads) cost credits (★). Each locked item shows how many more ★ she needs.

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
- see spelling and vocabulary accuracy and recently missed words
- paste this week's spelling list (used by Hover-Soccer in Chapter 2)
- reset one game (teams, story, and learning history for Baseball, Soccer, or Basketball; keeps her Star Knight, ship, and credits)
- reset everything

## Coming next

| Chapter | Sport / mission | Learning |
| --- | --- | --- |
| 4. Eclipse Ambush | Ship battle | mixed review |
| 5. The Missing Droid | Rescue mission | reading comprehension |

## Files

- `index.html`: the whole game (HTML, CSS, JavaScript; no build step)
- `sw.js`: offline cache
- `manifest.webmanifest`, `icon.svg`: home-screen app support

All characters, ships, and names are original designs.
