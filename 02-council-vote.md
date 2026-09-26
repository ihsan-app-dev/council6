# Round 2: Council Vote

Five judges each scored all 14 ideas from [`01-brainstorm.md`](01-brainstorm.md) on a 1–10 scale, each through their own lens. Each judge then ranked a top 3 and named one veto.

**Scoring rule:** a 1st-place vote is worth 3 points, 2nd place 2 points, and 3rd place 1 point. When points are tied, the total 1–10 score decides.

| Judge | Lens |
|---|---|
| Skeptical Investor | Market size, willingness to pay, renewal, durability |
| Solo Builder | Can one developer ship it in 1–3 months and maintain it alone? |
| Growth Marketer | Can you reach 3,000 payers without an ad budget? |
| Customer Advocate | Is it truly useful, and will users renew in years 2 and 3? |
| Risk Officer | Legal exposure, GDPR, platform dependency, incumbents (higher score = safer) |

## 🏆 Winner: **BorderDays**, a telework-day counter for cross-border commuters

**12 points · 3 of 5 first-place votes · average score 8.0/10 (the highest) · on all 5 judges' ballots · 0 vetoes**

## Final standings

| Rank | Idea | Points | 1st votes | Avg score | Vetoes |
|---|---|---|---|---|---|
| 🥇 1 | **BorderDays** | **12** | 3 | **8.0** | 0 |
| 🥈 2 | IndexRent | 8 | 2 | 7.0 | 0 |
| 🥉 3 | ParentDesk | 4 | 0 | 5.2 | 0 |
| 4 | Packs | 3 | 0 | 6.2 | 0 |
| 5 | DayCount | 3 | 0 | 5.8 | 0 |
| 6 | FirstDibs | 0 | 0 | 4.8 | 0 |
| 7 | Steuerbonus Inbox | 0 | 0 | 4.6 | 0 |
| 8 | SetlistPay | 0 | 0 | 4.4 | 0 |
| 9 | AskFirst | 0 | 0 | 4.0 | 1 |
| 10 | CertPack | 0 | 0 | 3.8 | 1 |
| 11 | SafeListing | 0 | 0 | 3.6 | 0 |
| 12 | CrateRadar | 0 | 0 | 3.6 | 1 |
| 13 | HutHop | 0 | 0 | 3.2 | 2 |
| 14 | PitBoard | 0 | 0 | 3.2 | 0 |

## Ballots

| Judge | 1st | 2nd | 3rd | Veto |
|---|---|---|---|---|
| Skeptical Investor | BorderDays | ParentDesk | DayCount | HutHop |
| Solo Builder | IndexRent | Packs | BorderDays | CrateRadar |
| Growth Marketer | BorderDays | DayCount | IndexRent | CertPack |
| Customer Advocate | BorderDays | ParentDesk | IndexRent | HutHop |
| Risk Officer | IndexRent | BorderDays | Packs | AskFirst |

### Raw scores (1–10)

| # | Idea | Investor | Builder | Marketer | Advocate | Risk | Total |
|---|---|---|---|---|---|---|---|
| 1 | BorderDays | 8 | 7 | 9 | 9 | 7 | **40** |
| 2 | DayCount | 6 | 5 | 8 | 6 | 4 | 29 |
| 3 | IndexRent | 5 | 8 | 7 | 7 | 8 | 35 |
| 4 | Packs | 5 | 7 | 5 | 7 | 7 | 31 |
| 5 | SafeListing | 3 | 3 | 5 | 4 | 3 | 18 |
| 6 | ParentDesk | 6 | 3 | 6 | 8 | 3 | 26 |
| 7 | Steuerbonus Inbox | 4 | 5 | 5 | 5 | 4 | 23 |
| 8 | FirstDibs | 4 | 3 | 6 | 6 | 5 | 24 |
| 9 | AskFirst | 3 | 3 | 5 | 7 | 2 | 20 |
| 10 | HutHop | 2 | 3 | 4 | 4 | 3 | 16 |
| 11 | CrateRadar | 4 | 2 | 5 | 5 | 2 | 18 |
| 12 | PitBoard | 3 | 2 | 3 | 4 | 4 | 16 |
| 13 | CertPack | 2 | 5 | 3 | 4 | 5 | 19 |
| 14 | SetlistPay | 2 | 5 | 4 | 5 | 6 | 22 |

