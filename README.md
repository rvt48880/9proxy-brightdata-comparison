# 9proxy vs bright data: Matching a Residential Proxy to Your Per-GB Budget, Your Target Sites and Your Setup Tolerance

Two names come up almost every time someone prices out residential proxies: 9Proxy, which sells bandwidth from around a dollar a gigabyte, and Bright Data, which lists its residential network at $8 per GB before any volume discount. An eight-fold gap invites an obvious question — is the cheap option a false economy, or is the expensive one charging for things you will never use?

The honest answer is that these two products are aimed at different jobs. Match the wrong one to your workload and you either overpay by thousands a month or spend your evenings reading block logs. Below is what each side actually charges, what each side actually gives you, and where the line between them sits.

If you already know you lean budget and just want to see the numbers, 👉 [compare 9Proxy's current residential plan prices](https://bit.ly/9-Proxy) and come back to the rest.

## The short version

|  | 9Proxy | Bright Data |
| --- | --- | --- |
| Residential IP pool | 20M+ IPs, 90+ countries | 400M+ IPs, 195 countries |
| Entry price | $3.00/GB (5 GB pack) or $0.24/IP | $8.00/GB pay-as-you-go |
| Cheapest published rate | $0.68/GB at the 10,000 GB tier; $0.018/IP at 500,000 IPs | $5.00/GB at the $1,999/month tier |
| Billing units | Per IP (unlimited bandwidth), per GB, or bundled | Per GB only |
| Monthly minimum | None | $499 / $999 / $1,999 on committed tiers |
| Targeting depth | Country, state, city, ZIP, ISP | Country, state, city, ZIP |
| Protocols | HTTP, HTTPS, SOCKS5 | HTTP, HTTPS, SOCKS5 |
| KYC gate | Not referenced in the public setup docs | Required for residential and mobile networks |
| Beyond proxies | Nothing else | Unlocker, SERP API, Browser API, datasets, Scraper Studio |
| Cheap way to start | $15 for 5 GB | 1,000 free Web Scraper records for a week, plus a deposit match up to $500 |

Bright Data is the broader platform. 9Proxy is the cheaper meter. Which of those matters more depends entirely on what you're pulling and how much of it.

## Two companies, two completely different billing philosophies

Bright Data runs residential proxies on a single unit: the gigabyte. You either pay as you go at $8/GB, or you commit to $499, $999 or $1,999 a month and the per-GB rate drops to $7, $6 and $5 respectively. That's the whole menu for rotating residential.

9Proxy splits the same product across two meters, and the second one is where the interesting math lives:

- **Residential by IP.** You buy a fixed number of IPs and pay nothing for traffic. Push 20 GB through one IP or 200 GB, the price doesn't move.
- **Residential by GB.** You buy bandwidth, generate as many endpoints as you want, and rotate freely.

That first model is genuinely unusual in this market, and it changes the cost equation for anyone whose workloads are data-heavy rather than request-heavy. Consider a scraper that pulls large product catalogs through a modest number of stable IPs. On the per-GB model, 500 GB of traffic at Bright Data's pay-as-you-go rate is $4,000. On 9Proxy's IP model, 100 IPs cost $24 and the bandwidth is unmetered. The catch is that residential IPs have a natural lifespan — the company says a few hours up to roughly 24 hours per IP — so you're buying a rotating-in-practice pool rather than permanent addresses.

The reverse case matters too. If your workload is thousands of tiny requests spread across thousands of IPs, the per-IP model wastes money, and 9Proxy's own per-GB plans become the sensible choice.

## What a gigabyte actually costs on each side

Bright Data's residential ladder, at list rates:

| Plan | Monthly commitment | Per GB | Volume included |
| --- | --- | --- | --- |
| Pay as you go | $0 | $8.00 | none |
| Growth | $499 | $7.00 | ~71 GB at list rates |
| Business | $999 | $6.00 | ~166 GB at list rates |
| Scale | $1,999 | $5.00 | ~400 GB at list rates |
| 1 TB and above | Custom quote | Contact sales | — |

Two things sit underneath that table. First, the plan cards on Bright Data's residential page advertise 141 GB, 332 GB and 798 GB for those same three commitments, which only adds up at the promotional rate — the published 50% discount code halves the per-GB rates to $4, $3.50, $3 and $2.50 for three months. Divide $499 by 141 GB and you land on $3.54, so the headline included volumes are calculated post-discount. At list rates the same money buys roughly 71 GB. If you're modelling a budget, work out which number applies to month four, not month one.

Second, each of those tiers is a minimum monthly commitment, not a discount you can dip in and out of.

9Proxy's bandwidth packs, by contrast, are one-off purchases with no renewal date:

| Pack | Price | Per GB | Validity |
| --- | --- | --- | --- |
| 5 GB | $15 | $3.00 | 180 days |
| 50 GB + 5 GB bonus | $105 | $2.10 | 180 days |
| 100 GB | $150 | $1.50 | 180 days |
| 200 GB | $200 | $1.00 | 180 days |
| 1,000 GB | $800 | $0.80 | 180 days |
| 2,000 GB | $1,500 | $0.75 | 180 days |

Beyond that the rate keeps sliding, reaching $0.68/GB at the 10,000 GB tier. The 180-day validity applies across the board and is extended to unlimited on Enterprise plans.

Put the two entry points side by side and the spread is blunt. At 200 GB a month, Bright Data's pay-as-you-go rate comes to $1,600. 9Proxy's 200 GB pack is $200. Same volume, same protocol support, different bill. Whether the extra $1,400 buys you something you need is the only question that matters.

## 9Proxy's full plan lineup

If you go the 9Proxy route, there are four structures rather than one. Here's the complete current lineup.

**Residential by IP — unlimited bandwidth per IP, IPs never expire:**

| Package | Total price | Effective per IP | Purchase |
| --- | --- | --- | --- |
| 100 IPs | $24 | $0.240 | [start with 100 IPs](https://bit.ly/9-Proxy) |
| 500 IPs | $72 | $0.144 | [buy the 500 IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $126 | $0.084 | [get the 1,000+500 bonus pack](https://bit.ly/9-Proxy) |
| 2,500 IPs | $210 | $0.084 | [order 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | $360 | $0.072 | [order 5,000 IPs](https://bit.ly/9-Proxy) |
| 15,000 IPs | $720 | $0.048 | [order 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | $863 | $0.035 | [order 25,000 IPs](https://bit.ly/9-Proxy) |
| 50,000 IPs | $1,438 | $0.029 | [order 50,000 IPs](https://bit.ly/9-Proxy) |

**Business IP packages, for six-figure IP counts:**

| Package | Total price | Effective per IP | Purchase |
| --- | --- | --- | --- |
| 100,000 IPs | $2,300 | $0.023 | [request the 100,000 IP package](https://bit.ly/9-Proxy) |
| 200,000 IPs | $4,140 | $0.021 | [request the 200,000 IP package](https://bit.ly/9-Proxy) |
| 500,000 IPs | $8,625 | $0.018 | [request the 500,000 IP package](https://bit.ly/9-Proxy) |

**Residential by GB, 180-day validity on every tier:**

| Pack | Price | Per GB | Purchase |
| --- | --- | --- | --- |
| 5 GB | $15 | $3.00 | [buy a 5 GB pack to test](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $105 | $2.10 | [buy the 55 GB pack](https://bit.ly/9-Proxy) |
| 100 GB | $150 | $1.50 | [buy 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | $200 | $1.00 | [buy 200 GB](https://bit.ly/9-Proxy) |
| 1,000 GB | $800 | $0.80 | [buy 1,000 GB](https://bit.ly/9-Proxy) |
| 2,000 GB | $1,500 | $0.75 | [buy 2,000 GB](https://bit.ly/9-Proxy) |
| 10,000 GB | Tier rate $0.68/GB | $0.68 | [check the 10,000 GB rate](https://bit.ly/9-Proxy) |

**Bundle packages — IPs and bandwidth in one purchase:**

| Bundle | What's inside | Price | Purchase |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | [buy the Starter bundle](https://bit.ly/9-Proxy) |
| Popular | 1,500 IPs + 50 GB | $180 | [buy the Popular bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | [buy the Pro bundle](https://bit.ly/9-Proxy) |

**Enterprise** is quoted per account rather than published as a flat rate. The published extras are unlimited data validity, a team of one owner plus up to five members, per-member traffic controls, activity logs, unlimited share codes, and dedicated support.

Two policies worth knowing before you buy: if a proxy fails within the first 60 seconds of activation you get the credit back, and IPs you touched in the last 24 hours sit on a reuse list you can draw from without paying again. Neither is standard across this industry.

## Where Bright Data's premium actually goes

The gap between $1/GB and $8/GB is not pure margin. Some of it buys things that are hard to substitute.

**Pool size and spread.** Bright Data advertises 400M+ residential IPs across 195 countries, up from 72M in 2024. 9Proxy reports 20M+ across 90+. For most scraping jobs in the US and Western Europe, 20 million is plenty — the pool depth per country is what matters, and 9Proxy publishes roughly 572,000 US IPs, 530,000 Canadian and around 446,000 UK. But if your target list spans smaller markets, the difference in available exit nodes shows up.

**Managed unblocking.** Web Unlocker and the SERP API bill per 1,000 successful results, from $1.50 down to $1.00 at the $1,999 tier, and failed fetches aren't charged. Scraper Studio and the Browser API add a managed rendering layer at $8/GB falling to $5/GB. If you'd otherwise be writing and maintaining anti-bot bypass logic, that's a real labour cost removed. 9Proxy doesn't offer an equivalent; you're buying raw proxy access and integrating it yourself.

**Included targeting.** Bright Data doesn't surcharge for country, state, city or ZIP targeting. Some providers do.

**Compliance posture.** Residential and mobile network access on Bright Data sits behind a KYC review that can include a short video call. That's friction, and for some buyers it's the reason they never sign up. For others — anyone who needs to show a legal or procurement team that their data source is documented — it's the point. The company also won summary judgment against Meta in January 2024 and had X Corp's claims dismissed in May 2024, which is the kind of paper trail nobody else in this category can produce.

**Free tier on the API products.** Every new account gets a recurring 5,000 credits a month across Web Unlocker, SERP API, Scraper Studio and Browser API, plus a first-deposit match up to $500. There's a separate one-week, 1,000-record trial of the Web Scraper API with no card required.

One billing detail that catches people out: Bright Data measures bandwidth as request headers plus POST data plus response headers plus response data. If you budgeted off payload size alone, your estimate is low.

## Where 9Proxy comes out ahead

**Unlimited bandwidth on IP plans.** This is the structural difference. A 100-IP package at $24 with no traffic metering is a different product from a per-GB meter, and for catalog scraping, media-heavy work, or anything where you can't predict volume, it removes the single biggest variable in your bill.

**No monthly minimum, ever.** You can buy a $15 pack, use it over 180 days, and never speak to a sales team. Bright Data's cheapest residential commitment is $499 a month.

**Bandwidth that doesn't evaporate.** 180 days is long for this industry, and unused IPs on the per-IP plans don't expire at all. Project-based work fits this model much better than a monthly window.

**Targeting without a surcharge.** The GB plans target down to country, state, city, ZIP and ISP level. ISP-level filtering matters more than people expect, because some detection systems fingerprint the carrier as well as the address.

**Support that isn't a ticket queue.** 24/7 human support through Telegram, email and tickets. For a solo operator, being able to message someone at 2 a.m. beats a portal.

**Protocol coverage.** HTTP, HTTPS and SOCKS5 across IPv4, which is what Scrapy, Puppeteer and Playwright-based stacks need.

## Setup differences you'll notice on day one

9Proxy's IP-based plans route through a desktop application that does local port forwarding, with optional proxy authentication. It's not difficult, but it means your scraping box needs the app running and the IPs are tied to that machine's session behaviour. The GB-based system skips the app entirely and runs from the dashboard, generating endpoints you authenticate with a username and password or an IP whitelist. Both rotation modes are available there: rotating, which switches IP per request or session, and sticky, which holds one IP for a configured duration. You can export the endpoint list as .txt or .csv and pull ready-made code samples in several languages.

Bright Data's flow is zone-based. You create a zone per product, pull credentials from the overview tab, and manage spend limits per zone by bandwidth or by dollar amount, recalculated every 15 minutes. More control, more configuration, and a KYC step before residential works at all.

## Which one should you actually pick?

**Go with 9Proxy if:**

- You're scraping lightly protected or mid-market sites where an 85–95% success rate is fine because you can retry failures
- Your bandwidth is large or unpredictable and you'd rather pay per IP than per gigabyte
- You want to start for $15 and validate the network against your own targets before spending real money
- You need city or ISP-level targeting without paying a premium for it
- Unused credits sitting for months is part of your normal rhythm

**Go with Bright Data if:**

- Amazon, Google SERPs, LinkedIn or similar heavily defended targets are core to your pipeline
- You'd rather buy managed unblocking and rendering than maintain it in-house
- You need mobile proxies, datacenter IPs or pre-built datasets from the same vendor
- Finance or legal wants a documented compliance process behind your IP sourcing
- Your volume is high enough that the $1,999 tier's $5/GB beats paying $1/GB for traffic that keeps failing

**The realistic answer for a lot of teams:** neither, exclusively. Routing most of your traffic through a budget network and keeping a smaller premium account for the targets that need it costs less than either single-vendor setup and removes the single point of failure.

## FAQ

**Is 9Proxy cheaper than Bright Data?**
On published rates, yes, by a wide margin. 9Proxy's bandwidth starts at $3.00/GB and falls to $0.68/GB at volume against Bright Data's $8.00/GB pay-as-you-go and $5.00/GB at the $1,999 monthly commitment. The per-IP plans change the comparison further, since traffic isn't metered at all.

**Does 9Proxy require a subscription?**
No. Packages are one-off balance purchases. IP-based packages don't expire, and bandwidth packs carry 180 days of validity.

**Does Bright Data have a free trial?**
There's a no-card trial of 1,000 records for one week on the Web Scraper API, plus a recurring 5,000 credits a month across the API products on any new account. Residential and mobile networks require KYC and don't have a free tier.

**Can I run both?**
Nothing stops you. Keep 9Proxy as the default exit for bulk work and hold a Bright Data account for the targets where you need either managed unblocking or a documented compliance story.

**Which has the bigger IP pool?**
Bright Data, comfortably — 400M+ residential IPs across 195 countries against 9Proxy's 20M+ across 90+. Whether that matters depends on whether your targets sit in the deep US and Western European pools or in smaller markets.

## Getting started

Start with the workload, not the vendor. Write down how many gigabytes you moved last month, how many distinct IPs you actually needed, and what your success rate has to be on your hardest target. That answers the question in about ten minutes, and it will point you one way or the other without much ambiguity.

If the numbers say budget, 👉 [create a 9Proxy account and start with a small pack](https://bit.ly/9-Proxy) so you can test the pool against your own targets before committing to a larger tier. If they say you need managed unblocking and a compliance trail, that's Bright Data's territory, and no per-GB discount is going to change it.
