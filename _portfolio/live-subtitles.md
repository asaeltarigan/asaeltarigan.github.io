---
title: "Live Subtitles EN to ID"
excerpt: "Real-time English speech to Indonesian subtitles, built so a live lecture stays readable as it is spoken."
collection: portfolio
chips:
  - "FastAPI"
  - "speech recognition"
  - "translation"
  - "low latency"
---

A live captioning tool for English speech translated into Indonesian, built to keep a spoken lecture readable in real time.

- Speech is captured in the browser and transcribed in short chunks, then translated before the sentence is forgotten
- Translation falls back through three engines in order, so a blocked or rate-limited provider degrades instead of failing
- Results are cached, which keeps repeated phrases instant and cuts load on the free tiers
- A microphone check page sits in front of the demo so a bad mic does not look like a bad model

Built for classrooms and events where the audience is Indonesian and the speaker is not. Demo on request: the service runs behind a temporary tunnel that is only open while in use.
