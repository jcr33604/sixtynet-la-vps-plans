# China Optimized VPS Los Angeles: Which SixtyNet Plan Runs AS9929, Why the Residential Plans Block Port 80/443, and What $200 a Year Actually Buys (Full Plan and Price Table)

Los Angeles China-optimized VPS pricing currently runs about $8 to $16 a month at entry level, $15 to $24 a month for 2 vCPU / 2GB, and around $66 a year for the smallest annual boxes. SixtyNet sells almost its entire Los Angeles line on annual billing, and its 2-core / 2GB / 40GB NVMe / 5TB plan is **$200 a year**, or $16.67 a month. That lands mid-band on price and above average on monthly traffic, since the $15–$24 comparison boxes generally give you 2TB.

What decides whether SixtyNet is the right buy is not the price. It's which of its three Los Angeles product groups you pick, and one line in the fine print: the residential-IP plans do not open ports 80 and 443. If you're building a website, that single sentence rules out half the catalogue. Below is the full plan breakdown, a like-for-like price comparison against two other Los Angeles China-optimized sellers, and the limits worth knowing before you pay.

> **Quick pick:** Most readers who want a China-optimized Los Angeles box for a site or a proxy should take **LAX-STARTER** (2 cores, 2GB RAM, 40GB NVMe, 5TB traffic, DDoS protected) at **$200/year**, discounted from $240. Skip every plan labelled "Residential IP" if you need to serve web pages on standard ports.
> 👉 [See the current SixtyNet Los Angeles plan list and prices](https://sixtynet.net/aff.php?aff=39)

## SixtyNet's Los Angeles line-up: three product groups wearing three different network labels

The SixtyNet VPS page opens with a network feature list that names **China Unicom Premium AS9929**, free BGP session setup, limited BGP technical support, a 100M basic network with 3x burst and 95th-percentile billing, and quarterly/annual payment discounts. That list is where most buyers stop reading, and it's where the confusion starts, because AS9929 is not printed on every plan.

Three groups sit below that header:

- **Residential IP**, four tiers from 2 cores / 2GB to 16 cores / 16GB. These carry the note that ports 80 and 443 stay closed for IP risk-control reasons.
- **Residential IP with "AS9929 Optimize for China"**, two tiers (2C/2G and 4C/4G). These are the only plans where the AS9929 label appears inside the plan specification itself. They also state that refunds are issued to website balance only.
- **LAX DDoS Protected**, four tiers labelled "Premium Network" with DDoS protection. These are the only plans in the list without the residential-IP restriction, which makes them the only practical choice for public web hosting.

So the honest reading of the page: AS9929 is the headline network for the brand, but the tag is attached to two residential plans, not to the LAX web-hosting line. If AS9929 routing is the specific reason you're buying, ask support to confirm which group it applies to on the plan you're about to order. That question costs nothing and it's the difference between getting the routing you wanted and getting a generic premium transit blend.

## SixtyNet plans and prices: the full table

These four are the plans with prices shown on the official VPS page. All are annual billing, and the $240 / $480 / $960 / $1,920 figures are the pre-discount prices the page displays.

| Plan | vCPU / RAM | NVMe storage | Traffic / network | Annual price | Order |
| --- | --- | --- | --- | --- | --- |
| LAX-STARTER | 2 cores / 2GB | 40GB (12,500 IOPS) | 5TB / 2G premium, DDoS protected | **$200** (list $240) | [Order LAX-STARTER](https://sixtynet.net/aff.php?aff=39) |
| LAX-MICRO | 4 cores / 4GB | 80GB (12,500 IOPS) | 10TB / 4G premium, DDoS protected | **$400** (list $480) | [Order LAX-MICRO](https://sixtynet.net/aff.php?aff=39) |
| LAX-MEDIUM | 8 cores / 8GB | 160GB (25,000 IOPS) | 20TB / 10G premium, DDoS protected | **$800** (list $960) | [Order LAX-MEDIUM](https://sixtynet.net/aff.php?aff=39) |
| LAX-LARGE | 8 cores / 16GB | 320GB (25,000 IOPS) | 40TB / 10G premium, DDoS protected | **$1,600** (list $1,920) | [Order LAX-LARGE](https://sixtynet.net/aff.php?aff=39) |

Two details in that table matter more than the headline specs.

**The whole LAX line is priced at exactly $40 per TB of annual traffic.** $200 for 5TB, $400 for 10TB, $800 for 20TB, $1,600 for 40TB. You are buying bandwidth, and the CPU, RAM and storage scale up alongside it whether you need them or not. If a workload is traffic-heavy but light on compute, there's no cheaper per-TB entry point in the range.

**LAX-LARGE doubles the price without adding a core.** MEDIUM and LARGE both have 8 cores. The extra $800 buys the second 8GB of RAM, another 160GB of NVMe and another 20TB of traffic. Anyone who assumes "LARGE" means twice the CPU should check that before ordering.

The residential groups are listed below. SixtyNet's page shows their configurations without a price beside them, so confirm the number on the order page rather than assuming it matches the LAX tiers.

| Group | vCPU / RAM | NVMe storage | Traffic | Notes |
| --- | --- | --- | --- | --- |
| Residential IP | 2 cores / 2GB | 40GB (12,500 IOPS) | 5TB / 2G network | Ports 80 & 443 closed |
| Residential IP | 4 cores / 4GB | 80GB (12,500 IOPS) | 10TB / 4G network | Ports 80 & 443 closed |
| Residential IP | 8 cores / 8GB | 160GB (25,000 IOPS) | 20TB / 10G network | Ports 80 & 443 closed |
| Residential IP | 16 cores / 16GB | 320GB (25,000 IOPS) | 40TB / 10G network | Ports 80 & 443 closed |
| AS9929 Optimize for China | 2 cores / 2GB | 40GB (12,500 IOPS) | 5TB / 2G network | Residential IP; refunds to account balance only |
| AS9929 Optimize for China | 4 cores / 4GB | 80GB (12,500 IOPS) | 10TB / 4G network | Residential IP; refunds to account balance only |

👉 [Compare the residential and DDoS-protected groups on SixtyNet's VPS page](https://sixtynet.net/aff.php?aff=39)

## What $200 a year buys compared with the rest of the Los Angeles market

The same 2 vCPU / 2GB / 40GB shape is sold by at least two other Los Angeles China-optimized providers, and the spread is worth seeing side by side. All figures below are from the providers' own plan pages.

| Provider | Plan | vCPU / RAM | Storage | Monthly traffic | Price | Billing |
| --- | --- | --- | --- | --- | --- | --- |
| SixtyNet | LAX-STARTER | 2 / 2GB | 40GB NVMe | 5TB | $200/yr ($16.67/mo) | Annual only |
| dedione | LAX.VPS.CN.2C2G40G | 2 / 2GB | 40GB SSD | 2TB | $14.99/mo | Monthly |
| bytevirt | VPS-2048-KVM-CN2 GIA-LA | 2 / 2GB | 40GB SSD | 2TB | $24.00/mo | Monthly |
| bytevirt | VPS-2048-KVM-Elite-LA | 2GB class | 40GB class | not listed in capture | from $16.00/mo | Monthly |

On a twelve-month basis, SixtyNet's $200 undercuts bytevirt's CN2 GIA 2048 plan by **$88 a year** and costs **$20.12 more** than dedione's equivalent, while carrying 5TB a month instead of 2TB. Put differently, that $20 buys you 36TB of extra annual transfer at SixtyNet, which is the cheapest per-TB rate in this comparison.

The trade-off is commitment. SixtyNet's LAX prices are annual; dedione and bytevirt both list monthly billing on their China-optimized Los Angeles plans, so you can leave after one month. If you haven't run traffic through a provider before, a $200 upfront payment is a bigger bet than $14.99.

One more number worth carrying into the decision: bytevirt's cheapest CN2 GIA Los Angeles box, the 512MB annual plan at $66 a year, has no SixtyNet equivalent. SixtyNet's smallest plan is 2 cores / 2GB. If your budget ceiling is around $70 a year, this isn't the shop for you.

👉 [Check the LAX-STARTER listing and current discount](https://sixtynet.net/aff.php?aff=39)

## The limits that decide whether SixtyNet works for you

**Ports 80 and 443 are closed on every residential plan.** SixtyNet repeats this notice under all four residential tiers and under both AS9929 residential tiers, citing IP risk control. A residential IP that accepts public web traffic stops looking residential, so the restriction follows from the product. It also means no Let's Encrypt HTTP validation, no plain HTTP site, no standard HTTPS. You can front it with a CDN or a reverse proxy on another host, but that's a second server and a second bill. For anything that serves pages to the public, buy from the LAX DDoS Protected group instead.

**Refund handling differs by group.** The AS9929 residential plans state that refunds are issued to website balance only, not back to your payment method. That's a meaningful difference if you're testing and might change your mind. A third-party review of SixtyNet posted on GitHub claims a three-day money-back window across the business, well short of the 30 days common in this segment. I could not confirm that window on SixtyNet's own pages, so treat it as a question for support rather than a fact.

**Overage policy is not stated on the LAX plans.** The page's feature list mentions 95th-percentile billing and a 3x burst rate on a 100M basic network, which are network-service terms rather than per-VPS guarantees, and the plan cards themselves don't say what happens when you pass 5TB. Compare that with bytevirt, which prints "Port speed limited to 1Mbps after traffic exceeded" on every China-optimized Los Angeles plan. A 1Mbps cap is effectively a dead server until the month rolls over. If you expect to bump the ceiling, ask SixtyNet in writing what happens first.

**Discounts are built into the listed price.** The $240 to $200 step is the 17% saving the page advertises, and the feature list also mentions quarterly and annual payment discounts. There's no coupon to hunt for on the LAX tiers.

## Which SixtyNet plan fits which job

**A personal site or small blog with Chinese visitors:** LAX-STARTER at $200 a year. 2 cores and 2GB handles a WordPress install or a static build with room to spare, and 5TB covers a site well past the point where it starts earning.

**A proxy or tunnel for a handful of people:** LAX-STARTER again. The workload is bandwidth-bound, and this is the cheapest per-TB entry in the range. Step up to LAX-MICRO only if concurrent connections start pushing memory.

**Media streaming or anything that moves serious volume:** LAX-MEDIUM. 20TB at $800 works out to the same $40 per TB, and the 10G network plus 25,000 IOPS storage removes the I/O ceiling you'd hit on the starter tier.

**Memory-hungry but not traffic-hungry:** LAX-LARGE, reluctantly. It's the only way to get 16GB, and you're paying for 40TB you may never touch. Running two LAX-MEDIUM boxes isn't cheaper, so if RAM is the constraint, this is the step.

**Anything involving social accounts, scraping or ad verification on a residential IP:** the residential or AS9929 groups, with ports 80/443 out of the picture by design. Budget for the balance-only refund rule.

## FAQ

**Is the LAX series the same as the AS9929 plans?**
No. AS9929 appears inside the specification of two residential plans only. The LAX DDoS Protected tiers list "Premium Network" without an AS number. The brand's network feature list mentions China Unicom Premium AS9929, but that is a page-level statement, not a per-plan guarantee.

**Can I host a website on a residential plan?**
Not on standard ports. 80 and 443 are closed. A CDN in front or a reverse proxy on a second server works around it, at extra cost and complexity.

**Does annual billing actually save money?**
On the LAX tiers, yes: $240 to $200, $480 to $400, $960 to $800, $1,920 to $1,600. That's the advertised 17%, applied at the listed price with no code required.

**What happens if I exceed 5TB in a month?**
SixtyNet doesn't state an overage rule on the LAX plan cards. Ask before ordering if you're anywhere near the limit.

**What if the plan I want is out of stock?**
Stock on this class of product moves daily, and third-party mirrors of provider pages routinely show different availability from the official site. Trust the number on the order page at the moment you buy.

## Before you order

Match the plan to the port question first, then to traffic. If you need to serve web pages, you're in the LAX group and the choice is LAX-STARTER at $200 a year unless you're moving more than 5TB a month. If you need a residential IP for account work, you're in the AS9929 group and the closed ports are part of the deal.

Two things to confirm with support before paying: which product group the AS9929 routing actually applies to, and what the refund terms are for the exact plan in your cart, since the residential group refunds to account balance only and the widely-cited three-day window is a third-party claim rather than something SixtyNet's own pages state.

👉 [Open SixtyNet's VPS page to confirm which group and plan you're buying](https://sixtynet.net/aff.php?aff=39)
