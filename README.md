# Sound Star Counter

A tap counter for speech-sound practice. The clinician taps **Correct!** each time the client produces the target sound correctly. Each tap fills a reward on the board, and the client gets a celebration when they reach the goal (25 by default).

**Live app:** https://heidenreich.github.io/sound-star-counter/

## Features

- **One screen, no scrolling** on iPhone and iPad, in portrait or landscape. The child's reward board sits above or beside the clinician's controls.
- **Reward board:** one reward per correct production, in rows of five, sized to fill the space available.
- **Reward themes:** Stars, Ocean (fish), Garden (flowers), Space (rockets) and Paws (paw prints). Each has its own shapes and colors, in light and dark mode. Switching themes mid-set keeps the count.
- **Rewards:**
  - On every tap, a chime and a little confetti.
  - Every 5, a big icon pops up over the board and the row wiggles.
  - At the goal, the whole board does a wave and confetti falls. The celebration never blocks the buttons, so you can keep counting past the goal.
- **Clinician data, kept away from the child's view:**
  - Attempts, accuracy % and a dot for every trial (filled = correct, hollow = not yet).
  - **Not yet** logs an attempt with no sound and no visible penalty.
  - **Undo** shows what it removed.
  - **New set** needs two taps.
- **Settings** (gear button): target sound, goal (10–50), reward theme, chime volume (Off / Low / Normal) and **Calm mode**. Calm mode is for kids sensitive to sound or motion: one soft chime, gentle fades, no confetti or fanfare. It turns on automatically when the device's Reduce Motion setting is on.
- **Accidental double-taps** (under 0.25 s apart) are ignored.
- **The screen stays awake** during a session where the browser allows it.

## Keyboard shortcuts

Works with a Bluetooth keyboard or a switch/clicker that sends keys.

| Key | Action |
| --- | --- |
| Space / Enter | Correct |
| N | Not yet (incorrect attempt) |
| Z | Undo |

Holding a key down counts once. When another button has keyboard focus, Space and Enter press that button instead.

## Running it

It's a single `index.html` with no build step and no dependencies (fonts load from Google Fonts). Open the file in any browser, or use the GitHub Pages link above.

On an iPad, open the link in Safari and use **Share → Add to Home Screen** to open it like an app.

## Privacy

No data leaves the device. The current set is stored only in that browser's local storage, and the app has no fields for names or other personal details.
