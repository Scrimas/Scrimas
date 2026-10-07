# Ismaël PHILIPPE — Scrimas

I'm a first-year MCB master's student in Grenoble; next year I'm moving on to the Pro2Bio M2, with a neuroscience focus.
Getting there wasn't part of any plan — I took a neurobiology course almost as a formality, had a
professor who was genuinely excited about the subject and transmitting knowledge, and that excitement turned out to be
contagious enough to change my whole trajectory.

Outside of coursework I build things: some bioinformatics-adjacent, some desktop apps, some reverse
engineering. It usually starts with something that bugs me, like a feature moved behind a paywall
or a file format nobody documented, and ends with a tool that fixes it for everyone. When I'm not
doing that, I'm usually playing electric guitar, which is also the reason
[TabEngine](https://github.com/Scrimas/TabEngine) exists.

Longer term, I'm aiming for a research engineer role in neuroscience, most likely somewhere in the
neural regeneration / 3D imaging space (tissue clearing, light-sheet microscopy). Still a few years
out, but that's the direction I'm rowing in.

Reach out:
[![Email](https://img.shields.io/badge/Email-6D4AFF?style=flat&logo=protonmail&logoColor=white)](mailto:isma.ph@proton.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ismael-philippe/)

---

## Featured

**[MHGU Save Editor](https://github.com/Scrimas/MHGU-Save-editor)**
The most polished thing I've shipped so far. A desktop save editor for Monster Hunter Generations
Ultimate (Switch, emulator saves), written in Rust + Slint, on top of a save format I
reverse-engineered and documented myself. Every value is read where the game keeps it, every edit is
described in game terms before anything touches the file, and every edit has been verified in game.
Nothing is written until you review it, and a snapshot is taken before every write. Single-file
builds for Linux (AppImage) and Windows, in the game's five languages.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Scrimas/MHGU-Save-editor/main/docs/screenshots/01-overview-dark.png">
    <img src="https://raw.githubusercontent.com/Scrimas/MHGU-Save-editor/main/docs/screenshots/01-overview-light.png" alt="MHGU Save Editor overview" width="80%">
  </picture>
</p>

**[TabEngine](https://github.com/Scrimas/TabEngine)**
A close second. A free, open-source desktop guitar tab player for Guitar Pro files (GP3/4/5/GPX) —
no account, no ads, no premium wall. I built it because Songsterr kept moving free features behind
a paywall. It's licensed GPLv3 specifically so it can't be forked and resold: free now, free forever.

<p align="center">
  <img src="https://raw.githubusercontent.com/Scrimas/TabEngine/master/.github/screenshot-light.png" alt="TabEngine screenshot" width="48%">
  <img src="https://raw.githubusercontent.com/Scrimas/TabEngine/master/.github/screenshot-dark.png" alt="TabEngine screenshot" width="48%">
</p>

---

## Projects

**[SeqProfiler](https://github.com/Scrimas/SeqProfiler)**  
Multi-FASTA bioinformatics pipeline in Python. ORF detection on both strands, transcription,
translation, and biochemical properties (T_m, pI, extinction coefficients, molecular mass) —
no BioPython. Built from scratch because I wanted to understand the math, not just call a function.
Still tinkering with it — less about adding features at this point, more about using it as a reason
to go deeper on both the biology and the code.

**[GeneticDriftSim](https://github.com/Scrimas/GeneticDriftSim)**  
Wright-Fisher population genetics simulator. Tracks allele frequency drift, mutation, and fixation
across generations in finite populations.

**[MacOS-Like](https://github.com/Scrimas/MacOS-Like)**  
Icon themes for KDE Plasma and GTK built on top of MacTahoe. Every installed app MacTahoe has no
artwork for gets its icon placed on a matching Tahoe-style tile, and the dark variant gets real
dark glass tiles instead of reusing the light theme's white ones.

---

## Donate

Everything here is free and will stay that way. If any of it has been useful
to you and you feel like donating:

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=flat&logo=paypal&logoColor=white)](https://paypal.me/Scrimas)
