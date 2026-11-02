---
title: Agentic AI weekly radar
type: narrative
created: 2026-10-19
updated: 2026-10-19
tags: [ai, identity]
confidence: medium
---

# Agentic AI weekly radar

Weekly (Monday) notes on agent swarms / multi-agent infra: A2A, MCP, x402, AP2, ERC-8004, kagent, Swarms, TradingAgents,
Letta, LangGraph, CrewAI, Hermes. Source data: `raw/agentic/YYYY-MM-DD.json`. Rule for chkm8: agents only write proposals;
`trade.py` stays the single order path. Related: [[cycle-playbook]], [[near]] (agent-money narrative).

## Log
- 2026-10-19: Hermes v0.22.0 "Threshold" (stable SemVer channel, signed pkgs, 600-plugin catalog, local llama.cpp, one gateway); v0.22.1 bad commit, v0.22.2 fix; we run v0.21.5+ (upgrade manually). TradingAgents v0.7.0 fixes lookahead in decision scoring. kagent alpha12-14: disable-bash flag, read-only share tokens, per-worker ServiceAccount. Protocol repos quiet (A2A +10, MCP +5, x402 +3 stars; AP2/ERC-8004 idle). No arXiv items. AI Agents tokens $3.48B, top-10 all red 7d (RLC -32%, ARC -25%, FET -17%). Try: read-only kagent ops agent on chkm8-nue-1. ([[digests/2026-10-19]])
- 2026-10-26: Hermes 257k stars (Δ+2,106), v0.22.5 (Oct 23) patch rollup, no new feature. kagent v1.0.0-alpha17 (Oct 21) adds gateway token passthrough for embedded controllers, stars 4,095 (Δ+43). TradingAgents the week's biggest mover (Δ+3,384 to 114k+) on v0.7.0's own-ChatGPT-plan support. LangGraph 1.2.17 and CrewAI 1.15.30 both routine patches. Papers: "The Helpful Agent Problem" (2610.31985, agents bypass oversight via emergent cooperation) and "Understanding Communication Failures in Multi-Agent LLM Systems" (2610.32060). AI-agent token sectors still red/flat ($3.39B AI Agents -0.6%, $1.77B AI Framework -1.7%, $1.17B Launchpad -0.9%) while framework stars keep growing — same revenue/token gap as GRASS/VVV/BAT. Try: read-only kagent ops agent for chkm8-nue-1 (view-only RBAC). ([[digests/2026-10-26]])
- 2026-11-02: TradingAgents the week's outlier again, Δ+4,421 stars to 119,838 on v0.7.1 (Oct 27, final-close scoring fixes + holiday-settlement correctness) — adoption keeps outpacing most other repos by an order of magnitude. kagent reaches v1.0.0-rc1 (Oct 30), its first release candidate — the trigger to finally stand up the long-flagged read-only ops agent on chkm8-nue-1 now that the API is stabilizing. Hermes crosses 259,710 stars (Δ+2,444), steady maintenance pace, no headline feature. CrewAI 1.15.34 (Nov 1) adds a standalone LiteLLM model catalog + `crewai skill search`. A2A/MCP/x402 protocol repos: steady modest growth (+92/+55/+19 stars), no releases. Paper flagged: "Beyond LLM Wrappers: Context Engineering and the Three-Engine Architecture for Reliable Financial AI" (2610.39230) — makes the case for why `trade.py` stays the single order path rather than letting an agent execute directly. AI-agent token sector data didn't come through in this week's pull; the framework-stars-vs-token-price gap pattern holds regardless. Try: read-only kagent ops agent on chkm8-nue-1 (view-only RBAC, chkm8 namespace) — concrete this time given rc1. ([[digests/2026-11-02]])
