---
title: LINK (Chainlink)
type: token
created: 2026-10-23
updated: 2026-10-23
tags: [defi, watchlist, centralization-risk, unlock-risk]
confidence: medium
---

# LINK (Chainlink)

Oracle and data network pitched as the "oracle for Wall Street". Screened via [[cycle-playbook]]. Its value accrual is a company-run reserve, similar to the treasury-buyback pattern in [[defi-revenue]]. Compare it with [[pump]] (company-run burn) and [[zro]] (open-market buybacks against unlocks).

## Narrative
TradFi and tokenization infrastructure, with two US spot ETFs. Grayscale GLNK listed Dec 2 2025 and Bitwise CLNK on Jan 14 2026. Neither stakes. They took $154.0M of net inflows across 198 sessions by Sep 16 2026, with only two redemption days (https://cryptoetf.today/en/blog/chainlink-etf-explained). The record inflow day was $9.48M on Oct 9 2026, and the funds hold about 2.35% of supply (https://bsc.news/news/chainlink-etf-record-inflow-day).

## Catalysts
- Link:NYC on Oct 29 2026 (https://cryptoticker.io/en/chainlink-reserve-purchases-price-impact/).
- Bitwise says it intends to stake CLNK later (cryptoetf.today). A staking ETF would be the real distribution upgrade. No date.

## Value accrual
Payment Abstraction converts enterprise and on-chain service fees into LINK and sends it to the Chainlink Reserve. The Reserve is an Ethereum contract with a multiday withdrawal timelock (https://www.tokenpost.com/news/investing/34983). It held 6.29M LINK (0.82% of supply) after buying 89,200 on Oct 15. Buys over the 30 days to mid-October totaled 431,900 LINK (~$5.41M) (cryptoticker). This is accumulation, not a burn.
- **Data check (2026-10-23):** DefiLlama `chainlink-staking` shows revenue of $5.41M/30d, "+23% m/m". The daily chart shows weekly buys flat at $1.01-1.16M, and the same $1,057,512 appears on both Oct 21 and Oct 22, which looks like a double count. Without it, revenue is roughly flat. This fails playbook item 1 (see the 10-18 data lesson in [[cycle-playbook]]).

## Unlocks / insiders
Circulating 766.85M of 1B. Insiders hold 54.4% of the final allocation. A "Node Operators & Company" cliff transfer of 18.75M LINK ($226M, 2.44% of float) happened Oct 9 2026. No further scheduled unlocks are listed, but company releases are discretionary (https://defillama.com/unlocks/chainlink). That one transfer equals about 43x a month of Reserve buying.

## Decentralization
Score 2: Chainlink Labs controls both the supply tap (non-circulating wallets released at its discretion) and the Reserve, and node operators are permissioned. The Reserve timelock is a real check. Unverified beyond the sources above.

## Log
- 2026-10-23: $12.06 (-0.2%), mcap $9.25B, about -77% from ATH (KuCoin headline). Watch-only 3.5/6: distribution ✓ (2 ETFs), story ✓, left-for-dead ✓, known overhang ✓, accrual ½ (reserve, not burn), revenue growth ✗ (flat weekly buys; DefiLlama +23% m/m looks inflated by a duplicate day). ETF outflow of -$397K on Oct 16 (TokenPost). Would buy: Reserve buys trending up over 2-3 months, or a staking ETF. Kill: ETF flows negative for weeks. (source: raw/digests/2026-10-23.json, DefiLlama API, [[digests/2026-10-23]])
