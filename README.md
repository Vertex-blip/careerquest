# CareerQuest

Explore six careers by making a few realistic decisions from the work itself. CareerQuest gives visitors a short mission, immediate reasoning for each choice, and a place to reflect on what felt interesting.

## Run

Open `index.html` in any modern browser. The app is static and can be published directly from the repository root with GitHub Pages. It needs no build step, server, account, or API key.

## What you can do

- Search and filter six careers across technology, creative work, science, communication, and community planning.
- Complete three decision scenarios per career, with an explanation after each choice.
- Rate personal interest, write a reflection, and compare completed paths in **My journey**.
- Clear all saved progress from **My journey**.

Progress and reflections are saved in browser `localStorage`, so they stay in the current browser profile and do not sync between devices. Missions are introductory exercises, **not career aptitude tests**. They do not represent every task in a profession.

## Project structure

- `index.html` — page structure and dialogs
- `style.css` — responsive visual system
- `app.js` — career data, scenarios, UI behavior, and persistence

There are no runtime dependencies or third-party requests. Typefaces are bundled under `fonts/` with their OFL licenses. User reflections are rendered as text, not HTML.

## License

MIT. See [LICENSE](LICENSE).
