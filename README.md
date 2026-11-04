# Von Neumann Architecture Simulator

An interactive simulator for teaching the Von Neumann architecture. Students step through the fetch, decode and execute cycle and watch the registers, the ALU and the memory change at each stage.

Live demo: https://injamam00155.github.io/von-neumann-simulator/

## What it shows

- The CPU registers PC, MAR, MDR, CIR and ACC, the ALU, and RAM
- The fetch, decode and execute stages, with a step button and an auto mode
- A small instruction set that includes LDA, STA, ADD, SUB and HLT

## Run it locally

It is a single static page with no build step. Clone the repository and open `index.html` in a browser.

## Deployment

The site is published with GitHub Pages. The workflow in `.github/workflows` builds and deploys it.

## Why I built it

I teach Cambridge IGCSE and A Level Computer Science, and this topic is easier to follow when students can see each register change.
