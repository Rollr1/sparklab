# SparkLab

A clickable prototype of a "Duolingo for AI" for kids aged 10 to 15. Short lessons, XP and streaks, a course map, and a parent progress view. Unit 1, **Make it real: AI + 3D printing**, is fully playable. Name, colors and mascot are placeholders.

See [CURRICULUM.md](CURRICULUM.md) for what kids learn and why parents would pay for it.

## What's in the demo

- **Course map** with 6 playable lessons and 7 "coming soon" units
- **Lesson types:** quizzes, a step-ordering game, prompt writing with a coach, a 3D design studio (type changes in words, watch the model update), a slicer with trade-off meters, and an animated layer-by-layer print of the kid's own design
- **Parent view:** streak, minutes this week, skills practiced, the kid's best prompt and 3D design, dinner-table questions. "Load sample progress" fills it for a demo.
- **Live AI coach (optional):** prompt feedback from Claude. Without it, an offline coach scores prompts, so the app always works.

## Running it

It's one static page with no build tools. Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works).

`app.html` is the source. Run `./build.sh` after editing it to regenerate `index.html`.

### Live AI

- Inside a Claude Artifact preview, live AI works automatically with no key.
- On any other host, open Settings (gear icon) and paste an Anthropic API key. It's stored only in that browser. Use a key with a low spending limit, since anyone with the page open could use it. A real launch should route AI calls through a small backend instead.

## Tech

Vanilla HTML, CSS and JavaScript. three.js (r128, from cdnjs) renders the 3D models. Progress is saved in the browser's localStorage. No login, no payments.
