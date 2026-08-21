# Business — Dog Mom Lifestyles

## What it is
A subscription box and lifestyle brand built around the bond between a woman and her dog. Founded by Jocelyn Mizrahi. Everything sold lives on dogmomlifestyles.com and is centered on the subscription box — no separate, unrelated product lines.

## Products
- **Ultimate Dog Mom Box** — $49.99/mo (Stripe/Subbly)
- **Ultimate Dog Mom VIP Box** — $69.99/mo (Stripe/Subbly)
- **Trendy Custom Dog Mom T-Shirt Club** — $22.99/mo, tracked separately from the main box revenue
- Also sold: individual items (totes, socks, sweatshirts, PJ sets, allergy-friendly treats, gift cards), Mystery/Jumbo Mystery boxes, "Adding One More Dog" add-on

## Real economics (source: "updated 2026 Expense + Revenue Profit Clean" Google Sheet, Jan–Aug 2026 actuals)

| Month | Revenue | Profit (Ult+VIP) | Subscribers |
|---|---|---|---|
| Jan | $18,446.85 | $8,196.30 | ~315 (180 Ult / 135 VIP) |
| Feb | $13,107.77 | $5,620.32 | 198 |
| Mar | $14,847.45 | $7,223.32 | 294 |
| Apr | $14,657.66 | $7,710.67 | 127* |
| May | $19,946.51 | $8,174.50 | 350 (peak) |
| Jun | $17,997.00 | $7,696.59 | 300 |
| Jul | $16,197.30 | $7,218.53 | 270 |
| Aug | $13,947.65 | $5,467.97 | 265 |

*Apr subscriber figure looks inconsistent with the Stripe breakdown in the same sheet (86 Ult + 148 VIP = 234) — logged as a data-quality gap in the sheet itself, not corrected here.

- **Average monthly revenue (Jan–Aug):** ~$16,100
- **Average monthly profit, Ult+VIP only (Jan–Aug):** ~$7,200 (~44% margin)
- **T-Shirt Club adds on top**, not included in the headline revenue/profit rows above: ~30–70 subscribers/month at $22.99, ~58–68% margin, roughly $400–$1,000/month additional profit.
- **Margins by product:** Ultimate ~36–52% depending on month (box-content cost varies monthly); VIP ~42–53% (consistently the better-margin tier).
- **Sep–Dec 2026 not yet filled in** (current date: Aug 20, 2026) — this is the holiday stretch the growth goal below is riding on.

### Retention
**Monthly churn: 10%** (confirmed by Jocelyn, tracked in Shopify). Jocelyn flagged that her Shopify numbers before August 2026 look unreliable, so **August 2026 onward is the clean baseline for churn/retention going forward**; anything before that should not be trusted for this metric.

**LTV (source: Breezeway dashboard, cross-checked across four different date ranges): roughly $200 raw, $220 to $230 AOV-adjusted, by month 12 to 15 of a subscriber's lifetime.** This resolves an earlier unit confusion (Jocelyn first said "15%," which isn't a valid LTV unit; the real figure is a dollar amount, confirmed consistent across multiple dashboard views).

### The real trend to reckon with
Subscribers peaked in May at 350, then declined to 265 by August — a 24% drop in three months. **Cause: Jocelyn got sick and stopped marketing for about three months.** This was not a demand problem, a product problem, or a channel that stopped working — it was an output gap. Both proven levers (Facebook ads, email) were simply not being pulled. This is actually a stronger position for the Q4 push than a genuine demand decline would be: the fix is resuming consistent marketing activity, not discovering a new strategy.

## What's capping the business right now
Two real constraints, not one:
1. **Traffic** — not enough new people finding the site/offer. Quantified: new-customer acquisition (5 to 12/month) is running well below the churn replacement rate (~26/month), so the subscriber base shrinks every month. See the Breezeway findings below.
2. **Jocelyn's own time/capacity** — she is stretched thin doing too much herself and needs help.

