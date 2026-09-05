# Efe Genc

Full-stack product engineer. I build early-stage, AI-native products end to end : web, mobile, backend and the product layer around the model : and I state how every figure I quote was measured.

- **Founder, [LILA](https://hellolila.app)** (Feb 2026 – present) : a proactive personal AI whose hardest problem is knowing when *not* to speak: one delivery gate with twelve ordered checks, every rejection logged with its reason, and an evaluation harness that scores silence as its own dimension. Sole author, ~9,500 commits, sixteen languages, store-ready with the release deliberately held.
- **Founding engineer, [Cendra](https://cendra.ai)** (Aug 2025 – Jul 2026) : primary author of the web application, sole author of both mobile apps, owner of the notification and real-time system. $1M seed led by Revo Capital, February 2026.
- **Founding frontend engineer, [ReadyFly](https://readyfly.io)** (Jun 2025 – Jun 2026) : Maya, an AI career agent.

## Open source I authored (published September 2026)

| Package | What it does | Install |
|---|---|---|
| [product-engineer](https://github.com/Bubblegunn/product-engineer) | An agent skill: your coding agent restates work as a customer outcome, writes a plain-language "For the customer" block in every commit and PR, and never calls unobserved work done | `npx skills add Bubblegunn/product-engineer` |
| [proactive-gate](https://github.com/Bubblegunn/proactive-gate) | LILA's delivery gate as a zero-dependency library: twelve ordered checks (consent, quiet hours, trust ramp, dismissal cooldown, daily budget), a reason on every rejection, a replay CLI | `npm i proactive-gate` |
| [workproof](https://github.com/Bubblegunn/workproof) | A verifiable engineering report from a private git repository, without showing code: six figures, the command behind each, a hash, and `verify` | `npx workproof` |
| [surviving-lines](https://github.com/Bubblegunn/surviving-lines) | Share of surviving lines next to commit share over a deterministic file sample; the method behind the ownership essay | `npx surviving-lines` |

## Open source contributions, reviewed and merged by maintainers who owe me nothing

| Project | Change | Outcome |
|---|---|---|
| [langchain-ai/openwiki #635](https://github.com/langchain-ai/openwiki/pull/635) | Bundled skills could not sync from read-only installations | Merged, released in v0.3.3 with a named changelog credit |
| [langchain-ai/openwiki #703](https://github.com/langchain-ai/openwiki/pull/703) | Onboarding tests wrote into the developer's real config directory on Windows | Merged |
| [mastra-ai/mastra #22903](https://github.com/mastra-ai/mastra/pull/22903) | `runEvals` gate loops broke the trajectory-scorer contract and hid the failure as a silent 0 | Approved and merged; shipped in `@mastra/core@1.64.0` |

Each carried red→green regression tests; on the mastra one, the reviewer reproduced the regression check himself before approving.

## Writing

Eleven essays on building this way : [efe-genc-portfolio.vercel.app/writing](https://efe-genc-portfolio.vercel.app/writing/) : including [The Spec Is the Fast Path](https://efe-genc-portfolio.vercel.app/writing/the-spec-is-the-fast-path/), [Knowing When Not to Speak](https://efe-genc-portfolio.vercel.app/writing/knowing-when-not-to-speak/) and [Showing Ownership When the Repositories Are Private](https://efe-genc-portfolio.vercel.app/writing/showing-ownership-private-repositories/). The [/stats](https://efe-genc-portfolio.vercel.app/stats/) page prints every number with its scope and method.

Most of my product work lives in private repositories (LILA, and my employers'); the four packages above are the parts of that work I could make public and reusable. Ankara, Türkiye · open to UK relocation · [efegenc95@gmail.com](mailto:efegenc95@gmail.com) · [LinkedIn](https://www.linkedin.com/in/efe-genc/)
