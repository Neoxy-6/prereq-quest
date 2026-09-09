# <github-username>

<!-- Public fork: use only your GitHub username. Do not add a student ID,
Discord name, legal name, email address, or other private identifier. -->

## Environment

OS: ubuntu

Editor / IDE: vscode

Shell: bash

Languages I have used: Chinese and English

## Things I have done before

- [x] SSH into another machine
- [x] Resolve a Git merge conflict
- [x] Build a Docker image
- [x] Read a stack trace
- [x] Compile software from source
- [x] Use a debugger
- [x] Use Linux as a primary development environment
- [ ] `sudo rm -rf /` a server ???!
- [x] Deploy code to an embedded controller and debug it on real hardware
- [x] Tune a control loop (PID) against a physical system
- [x] Build and deploy a web backend
- [x] Train a small neural network

## Something I built

- A complete FRC robot system, includes: driver station dashboard, networking, power distribution, structural build, vision system, path planing and motor controls
- A minimal neural network from scratch (not pretty well, but it ran
- Some websites, frontend and backend
- A few small apps that turned out useless

## Something I want to understand better

- More powerful robotics technology
- The theory behind neural networks and LLMs
- Ability of finding resouce, tachnology and more useful tools (I lose a lot of time here

## Mission 01 — Linux

### Task A — find the file

Path: missions/01-linux/files/.config/nested/.deep/.treasure

Command I used: grep -rlw "THE_PENGUIN_WAS_HERE" missions/01-linux/files 

### Task B — count the errors

Count: 8

Command I used: grep -c "ERROR" missions/01-linux/server.log

## Mission 03 — SSH

SSH token: FLAG{fe322c8dc745}

Command I used: ssh -i ~/.ssh/prereq-quest-key flag@217.142.229.247

Have you used SSH before? Briefly describe a time you did (or say you haven't): 2 years ago

## Mission 04 — Debug

What was wrong: `the-answer` should return "42" instead of "41", `base-value` is wrong

What I changed: changed line 14 in "main,janet", 40 -> 41 

## Mission 05 — Docker

What was wrong: line 33 in "Dockerfile", it put the file at `/app/main.janet`,  but `WORKDIR` is `/quest`

What I changed: "COPY app/main.janet /app/main.janet" to "COPY app/main.janet /quest/main.janet"

## Mission 06 — Improve something

What I changed: Added the "Have you used SSH before? Briefly describe a time you did (or say you haven't):" line to the Mission 03 section of answers/TEMPLATE.md.

Why: missions/03-ssh/README.md asks for that answer, but the templat didn't have the line — so anyone who copy the template might misses it. I did xd.
