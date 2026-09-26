# Breakout Playbook — NSE breakouts, measured

A single-page, data-driven playbook for trading base breakouts in liquid NSE stocks.

**Live page:** https://rishabhinai-netizen.github.io/breakout-playbook/ (password-protected; content is AES-256 encrypted in the browser, ask the author for access).

## What's inside
- **Action board** — today's regime, a sized basket, fresh entries (entry, close-basis stop, quantity, targets with historical odds), re-entry watch, setups at the pivot, holdings to manage, exits.
- **Track record** — what the rules would have said over the last 15 sessions, and how those calls have done.
- **Edge lab** — tested findings from 16,206 point-in-time breakouts (2010–2026, after costs) and a daily mark-to-market portfolio replay.
- Day-5 fork, factor explorer, entry/exit tests, glossary and caveats.

## Method in brief
Breakouts from multi-week bases, entered at the breakout-day close; 8% stop on the daily close; exit on a close below the 50-day average; 0.4% round-trip costs. Scores combine relative strength, distance above the 200-day average, nearness to the 52-week high, base length and depth, structure level and market breadth. A walk-forward logistic model provides calibrated odds of a +30% move.

## Disclaimer
Educational research only. **Not investment advice.** The author is not a SEBI-registered Research Analyst or Investment Adviser. Historical results include survivorship bias and overstate future performance. Trading involves risk of loss. Do your own research.
