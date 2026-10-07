# FWD 101 — Pavel’s input

**Advertising, monetization, and the sections Pavel owns**

**Author of this draft:** assembled from Pavel’s Cursor chats and the working files those chats produced  
**For:** Pavel, so he can correct it and then fold the finished text into `Forward Handle (FWD) 101.md`  
**Do not paste this file in as-is.** Boxes marked **Pavel confirms** are blanks only he can close.  
**Original company guide:** not edited  
**Data window:** chats and dashboards through early September 2026. Today is 7 October 2026, so every dollar figure below is historical, not a live number.

---

## How to use this file

The company guide asks Pavel to expand or correct:

- **§2 How FWD Makes Money**
- **§6 BDSMLR**, the monetization part
- **§14 Advertising Operations**
- **§17** the Advertising / Revenue part of the monthly owner update

Pavel’s own later description of his job is wider than “run the ads.” In the planning work with Allen and Simon he stated that he owns marketing, SEO, advertising, social signals, brand reputation, community communication, ad-network negotiations, pricing and tiers, the monetization strategy, and the tracking dashboards. Allen was not in the ad-network negotiations. Simon builds. Ezra needs a briefing before any user-facing monetization post goes live.

Each section below is written in the voice of the company guide, so a corrected version can be copied across. Notes in **Pavel confirms** stay here until he answers them.

Three kinds of statement are kept separate:

1. **How it works today** — what the properties actually sell and what the dashboards measure.
2. **What was agreed with Allen and Simon** — the plan for the new BDSMLR / RelayOS subscription. This is a plan, not live revenue.
3. **Explored and not launched** — chat-subscription ideas, SEO programs, advertiser cleanup lists.

Revenue models from the simulations ($50k/month, $193k/month, and similar) are **not** in this draft. Pavel explicitly did not want those treated as targets.

---

## What was read, and what was left out

33 chat transcripts in `101` were reviewed.

**Used for this draft** (advertising, monetization, Pavel’s operating work):

| Chat | What it is |
| --- | --- |
| BDSMLR monetization strategy (the long 2026 thread) | Premium history, data collection, IRC / RelayOS framing, payment processors, Pavel’s constraints |
| Stress-test and April 20 call | Decisions with Allen and Simon; Pavel’s statement of his own role |
| Product, tiers, blog posts (May–June 2026) | What free vs paid means on BDSMLR; ad rule for anonymous vs logged-in users |
| ISC and BDSMLR advertiser ratings (August 2026) | Who pays, who is dead, Revive inventory |
| Revive connection and daily stats export (August 2026) | How Ad Ops reads the ad server; direct-deal CPM vs Revive eCPM |
| Active banner / tabunder / interstitial link pulls | What is actually serving |
| PnL build and the accountant email (July 2026) | Company-level revenue picture, and the gap versus the books |
| BDSMLR GA4 events and Looker (August–September 2026) | Logged-in vs anonymous reporting |
| ISC chat monetization (March 2026) | Explored, not launched |
| ISC SEO and RelayOS IRC SEO | Traffic work Pavel ran; not yet an operating program in the company guide |

**Read and left out** because they are not FWD advertising or Pavel’s company role: university coursework, personal chats, a personal health file, a family Android project, and unrelated file-sorting or laptop troubleshooting.

---

# Draft for §2 — How FWD Makes Money

Advertising on **isexychat.com (ISC)** is the company’s main income. BDSMLR is a second, much smaller line: a mix of display and affiliate advertising plus the BDSMLR shop (PayPal). A new subscription product was designed with Allen and Simon. It is not the revenue the company is collecting today.

## Two properties, two very different ad businesses

FWD is the publisher. Advertisers pay FWD to reach people on the sites. The ad server is **Revive Adserver (hosted)**. Revenue is not one rate. Some partners pay a direct CPM. Many pay **revshare** or as affiliates, so the money shows up in FWD’s own dashboards, not as a reliable figure inside Revive.

### ISC — the advertising business

