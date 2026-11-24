# Campaign structure and naming

## Boosted posts vs Ads Manager

| | Boosted post | Ads Manager campaign |
|---|---|---|
| **Set up** | From the Page or Instagram post: "Boost" → goal "Get more messages" | Ads Manager → Create → Engagement (or Leads) objective → conversion location: messaging apps |
| **Speed** | Minutes | 15–30 minutes |
| **Control** | Basic audience, budget, duration | Full: placements, schedules, A/B tests, naming, end dates |
| **Frequency data** | Limited | Full (frequency, reach, CPM, by placement) |
| **Best for** | Quick, cheap message tests on organic posts | Structured tests, seasonal campaigns, scaling |
| **Our use** | Feb–Aug: 17 hook tests | Q4: Black Friday and campaigns with end dates |

**Recommendation:** start with boosted posts if you need speed and simplicity. Move to Ads Manager once you have winners to scale or need to watch frequency.

## Recommended Ads Manager structure for a message test

```
Campaign:  MSG | Hook test | Nov 2026            (Engagement objective, messaging apps)
│
├── Ad set: AU | Owners 25-65 | Broad | $15/day   (one audience for the whole test)
│   ├── Ad: T01 | Free hardware | Image A
│   ├── Ad: T02 | $89 price | Image A
│   └── Ad: T03 | Fees 2% | Image A
```

**Two ways to split budget:**

| Option | How | Pros | Cons |
|---|---|---|---|
| **A. One ad set per hook** | Each hook gets its own ad set with the same budget | Every hook gets equal spend, so the comparison is fair | More ad sets to manage |
| **B. All hooks in one ad set** | Meta decides which ad gets spend | Simple, finds a winner fast | Meta may starve some hooks of spend early, so they're never really tested |

For a true message test, use **option A** (or Meta's built-in A/B test tool). Use option B later, when you're scaling known winners.

## Naming convention

Use the same pattern everywhere so you can filter and sort in Ads Manager and in your results log.

```
Campaign:  [Objective] | [Purpose] | [Month Year]
Ad set:    [Location] | [Audience] | [Targeting] | [Daily budget]
Ad:        [Test ID] | [Theme] | [Creative variant] | [Run]
```

| Level | Example |
|---|---|
| Campaign | `MSG \| Hook test \| Nov 2026` |
| Ad set | `BNE \| Cafe owners 25-65 \| Broad \| $15/day` |
| Ad | `T04 \| Free hardware \| Video B \| Rerun 1` |

**Theme names must match exactly** in Ads Manager, the test plan and the workbook, or the theme summary won't add up.

## Settings to keep identical across a test

| Setting | Why |
|---|---|
| Objective and performance goal | Different goals = different optimisation |
| Audience and location | Different people = different costs |
| Placements | Stories and Feed cost differently |
| Daily budget per hook | Unequal spend = unfair comparison |
| Schedule (days and hours) | Weekends can cost more or less |
| Start date | Seasonality and competition change weekly |
