<picture>
  <img src="https://cdn.wolffi.sh/general/ogimage.jpg" alt="wolffish" />
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
      <a href="https://www.youtube.com/watch?v=MA6KkeZyFF4"><img src="https://cdn.wolffi.sh/general/Demo%20walkthrough.png" width="360" alt="Demo walkthrough" /></a>
      <br /><b>Demo walkthrough</b>
    </td>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=XZdBttn-99E"><img src="https://cdn.wolffi.sh/general/wolffish.jpg" width="360" alt="Cinematic launch" /></a>
      <br /><b>Cinematic launch</b>
    </td>
    <td align="center">
      <a href="https://www.youtube.com/watch?v=TKdTWd6BXR8"><img src="https://cdn.wolffi.sh/general/Cinematic%20reveal.png" width="360" alt="Cinematic reveal" /></a>
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

---

<sub>MIT License — [wolffi.sh](https://wolffi.sh) · [Docs](https://docs.wolffi.sh/) · [Discord](https://discord.com/invite/F5Ue36PzQ) · [X](https://x.com/the_wolffish)</sub>