ISC is a live advertising operation with years of daily history (the dashboard starts 1 January 2019).

As of the August 2026 advertiser review:

- Recent run-rate was on the order of **$1,600 per day**.
- Revive publisher **IsexyChat** was about **99.4% filled**.
- About **46 million ad requests** in a recent 30-day window, with only a few hundred thousand unfilled.
- Formats in the dashboard: **banners, tabs / tabunders, nav, buttons, interstitials**.

The book is concentrated. In the 90 days ending mid-August 2026, two partners were most of the money:

| Rank | Partner | Last 90 days (to ~18 Aug 2026) | About $/day |
| --- | --- | --- | --- |
| 1 | ReactAds / TP Media | $54,536 | $606 |
| 2 | GSM (Adnium) | $52,273 | $581 |
| 3 | 4thWhale | $18,404 | $204 |
| 4 | Chaturbate | $8,547 | $95 |
| 5 | Technius / Stripchat | $5,797 | $64 |
| 6 | StripCash | $3,045 | $34 |

Pavel’s working keep-list for ISC was: **ReactAds / TP Media, GSM (Adnium), 4thWhale, Chaturbate, Technius / Stripchat, StripCash.** Everything else was either fading, already dark, or a candidate to stop. That cleanup was analyzed in Revive. It had not been confirmed as finished in the chats.

Direct CPM deals Pavel named for daily tracking: **React Ads, Grand Slam Media (Adnium / GSM), 4th Whale, Stripchat / Technius.** Example from the July 2026 React Ads tabunder check: the **deal CPM is $10**. Revive’s own eCPM is a calculated field and must not be used as the invoice rate.

### BDSMLR — advertising plus the shop

BDSMLR’s ad dashboard runs from 1 February 2021. It used to be a real ad business. It is not that business anymore.

| Period | What the dashboard showed |
| --- | --- |
| About 2021–2024 | On the order of **$98k per year** |
| Lifetime through 20 Aug 2026 | About **$469k** |
| 2025 | About **$57k**, after TwinRed (about 30% of lifetime revenue) stopped in May 2025 and GrandSlam stopped in April 2025 |
| 2026 year to 20 Aug | About **$18k**, a pace near **$27k** for a full year |
| Last 90 days to 20 Aug 2026 | About **$80 per day** |

Of that last-90-day money, **Shop + Technius + Affiliatly (Oxy-Shop) were about 97%.** Exoclick was still reporting and was remnant (about $0.80/day). ReactAds and 4thWhale, the partners that pay on ISC, are not a live BDSMLR revenue line. A small ReactAds test on BDSMLR was quiet by late August (hundreds of impressions in the last week, not a business).

**BDSMLR Shop (`shop.bdsmlr.com`) is internal.** It is tracked in the BDSMLR Google Sheet. It is not a Revive advertiser, and it does not belong in the ISC report. In the last 90 days of that review it was the largest BDSMLR line, about **$44/day**. The shop is PayPal ecommerce: the old “Ad-free BDSMLR” subscription and related store activity. On the customer’s card statement the company name is **Forward Handle LLC**. The public product name on the shop has been “Ad-free BDSMLR subscription.”

Revive publisher **BDSMLR** was about **95.5% filled** in late July–August 2026, with some interstitial / close-tabunder requests already empty. So the problem on BDSMLR is demand (who will pay for the traffic), not a shortage of ad slots.

### Older BDSMLR premium, already in decline

Before the RelayOS plan, BDSMLR premium was **$20/month to remove ads** and nothing else. Pavel was clear: ad removal must not be the thing the company sells. It can only be a side effect of a subscription that has real features.

Measured premium results from the 2025–early 2026 data pull:

| Month | Premium revenue | Orders | Ad revenue used in that study |
| --- | --- | --- | --- |
| Sep 2025 | $3,035 | 139 | $3,600 |
| Oct 2025 | $3,123 | 142 | $3,600 |
| Nov 2025 | $1,812 | 83 | $3,600 |
| Dec 2025 | $2,023 | 72 | $3,600 |
| Jan 2026 | $1,100 | 48 | $3,600 |
| Feb 2026 | $850 | 35 | $3,600 |

