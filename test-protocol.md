# Test protocol

How much to spend, how long to run, what to check every day, and when to call a winner or a loser.

## 1. Set your target

Before launching, decide what a "good" cost per conversation is. Work back from what a customer is worth:

```
Customer value (first year)        e.g. $1,200
× Close rate from conversation     e.g. 5%  (1 in 20 chats becomes a customer)
= Value of one conversation        $60
× Share you're willing to spend    e.g. 50%
= Target cost per conversation     $30
```

If you don't know your close rate yet, start with your **account average** cost per conversation as the benchmark and aim to beat it. The [workbook](message-testing-workbook.xlsx) "Budget planner" sheet does this maths for you.

## 2. Budget per hook

Each hook needs enough spend to produce a few conversations, or you're judging noise.

```
Budget per hook  = target cost per conversation × conversations needed to judge
Test length      = budget per hook ÷ daily budget per hook
```

| Conversations per hook | What you can conclude |
|---|---|
| 0–2 | Almost nothing, unless spend is already 3x target with zero chats |
| 3–5 | Rough signal. Good enough to drop clear losers |
| 6–10 | Reasonable signal for comparing themes |
| 15+ | Confident comparison |

**Example:** target ₹1,000 per chat, 5 chats to judge → ₹5,000 per hook. At ₹400 a day, that's about 12–13 days per hook. In the case study we used ₹280–₹500 a day per ad.

## 3. How long to run

- **Minimum 3–4 days** before judging anything. Delivery is uneven in the first days.
- **Avoid editing ads mid-test.** Big edits restart Meta's learning and reset your comparison.
- **"Learning limited" is normal** for small message tests. Meta wants around 50 results a week to exit learning; small tests rarely get there. You're comparing hooks against each other, so that's fine, as long as every hook runs the same way.
- Run all hooks in a test **at the same time** so they face the same competition and season.

## 4. Daily check (5 minutes)

| Check | Where | Action if wrong |
|---|---|---|
| Is every ad delivering? | Ads Manager → Delivery column | Fix rejected or "not delivering" ads |
| Spend on track? | Amount spent vs plan | Check budgets and dates |
| Conversations arriving? | Results column + your inbox | Test the message flow yourself |
| Every chat answered within 15 min? | Inbox | Assign cover; fix the greeting |
| Any comments on the ad? | Ad preview → comments | Reply, or hide spam |
| Anything weird? | Frequency, CPM | See the [analysis guide](analysis-guide.md) |

## 5. Decision rules

Use these to stay objective. Write the decision in the "Decision" column of the workbook.

| Situation | Decision |
|---|---|
| Spent **2x target** with **0 conversations** | **Stop.** Retire the hook (or rewrite it completely) |
| Spent **3x target**, cost per conversation **over 2x target** | **Stop.** Retire |
| **5+ conversations**, cost **under target** | **Keep.** Candidate winner; re-run with fresh creative to confirm |
| Cost within ±30% of target after 5+ conversations | **Keep testing** or try a sharper hook in the same theme |
| Two ads on the same theme both beat target | **Winning theme.** Move it into your main campaign |
| Cost was good, then rose 50%+ on a re-run | **Fatigue.** Refresh creative, keep the offer (see [fatigue guide](fatigue-and-scaling.md)) |

## 6. Judge themes, not ads

A single ad can get lucky. Add up all ads in a theme:

```
Theme cost per conversation = total spend on theme ÷ total conversations on theme
```

The workbook's "Theme summary" sheet does this automatically with `SUMIFS`, and compares every theme to your account average.

## 7. Then check quality

Cheap conversations from the wrong people aren't a win. For each theme, track:

| Quality metric | How |
|---|---|
| % qualified | Of conversations, how many fit your customer profile? |
| % to demo/call | How many booked a demo or call? |
| Cost per qualified lead | Spend ÷ qualified conversations |
| Cost per customer | Spend ÷ customers (the number that matters most, once you have it) |

A theme with a slightly higher cost per conversation but twice the qualified rate is the real winner.
