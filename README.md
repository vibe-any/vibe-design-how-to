# vibe-design-how-to

A concise open-source guide for **vibe-design**.

[中文说明 / Chinese version](./README_CN.md)

This repository is the user guide for the `vibe-design` website at [design.vibec.pro](https://design.vibec.pro).

## What is vibe-design?

`vibe-design` turns design direction into reusable style prompts that people and AI coding tools can apply consistently.

<img width="3208" height="1732" alt="4004edd47da2b0284477e991d48dce38" src="https://github.com/user-attachments/assets/bde6c62d-818f-4d23-a64a-2f4af54001a9" />

It is useful when you want to:

- generate a UI in a recognizable visual style
- restyle an existing interface without changing product logic
- give an AI agent a stable design reference before implementation
- browse a large style library from one public source

## Core capabilities

- A curated style library with stable slugs
- Public `design.md` prompt endpoints for AI workflows
- A human-browsable style catalog on `design.vibec.pro`
- Reusable prompt patterns for design-aware coding sessions

## AI agent usage

Agents can fetch and save a Figma style prompt into the current workspace as `DESIGN.md`:

```bash
curl -fsSL https://design.vibec.pro/style/figma/design.md -o DESIGN.md
```

Example prompt:

```text
Fetch and save the Figma style guide into the current workspace as DESIGN.md:

curl -fsSL https://design.vibec.pro/style/figma/design.md -o DESIGN.md

Apply the resulting design style to the current project.
```

You can also point an agent to the site directly to browse styles:

- [design.vibec.pro](https://design.vibec.pro)

## Style list

Total styles: **96**

| Style | Slug | Category | Year | Link |
| --- | --- | --- | --- | --- |
| Airbnb Stays | `airbnb` | Editorial | 2020s | [Open](https://design.vibec.pro/style/airbnb) |
| Airtable | `airtable` | Brand | 2020s | [Open](https://design.vibec.pro/style/airtable) |
| Apple Gallery | `apple` | Editorial | 2020s | [Open](https://design.vibec.pro/style/apple) |
| Art Deco | `art-deco` | Retro | 1920s revival | [Open](https://design.vibec.pro/style/art-deco) |
| Bauhaus | `bauhaus` | Minimal | 1920s revival | [Open](https://design.vibec.pro/style/bauhaus) |
| Bento Grid | `bento-grid` | Minimal | 2020s | [Open](https://design.vibec.pro/style/bento-grid) |
| Binance Signal | `binance` | Product | 2020s | [Open](https://design.vibec.pro/style/binance) |
| BMW Corporate | `bmw` | Brand | 2020s | [Open](https://design.vibec.pro/style/bmw) |
| BMW M | `bmw-m` | Brand | 2020s | [Open](https://design.vibec.pro/style/bmw-m) |
| Bugatti Monolith | `bugatti` | Brand | 2020s | [Open](https://design.vibec.pro/style/bugatti) |
| Cal.com Flow | `cal` | Editorial | 2020s | [Open](https://design.vibec.pro/style/cal) |
| Claude | `claude` | Editorial | 2020s | [Open](https://design.vibec.pro/style/claude) |
| Claude Editorial | `claude-editorial` | Product | 2020s | [Open](https://design.vibec.pro/style/claude-editorial) |
| Clay Orbit | `clay` | Brand | 2020s | [Open](https://design.vibec.pro/style/clay) |
| Claymorphism | `claymorphism` | Tactile | 2021 | [Open](https://design.vibec.pro/style/claymorphism) |
| ClickHouse Pulse | `clickhouse` | Product | 2020s | [Open](https://design.vibec.pro/style/clickhouse) |
| Cohere Mineral | `cohere` | Product | 2020s | [Open](https://design.vibec.pro/style/cohere) |
| Coinbase Ledger | `coinbase` | Product | 2020s | [Open](https://design.vibec.pro/style/coinbase) |
| Composio Grid | `composio` | Product | 2020s | [Open](https://design.vibec.pro/style/composio) |
| Cursor Editorial | `cursor` | Product | 2020s | [Open](https://design.vibec.pro/style/cursor) |
| Dark Cyber | `dark-cyber` | Futuristic | 2020s | [Open](https://design.vibec.pro/style/dark-cyber) |
| Dell 1996 | `dell-1996` | Retro | 2020s | [Open](https://design.vibec.pro/style/dell-1996) |
| Editorial Serif | `editorial-serif` | Editorial | Timeless | [Open](https://design.vibec.pro/style/editorial-serif) |
| ElevenLabs Atmosphere | `elevenlabs` | Product | 2020s | [Open](https://design.vibec.pro/style/elevenlabs) |
| Expo Devices | `expo` | Product | 2020s | [Open](https://design.vibec.pro/style/expo) |
| Ferrari | `ferrari` | Brand | 2020s | [Open](https://design.vibec.pro/style/ferrari) |
| Figma Notes | `figma` | Brand | 2020s | [Open](https://design.vibec.pro/style/figma) |
| Flat Design | `flat-design` | Minimal | 2010s | [Open](https://design.vibec.pro/style/flat-design) |
| Framer Atmosphere | `framer` | Brand | 2020s | [Open](https://design.vibec.pro/style/framer) |
| Glassmorphism | `glassmorphism` | Futuristic | 2020s | [Open](https://design.vibec.pro/style/glassmorphism) |
| Grunge | `grunge` | Bold | 1990s revival | [Open](https://design.vibec.pro/style/grunge) |
| HashiCorp Stack | `hashicorp` | Product | 2020s | [Open](https://design.vibec.pro/style/hashicorp) |
| HP | `hp` | Product | 2020s | [Open](https://design.vibec.pro/style/hp) |
| IBM Carbon | `ibm` | Product | 2020s | [Open](https://design.vibec.pro/style/ibm) |
| Intercom Fin | `intercom` | Product | 2020s | [Open](https://design.vibec.pro/style/intercom) |
| Kraken Depth | `kraken` | Product | 2020s | [Open](https://design.vibec.pro/style/kraken) |
| Lamborghini Nocturne | `lamborghini` | Brand | 2020s | [Open](https://design.vibec.pro/style/lamborghini) |
| Linear Precision | `linear-app` | Product | 2020s | [Open](https://design.vibec.pro/style/linear-app) |
| Lovable | `lovable` | Product | 2020s | [Open](https://design.vibec.pro/style/lovable) |
| Mastercard | `mastercard` | Brand | 2020s | [Open](https://design.vibec.pro/style/mastercard) |
| Material Design | `material-design` | Product | 2014+ | [Open](https://design.vibec.pro/style/material-design) |
| Maximalism | `maximalism` | Bold | Contemporary | [Open](https://design.vibec.pro/style/maximalism) |
| Memphis | `memphis` | Retro | 1980s | [Open](https://design.vibec.pro/style/memphis) |
| Meta Devices | `meta` | Editorial | 2020s | [Open](https://design.vibec.pro/style/meta) |
| Swiss Minimalism | `minimalism` | Minimal | Timeless | [Open](https://design.vibec.pro/style/minimalism) |
| MiniMax Spectrum | `minimax` | Product | 2020s | [Open](https://design.vibec.pro/style/minimax) |
| Mintlify Docs | `mintlify` | Editorial | 2020s | [Open](https://design.vibec.pro/style/mintlify) |
| Miro Workshop | `miro` | Brand | 2020s | [Open](https://design.vibec.pro/style/miro) |
| Mistral Horizon | `mistral-ai` | Editorial | 2020s | [Open](https://design.vibec.pro/style/mistral-ai) |
| MongoDB Atlas | `mongodb` | Product | 2020s | [Open](https://design.vibec.pro/style/mongodb) |
| Neo-Brutalism | `neo-brutalism` | Bold | 2020s | [Open](https://design.vibec.pro/style/neo-brutalism) |
| Neumorphism | `neumorphism` | Tactile | 2020 | [Open](https://design.vibec.pro/style/neumorphism) |
| Nike | `nike` | Brand | 2020s | [Open](https://design.vibec.pro/style/nike) |
| Nintendo 2001 Chrome | `nintendo-2001` | Retro | 2001 | [Open](https://design.vibec.pro/style/nintendo-2001) |
| Notion Workspace | `notion` | Editorial | 2020s | [Open](https://design.vibec.pro/style/notion) |
| NVIDIA Grid | `nvidia` | Product | 2020s | [Open](https://design.vibec.pro/style/nvidia) |
| Ollama Local | `ollama` | Product | 2020s | [Open](https://design.vibec.pro/style/ollama) |
| OpenCode Manual | `opencode-ai` | Product | 2020s | [Open](https://design.vibec.pro/style/opencode-ai) |
| Pinterest | `pinterest` | Editorial | 2020s | [Open](https://design.vibec.pro/style/pinterest) |
| PlayStation Chapters | `playstation` | Brand | 2020s | [Open](https://design.vibec.pro/style/playstation) |
| Pop Art | `pop-art` | Bold | 1960s revival | [Open](https://design.vibec.pro/style/pop-art) |
| PostHog | `posthog` | Product | 2020s | [Open](https://design.vibec.pro/style/posthog) |
| Raycast Command | `raycast` | Product | 2020s | [Open](https://design.vibec.pro/style/raycast) |
| Renault | `renault` | Brand | 2020s | [Open](https://design.vibec.pro/style/renault) |
| Renault Performance | `renault-performance` | Brand | 2020s | [Open](https://design.vibec.pro/style/renault-performance) |
| Replicate Notebook | `replicate` | Product | 2020s | [Open](https://design.vibec.pro/style/replicate) |
| Resend Domaine | `resend` | Product | 2020s | [Open](https://design.vibec.pro/style/resend) |
| Vaporwave | `retro-vaporwave` | Retro | 1980s revival | [Open](https://design.vibec.pro/style/retro-vaporwave) |
| Revolut | `revolut` | Product | 2020s | [Open](https://design.vibec.pro/style/revolut) |
| Runway | `runwayml` | Editorial | 2020s | [Open](https://design.vibec.pro/style/runwayml) |
| Sanity | `sanity` | Product | 2020s | [Open](https://design.vibec.pro/style/sanity) |
| Sentry | `sentry` | Product | 2020s | [Open](https://design.vibec.pro/style/sentry) |
| Shopify Cinematic | `shopify` | Product | 2020s | [Open](https://design.vibec.pro/style/shopify) |
| Skeuomorphism | `skeuomorphism` | Tactile | 2007–2012 revival | [Open](https://design.vibec.pro/style/skeuomorphism) |
| Slack Mosaic | `slack` | Product | 2020s | [Open](https://design.vibec.pro/style/slack) |
| SpaceX Launch | `spacex` | Brand | 2020s | [Open](https://design.vibec.pro/style/spacex) |
| Spotify Immersive | `spotify` | Editorial | 2020s | [Open](https://design.vibec.pro/style/spotify) |
| Starbucks Flagship | `starbucks` | Brand | 2020s | [Open](https://design.vibec.pro/style/starbucks) |
| Stripe | `stripe` | Brand | 2020s | [Open](https://design.vibec.pro/style/stripe) |
| Supabase System | `supabase` | Product | 2020s | [Open](https://design.vibec.pro/style/supabase) |
| Superhuman Editorial | `superhuman` | Product | 2020s | [Open](https://design.vibec.pro/style/superhuman) |
| Tesla | `tesla` | Brand | 2020s | [Open](https://design.vibec.pro/style/tesla) |
| The Verge | `theverge` | Editorial | 2020s | [Open](https://design.vibec.pro/style/theverge) |
| Together AI | `together-ai` | Product | 2020s | [Open](https://design.vibec.pro/style/together-ai) |
| Uber Grid | `uber` | Product | 2020s | [Open](https://design.vibec.pro/style/uber) |
| Vercel Edge | `vercel` | Product | 2020s | [Open](https://design.vibec.pro/style/vercel) |
| Vodafone Broadcast | `vodafone` | Brand | 2020s | [Open](https://design.vibec.pro/style/vodafone) |
| VoltAgent | `voltagent` | Product | 2020s | [Open](https://design.vibec.pro/style/voltagent) |
| Warp Terminal | `warp` | Product | 2020s | [Open](https://design.vibec.pro/style/warp) |
| Webflow Studio | `webflow` | Product | 2020s | [Open](https://design.vibec.pro/style/webflow) |
| WIRED | `wired` | Editorial | 2020s | [Open](https://design.vibec.pro/style/wired) |
| Wired Editorial | `wired-editorial` | Editorial | 2020s | [Open](https://design.vibec.pro/style/wired-editorial) |
| Wise | `wise` | Brand | 2020s | [Open](https://design.vibec.pro/style/wise) |
| xAI Frontier | `x-ai` | Product | 2020s | [Open](https://design.vibec.pro/style/x-ai) |
| Y2K Gloss | `y2k` | Retro | 2000s | [Open](https://design.vibec.pro/style/y2k) |
| Zapier | `zapier` | Product | 2020s | [Open](https://design.vibec.pro/style/zapier) |

## Notes

- This repository is intentionally static and documentation-only.
- It does not embed the full style site locally.
- Style links above go directly to the hosted `vibe-design` website.
- For agent integration, prefer the `https://design.vibec.pro/style/<style-slug>/design.md` pattern.

## References

- [Google DESIGN.md](https://github.com/google-labs-code/design.md)
- [awesome-design-md](https://github.com/voltagent/awesome-design-md)
