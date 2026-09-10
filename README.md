# Rack Zero

A guided, single-file rack-building simulator. Nova, your build guide, walks you from an empty 19-inch frame to a finished rack — power budget and redundancy planning first, then mounting, structured cabling, and boot order — all grounded in real electrical and rack-mount practice.

Open `index.html` directly in a browser, or serve it with GitHub Pages.

## Two build paths

**Home Lab**
- Pick a 9U or 12U wall-mount frame
- Budget a 15A or 20A / 120V circuit against the NEC 80%-continuous-load rule
- Right-size a UPS (compact / standard / large) against that circuit
- Mount a patch panel, cable bar, switch, router, and NAS in the correct order
- Wire power, run structured cabling, and power everything on in the right boot sequence

**Datacenter Build**
- Choose an Uptime Institute Tier (I–IV), with real uptime/downtime figures
- Budget a 208V L6-20 or L6-30 circuit; Tier III/IV requires redundant A + B feeds
- Pick a PDU type (basic / metered / switched)
- Mount a patch panel, cable bar, ToR switch, core router, and dual-corded 2U server
- Wire both feeds, cable the ToR switch to the core router, and boot in order

## Features

- A technician avatar who visibly walks to the rack slot you click and performs the install
- Autosaving "build" profiles (rename, reset, switch between, or start a new build) stored in the browser via `localStorage`
- Light/dark theme support

## Disclaimer

This is a teaching simulation, not electrical advice. Always verify wiring and breaker capacity against your own local electrical code before doing this for real.
