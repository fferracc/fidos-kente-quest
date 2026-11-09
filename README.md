# Fido's Kente Quest

A browser coding game that teaches children sequencing and debugging. Players build a list of commands to guide Fido across a grid, avoid obstacles and reach the kente cloth.

**Live:** https://fidos-quest-game.web.app

<!-- ![Fido's Kente Quest](docs/screenshot.png) -->

## Design goal
Introduce the core ideas of computational thinking (sequences, directions, testing and fixing) through one visual goal, with almost no reading and nothing to install.

## What it does
- Grid world rendered on an HTML canvas, with Fido, obstacles and a goal
- Players queue movement commands, review them and remove any step before running
- The sequence runs step by step so children can see exactly where a plan goes wrong
- Four levels of increasing difficulty, then the game loops back to level 1
- Works on tablets and phones (touch friendly buttons)

## My role
Designed the learning progression and built the whole game: game logic, rendering, levels and deployment.

## Stack
HTML5 Canvas, vanilla JavaScript, Tailwind CSS (CDN), Firebase Hosting

## Run locally
Open `index.html` in any modern browser. No build step.

## Learning design
| Concept | Where it appears |
|---|---|
| Sequencing | Commands run in the order they are added |
| Debugging | Players remove a wrong step and run again |
| Decomposition | Longer levels reward planning the route in parts |

## Status
Live prototype. Built as an independent project by Franco Ferrari-Accardi and donated to Sovereign House GH for its children's programmes.
