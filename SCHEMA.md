# chkm8 market wiki: schema

## Domain
Crypto market intelligence for chkm8 (an AI agent trading small size on Lighter perps + occasional spot).
Purpose: accumulate daily observations into durable knowledge (narratives, tokens, what signals worked)
so trade/investment decisions are informed by a track record, not vibes.

## Layout
- `raw/digests/YYYY-MM-DD.json`: immutable daily data pulls (CoinGecko, DefiLlama, Lighter, X). Never edit.
- `digests/YYYY-MM-DD.md`: the emailed morning digest for that day.
- `narratives/<slug>.md`: one page per market narrative/sector (e.g. `ai-agents.md`, `privacy.md`, `rwa.md`).
- `tokens/<symbol-lowercase>.md`: one page per token that matters (recurring mover, held/traded, watchlist).
- `signals.json`: machine-readable watchlist calls, scored every morning against live prices.
- `index.md`: catalog of every page with a one-line summary. `log.md`: append-only action log.

## Conventions
- File names lowercase-hyphenated. Every page starts with YAML frontmatter:
  ```yaml
  ---
  title: ...
  type: token | narrative | digest
  created: YYYY-MM-DD
  updated: YYYY-MM-DD
  tags: [from taxonomy]
  confidence: high | medium | low
  ---
  ```
- Link pages with `[[slug]]`; every token page links its narrative(s) and vice versa.
- Every claim about a project (team, unlocks, admin keys, insider supply) needs a source URL or "unverified".
- Token pages have a dated **Log** section: append `- YYYY-MM-DD: observation (source: digest/raw)`; never rewrite history.
- Token pages carry a **Decentralization** line: score 0 (credible) to 3 (centralized LARPing as decentralized),
  facts + sources, or `unknown`. Mirrors `~/chkm8/research/decentralization.json`.

## Page thresholds
- Create a token page when it appears in 2+ digests as a top mover/trending/chatter, or we trade it.
- Create a narrative page when a sector leads/lags on 2+ days or several tokens share a story.
- Don't create pages for one-off pumps or bot-spam tickers.

## Signals (signals.json)
Each morning add 0-3 watchlist calls ONLY when there's a real thesis. Object:
`{"date","symbol","coingecko_id","direction":"long|short","price","thesis","invalidation","horizon_days"}`.
Price = CoinGecko USD at digest time. Never delete; the scorecard grades them. Review hit rate weekly
and write lessons into the relevant narrative/token pages.

## Tag taxonomy
L1, L2, defi, perps-dex, ai, privacy, rwa, meme, gaming, depin, identity, stablecoin, exchange-token,
centralization-risk, unlock-risk, momentum, mean-reversion, ct-froth, bot-spam, traded, watchlist
