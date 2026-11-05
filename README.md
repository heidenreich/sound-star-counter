# Sound Star Counter

A tap counter for speech-sound practice. The clinician taps **Correct!** each time the client produces the target sound correctly. Each tap fills a star, and the client gets a celebration when they reach the goal (25 by default).

## Features

- **Star board:** one star per correct production, in rows of five.
- **Rewards:** a chime and a little confetti on every tap. Every 5 stars, the row wiggles and a praise message appears. At the goal, a full-screen celebration with confetti.
- **Accuracy tracking:** **Not yet** logs an attempt without a star, so you get correct / attempts / % accuracy plus a trial-by-trial dot record.
- **Editable target sound** (e.g. `/r/`, `/s/`, `th`) and goal (10, 15, 20, 25, 30 or 50).
- **Undo** for mis-taps, and **New set** to clear the board (tap twice to confirm).
- **Chime toggle** for quiet rooms.
- **Saves the current set** in the browser, so reloading the page doesn't lose the count.
- Works in light and dark mode, and on phones, tablets and laptops.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| Space / Enter | Correct |
| N | Not yet (incorrect attempt) |
| Z | Undo |

## Running it

It's a single `index.html` with no build step and no dependencies (fonts load from Google Fonts). Open the file in any browser, or host it with GitHub Pages:

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
3. The app will be live at `https://heidenreich.github.io/sound-star-counter/`.

On an iPad, open that URL in Safari and use **Share → Add to Home Screen** to open it like an app.

## Privacy

No data leaves the device. The current set is stored only in that browser's local storage.
