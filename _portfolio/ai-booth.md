---
title: "AI Booth — BINUS SoCS"
excerpt: "Three small AIs running live in the browser — hand tracking, doodle recognition, face filters — built for an open-day booth."
collection: portfolio
chips:
  - "browser-only"
  - "on-device inference"
  - "hand tracking"
  - "face tracking"
---

A showcase built for the School of Computer Science booth: three small AIs that run live in the visitor's browser with nothing uploaded to a server.

- **Palm Dragon** — a tiny dragon that lives on your hand and reacts to ten hand poses: open palm, fist, peace, wave
- **Sketch AI** — draw a doodle and the neural net guesses it live, out loud, as you draw
- **AR Mask** — a face-tracking filter with cat, bunny and crown modes that reacts when you smile

The point is not the demos themselves but the demonstration: the model runs on the visitor's own device, in the browser, with no upload and no login. That is what makes it usable at a public booth where nobody is going to install anything.

The whole thing is static files served from a single port, so it runs on the same VPS as the rest of my systems.