## Acquisition
- Facebook ads bring in new customers, and are also the source of the email list (see the funnel note below).
- Klaviyo runs email/retention.
- **Email list size: ~5,500 people. The list is built from the website popup, and popup traffic comes from ads.** Email is therefore downstream of paid traffic, not a parallel channel.
- **Klaviyo email open rate: ~43–44%** — well above the ~15–25% ecommerce average, meaning the list is healthy and engaged. Verified Klaviyo access is connected (account: Dog Mom Lifestyles, dogmomlifestyles.com). Click rate not yet broken out separately — logged as a smaller remaining gap, worth pulling campaign-by-campaign in a future `/review` session.
- **Last few real customers came through both paths**: Facebook ads directly, and email (people who saw an ad and converted later via Klaviyo). Not one clean channel — both are live and working. This matters for how positioning gets tested: paid reach plus a warm, high-engagement list are the two real levers already proven to convert, which is good news against the Q4 goal below.

### Breezeway dashboard findings (real data, checked across four periods: Mar–Apr, May–Jun, Jul, and Jan–Feb 2026)
- **Klaviyo is the dominant last-click attribution channel in every single period shown**, consistently ahead of Facebook Ads and Google Ads combined. **Resolved by Jocelyn: this is not a separate channel. The email list is built from the website popup, and the popup traffic comes from ads.** So the real funnel is: Facebook ads drive traffic, the popup captures the people who don't buy on the spot, Klaviyo closes them later and takes the last-click credit. Facebook is doing the sourcing that Klaviyo gets attributed for.
- **Strategic consequence of the above: ad spend and email are not independent levers.** Cutting ad spend starves the email list at the same time, because ads are what fill it. The May–June drop to $348 in ad spend did not just lose immediate conversions, it stopped refilling the list that does the closing, which compounds the decline instead of merely pausing it. Any plan that treats "push email harder" as an alternative to ad spend is wrong on this business; email volume is downstream of ad volume.
- **New-customer counts are critically low**: 12 (Mar–Apr), 5 (May–Jun), 7 (Jul). **Confirmed by Jocelyn: this dashboard counts NEW customers, not subscription renewals.**
- **The single most important number in this brain: acquisition is running far below the replacement rate.** At roughly 265 subscribers and 10% monthly churn, about 26 subscribers are lost per month. Bringing in 5 to 12 new customers means a net loss of roughly 15 to 21 subscribers every month. This is not slow growth, it is a shrinking base, and it explains the 350 (May) to 265 (Aug) decline precisely. **Break-even is roughly 26 new customers per month. Any growth plan has to clear that number before a single subscriber of actual growth is added.**
- **Ad spend collapsed in the same window**: $2,702.70 (Mar–Apr) → $348.34 (May–Jun) → $1,352.49 (Jul). This lines up with and quantifies the "Jocelyn got sick, marketing paused" story above.
- **ROAS in this window is extremely volatile** (10.19, 43.79, 1.59 across the three periods) and based on very small order counts, so treat as directional/noisy, not a stable number to plan against.
- 1-day purchase rate stays consistently high across every period shown (88 to 93%), reinforcing the existing "83% buy right away" figure in `offer.md`.

## Where she's trying to go
Goal: reach $70,000/month by the end of the year, riding the holiday season. Against current actuals (~$16,100/month average) this is roughly a 4x jump in about 4 months.

**Pressure-tested against the real acquisition numbers, this goal is not currently achievable on the present trajectory, and the brain should say so plainly rather than plan around it.** At roughly $52 to $58 blended revenue per subscriber, $70,000/month needs somewhere near 1,200 to 1,300 active subscribers. The base is 265 and shrinking by 15 to 21 per month. Closing that gap by December would require adding roughly 950 net subscribers in four months, which means clearing the ~26/month churn replacement AND adding ~240 net new per month on top, against a current run rate of 5 to 12 new customers per month. That is a 20x+ change in acquisition, not a push.

What IS realistic and worth planning first, in order:
1. **Get back above the churn replacement line (~26 new customers/month).** Until acquisition clears that, every other effort is being poured into a leaking bucket. This is the whole ballgame right now.
2. **Restart consistent ad spend**, since ads feed both direct conversions and the popup that builds the email list. The proven levers were switched off, not broken.
3. **Improve the 1.2% conversion rate**, which multiplies the value of every visitor without buying more traffic.
4. **Turn on the Ultimate → VIP upgrade path**, which raises revenue per existing subscriber and does not depend on acquisition at all.

A more honest Q4 target would be rebuilding to the May peak (350 subscribers) and establishing consistent positive net growth, then setting a bigger number from a base that is actually growing. **Do not tell Jocelyn the $70k goal is on track. Tell her what it would actually take, and what the better near-term goal is.**
