# AmongGhosts: A VR Deception Game

A VR social-deduction game built for a university game development project. This repository presents the project — the concept, the team's roles, and the demo — and points to the actual codebase, which lives in a teammate's repository (see below).

## Concept

20 NPCs are spawned into the environment; 5 of them are secretly "imposters." The player has to figure out which is which using two tools:

- **Voice commands** — speak an instruction ("Stop", "Jump", "Repeat After Me") and see how each NPC responds. Speech is captured via Unity's microphone API, converted to text, and matched against the expected commands to judge whether a response is "real."
- **Flare gun** — once you're confident, take the shot. Hits are tracked and scored.

The core design question the team explored: what makes voice interaction in VR actually feel immersive, rather than gimmicky — balanced against the practical challenge of speech-recognition latency.

## Team

Built as a team project — pictured below.

![Team photo](./team_photo.jpg)

## Roles

Coding was done collaboratively; the full codebase lives in a teammate's repository (below), since development happened on a shared machine.

## Code

The full Unity project is hosted here: **[Ezzivdb/AMONGOES](https://github.com/Ezzivdb/AMONGOES)**

## Demo & Presentation

- 🎥 [Demo video](https://drive.google.com/file/d/1s2P5f-DsRy1E7MvSli8pO_F77itRZQeE/view) *(hosted externally — link current as of this writing)*
- 📊 [Presentation slides](./Presentation.pdf)

