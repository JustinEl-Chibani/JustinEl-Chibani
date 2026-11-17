# 👋 Welcome to My GitHub!

Hi, I'm Justin. This is where I share projects I've built — mainly from school and some personal work.

## 📂 What's Here:

- Projects developed for coursework and labs
- Personal projects
- Forked versions of my work with others (for easier access)

  *Everything here reflects what I've worked on directly.*

## 🌐 Portfolio

You can also check out my portfolio (still a work in progress): [justinelchibani.dev](https://justinelchibani.dev/)

## me:

```mermaid
stateDiagram-v2
    state decide <<choice>>

    [*] --> WakeUp
    WakeUp --> Rot
    Rot --> Shower
    Shower --> decide
    decide --> Studying: exam soon
    decide --> Working: shift today
    decide --> Gym: nothing due (rare drop)

    Studying --> Eating: stomach rumble
    Eating --> Studying: refilled
    Studying --> Working: "I'll finish it later"

    Working --> Debugging: pushed to main
    Debugging --> Debugging: fixed 1 bug, made 2 more
    Debugging --> Working: works on my machine

    Gym --> Gym: "one more set"
    Gym --> Studying: remembered an assignment
    Gym --> Eating: hungry
    Gym --> Sleep: dead

    Studying --> Sleep: unreasonable time
    Working --> Sleep: reasonable time
    Sleep --> [*]
```
