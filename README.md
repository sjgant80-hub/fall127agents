# Fall127 · FallWatch

**Live:** [sjgant80-hub.github.io/fall127agents](https://sjgant80-hub.github.io/fall127agents/)

**The 127 Eyes That Never Blink**

Sovereign 127-agent market intelligence engine. Single HTML file. Zero dependencies. Runs entirely in the browser.

## Architecture

```
MACCubeFACE(127) · 2^7 - 1 agents · sovereign substrate
```

| Group | Agents | Type | Domain |
|-------|--------|------|--------|
| α Market Data | 1-20 | TYPE_A heuristic | Equities, forex, commodities, crypto, bonds |
| β News Sentiment | 21-40 | TYPE_B femto LLM | Sector news, central banks, geopolitics |
| γ Social Signal | 41-60 | TYPE_B femto LLM | Reddit, X, Discord, Google Trends, GitHub |
| δ On-Chain | 61-80 | TYPE_A heuristic | BTC/ETH flows, DeFi, mining, liquidations |
| ε Macro Indicators | 81-100 | TYPE_A heuristic | CPI, PMI, NFP, housing, trade, OPEC |
| ζ Cross-Correlation | 101-120 | TYPE_C statistical | Paired agent co-firing detection |
| η Pattern Match | 121-126 | TYPE_B femto LLM | GFC 2008, COVID 2020, rate hike 2022 |
| θ Contrarian | 127 | TYPE_B femto LLM | The adversarial check |
| Ω Orchestrator | 0 | API cascade | Convergence detection + synthesis |

## Agent Types

- **TYPE_A** (~100 agents): Heuristic monitors. No LLM. Threshold/keyword/pattern matching. Sovereign compute.
- **TYPE_B** (~20 agents): Femto LLM wrappers. WebLLM 1-3B or free API cascade.
- **TYPE_C** (~6 agents): Cross-correlators. Statistical. Watches pairs of agents for co-firing.
- **TYPE_Ω** (1 agent): Orchestrator. API cascade for synthesis. Convergence detection.

## Convergence Detection

Adapted from FallConsensus:
- When ≥7 agents fire simultaneously
- Calculate signal similarity across firing agents
- If avg similarity ≥70%, min pairwise ≥50%, variance <0.15
- **CONVERGENCE DETECTED** → orchestrator synthesises

## Bloom Vector

7-ring market state mapped to prime spine {2, 3, 5, 7, 11, 13, 17}:

| Ring | Dimension | What it measures |
|------|-----------|-----------------|
| R0 | Ground | Signal strength — how many agents fired |
| R1 | Signal | Novelty — how different from recent history |
| R2 | Gate | Missing signals — what SHOULD be present |
| R3 | Heart | Sentiment direction across firing agents |
| R4 | Voice | Signal vs noise ratio |
| R5 | Mirror | Historical pattern recognition |
| R6 | Watcher | Meta — is convergence real or noise |

## Features

- 127-tile dashboard grid with real-time status
- Convergence detection engine
- Bloom vector visualisation
- Historical pattern matching (GFC, COVID, rate hikes, black swan)
- Agent 127 adversarial contrarian check
- IndexedDB persistence
- API cascade ready (Gemini → DeepSeek → WebLLM → Anthropic)
- JSON export
- Keyboard shortcuts (Space: start/stop, C: single cycle, Esc: close modal)
- Works on phone

## Shared Substrate

Fall127 is the shared architecture for three products:

1. **FallWatch** (this) — Market intelligence
2. **FallRecruit** — 127-agent recruitment engine
3. **FallMirror** — 127-agent life OS

Same architecture. Different domain SI. Build once, deploy three times.

## Run

Double-click `Fall127.html`. Or `index.html`. That's it.

No build step. No server. No dependencies. Sovereign.

---

◊·κ=1 · one file · 127 brains · sovereign
