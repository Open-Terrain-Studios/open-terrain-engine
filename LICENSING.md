# Licensing — plain English

> This is a friendly summary to help you understand the model. **It is not the license and not legal advice.** The
> binding terms are in **[LICENSE](LICENSE)** (Business Source License 1.1); if anything here differs from the
> LICENSE, the LICENSE wins.

## The short version

Open Terrain Engine is **Source-available / Fair Source — not open source.** The source is published so you can read
it, learn from it, and build real games with it. You can **make and ship games commercially for free** — a royalty
only kicks in once an individual title becomes a genuine hit (over **$1,000,000** in lifetime gross revenue). And you
**can't** take the engine *itself* to market. Think of it as **selling the milk, not the cow** — plus a small share of
the biggest hits: make and sell your games, we only participate once a title is a real success, and either way don't
repackage and sell the engine.

## What you CAN do (the Additional Use Grant)

- **Read, study, and modify** the source.
- **Build, run, and distribute your own games and applications** with it — **including commercially** — **free of
  charge for each title until that title passes $1,000,000 in lifetime gross revenue.**
- **Ship the engine's runtime embedded inside your game** (that's how your game runs on a player's machine).
- **Use it inside your company / studio.**

## The royalty (only on hits)

For any single title that crosses **$1,000,000 in lifetime gross revenue**, continued production use of that title
needs a **commercial license** — an indicative **~5% royalty** on revenue above the threshold (Unreal-style
economics; the exact rate and the precise definition of "gross revenue" are set in the commercial terms). Key points:

- The threshold is **per title**, measured over the title's lifetime — each game gets its own $1M.
- Most projects never reach it, and pay nothing.
- Because the engine is BSL, each released version becomes **Apache-2.0 four years after it's published** — once a
  version converts, it is royalty-free, so the royalty applies only while a version is within its BSL term.

If a title is over the threshold (or you want the engine for something the grant doesn't cover), email
**licensing@openterrain.studio**.

## What you CAN'T do (without contacting us)

- **Offer the engine itself as a product or service** — i.e. resell it, host it as a service, sublicense it, or ship a
  game engine / development framework / SDK / tool whose value comes substantially from Open Terrain Engine.
- **Ship a competing engine** built from it (a fork, a modified version, or a substantial portion of it).
- **Keep selling a title that has passed $1,000,000 lifetime gross** without a commercial (royalty) license.
- **Use our trademarks** ("Open Terrain Engine", "Open Terrain Studios", logos) to brand or market your product. The
  license grants no trademark rights.

If you want to do any of those, that's a conversation — email **licensing@openterrain.studio**.

## The "it becomes open source eventually" part

The BSL is **time-delayed open source.** Each released version of the engine automatically converts to the
**Apache License 2.0** on its **Change Date** — four years after that version was first made publicly available. After
that date, that version is fully open-source under Apache-2.0, with no restrictions and no royalty.

So the restrictions above are temporary and per-version: the newest releases are Fair-Source; older releases roll into
permissive open source on schedule.

## Why this model

It keeps the engine **source-available** (you can see everything, nothing is a black box) and **sustainable** — the
studio is funded both by the engine's biggest commercial hits (the royalty) and by not letting competitors resell the
engine — while guaranteeing each version **becomes open source over time**. The royalty is modeled on Unreal Engine's
proven approach: free for the vast majority of projects, a fair share only once a title is a real commercial success.

## Common questions

**Do I owe anything to ship a game made with it?** Not until a single title passes **$1,000,000 in lifetime gross
revenue.** Below that, building and selling your game is covered by the Additional Use Grant at no charge. Above it,
that title needs a commercial license (indicative ~5% royalty). (Separate from this license, distributing on a store
like Steam has that store's own terms.)

**Is the threshold per game or for my whole studio?** Per **title** — each game has its own $1,000,000
lifetime-gross threshold.

**Can I use it at work / for a client project?** Yes — building games/applications, including for clients, is
permitted (subject to the same per-title threshold). Offering the *engine* to your client as an engine/SDK/service is
the line that needs a commercial license.

**My contribution / dependencies?** Every dependency the engine itself uses is permissive (MIT / Apache-2.0 / BSD /
Zlib / public-domain) — zero copyleft — so adopting it doesn't drag copyleft obligations into your game.

**Is "BSL" the same as the BSD license?** No — completely different. BSD is a permissive open-source license; the
**Business Source License (BSL)** is a source-available license with the time-delayed-open-source model described
above.

Questions the LICENSE doesn't answer? **licensing@openterrain.studio.**
