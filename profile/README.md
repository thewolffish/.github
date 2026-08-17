<picture>
  <img src="https://cdn.wolffi.sh/generic/banner.jpg" alt="wolffish" />
</picture>

# wolffish

**A brain you own, not a chatbot you rent.**

Wolffish is a local-first, markdown-powered personal AI desktop app built with Electron. It runs on macOS, Windows, and Linux, and maps the human brain’s architecture onto a deterministic agentic software pipeline where 15 runtime modules each handle one specific function — routing input, building context, and enforcing safety.

Built around a 15-module architecture modeled after the human brain, from memory consolidation to safety gating. Every piece of state lives in readable markdown. No black boxes.

### Repos

|                                                                         |                                                            |
| ----------------------------------------------------------------------- | ---------------------------------------------------------- |
| **[wolffish-app](https://github.com/thewolffish/wolffish-app)**         | Electron desktop agent — the brain and runtime             |
| **[wolffish-landing](https://github.com/thewolffish/wolffish-landing)** | Landing page at [wolffi.sh](https://wolffi.sh)             |
| **[wolffish-docs](https://github.com/thewolffish/wolffish-docs)**       | Documentation at [docs.wolffi.sh](https://docs.wolffi.sh/) |
| **[wolffish-extension](https://github.com/thewolffish/wolffish-extension)** | Chrome/Brave browser extension for agent browser control          |
| **[wolffish-mobile](https://github.com/thewolffish/wolffish-mobile)**   | iOS + Android companion app — a remote for your desktop agent |
| **[wolffish-relay](https://github.com/thewolffish/wolffish-relay)**     | Zero-retention rendezvous relay for the phone ↔ desktop tunnel |
| **[wolffish-signing](https://github.com/thewolffish/wolffish-signing)** | Windows code signing for releases                          |

### Stack

`Electron` `React` `TypeScript` `SQLite` `Claude` `OpenAI` `Ollama` `Tailwind`

### Principles

- **Local-first** — runs offline with Ollama, cloud providers are optional
- **Markdown is truth** — fork it, diff it, version it, read it
- **Skills via markdown** — drop a folder to teach it new workflows
- **Safety-gated** — destructive operations require explicit approval

### Watch

<table>
  <tr>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=oog1q7T8H-s"><img src="https://cdn.wolffi.sh/generic/demo_walkthrough.jpg" width="360" alt="Demo walkthrough" /></a>
      <br /><b>Demo walkthrough</b>
    </td>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=XZdBttn-99E"><img src="https://cdn.wolffi.sh/generic/cinematic_launch.jpg" width="360" alt="Cinematic launch" /></a>
      <br /><b>Cinematic launch</b>
    </td>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=TKdTWd6BXR8"><img src="https://cdn.wolffi.sh/generic/cinematic_reveal.jpg" width="360" alt="Cinematic reveal" /></a>
      <br /><b>Cinematic reveal</b>
    </td>
  </tr>
</table>

### Install

macOS / Linux / Windows:

```
curl -fsSL https://releases.wolffi.sh/install.sh | sh
```

Windows (PowerShell):

```
irm https://releases.wolffi.sh/install.ps1 | iex
```

Or download the latest release directly from [wolffi.sh](https://wolffi.sh/).

### Get the mobile app

Wolffish Mobile is the companion phone app — pair it to your desktop once by scanning a QR code, then reach your agent from anywhere over an end-to-end encrypted tunnel.

<table>
  <tr>
    <td align="center">
      <a href="https://apps.apple.com/us/app/wolffish/id6792797989"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" width="168" height="56" alt="Download on the App Store" /></a>
    </td>
    <td align="center">
      <a href="https://play.google.com/store/apps/details?id=sh.wolffi.mobile"><img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" width="214" height="83" alt="Get it on Google Play" /></a>
    </td>
  </tr>
</table>

Source: [thewolffish/wolffish-mobile](https://github.com/thewolffish/wolffish-mobile)

---

<sub>MIT License — [wolffi.sh](https://wolffi.sh) · [Docs](https://docs.wolffi.sh/) · [Discord](https://discord.com/invite/F5Ue36PzQ) · [X](https://x.com/younesbites)</sub>
