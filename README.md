# Ironclad

A fully offline, locally AI-supervised home security system.

A mini PC runs local AI (Frigate + Home Assistant) that watches PoE cameras and an ESP32 sensor network around the clock, confirms intruders with two independent signals, and responds with a tracking spotlight, sirens, voice warnings and alerts. No cloud account and no internet dependency.

## Highlights

- **Fully offline:** cameras and sensors sit on an isolated network with no route to the internet
- **Layered detection:** PoE cameras with person and face recognition, mmWave radar, PIR and door sensors
- **Non-harmful deterrence:** tracking white spotlight, strobe sirens, voice warnings
- **Escalation levels 0–3** with Home, Night and Away modes
- **Cost-efficient:** core build about 49,000 BDT, reusing an existing mini PC

## Documentation

- [Project plan](docs/PLAN.md): architecture, hardware and costs, deterrence design, escalation logic, offline operation, build phases, risks

## Status

Planning. Next up: Phase 1 (core recording with Frigate and Home Assistant).