Premium fell about **72%** across that window. Even in December 2025, when the site was up, monthly churn on that product was still about **68%**, and the longer read of the product was about **84% monthly churn** and about **1.2 months** of subscriber life. People paid, got ad removal only, and left. PayPal has processed that shop product for years. Pavel’s note at the time: chargebacks on it were low, and PayPal had not challenged that specific product.

## Company totals, and why two sets of numbers exist

In July 2026 Pavel built an updated P&L from the ISC dashboard plus the expense file then on hand.

| | Jan 2025 – July 2026 (19 months) | Share |
| --- | ---: | ---: |
| ISC advertising | $751,670 | 95.3% |
| BDSMLR PayPal ecommerce | $36,847 | 4.7% |
| Combined revenue in that build | $788,517 | |
| Expenses then recorded | $107,143 | |
| Net in that build | $681,374 | |

That profit margin is **not safe to repeat to Sakura.** Expense records in the file stopped around July 2025. Later months were revenue-only, so the margin is overstated. Melissa’s books are the financial record. This P&L was an Ad Ops view.

2026 dashboard revenue (mostly ISC) rose hard in the spring and then eased:

| Month 2026 | Dashboard revenue |
| --- | ---: |
| January | $33,512 |
| February | $29,998 |
| March | $35,508 |
| April | $45,275 |
| May | $52,536 (highest month in that series) |
| June | $46,349 |
| July, through the 23rd | $30,952 |

The accountant’s email the same week used different figures for the same months: March $16,619, April $34,167, May $25,983, June $44,219, July $31,349. She asked whether the next months would stay near June. A projection of about **$45k per month** for August–December 2026 was drafted from the dashboard, not from her deposit list.

**Pavel confirms:** which series Melissa should use in the owner update (dashboard billings, bank deposits, or something else), and what the gap is. Do not put both into §2 as if they were the same number.

A finance allocation used for that P&L (FWDAD-375) split Pavel **90% ISC / 10% BDSMLR** and Rigela **75% ISC / 25% BDSMLR**. That matches “ISC is the job, BDSMLR ads are the smaller book.” It is an allocation, not a job description.

**Pavel confirms:** whether that split still describes where the time goes.

## What this means for the sentence already in the guide

The guide is right that advertising is a major source of income, that BDSMLR also has premium, and that the new BDSMLR experience has less advertising and a weaker premium pitch than the old one.

The missing scale is:

- **ISC advertising is the company.** Protecting ReactAds, GSM, and 4thWhale matters more than any new BDSMLR idea.
- **BDSMLR display advertising is a remnant plus a shop.** Rebuilding it means taking partners that already pay on ISC and giving them BDSMLR inventory, not adding more dead affiliate tabs.
- **The old $20 ad-free membership failed as a product.** The replacement is a feature subscription on RelayOS. It is designed. It is not the current P&L.

## Planned BDSMLR subscription (not current revenue)

Agreed direction after the 20 April 2026 call with Allen and Simon, and the tier work through June:

- **Anonymous visitors see ads. Logged-in users, free or paid, do not.** Ad-free is therefore not a reason to subscribe. Pavel corrected the tier matrix on this point himself.
- The paid product is a **RelayOS subscription** (IRC bouncer / offline messaging and power-user tools), bought on a neutral property under **Forward Handle LLC**. The receipt must not describe an adult purchase. BDSMLR-only perks stay on BDSMLR and are not advertised on the RelayOS pricing page.
- One subscription at the RelayOS level. Premium on RelayOS is premium on the connected properties. Users have a tenant account and a separate billing account, linked afterwards.
- Offline messaging is **same-network only** (BDSMLR to BDSMLR). Cross-network messaging was rejected.
- Free logged-in users get a **quota** of offline messages. Subscribers get unlimited. Allen’s rule was to set the free quota high enough that only the most active people hit it. Pavel’s rule for public posts: do not publish a specific number until it is chosen.
- Paid BDSMLR tools in the June tier draft: unpixelated deep search, archive sorting and layouts, posting to private blogs. Reading a private blog you already follow stays available. Privacy toggles stay free.
- Full migration of users into the WordPress side was the decision on 20 April, because offline delivery needs the users in that database. Simon owns that build.
- Price in the June tier draft is **$5/month**. Earlier planning used **$12/month**. The dead product was **$20/month**.

