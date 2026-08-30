# Hyperlift — Build-Up & Riser VST3 / AU Plugin for macOS and Windows

**One Intensity knob. 25 presets. Eight stackable build-up effects.** Hyperlift is a
multi-FX build-up processor for electronic music producers — a riser engine that turns a
single macro into a controlled climb from subtle motion to a full drop, on any track, bus,
or master.

Instead of automating a dozen plugins, you ride one knob and Hyperlift sweeps a filter,
grows a reverb tail, feeds the delays, and layers risers underneath — all in time, all in
one move.

### Download

| Platform | Installer |
|---|---|
| **macOS** (Apple Silicon + Intel) | [**Download .dmg**](https://github.com/alexlarichev/hyperlift-releases/releases/latest/download/Hyperlift-mac.dmg) |
| **Windows** (64-bit) | [**Download .exe**](https://github.com/alexlarichev/hyperlift-releases/releases/latest/download/Hyperlift-Win64.exe) |

Both installers are code-signed — notarized by Apple on macOS — so they install without
security warnings. See [all releases](https://github.com/alexlarichev/hyperlift-releases/releases).

---

## Features

- **One Intensity macro** drives the entire build-up. Automate it and the whole climb
  follows.
- **25 presets**, from the gentlest lift to total chaos — tuned for EDM, house, techno,
  trance, dubstep and bass music.
- **8 FX pads** — high-pass filter, delay, reverb, noise, pitch, Shepard tone, flanger and
  sidechain pump — each with its own 0–200% power strip, switchable in any preset.
- **Tempo-synced looper** with selectable divisions. Captures forward from the moment you
  engage it, so the bar you are entering is the bar that loops.
- **Global pitch shifter**, ±4 octaves on a continuous fader — ride it like tape slowing
  down or speeding up. Sits after the looper, so a frozen loop can be pitched.
- **Transparent output limiter** holding the output at −0.1 dBFS, so a build-up that adds
  several dB on the way up never pushes your master into clipping.
- **Full host automation** on every control, resizable interface, and a built-in manual.

## System requirements

| | macOS | Windows |
|---|---|---|
| **Formats** | VST3, Audio Unit (AU) | VST3 |
| **Architecture** | Universal — Apple Silicon (M1–M4) and Intel | 64-bit |
| **OS** | macOS 10.13 High Sierra or newer | Windows 10 / 11 |
| **Latency** | 2 ms, constant and reported to the host | same |

Hyperlift is a **plugin**, not a standalone application — load it inside a DAW.

### DAW compatibility

Hyperlift runs in any host that loads VST3 or Audio Unit plugins — Logic Pro, Ableton
Live, FL Studio, Cubase, Studio One, Reaper, Bitwig Studio and Nuendo among them.

## Installation

**macOS** — open the `.dmg`, double-click **Install Hyperlift**, and follow the installer.
It offers VST3 and Audio Unit; pick either or both. Plugins land in
`/Library/Audio/Plug-Ins/`.

**Windows** — run the `.exe`. The VST3 installs to
`C:\Program Files\Common Files\VST3\` by default, or a folder you choose. Close your DAW
before installing.

In your DAW's plugin list Hyperlift appears under the manufacturer **EDM Ghost
Production**. On first launch, click the avatar in the top corner and sign in with your
account.

## Demo vs. licensed

The download **is** the full plugin — nothing is disabled and no presets are held back.
Unlicensed, it periodically adds a short burst of noise to the output. Signing in with a
licensed account removes it.

A license activates on **two devices** at a time, managed from your account dashboard, and
keeps working offline for up to 24 hours of plugin use between check-ins.

[**Get a license →**](https://edm-ghost-production.com/plugins/hyperlift)

## FAQ

**Is there a free trial?**
Yes — the demo above is the complete plugin with a periodic noise burst. No time limit.

**Does it work on Apple Silicon?**
Yes. The macOS build is a universal binary and runs natively on M1, M2, M3 and M4, as well
as Intel Macs. It also runs under Rosetta for hosts in Intel mode.

**Is there an AAX version for Pro Tools?**
Not at the moment. macOS ships VST3 and AU; Windows ships VST3.

**Where do I put it on my project?**
Anywhere you want the lift — a single track, a bus, or the master. The built-in limiter
means dropping it on a finished master will not push it into clipping.

**How do I move my license to another computer?**
Remove the old device from your dashboard; that frees an activation slot immediately.

**Where is the manual?**
Inside the plugin — open the account panel and click **User manual**.

## Support

- Support: [dashboard.edm-ghost-production.com/support](https://dashboard.edm-ghost-production.com/support/)
- Manage devices: [dashboard.edm-ghost-production.com/account/plugin](https://dashboard.edm-ghost-production.com/account/plugin)
- Website: [edm-ghost-production.com](https://edm-ghost-production.com)

---

This repository hosts the public installers only. The source code lives in a private
repository.

© EDM Ghost Production Inc. — built by producers, for producers.

<sub>Keywords: build-up plugin, riser plugin, EDM build up VST, drop effect plugin, uplifter,
transition FX, VST3 plugin, Audio Unit plugin, AU plugin macOS, Windows VST3, pitch shifter
plugin, tempo-synced looper plugin, output limiter plugin, multi-FX plugin, Logic Pro
plugin, Ableton Live plugin, FL Studio plugin, EDM production tools, house techno trance
dubstep.</sub>
