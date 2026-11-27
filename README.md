# Bounce Back

A vertical bounce-climber made by Oneth Welikanna for Hack Club Harvest. Theme: **Bounce Back**.

Fall off the screen and a trampoline net throws you back up, with double points for your next 8 bounces. Every fall costs a heart, and the run ends when you run out. Climb through blue sky, golden hour and dusk into space.

## Play

Open `index.html` in any modern browser, or play it on itch.io (https://wdorw.itch.io/bounce-back).

## Controls

- Desktop: Left/Right arrows or A/D to steer. P or Esc pauses, M mutes.
- Phone: hold the left or right side of the screen.

## Platforms

- White: normal bounce
- Yellow spring: big bounce, 15 points
- Teal: moves side to side
- Tan: crumbles after you land
- Orange spikes: cost a heart

You earn an extra heart every 1000 points (up to 5).

## Tech

One self-contained HTML file, plain JavaScript and canvas, no build step and no dependencies. Sound is generated with the Web Audio API. The only external request is Google Fonts, and the game falls back to system fonts if it can't load.

## Run locally

```
python3 -m http.server
```

Then open http://localhost:8000.

## License

MIT, see LICENSE.