**Pavel confirms:** the price that should appear in the company guide, or a note that price is not final.

Audience the plan was built on (database and GA, early 2026):

- About **3.2 million** registered BDSMLR accounts.
- About **66k** monthly active users, about **12.7k** daily.
- About **9.1k** people sent or received a message in 30 days; about **5.6k** of those did more than one message.
- Roughly **99% of traffic is not logged in** (on the order of 1.0 million non-logged-in users versus about 23k logged-in in the GA cut used in April). Direct traffic is the bulk. That is why anonymous ads can be the BDSMLR ad plan even if logged-in users see none.

## Payment processors (status as of the chats, not a legal conclusion)

| Path | Where it stood |
| --- | --- |
| PayPal on `shop.bdsmlr.com` | Live for the old ad-free subscription. Forward Handle LLC on the statement. |
| CCBill | Applied. They could not tell what the site was selling, asked for six months of financials, and treated the new model as a proof of concept. A written adult-merchant compliance list exists in the working folder. This is not an approval. |
| Stripe | Not tried yet, as of those threads. Considered only if the sold product is a plain IRC client, with chat domains kept out of search indexes. |
| Adult vs mainstream framing | Unsettled on purpose. Selling “BDSMLR Premium” makes the adult-processor path clearer and the compliance work heavier. Selling a neutral IRC subscription makes PayPal/Stripe thinkable and makes a user complaint that reveals the adult sites a serious risk. Pavel, Allen, and Simon had not picked one path in the chats. |

**Pavel confirms:** what Sakura and Adam should be told is still open, and who is talking to which processor now.

---

# Draft for §3 — Pavel, and the people on the ad team

The guide’s paragraph is usable. This is the operational version.

**Pavel — Advertising, monetization, and the commercial side of the properties**

Pavel runs the function that turns traffic into revenue, and he owns the commercial decisions around it:

- which advertisers stay, which get more inventory, and which are switched off;
- negotiations with ad networks (this was Pavel’s, not Allen’s);
- Revive: campaigns, banners, tabunders, interstitials, zones;
- the ISC and BDSMLR revenue dashboards, and the Looker reports built from them;
- pricing, tiers, and the monetization strategy for BDSMLR and for any RelayOS subscription;
- SEO and on-site acquisition that exists to feed that revenue (ISC chat keywords, a possible RelayOS client site);
- community communication when a monetization change will be visible to users (blog posts and on-site banners; there is no list of confirmed emails to mail).

Allen used to supply product and technical direction. Pavel executed advertising and brought the monetization plan, the numbers, and the user-facing explanation. After Allen, Pavel is the person who can say what the ad business is doing. He is not the person who ships the new BDSMLR platform. That remains Simon.

**Marko — Advertising operations, part-time**

Marko works in Revive with Pavel. He is the named contact on at least one live ISC advertiser account (Candy AI). The chats do not record a written split of weekly tasks.

**Pavel confirms:** what Marko does in a normal week, and what he can do if Pavel is away.

**Rigela — Data entry**

Rigela supports the advertising numbers. The finance allocation treated her time as mostly ISC. The chats do not spell out her weekly checklist (sheet updates, network logins, invoice matching).

**Pavel confirms:** Rigela’s actual recurring tasks, and who covers them if she is away.

**Ezra** is not on the ad team. He is the person who will receive the tickets when a monetization post, a new paywall, or a login change confuses users. Pavel’s rule from the April plan: brief Ezra before those posts go up.

