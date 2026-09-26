# Round 1: Brainstorm (14 ideas)

**Goal:** 3,000 paying subscribers at €70/year (or €8/month), which comes to about **€210k/year**. It should be simple and useful, a solo developer should be able to build the MVP in 1–3 months, and customers should keep paying every year.

Five independent brainstorm agents each took a different angle and started from a clean slate:

| Agent | Lens |
|---|---|
| A | Professionals & work life |
| B | Hobbies & passion communities |
| C | Everyday life admin (EU) |
| D | Tiny businesses & creators |
| E | Contrarian / non-obvious |

> Agents A and C both proposed **BorderDays**, although neither saw the other's work.

---

## 1. BorderDays: a telework-day counter for cross-border commuters *(Agents A + C)*
- **What:** You log each day with one tap (optionally detected by location). The app shows how many work-from-home days you have left before your tax or social-security position changes, and it produces a year-end PDF log.
- **Who pays:** People who live in France, Belgium or Germany and work in Luxembourg (about 120k French residents alone), plus people who live in France and work in Switzerland (about 230k). That is roughly 500k people in total.
- **Why €70/yr:** In Luxembourg, working more than 34 days a year outside the country makes *all* of those days taxable at home. Part-days count as full days, and a circular from June 2026 added pro-rata rules. Switzerland has a 40% telework threshold, and social-security cover (A1) is lost above 49.9%. Automatic data exchange starts in 2027. Getting it wrong can cost thousands in back-tax, and the counter resets every January.
- **Reach:** Large "Frontaliers" Facebook groups, lesfrontaliers.lu, and SEO for searches like "compteur 34 jours télétravail" and "Grenzgänger Homeoffice Tage". Also the cross-border workers' association GTE, tax preparers, and employer plans sold to Luxembourg banks and Big4 firms.
- **MVP:** Daily log, a rules engine for each country pair (FR-LU, BE-LU, DE-LU, FR-CH), a forecast of days left, a PDF export, and alerts when rules change.
- **Risk:** It is a narrow market (about 0.6% conversion needed). HR tools could bundle it, background location on iOS is unreliable, and there is liability if a count is wrong.
- **Alternatives:** Spreadsheets, employer portals, and trackers made for digital nomads.

## 2. DayCount: a Schengen 90/180 and tax-residency tracker for part-year residents *(Agent E)*
- **What:** It records which country you sleep in each night. It then shows how many Schengen days you have left and how close you are to the 183-day tax-residency threshold in Spain, France or Portugal, and to the UK's residence test.
- **Who pays:** British, American, Canadian and Australian retirees with second homes in Spain, France or Portugal who spend 3–6 months a year there.
- **Why €70/yr:** Since the EU Entry/Exit System (EES) started in late 2025, borders record every entry and exit, so overstays lead to fines or bans. Accidentally becoming a tax resident costs thousands. These people plan their stays every year.
- **Reach:** English-language expat papers (The Connexion, Olive Press, Sur in English), Facebook groups for Brits in Spain and France, referral deals with gestors and estate agents, and SEO for "90/180 calculator EES".
- **MVP:** Per-night log from background location, a forward planner, tax-residency counters, alerts, PDF evidence and a view for couples.
- **Risk:** Free 90/180 calculators already exist, there is liability for accuracy, and background location drains the battery.
- **Alternatives:** Free Schengen calculators (immigration only) and Monaeo (tax only, expensive).

