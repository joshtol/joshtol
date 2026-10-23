<div align="center">
  <img alt="One Thousand Drones · one mind, many machines." src="assets/otd-banner-personal-1200x360.png" width="100%" />
</div>

<h1 align="center">Joshua Tollette</h1>

<p align="center">
  I build autonomous systems and the interfaces that make them usable.
</p>

<p align="center">
  Two projects have most of my attention right now: <b>One Thousand Drones</b>, a defense R&amp;D company building brain-to-swarm control, and <b>Emotive Engine</b>, an open-source animation runtime for expressive AI interfaces.
</p>

---

## One Thousand Drones

My company. A SAM.gov-registered defense research lab building **Brain-to-Swarm**: a non-invasive EEG interface that lets an operator supervise a drone swarm through motor imagery, paired with a safety layer and a training academy.

The public site ships with a live Aplomado HID demo, a technical brief on the three-part system, and a briefing-request flow. Built on Next.js 16, React 19, and TypeScript, deployed on Vercel.

**Site** · [onethousanddrones.com](https://onethousanddrones.com) · **Demo** · [demo.onethousanddrones.com](https://demo.onethousanddrones.com)

<table>
  <tr>
    <td width="50%"><a href="https://onethousanddrones.com"><img alt="The One Thousand Drones home page: ONE MIND. MANY MACHINES., an EEG headset render, and the Aplomado HID section below" src="assets/shot-apex-home-2026-10.webp" width="100%" /></a><br><sub>onethousanddrones.com, captured October 2026.</sub></td>
    <td width="50%"><a href="https://onethousanddrones.com/#aplomado"><img alt="The Aplomado HID section of the company site: three drones over a hex floor, the decoded intent HOLD, and the Aplomado mark beside its description" src="assets/shot-apex-aplomado-2026-10.webp" width="100%" /></a><br><sub>The Aplomado HID section, simulated signal. onethousanddrones.com, captured October 2026.</sub></td>
  </tr>
</table>

## Academy

An open hardware-engineering curriculum. Twenty-two projects from your first ESP32 board to an EEG BCI, each one a board you draw, lay out and check yourself. L1.01 is free.

**Start** · [academy.onethousanddrones.com](https://academy.onethousanddrones.com) · **Library** · [academy.onethousanddrones.com/library](https://academy.onethousanddrones.com/library)

<table>
  <tr>
    <td width="50%"><a href="https://academy.onethousanddrones.com"><img alt="The L1.01 board's Gerber layers separate into a stack and close back into one board" src="assets/loop-gerber-explode.webp" width="100%" /></a><br><sub>The L1.01 board's layers, drawn from its own Gerbers.</sub></td>
    <td width="50%"><a href="https://academy.onethousanddrones.com"><img alt="The L1.01 ESP32-S3 USB-C breakout board turning once" src="assets/loop-board-turntable.webp" width="100%" /></a><br><sub>The L1.01 board, rendered from its released 3D model.</sub></td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%"><a href="https://academy.onethousanddrones.com/projects/l1-01-wroom-breakout/v1/guide"><img alt="The L1.01 WROOM BREAKOUT build guide: the board on a hex stage card, requirements in progress" src="assets/shot-acad-guide-2026-10.webp" width="100%" /></a><br><sub>The L1.01 build guide, captured October 2026.</sub></td>
    <td width="50%"><a href="https://academy.onethousanddrones.com/library"><img alt="The Academy library: REFERENCE GUIDES., a featured guide on controlling a drone with your brain, and the newest guides" src="assets/shot-academy-library-2026-10.webp" width="100%" /></a><br><sub>The free reference library, captured October 2026.</sub></td>
  </tr>
</table>

## Hex Cluster

The printable carrier system our test boards live in. Dovetailed on all six edges, released CC BY 4.0, with a browser configurator that exports only the parts a layout needs.

**Configurator** · [hex.onethousanddrones.com](https://hex.onethousanddrones.com) · **About** · [academy.onethousanddrones.com/hex](https://academy.onethousanddrones.com/hex)

<table>
  <tr>
    <td width="50%"><a href="https://hex.onethousanddrones.com"><img alt="A ground-control mast build assembles part by part in the Hex Cluster configurator" src="assets/loop-hex-gcs-mast.webp" width="100%" /></a><br><sub>A GCS mast build assembling, rendered by the configurator itself.</sub></td>
    <td width="50%"><a href="https://onethousanddrones.com/#hex"><img alt="The Hex Cluster section of the company site: an exploded line drawing of a base tile with numbered balloons beside the parts list and its measured sizes in mm" src="assets/shot-apex-hex-2026-10.webp" width="100%" /></a><br><sub>Parts drawn from the CAD, sizes measured from it. onethousanddrones.com, captured October 2026.</sub></td>
  </tr>
</table>

## Emotive Engine

<p align="center">
  <a href="https://www.npmjs.com/package/@joshtol/emotive-engine"><img src="https://img.shields.io/npm/v/@joshtol/emotive-engine.svg?style=for-the-badge&labelColor=08090d&color=c8963e" alt="npm version" /></a>
  <a href="https://www.npmjs.com/package/@joshtol/emotive-engine"><img src="https://img.shields.io/npm/dm/@joshtol/emotive-engine.svg?style=for-the-badge&labelColor=08090d&color=c8963e" alt="npm downloads" /></a>
  <img src="https://img.shields.io/badge/license-MIT-c8963e.svg?style=for-the-badge&labelColor=08090d" alt="MIT license" />
</p>

An open-source runtime that turns AI interfaces into expressive characters. You drive it with a natural-language `feel()` call, and it renders emotion as motion.

- 15 emotions and 179 gestures
- 8 elemental shader systems with 160 elemental gestures
- 3D WebGL path with custom GLSL: subsurface scattering, physically based materials, bloom
- Lightweight 2D Canvas path: particles, shape morphing, gaze tracking, mobile-optimized
- Framework-agnostic, working with React, Vue, or vanilla JS

```bash
npm install @joshtol/emotive-engine
```

**Demo** · [emotiveengine.com](https://www.emotiveengine.com) · **Repo** · [emotive-engine](https://github.com/joshtol/emotive-engine)

<table>
  <tr>
    <td width="50%"><a href="https://www.emotiveengine.com"><img alt="Emotive Engine characters cycling through a second set of elemental gestures" src="assets/loop-emotive-elemental-2.webp" width="100%" /></a><br><sub>Elemental gestures, from the engine's own preview set.</sub></td>
    <td width="50%"><a href="https://www.emotiveengine.com/examples"><img alt="The Emotive Engine examples gallery: Crystal Soul, Basic Usage, 3D Elemental and Solar Eclipse" src="assets/shot-emo-examples-2026-10.webp" width="100%" /></a><br><sub>The examples gallery, emotiveengine.com, captured October 2026.</sub></td>
  </tr>
</table>

---

## Also on the workbench

<table>
  <tr>
    <td width="24%"><a href="https://github.com/Otd-llc/ee-calculators"><img alt="The voltage divider calculator on a phone: two resistors in, the output voltage out" src="assets/shot-ee-voltage-divider.webp" width="100%" /></a></td>
    <td valign="top"><b><a href="https://github.com/Otd-llc/ee-calculators">ee-calculators</a></b><br>Tested TypeScript for nine electronics calculators. The MIT-licensed core behind the OTD Academy tools.<br><sub>The voltage divider, from the repo's own docs.</sub></td>
  </tr>
  <tr>
    <td></td>
    <td valign="top"><b><a href="https://github.com/joshtol/caribbean-diving-guide-2025">Caribbean Diving Guide 2025</a></b><br>A full reef-diving guide generated end to end with an agentic AI pipeline.</td>
  </tr>
</table>

---

## Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-08090d?style=for-the-badge&logo=typescript&logoColor=c8963e" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Go-08090d?style=for-the-badge&logo=go&logoColor=c8963e" alt="Go" />
  <img src="https://img.shields.io/badge/Python-08090d?style=for-the-badge&logo=python&logoColor=c8963e" alt="Python" />
  <img src="https://img.shields.io/badge/Next.js-08090d?style=for-the-badge&logo=next.js&logoColor=c8963e" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-08090d?style=for-the-badge&logo=react&logoColor=c8963e" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-08090d?style=for-the-badge&logo=node.js&logoColor=c8963e" alt="Node.js" />
  <img src="https://img.shields.io/badge/Docker-08090d?style=for-the-badge&logo=docker&logoColor=c8963e" alt="Docker" />
  <img src="https://img.shields.io/badge/Google_Cloud-08090d?style=for-the-badge&logo=google-cloud&logoColor=c8963e" alt="Google Cloud" />
</p>

---

## Connect

I'm open to talking about autonomous systems, brain-computer interfaces, and hard interface problems.

<p>
  <a href="https://www.linkedin.com/in/joshuatollette/"><img src="https://img.shields.io/badge/LinkedIn-08090d?style=for-the-badge&logo=linkedin&logoColor=c8963e" alt="LinkedIn" /></a>
  <a href="https://onethousanddrones.com"><img src="https://img.shields.io/badge/onethousanddrones.com-08090d?style=for-the-badge&logo=googlechrome&logoColor=c8963e" alt="Website" /></a>
  <a href="mailto:josh@onethousanddrones.com"><img src="https://img.shields.io/badge/Email-c8963e?style=for-the-badge&logo=gmail&logoColor=08090d" alt="Email" /></a>
</p>

---

<sub><b>ONE THOUSAND DRONES</b> · [onethousanddrones.com](https://onethousanddrones.com) · [academy.onethousanddrones.com](https://academy.onethousanddrones.com) · [github.com/Otd-llc](https://github.com/Otd-llc)</sub>
<!-- otd-readme-kit footer v1 -->