---

## Why BorderDays won

- **Two brainstormers proposed it independently.** Agents A (professionals) and C (life admin) both arrived at it without seeing each other's work.
- **It is the only idea every judge ranked in their top 3.** It never scored below 7, and no judge vetoed it.
- **The audience is concentrated and reachable.** About 500k cross-border commuters, all under the same legal thresholds, gather in a few named places: the big "Frontaliers" Facebook groups, lesfrontaliers.lu and the GTE association. Reaching 3,000 payers means converting about **0.6%** of them.
- **Getting it wrong is expensive.** Luxembourg's 34-day rule is all-or-nothing: once you pass 34 days, every day worked outside Luxembourg becomes taxable at home. Part-days count as full days. The social-security threshold (49.9%) and Switzerland's 40% rule add more risk. A mistake can cost thousands in back-tax, which dwarfs €70.
- **Renewal is built in.** The counter resets every January. People stay cross-border commuters for years, and the rules keep changing (a circular from June 2026, automatic data exchange from 2027).
- **The MVP is small.** It is a day log, a threshold engine and a PDF export. There is no scraping and no marketplace to depend on.

## What the judges said to build: the council's combined conditions

1. **Logging that takes almost no effort and doesn't use GPS** *(Advocate, Builder).* The user sets a usual pattern once ("I telework Mondays and Fridays"). Every Friday they get one notification: "Confirm this week? ✓ / Edit". Leave background location out of v1.
2. **One number on the home screen** *(Advocate).* A big green, amber or red "X days left", with a plain-language reason.
3. **Charge for proof and alerts, not the arithmetic** *(Marketer, Investor).* The counting is free because free calculators already exist, for example Helvicare for Switzerland. The paid features are saved history, a year-end PDF proof log (the worker carries the burden of proof), threshold alerts and alerts when rules change.
4. **Present it as a log, not a tax opinion** *(Risk).* It counts only the days the user enters. Every rule shows its source, and there is a clear disclaimer.
5. **Launch timing** *(Marketer).* Put a free, no-signup "Compteur 34 jours" web counter live in **December**, just before the January reset. Co-promote it with lesfrontaliers.lu and the GTE newsletter. Offer a founding-member price of €49 for the first year.
6. **Plan for employers** *(Investor).* If employers' HR tools become the official record, switch to selling employer seats to Luxembourg banks and Big4 firms. A single deal there can bring hundreds of seats.

**Suggested sequencing (synthesis, not a council vote):** launch with **France → Luxembourg only**. It is the largest segment and needs one rule set. Add BE-LU, DE-LU and FR-CH once there are paying users. This addresses the Builder's main worry about maintaining four legal rule sets that keep moving.

## Main risks the council raised

- **Employer tools:** Luxembourg employers already track days internally. Individual commuters have to see the count as *their own* liability, or the consumer market shrinks.
- **HR platforms bundling it:** HR tools such as Lucca could add the feature for free.
- **Rule upkeep:** thresholds and interpretations change, so rule maintenance never ends.
- **Logging discipline:** if users forget to log, they see no value. That is why the weekly confirm-once flow matters.

## Runner-up: IndexRent (French small-landlord rent indexation autopilot)

The Solo Builder and Risk Officer both ranked it 1st. It has the lowest maintenance and the fewest ways to fail: public INSEE data, a formula fixed in law and no sensitive data. However, the Investor pointed out that the IRL index actually rose **about +0.8–1.15%** in Q1–Q2 2026, not the 3% in the brainstorm. That puts the realistic payback at about **€90 per unit per year**, which makes €70/yr a harder sell. The market is also crowded with free calculators (Bailzen, LoyerPlus, Rentila and others). If BorderDays fails validation, IndexRent is the fallback.

---

*Caveat: the facts about laws and markets above come from the agents' own web searches during this session. They are not legal or tax advice. Check them against primary sources before building.*
