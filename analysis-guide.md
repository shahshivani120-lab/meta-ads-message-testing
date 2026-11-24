# Analysis guide

What to look at, in what order, and how to diagnose a problem.

## The metrics that matter (in order)

| # | Metric | What it tells you |
|---|---|---|
| 1 | **Cost per messaging conversation started** | How well the message works. Your main comparison number |
| 2 | **Messaging conversations started** | Volume. Need enough to trust #1 |
| 3 | **Qualified rate** (from your log) | Whether the message attracts the right people |
| 4 | **CTR (all)** | Whether the hook and visual stop the scroll |
| 5 | **CPM** (cost per 1,000 impressions) | How expensive the audience is to reach |
| 6 | **Frequency** | How many times the average person has seen the ad. Rising = fatigue risk |
| 7 | **Reach** | How many unique people saw it |

Find these in Ads Manager: **Columns → Customise columns** and add "Messaging conversations started", "Cost per messaging conversation started", "CTR (all)", "CPM", "Frequency" and "Reach". Save it as a preset called "Message test".

## Diagnosis table

When a hook underperforms, find the row that matches:

| What you see | Likely cause | What to try |
|---|---|---|
| High CPM, normal CTR | Audience is small or competitive (e.g. busy season) | Widen location or age, try broad targeting, avoid peak weeks |
| Low CTR | Hook or visual doesn't stop the scroll | New first line, clearer visual, bigger text on image |
| Good CTR, few conversations | People are curious but the offer isn't worth a message | Make the offer more concrete; add a price or a "free" element; fix the pre-filled message |
| Many conversations, few qualified | The hook attracts the wrong people | Be more specific about who it's for ("café owners with 2+ staff") |
| Qualified chats, no demos booked | Replies are slow or unclear | Reply within 15 min; use the [scripts](whatsapp-reply-scripts.md); offer a specific time |
| Was cheap, now expensive | Creative fatigue (frequency rising) | Refresh creative on the same offer |
| No delivery | Ad rejected, budget too low, audience too narrow | Check Account Quality, raise budget, widen audience |

## Comparing themes fairly

1. **Group ads by theme** (workbook "Theme summary" sheet).
2. **Compare cost per conversation to your account average**, not to each other one by one.
3. **Ignore themes with fewer than 3 conversations** unless they've spent 2–3x target with zero.
4. **Look for 2x differences.** With small numbers, a 20% difference is noise. A 2–4x difference (like ₹686 vs ₹3,021) is a real signal.
5. **Check time periods.** If one theme ran in December and another in March, seasonality may explain the difference. Run competing themes at the same time when you can.

## Reading the case-study results

| Theme | Cost per chat | vs average (₹1,288*) | Verdict |
|---|---|---|---|
| Free hardware / no upfront cost | ₹686 | −47% | ✅ Winner |
| $89 all-in-one, named price | ₹958 | −26% | ✅ Winner (close second) |
| Transaction fees ("Still on 2%?") | ₹1,309 | +2% | ➖ Average, but high attention |
| Hidden add-on costs, no price | ₹2,136 | +66% | ❌ Retire |
| Menu insights | ₹2,241 | +74% | ❌ Retire |
| Operational pain | ₹2,611 | +103% | ❌ Retire |
| Delivery commissions | ₹3,021 | +135% | ❌ Retire |

\* ₹73.4K spend ÷ 57 conversations across the 17 boosted posts. The account's wider average across 19 messaging campaigns was ₹1,371.

**The pattern:** themes with a concrete offer (free hardware, a named price) won. Themes that only described a problem lost. That single insight shaped the Black Friday campaign.