**Backup.** The guide’s own test — who runs this if Pavel is unavailable — is not answered in the chats. Marko can operate Revive. He is part-time. The dashboards and the network relationships sit with Pavel.

**Pavel confirms:** the backup name to put in the guide.

---

# Draft for §6 — BDSMLR monetization

Keep Simon’s development status as he wrote it. Replace or extend “3. Explore and Improve Monetization” with the following.

## What is live

BDSMLR is a hybrid of the old site and the new one (`api-prod`). Monetization did not move across cleanly.

- **Anonymous browsing is the ad audience.** Logged-in free users are not supposed to see ads. That is a product rule Pavel set, not a guess.
- **The new experience has far fewer ads than the old one.** Revive on the BDSMLR publisher still serves banners, tabunders, and a thin interstitial (in mid-August the homepage interstitial that was actually filling was ReactAds, one creative). Candy AI on BDSMLR was created and never given banners.
- **The shop is the healthiest BDSMLR revenue line**, and it is still the old PayPal ad-free subscription, which the data says does not retain people.
- **Premium is not being sold as a feature product on the new site.** The feature list exists (messaging quota, private-blog posting, search and archive tools). The public blog has carried update posts about the direction. The subscription people can buy today is still the old ad-free product.
- A **recommendation engine** was Allen and Akira’s work for logged-out engagement. In the monetization plan it is also a possible paid discovery feature, only if the quality is good enough. Pavel does not own the engine. He does own what happens to ad impressions if logged-out browsing gets better, and which of those tools sit behind the paywall.

## What Ad Ops and Development have to do together

Pavel does not need a new affiliate network on BDSMLR. The August recommendation, in his own follow-up to the ratings, was:

1. Treat the **shop** as a real revenue line (offer, checkout, how it is described), because it is already ahead of the ad tags.
2. **Offer BDSMLR inventory to the ISC winners** — GSM, ReactAds / TP Media, 4thWhale, Chaturbate — if those partners will take the traffic. ReactAds on BDSMLR died years ago; 4thWhale died in 2021; GSM is not in the live BDSMLR mix. There is already some empty interstitial room to place them.
3. Leave remnant tags (Exoclick, and anything paying nothing) in place only if they cost no time.
4. When Simon is ready, put **anonymous-user ads** on the new experience in the formats ISC already runs: interstitials and tabunders, plus banners. Simon had said the ISC interstitial could be ported. Logged-in pages stay ad-free.
5. **Do not A/B test the advertising** as a way to decide the strategy. Pavel rejected that in the post-April plan.
6. Subscription launch waits on Simon’s migration and on a processor decision. Pavel’s side of that launch is the tier, the price, the blog and banner explanation, the dashboard, and Ezra’s briefing.

Blog orientation labels (about 84,500 blogs: gay, trans, straight, lesbian, and a large “other”) exist and can be used later to match interstitial and tabunder campaigns to the page. That targeting is prepared data, not a live system described in the chats.

## Ownership line for the guide

**Advertising / monetization:** Pavel, with Marko and Rigela  
**Placements, login state, and paywall behavior on the new site:** Simon  
**User-facing explanation:** Pavel, with Ezra warned first  
**Recommendation engine:** Simon / Akira, with Pavel on the revenue effect

---

# Draft for §7 — ISC, advertising only

Simon’s note stands: the technical review of ISC is his, and this file does not conclude anything about servers or volunteer access.

On the commercial side, ISC is not a project waiting to be understood. It is the revenue line in §2.

What Ad Ops is doing there:

- Running a filled Revive publisher (IsexyChat) across banners, tabunders, and interstitials.
- Watching a short list of partners daily and monthly, not the long historic tab list.
- Cutting partners who no longer pay. Pavel’s August notes, which he should mark done or still to do:

| Partner | Pavel’s note |
| --- | --- |
| JuicyAds | Stopped. Payment has been requested. |
| Streamray (all three) | Stopped. Advertiser is dead. |
| GSM India | Stopped. Removed from the main ISC mix because the advertiser does not want Indian traffic. |
| Flirt4Free | Advertiser is dead. |
| CamSoda | Almost dead, on the order of $1k per year. |
| Lovense, WeVibe, TwinRed | Can be removed or stopped. |
| shop.bdsmlr.com | Not an ISC line. Keep it out of the ISC report. |

Revive also had live tags that were **not in the Google Sheet** (OnlyFans, JoyOurSelf, LiveSexAwards, MFC, and others). Unlinking only the “dead” names does not create empty inventory, because those leftovers and the keep-list already share the zones. A real shift of inventory toward ReactAds, GSM, and 4thWhale means deciding, partner by partner, what happens to that untracked 15% or so.

**Chat on ISC has not been monetized as a product.** Pavel looked at it in March 2026 with GA4 (on the order of 4.9 million users over 13 months, very weak next-day return, stronger engagement on gender-matched pages). Ideas he wanted examined: bumping people who match the gender choice in the funnel, gender-matched chatbots, and short interstitial ads on actions such as a direct message. No launch decision is in the chats. ISC’s money today is the display and affiliate book, not a chat subscription.

**SEO** is in Pavel’s scope because it feeds that book. In August 2026 he compared ISC’s pages and room list with search data and had copy drafted for the AI sex chat page, tracked as a Jira comment (“sex chat keywords research”). A separate SEO plan exists for a future RelayOS IRC client (two domains, one with RelayOS in the name, one the BDSMLR shop; content written with AI; about 5–10 hours a week). That plan is a proposal, not a live channel.

---

# Draft for §12 — How an advertising change actually moves

The guide’s arrow is right. The concrete version:

1. Pavel sees it in the dashboard or in Revive: a partner dies, a CPM deal is wrong, a zone is empty, or a placement is missing on the new BDSMLR.
2. If it is only a campaign, a banner, a link, or a zone link, **Ad Ops changes it in Revive.** Development is not required. Marko can do this work with Pavel.
3. If the site has to render a new placement, hide ads for logged-in users, or show a subscribe state, **Simon has to build it.** Example already identified: port the ISC interstitial onto the new BDSMLR for anonymous sessions.
4. Rigela records the outcome in the sheets the Looker reports read. Revshare and affiliate money is entered from the partner, not from Revive’s eCPM.
5. Pavel reads the next days and weeks: impressions, fill, and revenue by partner. He does not use Revive eCPM as revenue.

GA4 on BDSMLR is the other half of the same loop. Most of the old events are legacy. The split Pavel asked development for, and which development then added as a **logged-in parameter** (seen again in GA on 4 September 2026), is the one that matches the product rule: anonymous sessions are the ad audience, logged-in sessions are not. Looker reports were specified for that split. They are a reporting tool, not a second source of invoice numbers.

---

# Draft for §14 — Advertising Operations

**Lead:** Pavel  
**With him:** Marko (part-time, Revive) and Rigela (data)

Development keeps the sites up. Ad Ops sells the attention those sites produce, and Pavel decides what else is charged for.

## Systems

| System | What it is for |
| --- | --- |
| Revive Adserver, hosted | Campaigns, creatives, zones, and what actually served. Publishers in use: IsexyChat and BDSMLR. |
| Revive access for Ad Ops | The hosted API only accepts an allow-listed IP. The earlier MCP host on the old Tailscale machine was offline for weeks (found mid-May 2026). A replacement on the tailnet (`adops`) was up and used in August 2026. |
| ISC Dashboard Stats (Google Sheet) | Daily partner revenue from 2019. This is the ISC revenue book. |
| BDSMLR Dashboard Stats (Google Sheet) | Daily partner revenue from 2021, including the shop. |
| GA4 | BDSMLR and ISC behavior. BDSMLR property used in the August setup: `322459837`. A second property was added in the same setup: `328421085`. |
| Looker Studio | The reports Pavel is building for himself from those sheets and from GA. Not a system Sakura needs to open. |
| PayPal, shop.bdsmlr.com | The existing BDSMLR subscription checkout. |
| Jira project FWDAD | Monetization and tracking tasks that need development, including the logged-in GA parameter. |