## 3. IndexRent: a "never lose rent money" autopilot for small landlords *(Agent D)*
- **What:** It tracks when each of your leases can legally be indexed (the IRL index in France) and when charges must be reconciled. It sends the calculated increase with a ready-made letter, keeps a deadline calendar, and prepares a yearly income summary for the tax return (French form 2044).
- **Who pays:** French landlords aged 45–70 who manage 1–3 units themselves. Germany and Belgium would follow.
- **Why €70/yr:** In France a missed IRL indexation cannot be backdated. On €750 rent at 3%, that is about €270 a year per unit, lost for good and compounding.
- **Reach:** SEO for "calcul révision loyer IRL", which people search every quarter, using a free calculator to capture emails. Also landlord Facebook groups, UNPI (the French landlords' association), and YouTubers who cover property investing.
- **MVP:** Lease input, automatic IRL updates from INSEE, reminders with PDF letters, a deadline calendar and the annual summary.
- **Risk:** Free calculators and cheap all-in-one tools exist. It has to be sold as "stop losing money", not as "management software".
- **Alternatives:** Rentila, Smartloc, Qalimo, agencies charging 7–8%, and spreadsheets.

## 4. Packs: prepaid session bundles for solo coaches *(Agent D)*
- **What:** Coaches sell and track 10-session packs. Each client gets a live "5 of 10 left" link, and a payment link is sent automatically when a pack runs low.
- **Who pays:** Independent personal trainers, Pilates and yoga teachers, tutors and music teachers who currently track packs in phone notes or WhatsApp.
- **Why €70/yr:** Each renewal that slips through costs €300–600, and the tool removes the awkward "you owe me" conversation. Coaches use it after every session.
- **Reach:** Fitness creators as affiliates, Facebook groups for tutors and music teachers, a free template that upsells to the app, and gyms that rent space to freelancers.
- **MVP:** Client list, one-tap "session used", a balance page for clients, low-balance nudges with a Stripe or SumUp payment link, and a simple report.
- **Risk:** Booking suites (Fresha, Mindbody, Teachworks) already include packs, so this must stay radically simpler.
- **Alternatives:** Booking suites at €20–60/month, and paper punch cards.

## 5. SafeListing: EU product-safety paperwork for handmade sellers *(Agent D)*
- **What:** It generates the product-safety information, labels and packaging-recycling registrations (EPR) that EU rules (GPSR) require on every listing, and keeps them up to date.
- **Who pays:** Etsy, Vinted Pro and Amazon Handmade sellers with 20–300 listings of candles, soap, jewellery or kids' items.
- **Why €70/yr:** GPSR has applied since December 2024. Listings without the right information get removed, and a consultant costs €300 or more. France and Germany add yearly EPR and LUCID declarations.
- **Reach:** Etsy seller groups, r/EtsySellers, SEO for "GPSR Etsy template", affiliate deals with craft YouTubers, and craft fairs.
- **MVP:** A wizard by product type, safety text and labels, a PDF technical file, a deadline calendar and bulk CSV export.
- **Risk:** Legal liability if the guidance is wrong, and sellers may see it as a one-time setup and cancel after year one.
- **Alternatives:** Consultants, Lizenzero (packaging only) and ChatGPT.

## 6. ParentDesk: an admin inbox for an aging parent's paperwork *(Agent C)*
- **What:** The family photographs or forwards the parent's letters. AI explains each one in plain language and pulls out deadlines. It also tracks German long-term care budgets so none of them expire unused.
- **Who pays:** People aged 45–60 living more than an hour from a parent who has a care grade (Pflegegrad 1–3), sharing the work with siblings.
- **Why €70/yr:** The monthly care relief allowance (Entlastungsbetrag) is €131/month (€1,572 a year). About 50% of it goes unused, and over €2bn lapses every year. It also covers the one-month deadline to object to a care-grade decision and the roughly €3.5k respite-care budget. Families keep paying for as long as the parent needs care, often 4–8 years.
- **Reach:** SEO for "Entlastungsbetrag verfällt" ("relief allowance expiring"), caregiver Facebook groups, home-care providers paying referral fees, and employer caregiver benefits.
- **MVP:** Photo, PDF or WhatsApp intake, plain-language summaries with deadlines, a shared family timeline, a care-budget tracker, letter templates, and a document vault.
- **Risk:** It handles health data (GDPR Art. 9), which is a trust and security burden. Families stop paying when the parent moves into a care home or dies, and parents may not cooperate.
- **Alternatives:** nui (free, funded by selling care boxes), free care counselling, and paper folders plus WhatsApp.

## 7. Steuerbonus Inbox: year-round capture of German household tax deductions *(Agent C)*
- **What:** You forward invoices from tradespeople, cleaners and gardeners, plus your annual service-charge statement. It extracts the labour share that is deductible under §35a of German tax law and produces totals ready for the tax portal (ELSTER).
- **Who pays:** German dual-income homeowners, and tenants in managed buildings, who file their own taxes.
- **Why €70/yr:** 20% of labour costs comes straight off the tax bill. Tenants almost never claim the deductible part of their service charges (often €50–200 on its own). A typical user finds €150–400 a year.
- **Reach:** r/Finanzen, personal-finance newsletters, SEO during tax season, finance YouTubers, cleaning platforms such as Helpling, and tax advisors.
- **MVP:** An inbox address, AI extraction of the labour share, a service-charge parser, running totals against the caps, and an ELSTER export.
- **Risk:** The value is invisible for 11 months, which invites churn. Tax apps (WISO, Taxfix) could copy it, and it must not count as regulated tax advice.
- **Alternatives:** WISO and Taxfix (year-end only), wage-tax help associations at €100–300 a year, and a shoebox.

## 8. FirstDibs: registration alerts for city parents *(Agent E)*
- **What:** It watches the booking pages of swim courses, holiday camps, sports clubs and music schools, and alerts parents within minutes when registration opens or a waitlist place frees up.
- **Who pays:** Parents of 3–12-year-olds in cities where places are scarce (Munich, Berlin, Hamburg, Amsterdam, Zurich). Beginner swim courses (Seepferdchen in Germany) have huge waitlists, and camps sell out in minutes.
- **Why €70/yr:** There are 4–5 school holidays a year, each a childcare crisis, and missing a camp costs days of leave. Families stay for roughly 10 years per child.
- **Reach:** One city at a time: class WhatsApp groups, parent Facebook groups, Nebenan.de, parent-council newsletters, and flyers before registration opens. A free month for each referral.
- **MVP:** A curated list of about 150 providers per city, page-change monitoring, user-submitted pages, push and SMS alerts, a calendar of opening dates, and age filters.
- **Risk:** The local data does not scale by itself, each city has to be seeded, and providers may block scraping.
- **Alternatives:** Visualping and Distill, but parents do not know which 40 pages to watch. The curated list is the product.

## 9. AskFirst: a scam hotline for parents, paid for by their adult children *(Agent E)*
- **What:** A WhatsApp or SMS number where an older parent forwards suspicious texts, screenshots, letters or call descriptions and gets a plain-language verdict in seconds. The adult child is alerted if the risk is high.
- **Who pays:** Adults aged 40–60 who live far from parents over 70.
- **Why €70/yr:** A single scam costs thousands. Scams keep evolving, and the service works well as a gift.
- **Reach:** Mumsnet's "Elderly parents" board, carers' groups, police fraud talks, U3A and church groups, and bank partnerships.
- **MVP:** A WhatsApp Business number with SMS fallback, an LLM plus reputation checks, large-font replies, family alerts, and a weekly "scam of the week" message.
- **Risk:** Meta, banks and Norton are adding free AI scam warnings. A wrong "safe" verdict would be a disaster, so it must lean cautious.
- **Alternatives:** Meta's built-in warnings, scamchecker.app and Norton Genie, which each cover a single channel.

## 10. HutHop: Alpine hut-trek availability and cancellation alerts *(Agent B)*
- **What:** It finds runs of consecutive free nights across a multi-hut trek and alerts you when a cancellation fills a gap.
- **Who pays:** Members of the German, Austrian and Swiss Alpine clubs (DAV, ÖAV, SAC) and international hikers planning 4–10-night treks (Tour du Mont Blanc, Alta Via 1, Stubaier Höhenweg, Haute Route).
- **Why €70/yr:** A trek costs €1–3k, and one blocked night ruins it. Pitched as a "season pass".
- **Reach:** SEO for "Stubaier Höhenweg Hütten ausgebucht" and "TMB refuges full", TMB Facebook groups, r/Dolomites, Alpine club newsletters, and hiking bloggers.
- **MVP:** Ingest data from hut-reservation.org and montourdumontblanc.com, a route solver, gap watching, and alerts with deep links (no auto-booking).
- **Risk:** It is seasonal, so people pay monthly and cancel. The platforms may block polling. *Agent E independently considered and cut this idea:* TMB Trail Guide already charges $5/month and most people do only one trek a year.
- **Alternatives:** DAV Bettencheck (no alerts), TMB Trail Guide ($5/month), HutAlert (US, $19/month).

## 11. CrateRadar: alerts for records on your Discogs wantlist across EU marketplaces *(Agent B)*
- **What:** You import your Discogs wantlist once. It alerts you when those exact pressings appear on eBay, Kleinanzeigen, Vinted, Marktplaats or Leboncoin below the Discogs median price.
- **Who pays:** EU record collectors aged 30–55 with wantlists of 200+ items who spend €100+ a month.
- **Why €70/yr:** One underpriced record pays for the year, and wantlists never shrink.
- **Reach:** r/vinyl, the Discogs forums, collector YouTubers, genre forums, and record fairs.
- **MVP:** Discogs OAuth import, fuzzy matching (catalogue number, title and image hash), a price-versus-median badge, filters and push alerts.
- **Risk:** Anti-bot measures and terms of service on the marketplaces (Vinted and Kleinanzeigen especially) mean constant scraper maintenance.
- **Alternatives:** Discogs alerts (Discogs only), keyword alert tools, and do-it-yourself open-source scripts.

## 12. PitBoard: a motorcycle trackday calendar with sell-out alerts *(Agent B)*
- **What:** A single European calendar of trackdays, filtered by rider group and lap-time class, with alerts when new dates are released or spots free up.
- **Who pays:** Amateur riders in Germany, Austria, Switzerland and the Benelux doing 5–15 trackdays a year at €250–450 each.
- **Why €70/yr:** Popular dates sell out in hours, and one secured date justifies the price.
- **Reach:** The 1000PS forum, trackday Facebook groups, affiliate deals with organisers, rider YouTubers, and flyers in the paddock.
- **MVP:** About 40 organiser scrapers, filters, alerts and a season log.
- **Risk:** A smaller market, and a lot of scraper maintenance.
- **Alternatives:** TrackDay|HUB and EuropaTrackdays (calendars without group alerts), and Facebook groups.

## 13. CertPack: a certificate wallet for freelance industrial technicians *(Agent A)*
- **What:** You photograph each safety certificate, get reminders before it expires, and send agencies a single "compliance pack" link.
- **Who pays:** Wind-turbine technicians (GWO), offshore workers (BOSIET) and rope-access technicians (IRATA) on day rates of €300–600.
- **Why €70/yr:** An expired certificate means you cannot start the job. GWO modules expire every 24 months, and these workers change agency constantly.
- **Reach:** Wind-tech and rope-access groups, r/windturbine, training centres as referral partners, and SEO for "GWO refresher near me".
- **MVP:** OCR of expiry dates, reminders, a shareable pack, a refresher-course finder, and an IRATA hours log.
- **Risk:** WINDA already stores GWO records for free, the niche is small, and it would need to expand to yacht crew and scaffolders.
- **Alternatives:** WINDA, employer systems, and the phone's camera roll.

## 14. SetlistPay: live-performance royalty claims for gigging songwriters *(Agent A)*
- **What:** It logs every gig and reminds you to submit setlists to your collecting society before the deadline, so royalties from live shows get claimed.
- **Who pays:** Songwriters who play their own songs at 30–150 gigs a year and belong to a collecting society (PRS, GEMA, SACEM, Buma, SABAM and others).
- **Why €70/yr:** Venues already pay licences, but the money only reaches writers who submit setlists. GEMA's deadline is 6 weeks, and PRS reports more than 106k performances whose royalties went unpaid.
- **Reach:** r/WeAreTheMusicMakers, songwriter groups, music colleges, and SEO for "GEMA Setliste einreichen".
- **MVP:** A song catalogue, a gig log with calendar import, setlist templates, a deadline reminder for each society, portal-ready exports, and a tracker comparing what was claimed with what was paid.
- **Risk:** Payouts from small venues can be tiny, which drives churn. The societies have no APIs, so it can only remind and format.
- **Alternatives:** Each society's own portal, Songtrust (takes a percentage), and Tour Tech SARA (US).
