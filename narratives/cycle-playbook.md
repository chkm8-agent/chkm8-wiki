---
title: Cycle playbook: what the 2026 spot winners had in common
type: narrative
created: 2026-10-01
updated: 2026-10-18
tags: [watchlist, momentum, unlock-risk, centralization-risk]
confidence: medium
---

# Cycle playbook: what the winners had in common

Reference set chosen by r3lik: **HYPE, LIT, ZEC, NEAR**. Returns as of 2026-10-01 (CoinGecko): HYPE +136% 200d,
ZEC +494% 200d / +1041% 1y, NEAR +262% 200d, LIT +250% 200d. Use this page to screen new spot candidates.

## The four stories
| Token | Narrative | Hard catalyst | Value accrual | Watch-outs |
|---|---|---|---|---|
| [[hype]] | Onchain perps eat CEX share ("flippening Binance") | Revenue >$1B cumulative; ETF inflows | Assistance Fund buys back HYPE with protocol revenue | Monthly vesting unlocks; perps revenue has cooled vs summer peak (track m/m in digest) |
| [[lit]] | Verifiable zero-fee perps + distribution via Robinhood Chain | Robinhood Wallet integration (Jul 2026) | Revenue buybacks moved from treasury to **burn** (~15.5M LIT bought back) | Insiders 50% of supply locked, **cliff ~Dec 30 2026**; Lighter perps revenue falling (DefiLlama change_1m about -52% on 2026-10-01) |
| [[zec]] | Privacy as a "private complement to Bitcoin" | Grayscale ZCSH ETF (Aug 25 2026), Paradigm endorsement, protocol upgrade | None directly; monetary premium / access trade | Ainvest: it's "an access trade, not a privacy trade"; parabolic (+1000% 1y) |
| [[near]] | Chain abstraction + AI agents ("money agents will choose") | Bitwise NEAR ETF on NYSE Arca (late Sep 2026); NEAR Intents volume >$32B vs <$1B a year ago | Intents fees; proposal to cut issuance to 1.6% | Still -76% from ATH; ETF-driven flows can reverse |

Sources: yahoo finance (HYPE buybacks, May 2026), buyhype.org (assistance fund), crypto.news (HYPE ATH absorbing unlocks),
tokenomist.ai (LIT tokenomics & Dec 2026 cliff), coinmarketcap/dailycoinbrief (LIT Robinhood), bit.com + cryptobriefing +
ainvest + tatum.io (ZEC), approx.org + edgex + kcex + svrn.net (NEAR), DefiLlama fees API (revenue m/m).

## The pattern (screening checklist)
1. **Real usage that shows up in revenue or volume**, not just TVL (HYPE/LIT fees, NEAR Intents volume).
2. **Value accrual to the token**: buybacks/burns funded by revenue (HYPE, LIT) or supply cuts (NEAR).
3. **A distribution or access unlock**: ETF (ZEC, NEAR, HYPE), mega-distribution partner (LIT × Robinhood).
4. **Rotation from a "dead" large cap**: ZEC and NEAR were left for dead (ZEC was ~#82, NEAR -90% from ATH) before rerating.
5. **Clear one-line story** CT can repeat (privacy BTC, agent money, onchain Binance).
6. **Known supply overhang** priced and dated: unlock calendars matter (LIT Dec 2026 cliff, HYPE monthly vesting).

Red flags that disqualify: revenue is incentives/emissions; insiders >50% with near unlocks and no buyback offset;
admin keys / foundation control dressed up as decentralization (operator's standing view); CT "conviction" that is
paid-group spam or vote-farming.

**Scorecard lesson (2026-10-07):** in the 10-07 liquidation flush, spot calls with *rising* revenue m/m held (RAY +21% since call)
while buyback stories without revenue growth fell 12-13% (UNI, SKY, FLUID). Treat item 1 (revenue growth) as mandatory, and treat
item 2 (buyback) as a bonus, not a substitute. See [[defi-revenue]].

**Data lesson (2026-10-18):** a revenue spike has to be traced to its source before item 1 counts. DefiLlama's
'GMX Solana' +327% m/m was a sister token's (GT) treasury buyback counted as holders revenue, not GMX fees
(see [[gmx]]). Check the daily chart for a step change on a single date and read the adapter methodology.

## Next-candidates logic
Look for tokens that match 3+ of the checklist **before** the catalyst is fully priced: revenue rising m/m,
buyback/burn live, ETF filing or distribution deal pending, and still well below ATH. Track in `signals.json`
as `long` with horizon 30-90d, not as perps trades.