The Google Cloud project still used for the Sheets and GA connections is named `reblogme-2aa32`. That is a leftover name from the shut-down ReblogMe work. It is an access key, not a live product.

## A normal week

**Pavel confirms** the week in his own words. From the chats, the recurring work is:

- Read ISC first. ReactAds, GSM, and 4thWhale move the month. A small partner does not.
- Check new or broken campaigns in Revive (sizes, click URLs, whether a tag is delivering or only exists).
- Keep the two dashboards current. Direct-deal rows use the **contract CPM**. Revshare and affiliate rows use the partner’s reported revenue, or they are volume-only until the partner pays.
- Match what Revive is serving with what the sheet is paying. Partners can be live in one and invisible in the other. That mismatch was still true in August.
- When development changes login, page layout, or the new BDSMLR shell, re-check fill and revenue. Those changes change impressions.
- Prepare the figures Melissa and, monthly, Sakura actually need. See §17.
- Speak to partners when a placement, a geo, or a payment is stuck (JuicyAds payment requested; GSM India already declined).

## What Ad Ops will not do

- Ad Ops will not rebuild BDSMLR or ISC. Simon does.
- Ad Ops will not decide banking authority, contracts, or who may approve contractor pay. That is Sakura, Adam, and Melissa.
- Ad Ops will not describe RelayOS’s code. Simon is still reviewing that. Pavel’s commercial description is only: RelayOS is where a future subscription would be billed, and the IRC client is the product being sold in that plan.

## Decisions Pavel can make, and decisions that need Sakura

From the way the work already runs, Pavel can:

- turn a non-paying tag off;
- move inventory toward a partner who is already under contract;
- ask Simon for a placement or a tracking parameter;
- draft the user-facing post.

These need a wider decision, and should come to Sakura in the form the guide already asks for (what happened, why it matters, options, recommendation):

- a new payment processor, or a change in what the receipt says the company sells;
- a price and a public paywall on BDSMLR or RelayOS;
- killing a partner that is still a meaningful share of ISC (ReactAds, GSM, 4thWhale);
- any plan whose downside is a large share of monthly revenue.

**Pavel confirms:** the threshold in dollars or percent where he wants Sakura in the loop. Nothing in the chats sets one.

---

# Draft for §17 — What Pavel puts in the monthly owner update

Rotchilda collects it. Pavel supplies a short advertising and revenue section. Sakura should not have to open Revive, GA, or Looker.

Suggested standing items, all of which Pavel already has a source for:

1. **ISC revenue this month vs last month vs the same month last year**, from the ISC sheet, plus one sentence on whether ReactAds, GSM, and 4thWhale are healthy.
2. **BDSMLR this month:** shop vs display/affiliate, from the BDSMLR sheet. One sentence is enough unless something broke.
3. **Anything that changed the number:** a partner paused, a placement shipped or removed, a logging change, a processor conversation.
4. **One risk.** The structural one is concentration: two ISC partners are most of the company.
5. **One recommendation,** or “none this month.”
6. **Decisions for Sakura:** none, or the short form from §18 of the guide.

Do not put simulation ranges, “perfect storm” cases, or unlaunched chat-subscription math in this update.

**Pavel confirms:** the day of the month the sheets are trustworthy enough to send, and whether Melissa’s deposit total or Pavel’s dashboard total is the number in the owner pack. They were not the same number in July 2026.

A line worth adding under Financials, for Melissa rather than for Pavel to calculate: advertising income in the books should be reconcilable to the ISC and BDSMLR sheets. If it is not, the update should say which one is cash and which one is delivery.

---

# Glossary lines to add when Pavel is happy with them

