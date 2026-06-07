# Open Terrain Engine

**An AI-native, code-first desktop game engine.** Open Terrain Engine is purpose-built so that an LLM coding agent
can author 100% of a game in **idiomatic, human-editable C#**, introspect the world as structured data, and verify
it through a **deterministic, headless contract** exposed over a built-in **[MCP](https://modelcontextprotocol.io)
server** — so any conformant AI assistant (or a human) can write, run, screenshot, and assert a game in a tight loop.

> **Source-available / Fair Source — *not* open source.** Open Terrain Engine is licensed under the
> [Business Source License 1.1](LICENSE). You can read the source, learn from it, and **build and ship your own
> games with it — including commercially, free under $1M lifetime gross per title (a ~5% royalty applies above that)**. You may **not** take the engine itself to market (resell it, host it, or
> ship a competing engine/SDK). Each released version automatically becomes **Apache-2.0** on its **Change Date** —
> four years after that version is first made publicly available. See **[LICENSING.md](LICENSING.md)** for the
> plain-English version.

> ⚠️ **Status: pre-release, in active development.** The engine is not yet ready for general use; APIs, formats, and
> this repository's contents will change. Star/watch to follow along — public releases will land here.

---

## Why it's different

- **AI-native, not AI-bolted-on.** The primary user is a coding agent. The whole engine is reachable from code *and*
  from a model-agnostic MCP tool surface — there are no editor-only features. Every capability returns a structured,
  agent-readable result (no silent failures, no black screens).
- **Code-first, idiomatic C#.** A game is real, refactorable C# you own — not nodes in a closed editor or generated
  spaghetti. Open any file and edit it like a human wrote it.
- **Deterministic by construction.** A fixed-point simulation core (Q32.32, no floating point) makes the simulation
  **bit-identical across Linux and Windows** — proven by a permanent cross-OS CI gate, not assumed. This is what makes
  lockstep multiplayer, replays, and reliable AI verification possible.
- **Verify what you ship.** The dedicated server and the AI-verification runtime are the *same* headless build with
  render/audio/input compiled out, and it compiles to **Native AOT**. The agent's loop is
  *write C# → run headless → screenshot + state-dump → assert*.
- **Genre-general.** FPS, third-person, side-scroller, top-down, and RTS are *compositions* of shared engine
  primitives, not separate products. Lockstep (RTS/fighting) and snapshot-netcode (FPS/single-player) paths coexist.
- **Zero copyleft.** Every dependency (transitively) is MIT / Apache-2.0 / BSD / Zlib / public-domain — so the
  licensing above is clean and unencumbered.

## Platforms & distribution

Linux + Windows desktop, built on the SDL3 GPU API over Vulkan. Designed for Steam distribution.
.NET 10 LTS · C# 14.

## Licensing in one breath

| You want to… | Allowed under the BSL? |
|---|---|
| Read, study, and modify the source | ✅ Yes |
| Build a game and sell it — free under **$1M lifetime gross per title** (ship the runtime inside it) | ✅ Yes |
| Keep selling a title **after it passes $1M** lifetime gross | 💲 Commercial license (~5% royalty) |
| Use it at a company, internally | ✅ Yes |
| Re-sell, re-host, or re-brand **the engine itself** / ship a competing engine or SDK | ❌ Not without a commercial license |
| Use a 4-year-old released version under Apache-2.0 | ✅ Yes (automatic on the Change Date) |

For a title past the $1M royalty threshold, commercial-engine licensing, or anything the [Additional Use Grant](LICENSE) doesn't cover, contact
**licensing@openterrain.studio**. Full detail: **[LICENSING.md](LICENSING.md)** · the binding terms: **[LICENSE](LICENSE)**.

## Trademarks

"Open Terrain Engine" and "Open Terrain Studios" are trademarks of Open Terrain Studios LLC. The BSL grants no trademark
rights; building a game with the engine does not let you use our names or logos to brand or market your product.

---

© 2026 Open Terrain Studios LLC. Licensed under the Business Source License 1.1.
