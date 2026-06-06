# Licensing — plain English

> This is a friendly summary to help you understand the model. **It is not the license and not legal advice.** The
> binding terms are in **[LICENSE](LICENSE)** (Business Source License 1.1); if anything here differs from the
> LICENSE, the LICENSE wins.

## The short version

Open Terrain Engine is **Source-available / Fair Source — not open source.** The source is published so you can read
it, learn from it, and build real games with it. What you *can't* do (without a separate commercial license) is take
the engine itself to market. Think of it as **selling the milk, not the cow**: use the engine to make and sell your
games freely; just don't repackage and sell the engine.

## What you CAN do (the Additional Use Grant)

- **Read, study, and modify** the source.
- **Build, run, and distribute your own games and applications** with it — **including commercially.**
- **Ship the engine's runtime embedded inside your game** (that's how your game runs on a player's machine).
- **Use it inside your company / studio.**

## What you CAN'T do (without contacting us)

- **Offer the engine itself as a product or service** — i.e. resell it, host it as a service, sublicense it, or ship a
  game engine / development framework / SDK / tool whose value comes substantially from Open Terrain Engine.
- **Ship a competing engine** built from it (a fork, a modified version, or a substantial portion of it).
- **Use our trademarks** ("Open Terrain Engine", "Open Terrain Studios", logos) to brand or market your product. The
  license grants no trademark rights.

If you want to do any of those, that's a conversation — email **licensing@openterrain.studio** about a commercial
license.

## The "it becomes open source eventually" part

The BSL is **time-delayed open source.** Each released version of the engine automatically converts to the
**Apache License 2.0** on its **Change Date** — four years after that version was first published (whichever comes
first per the LICENSE). After that date, that version is fully open-source under Apache-2.0, no restrictions.

So the restrictions above are temporary and per-version: the newest releases are Fair-Source; older releases roll into
permissive open source on schedule.

## Why this model

It keeps the engine **source-available** (you can see everything, nothing is a black box, you're never locked out of
code you depend on) and **sustainable** (the studio can fund development because the engine itself isn't free for
competitors to resell), while guaranteeing it **becomes open source over time**. It's the same model used by projects
like MariaDB, Sentry, and CockroachDB.

## Common questions

**Do I owe royalties or fees to ship a game made with it?** No. Building and selling your game is covered by the
Additional Use Grant at no charge. (Separate from this license, distributing on a store like Steam has that store's
own terms.)

**Can I use it at work / for a client project?** Yes — building games/applications, including for clients, is
permitted. Offering the *engine* to your client as an engine/SDK/service is the line that needs a commercial license.

**My contribution / dependencies?** Every dependency the engine itself uses is permissive (MIT / Apache-2.0 / BSD /
Zlib / public-domain) — zero copyleft — so adopting it doesn't drag copyleft obligations into your game.

**Is "BSL" the same as the BSD license?** No — completely different. BSD is a permissive open-source license; the
**Business Source License (BSL)** is a source-available license with the time-delayed-open-source model described above.

Questions the LICENSE doesn't answer? **licensing@openterrain.studio.**
