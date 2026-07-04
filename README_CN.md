# vibe-design-how-to

一个简洁的 **vibe-design** 开源说明。

[English version](./README.md)

这个仓库是 [design.vibec.pro](https://design.vibec.pro) 上 `vibe-design` 网站的使用说明。

## 什么是 vibe-design？

`vibe-design` 把设计方向沉淀成可复用的样式提示词，让人类和 AI 编码工具都可以稳定复用同一套视觉风格。

它适合这些场景：

- 生成具有明确视觉风格的 UI
- 在不改动产品逻辑的前提下重塑现有界面
- 在实现之前先给 AI Agent 一个稳定的设计参考
- 通过统一的公开来源浏览大量样式

## 核心能力

- 使用稳定 slug 的样式库
- 面向 AI 工作流的公开 `design.md` prompt 地址
- 可在 `design.vibec.pro` 上直接浏览的样式目录
- 可复用的、面向设计实现的 prompt 模式

## AI Agent 用法

Agent 可以直接获取某个 style prompt，比如 Figma style：

```bash
curl https://design.vibec.pro/figma/design.md
```

提示词示例：

```text
Install the Figma style by using:
curl https://design.vibec.pro/figma/design.md

Apply the resulting design system to the current landing page.
```

你也可以直接让 Agent 访问站点来选择样式：

- [design.vibec.pro](https://design.vibec.pro)

## 样式列表

样式总数：**96**

| Style | Slug | Category | Year | Link |
| --- | --- | --- | --- | --- |
| Airbnb Stays | `airbnb` | Editorial | 2020s | [Open](https://design.vibec.pro/airbnb) |
| Airtable | `airtable` | Brand | 2020s | [Open](https://design.vibec.pro/airtable) |
| Apple Gallery | `apple` | Editorial | 2020s | [Open](https://design.vibec.pro/apple) |
| Art Deco | `art-deco` | Retro | 1920s revival | [Open](https://design.vibec.pro/art-deco) |
| Bauhaus | `bauhaus` | Minimal | 1920s revival | [Open](https://design.vibec.pro/bauhaus) |
| Bento Grid | `bento-grid` | Minimal | 2020s | [Open](https://design.vibec.pro/bento-grid) |
| Binance Signal | `binance` | Product | 2020s | [Open](https://design.vibec.pro/binance) |
| BMW Corporate | `bmw` | Brand | 2020s | [Open](https://design.vibec.pro/bmw) |
| BMW M | `bmw-m` | Brand | 2020s | [Open](https://design.vibec.pro/bmw-m) |
| Bugatti Monolith | `bugatti` | Brand | 2020s | [Open](https://design.vibec.pro/bugatti) |
| Cal.com Flow | `cal` | Editorial | 2020s | [Open](https://design.vibec.pro/cal) |
| Claude | `claude` | Editorial | 2020s | [Open](https://design.vibec.pro/claude) |
| Claude Editorial | `claude-editorial` | Product | 2020s | [Open](https://design.vibec.pro/claude-editorial) |
| Clay Orbit | `clay` | Brand | 2020s | [Open](https://design.vibec.pro/clay) |
| Claymorphism | `claymorphism` | Tactile | 2021 | [Open](https://design.vibec.pro/claymorphism) |
| ClickHouse Pulse | `clickhouse` | Product | 2020s | [Open](https://design.vibec.pro/clickhouse) |
| Cohere Mineral | `cohere` | Product | 2020s | [Open](https://design.vibec.pro/cohere) |
| Coinbase Ledger | `coinbase` | Product | 2020s | [Open](https://design.vibec.pro/coinbase) |
| Composio Grid | `composio` | Product | 2020s | [Open](https://design.vibec.pro/composio) |
| Cursor Editorial | `cursor` | Product | 2020s | [Open](https://design.vibec.pro/cursor) |
| Dark Cyber | `dark-cyber` | Futuristic | 2020s | [Open](https://design.vibec.pro/dark-cyber) |
| Dell 1996 | `dell-1996` | Retro | 2020s | [Open](https://design.vibec.pro/dell-1996) |
| Editorial Serif | `editorial-serif` | Editorial | Timeless | [Open](https://design.vibec.pro/editorial-serif) |
| ElevenLabs Atmosphere | `elevenlabs` | Product | 2020s | [Open](https://design.vibec.pro/elevenlabs) |
| Expo Devices | `expo` | Product | 2020s | [Open](https://design.vibec.pro/expo) |
| Ferrari | `ferrari` | Brand | 2020s | [Open](https://design.vibec.pro/ferrari) |
| Figma Notes | `figma` | Brand | 2020s | [Open](https://design.vibec.pro/figma) |
| Flat Design | `flat-design` | Minimal | 2010s | [Open](https://design.vibec.pro/flat-design) |
| Framer Atmosphere | `framer` | Brand | 2020s | [Open](https://design.vibec.pro/framer) |
| Glassmorphism | `glassmorphism` | Futuristic | 2020s | [Open](https://design.vibec.pro/glassmorphism) |
| Grunge | `grunge` | Bold | 1990s revival | [Open](https://design.vibec.pro/grunge) |
| HashiCorp Stack | `hashicorp` | Product | 2020s | [Open](https://design.vibec.pro/hashicorp) |
| HP | `hp` | Product | 2020s | [Open](https://design.vibec.pro/hp) |
| IBM Carbon | `ibm` | Product | 2020s | [Open](https://design.vibec.pro/ibm) |
| Intercom Fin | `intercom` | Product | 2020s | [Open](https://design.vibec.pro/intercom) |
| Kraken Depth | `kraken` | Product | 2020s | [Open](https://design.vibec.pro/kraken) |
| Lamborghini Nocturne | `lamborghini` | Brand | 2020s | [Open](https://design.vibec.pro/lamborghini) |
| Linear Precision | `linear-app` | Product | 2020s | [Open](https://design.vibec.pro/linear-app) |
| Lovable | `lovable` | Product | 2020s | [Open](https://design.vibec.pro/lovable) |
| Mastercard | `mastercard` | Brand | 2020s | [Open](https://design.vibec.pro/mastercard) |
| Material Design | `material-design` | Product | 2014+ | [Open](https://design.vibec.pro/material-design) |
| Maximalism | `maximalism` | Bold | Contemporary | [Open](https://design.vibec.pro/maximalism) |
| Memphis | `memphis` | Retro | 1980s | [Open](https://design.vibec.pro/memphis) |
| Meta Devices | `meta` | Editorial | 2020s | [Open](https://design.vibec.pro/meta) |
| Swiss Minimalism | `minimalism` | Minimal | Timeless | [Open](https://design.vibec.pro/minimalism) |
| MiniMax Spectrum | `minimax` | Product | 2020s | [Open](https://design.vibec.pro/minimax) |
| Mintlify Docs | `mintlify` | Editorial | 2020s | [Open](https://design.vibec.pro/mintlify) |
| Miro Workshop | `miro` | Brand | 2020s | [Open](https://design.vibec.pro/miro) |
| Mistral Horizon | `mistral-ai` | Editorial | 2020s | [Open](https://design.vibec.pro/mistral-ai) |
| MongoDB Atlas | `mongodb` | Product | 2020s | [Open](https://design.vibec.pro/mongodb) |
| Neo-Brutalism | `neo-brutalism` | Bold | 2020s | [Open](https://design.vibec.pro/neo-brutalism) |
| Neumorphism | `neumorphism` | Tactile | 2020 | [Open](https://design.vibec.pro/neumorphism) |
| Nike | `nike` | Brand | 2020s | [Open](https://design.vibec.pro/nike) |
| Nintendo 2001 Chrome | `nintendo-2001` | Retro | 2001 | [Open](https://design.vibec.pro/nintendo-2001) |
| Notion Workspace | `notion` | Editorial | 2020s | [Open](https://design.vibec.pro/notion) |
| NVIDIA Grid | `nvidia` | Product | 2020s | [Open](https://design.vibec.pro/nvidia) |
| Ollama Local | `ollama` | Product | 2020s | [Open](https://design.vibec.pro/ollama) |
| OpenCode Manual | `opencode-ai` | Product | 2020s | [Open](https://design.vibec.pro/opencode-ai) |
| Pinterest | `pinterest` | Editorial | 2020s | [Open](https://design.vibec.pro/pinterest) |
| PlayStation Chapters | `playstation` | Brand | 2020s | [Open](https://design.vibec.pro/playstation) |
| Pop Art | `pop-art` | Bold | 1960s revival | [Open](https://design.vibec.pro/pop-art) |
| PostHog | `posthog` | Product | 2020s | [Open](https://design.vibec.pro/posthog) |
| Raycast Command | `raycast` | Product | 2020s | [Open](https://design.vibec.pro/raycast) |
| Renault | `renault` | Brand | 2020s | [Open](https://design.vibec.pro/renault) |
| Renault Performance | `renault-performance` | Brand | 2020s | [Open](https://design.vibec.pro/renault-performance) |
| Replicate Notebook | `replicate` | Product | 2020s | [Open](https://design.vibec.pro/replicate) |
| Resend Domaine | `resend` | Product | 2020s | [Open](https://design.vibec.pro/resend) |
| Vaporwave | `retro-vaporwave` | Retro | 1980s revival | [Open](https://design.vibec.pro/retro-vaporwave) |
| Revolut | `revolut` | Product | 2020s | [Open](https://design.vibec.pro/revolut) |
| Runway | `runwayml` | Editorial | 2020s | [Open](https://design.vibec.pro/runwayml) |
| Sanity | `sanity` | Product | 2020s | [Open](https://design.vibec.pro/sanity) |
| Sentry | `sentry` | Product | 2020s | [Open](https://design.vibec.pro/sentry) |
| Shopify Cinematic | `shopify` | Product | 2020s | [Open](https://design.vibec.pro/shopify) |
| Skeuomorphism | `skeuomorphism` | Tactile | 2007–2012 revival | [Open](https://design.vibec.pro/skeuomorphism) |
| Slack Mosaic | `slack` | Product | 2020s | [Open](https://design.vibec.pro/slack) |
| SpaceX Launch | `spacex` | Brand | 2020s | [Open](https://design.vibec.pro/spacex) |
| Spotify Immersive | `spotify` | Editorial | 2020s | [Open](https://design.vibec.pro/spotify) |
| Starbucks Flagship | `starbucks` | Brand | 2020s | [Open](https://design.vibec.pro/starbucks) |
| Stripe | `stripe` | Brand | 2020s | [Open](https://design.vibec.pro/stripe) |
| Supabase System | `supabase` | Product | 2020s | [Open](https://design.vibec.pro/supabase) |
| Superhuman Editorial | `superhuman` | Product | 2020s | [Open](https://design.vibec.pro/superhuman) |
| Tesla | `tesla` | Brand | 2020s | [Open](https://design.vibec.pro/tesla) |
| The Verge | `theverge` | Editorial | 2020s | [Open](https://design.vibec.pro/theverge) |
| Together AI | `together-ai` | Product | 2020s | [Open](https://design.vibec.pro/together-ai) |
| Uber Grid | `uber` | Product | 2020s | [Open](https://design.vibec.pro/uber) |
| Vercel Edge | `vercel` | Product | 2020s | [Open](https://design.vibec.pro/vercel) |
| Vodafone Broadcast | `vodafone` | Brand | 2020s | [Open](https://design.vibec.pro/vodafone) |
| VoltAgent | `voltagent` | Product | 2020s | [Open](https://design.vibec.pro/voltagent) |
| Warp Terminal | `warp` | Product | 2020s | [Open](https://design.vibec.pro/warp) |
| Webflow Studio | `webflow` | Product | 2020s | [Open](https://design.vibec.pro/webflow) |
| WIRED | `wired` | Editorial | 2020s | [Open](https://design.vibec.pro/wired) |
| Wired Editorial | `wired-editorial` | Editorial | 2020s | [Open](https://design.vibec.pro/wired-editorial) |
| Wise | `wise` | Brand | 2020s | [Open](https://design.vibec.pro/wise) |
| xAI Frontier | `x-ai` | Product | 2020s | [Open](https://design.vibec.pro/x-ai) |
| Y2K Gloss | `y2k` | Retro | 2000s | [Open](https://design.vibec.pro/y2k) |
| Zapier | `zapier` | Product | 2020s | [Open](https://design.vibec.pro/zapier) |

## 说明

- 这个仓库刻意保持为纯静态文档说明。
- 它不会在本地嵌入完整的 style 网站内容。
- 上面的 style 链接都会直接跳转到托管中的 `vibe-design` 网站。
- 如果是给 agent 接入，推荐使用 `https://design.vibec.pro/<style-slug>/design.md` 这种格式。

## 参考资料

- [Google DESIGN.md](https://github.com/google-labs-code/design.md)
- [awesome-design-md](https://github.com/voltagent/awesome-design-md)
