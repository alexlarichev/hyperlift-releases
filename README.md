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

## Changelog

### 1.1.0 — 2026-09-13

- **Buttons no longer stick under fast clicks.** LOOP, PITCH, BYPASS, LIMITER and STEREO now flip on every click, however fast you go. A double-click on the STEREO button counts as one click; a double-tap on its strip still resets MIN.
- **Easier to read, easier to grab.** The captions under the FX pads are 20 % larger, the power strips under them are a touch taller, and the LOOP/PITCH block sits closer to INTENSITY.
- **Typed values look right from the first keystroke.** The number waiting in the power-strip, OUTPUT and PITCH entry boxes now uses the same font and colour as what you type.

### 1.0.9 — 2026-09-12

- **The avatar shows there is an update.** While a newer build is out, the account avatar's ring turns blue, the same blue as Update available inside the menu, so you notice it without opening anything. A license problem still shows in red or amber, as before.

### 1.0.8 — 2026-09-11

- **Update available as a one-time toast.** When a newer build is out, a toast says so the moment you open the plugin. Click it to download the installer for your platform, or close it and it stays away until the next release.

### 1.0.7 — 2026-09-11

- **Update available, right in the plugin.** When a newer build is out, the About card and the account menu say so, with the version you have and the one you can get. A click downloads the installer for your platform.

### 1.0.6 — 2026-09-09

- **Sign-in works with hyphenated domains again.** The email check rejected them outright, so anyone on an address like my-studio.com could not log in and the plugin never said why.

### 1.0.5 — 2026-09-09

- **GUI SIZE in the About card.** Set the window to an exact scale between 60 and 150 % instead of dragging the corner until it looks right.
- The About card now stamps the real build date, and the credit line links out.

### 1.0.4 — 2026-09-05

- **RESET button in the preset rack.** It lights up as soon as you’ve changed anything in the current preset, and one click puts the pads, power strips, LOOP, PITCH, STEREO and OUTPUT back to their defaults. INTENSITY is left alone, and your DAW’s Undo reverts the whole reset in one step.
- **BYPASS now looks bypassed everywhere.** The INTENSITY dial, the power strips under the pads, STEREO and OUTPUT all dim along with the rest of the interface.

### 1.0.3 — 2026-09-04

- **BYPASS now bypasses the looper and pitch shifter too.** With LOOP or PITCH engaged, a bypassed plugin used to keep processing.
- **The limiter no longer switches off with BYPASS.** It’s an output safety — it holds the ceiling either way.
- LOOP and PITCH rows dim under BYPASS, like the rest of the UI.

### 1.0.2 — 2026-09-01

- **Windows installer and plugin are now code-signed.** Fixes the Smart App Control / “unknown publisher” block on Windows 11.

### 1.0.1 — 2026-08-31

Windows installer fixes:

- Custom install folders now work with every DAW, including FL Studio.
- Upgrading no longer leaves the old version behind.
- Uninstall works with your DAW still open — no reboot required.

### 1.0.0 — 2026-08-30

- First public release: one Intensity knob, 25 presets, eight FX pads with power strips, a tempo-synced looper, a global pitch shifter and an output limiter. VST3 and Audio Unit on macOS (Apple Silicon and Intel), VST3 on Windows.

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
