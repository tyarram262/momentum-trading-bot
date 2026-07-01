# Open Positions — Day 6 (2026-07-01, Run 7 POST-CLOSE ~16:07 ET) — HOLD ×2; PANW stop RATCHETED 332→340.50; CRWD stop HELD 748

Strategy value (pre-deposit book): **$104.83** | Settled buying power: **$73.05** | Cumulative: **+4.83%** vs $100 baseline
⚠️ Cash shows **$473.05** incl. **$400.00 PENDING deposit (UNSETTLED — not tradable, good-faith rail)**. Total portfolio value $504.87.
⚠️ **CAPITAL EVENT (Run 5, unchanged):** pending deposit shrank $800 → $400 before settling. External flow, NOT P&L. Re-base baseline when it settles.

| Ticker | Qty | Entry | Close 7/1 | Trailed Stop | Target | Size | Unreal P&L | RS_20 | RS_60 |
|--------|-----|-------|-----------|--------------|--------|------|-----------|-------|-------|
| PANW | 0.052115 | 287.82 | 352.09 | **340.50** (RAISED from 332) | 360 | $15.00→$18.35 | **+$3.35 (+22.3%, +11.0R)** | 1.2068 | 1.9211 |
| CRWD | 0.017391 | 690.01 | 772.46 | **748.00** (HELD) | 800 | $12.00→$13.43 | **+$1.43 (+12.0%, +3.3R)** | 1.0233 | 1.7124 |

Equity value: $31.78 | 2/4 slots used | 2 slots free | 0/3 new buys today (market now closed)

## Stop logic (up-only trailing)
- **PANW** stop **RATCHETED 332.00 → 340.50**: 7/1 daily bar confirmed a higher-low at **341.00** (rising session lows 327.35 → 341.00); new stop sits just below it, 1.99R below the 352.09 close. Locks **+$2.75 (+18.3%)**. Sell full if PANW < 340.50.
- **CRWD** stop **HELD 748.00**: computed 1R-trail from close = 747.45 ≈ current stop; ratcheting under today's low (765.00) would leave only 0.30R of room = noise-level, unacceptable into tomorrow's split. Locks +$1.01. Sell full if CRWD < 748.
- 🚨 **CRWD 4:1 SPLIT EFFECTIVE 2026-07-02 (tomorrow):** post-split figures — entry ≈ **172.50**, stop **187.00**, target **200.00**, qty ≈ **0.069564**. The ~75% price drop at open is the SPLIT, not a stop hit. Verify via get_equity_positions before any action.

## Notes
- Portfolio open risk to trailed stops: **$1.03 = 0.98%** of account (cap 5%) — both stops above entry, book is playing with house money.
- Both holdings cyber (correlated, at max 2) → any 3rd position must be non-cyber.
- Earnings far out: PANW 2026-08-17, CRWD 2026-08-26.
- Regime at close: SPY 745.69 **above** 50DMA 736.61 (supportive) but rotation day-3 out of tech (QQQ −1.53%, XLK −2.56%, SMH −5.46%), VIX ~16.4 calm/orderly. Hostile for new tech entries.
- Next run (Day 7): rebuild full RS leaderboard; check $400 deposit settlement (re-base if settled); handle CRWD split.