**Revive**  
The hosted ad server. Campaigns and creatives are set up here. It is the record of what was requested and what was shown. It is not the record of revshare money.

**Tabunder**  
An ad that opens in a new tab, usually when the current tab is closed or a similar action happens. FWD also calls the older version of this a popunder. It is a major ISC format.

**Interstitial**  
A full-page ad between actions. ISC runs them. BDSMLR’s new experience mostly does not, yet.

**Deal CPM vs eCPM**  
Deal CPM is the rate in the contract (React Ads tabunders were at $10). eCPM is Revive’s calculated yield. Invoices and the owner report use the deal rate or the partner’s statement, not eCPM.

**Revshare**  
The partner pays a share of what they earn from the visitor, not a fixed price per thousand views. Candy AI on ISC was in this category: hundreds of thousands of impressions in Revive and $0 revenue inside Revive.

**Fill**  
The share of ad requests that received an ad. ISC was essentially full. Empty requests are not the ISC problem.

**Anonymous vs logged-in**  
On the planned and partly described BDSMLR rule: ads for people who are not logged in; no ads once they are logged in. The GA parameter development added is what makes this measurable.

**RelayOS subscription**  
The planned paid product (IRC bouncer, offline messages, and extra tools). Billed on a neutral site as Forward Handle LLC. Not the same thing as the old $20 ad-free BDSMLR subscription, which still exists on the shop.

---

# Pavel’s checklist before this goes into the company guide

Answer these in place, then delete the ones that are done. Short answers are enough.

1. **Books vs dashboard.** Which monthly total should §2 and the owner update use? What is the gap (timing, fees, which properties, unpaid revshare)?
2. **Price.** $5, $12, or “not set”? Should the guide mention the dead $20 product at all?
3. **Processor.** One sentence on PayPal, CCBill, and Stripe as of this month. Anything Adam should see?
4. **August cleanup.** Which of the kill-list partners are actually off in Revive now?
5. **Untracked ISC tags** (OnlyFans, JoyOurSelf, LiveSexAwards, and the rest). Keep, ask for a rate, or remove?
6. **BDSMLR test.** Has anyone actually offered GSM / ReactAds / 4thWhale / Chaturbate a BDSMLR placement?
7. **Shop.** Is shop revenue “advertising,” “subscriptions,” or its own line when Sakura reads the update?
8. **Marko’s week** and **Rigela’s week**, in one sentence each.
9. **Backup** if Pavel is out.
10. **Sakura’s threshold.** What ad decision must be brought to her?
11. **Logged-in ads.** Confirm the rule still stands: anonymous sees ads, every logged-in user does not, on both the old and the new BDSMLR.
12. **Anything in §2 that is now wrong** because October is not August.

---

# Working files behind this draft

These already exist in the Cursor folder. They are the detail behind the summaries above. They are not written for Sakura.

- `PnL/Forward_Handle_PnL_Executive_Summary.md` and the July 2026 dashboard files
- `ad data analysis/isc-advertiser-rating.html`
- `ad data analysis/bdsmlr-advertiser-rating.html`
- `BDSMLR_Monetization_Plan/PRODUCT_DECISIONS_SUMMARY_20042026.md`
- `BDSMLR_Monetization_Plan/BDSMLR_TIER_MATRIX_V1.md`
- `BDSMLR_Data_Collection/1_FINAL_DELIVERABLES/EXECUTIVE_SUMMARY_OPTION_B.md`
- `BDSMLR_Monetization_Plan/GA4_EVENT_TRACKING_SPECIFICATION.md` (if present) and the Looker instructions saved from the September GA thread
- `ISC_Chat_Monetization_Plan/` — exploration only

Chat ids, if a line in this draft needs to be traced: `f9fe7de8`, `a19a115d`, `b9efb15e`, `907cf478`, `808052b5`, `45afa34c`, `b2b69558`, `6ce00001`, `8dc09355`, `0f9b5f3b`, `50c8eb2e`, `554341b2`, `31c8815f`.
