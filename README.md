# Meta Ads Message Testing Kit

A simple method for finding **the message your buyers actually reply to** using small Meta Ads budgets, before you scale spend.

Built from a 2026 programme for an Australian restaurant-tech SaaS: **17 hooks tested**, and the winning "free hardware / no upfront cost" hook got conversations **~4x cheaper** than the weakest theme (₹686 vs ₹3,021 per chat). The winner then led the Black Friday campaign. [Read the case study (PDF)](https://shahshivani120-lab.github.io/case-studies/Meta_Ads_Case_Study_Shivani_Shah.pdf).

---

## The idea

Most ad tests change too many things at once. Here, **every ad is a test of one message**. Keep the objective, audience and budget steady, change only the hook, and the cost per conversation tells you how well that message worked.

It suits B2B and SMB offers where buyers won't fill in a form but **will reply to a message** (WhatsApp, Messenger, Instagram DM).

## The method

1. **Pick one objective and keep it.** Messaging conversations work well for busy owners and small-business buyers. Every result is a real conversation.
2. **List 5–8 message themes.** For example: free or no upfront cost, a named price, hidden costs of the current tool, fees, a specific pain, a time saving, a competitor comparison.
3. **Write one hook per ad.** One theme, one first line, one offer. Plan them in [`hook-test-plan.csv`](hook-test-plan.csv).
4. **Run small and steady.** A fixed small daily budget per ad (we used ₹280–₹500 a day), long enough to get several conversations. A weak hook never burns much money.
5. **Log every result** in [`results-tracker.csv`](results-tracker.csv) and calculate cost per conversation by theme.
6. **Keep, re-run or retire.** Winners get re-run and tracked; losing themes are dropped.
7. **Watch for fatigue.** In a small audience the same people see the ad again and again. When a re-run costs much more than its first run, refresh the creative, not the offer.
8. **Scale the winning offer** into a structured campaign with a set end date (for example a seasonal promotion).

## What we learned (and what usually holds)

| Lesson | Evidence from the programme |
|---|---|
| **Lead with the offer, not the problem.** | Pain-only hooks ("long hours", "wrong orders") got 2 chats from 3 ads at ₹2,611 each. Free hardware got 17 chats at ₹686. |
| **Put a number on it.** | A named "$89 all-in-one" price ran at ₹958 per chat; the same idea without a price cost ₹2,136. |
| **Test small, then scale.** | Small daily budgets were enough to see which hooks worked before the Black Friday budget went in. |
| **Winners wear out.** | Re-running a winner 8 days later: +8% cost. Three months later: +160%. |

## Reading your results

- **Cost per conversation by theme** is the main number. Compare themes, not single ads.
- **Conversations, not clicks.** A cheap click that never replies isn't a win.
- **Re-run change %** = (re-run cost − first-run cost) ÷ first-run cost. Above ~50% means fatigue.
- **Next step:** track which conversations become demos and customers, so you can report cost per customer, not just cost per message.

## Files in this repo

- [`hook-test-plan.csv`](hook-test-plan.csv): plan themes, hooks, offers and budgets before launch
- [`results-tracker.csv`](results-tracker.csv): log each ad and compare cost per conversation (example rows from the case study)
- [`hook-ideas.md`](hook-ideas.md): theme list and hook patterns to start from

---

**Want me to run this for you?** I run Meta and Google Ads for B2B and SaaS brands.
📅 [Book a free 20-minute call](https://calendly.com/shahshivani120) · 🌐 [Portfolio](https://shahshivani120-lab.github.io/) · 💼 [LinkedIn](https://www.linkedin.com/in/shivanishah-growth)

*Made by [Shivani Shah](https://github.com/shahshivani120-lab). Free to use and adapt.*
