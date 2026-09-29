# Guy Dance

Resist the scroll. Earn a guy. Get everyone dancing.

Every time you close Instagram (or any distracting app) instead of scrolling, a new 16-bit guy joins the dance floor. Give in and one goes home. The goal is to get as many guys dancing as possible by the end of the week.

## Status

Prototype v0.2: a web app you can add to your phone's home screen.

- Close Instagram (or tap **I closed Instagram**) and a guy joins the queue backstage
- The next day, everyone you earned walks on stage for the party
- Tap **I gave in** to send one home
- **New week** clears the floor

Progress is saved on your device only.

## Put it on your phone

1. Open the live site in Safari, tap Share, then **Add to Home Screen**.
2. For automatic rewards on iPhone, open Shortcuts → Automation → + → App → Instagram → **Is Closed** → Run Immediately. Then add the action **Open URLs** with `https://kenzo8it.github.io/guy-dance/?closed=1`.

## Ideas for next versions

- Real app-blocking hooks on iOS and Android (Screen Time API and Digital Wellbeing)
- A warning when a distracting app opens, or 15 minutes after (your choice)
- More dance moves, outfits and sounds
- A weekly recap you can print
