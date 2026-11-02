# unmetered dedicated server hosting: How to Spot a Truly Unlimited Port, Plus RackNerd's Full Plan Lineup and Real Monthly Prices

Most "unmetered dedicated server hosting" pages won't tell you the one thing that decides whether unmetered actually means unmetered: whether the port is dedicated or shared. A shared 1Gbps port with an "unmetered" label can quietly throttle you to a fraction of that speed the moment you sustain real traffic for a few hours. A dedicated unmetered port lets you push the full line rate around the clock, every day of the month.

This guide covers both sides. We'll walk through how the unmetered trap works, then break down RackNerd's entire dedicated server lineup — seven 1Gbps plans from **$139/month**, six true 10Gbps unmetered plans from **$599/month**, and 20Gbps/40Gbps tiers on the same chassis — with the actual order pages linked for each plan.

> **Quick picks**
> - Need a true unmetered port for streaming, CDN origin, or VPN traffic? The entry **10Gbps unmetered plan at $599/month** (about **$509/month** with the 15OFFDEDI promo code) is the cheapest verified entry point, and the older Xeon inside it doesn't hold back a bandwidth-bound workload. 👉 [Check RackNerd's current unmetered server lineup and pricing](https://bit.ly/RacKnerd)
> - Running a normal website, game server, or dev stack? You don't need unmetered anything. The 35TB–100TB monthly quotas on the $139–$199 plans cover that comfortably.

## What "unmetered" actually means (and where providers cheat)

Unmetered means the provider doesn't count your bytes or bill overage. It says nothing about how fast you can actually go, and that's where the gap lives.

There are two very different products wearing the same label:

1. **Shared unmetered port.** The server sits on a 1Gbps (or 10Gbps) uplink that dozens of other machines also use, guarded by a fair-use policy. Sustain heavy transfer for a few hours and you get "politely shuffled onto a slower lane" — a pattern that shows up repeatedly in buyers' comparisons of unmetered providers. One frequently cited example: a Los Angeles IPTV relay sold as "1Gbps unmetered" that dropped to around 200Mbps on Friday nights, because the port was never actually dedicated.
2. **Dedicated unmetered port.** The full port is yours alone, with no fair-use clause and no off-peak shaping. You can sustain the rated speed 24/7/365.

RackNerd's high-bandwidth line falls squarely in the second category. Its 10Gbps, 20Gbps, and 40Gbps unmetered servers are advertised as 100% unshared ports, and the company's own pitch — in the CEO's release notes — was explicitly about breaking the industry habit of stamping "unmetered" on shared ports. When you evaluate any provider, including the ones mentioned later in this article, the first question to ask is exactly that: dedicated port, or shared?

A second trap: "unlimited" is a marketing word, "unmetered dedicated port" is a technical one. If a plan page doesn't state the port is unshared, assume it isn't.

## RackNerd's dedicated server lineup: two tracks

RackNerd sells dedicated servers in two separate tracks, and understanding the split saves you a lot of confusion:

- **Standard 1Gbps line (metered quotas).** Monthly transfer allowances from 35TB to 200TB on a 1Gbps port. This is what the main dedicated servers page lists, starting at $139/month.
- **True unmetered line (dedicated ports).** 10Gbps, 20Gbps, and 40Gbps unshared ports with no transfer cap at all, sold on separate category pages. The company also runs occasional 1Gbps unmetered specials outside the main catalog.

All dedicated servers — both tracks — include full root access, IPMI/KVM console access for remote reinstalls and power cycling, DDoS protection, Noction IRP intelligent routing, five usable IPv4 addresses (unless noted), and your choice of Linux, Windows, FreeBSD, or a custom ISO. Bare metal deployment is officially quoted at typically under 48 hours.

### Standard 1Gbps dedicated servers (all seven plans)

These are metered plans — fixed quotas at a fixed monthly price, no overage billing.

| Plan | RAM | Storage | Bandwidth & IPs | Price/mo | Order |
| --- | --- | --- | --- | --- | --- |
| Intel Xeon E3-1230 v2 | 16 GB | 480 GB SSD | 35 TB @ 1Gbps, 5 IPs | $139 | [Order the E3-1230 v2](https://my.racknerd.com/cart.php?a=add&pid=12&aff=11397) |
| Intel Xeon E3-1270 v3 | 32 GB | 2× 1 TB SSD | 35 TB @ 1Gbps, 5 IPs | $169 | [Order the E3-1270 v3](https://my.racknerd.com/cart.php?a=add&pid=869&aff=11397) |
| Dual Xeon E5-2650 v2 | 64 GB | 1 TB SSD | 100 TB @ 1Gbps, 5 IPs | $199 | [Order the dual E5-2650 v2](https://my.racknerd.com/cart.php?a=add&pid=867&aff=11397) |
| Dual Xeon E5-2650 v2 | 128 GB | 1 TB SSD + 3 TB HDD | 50 TB @ 1Gbps, 5 IPs | $245 | [Order the 128 GB build](https://my.racknerd.com/cart.php?a=add&pid=871&aff=11397) |
| Virtualization Node Special | 256 GB | 4× 2 TB SSD | 100 TB @ 1Gbps, 29 IPs | $349 | [Order the virtualization node](https://my.racknerd.com/cart.php?a=add&pid=868&aff=11397) |
| Dual Xeon E5-2680 v4 | 256 GB | 4× 2 TB SSD | 100 TB @ 1Gbps, 61 IPs | $399 | [Order the E5-2680 v4 node](https://my.racknerd.com/cart.php?a=add&pid=870&aff=11397) |
| 160 TB Storage Special | 64 GB | 256 GB SSD + 10× 16 TB HDD | 200 TB @ 1Gbps, 5 IPs | $479 | [Order the 160 TB storage server](https://my.racknerd.com/cart.php?a=add&pid=526&aff=11397) |

A few of these deserve context. The two "Virtualization Node" builds ship with 29 and 61 IPv4 addresses respectively, aimed at people running their own VPS farms. The 160TB storage special — 160TB of raw HDD in Los Angeles DC-02 with a 200TB monthly quota — is positioned for backup, archival, and large-file mirroring, and it's hard to find comparable raw capacity at this price from mainstream hosts.

For a typical web app, staging server, or small game backend, the $139 or $199 plans are plenty. 35TB of monthly transfer works out to roughly 1.2TB per day; the 100TB quota is nearly 3.3TB per day.

### True 10Gbps unmetered servers (all six plans)

This is the lineup built around the keyword. Every plan below has a dedicated, unshared 10Gbps port with no transfer cap, five usable IPs, IPMI/KVM, and DDoS protection. Locations: Los Angeles, New Jersey, London, and Montreal.

| Plan | CPU | RAM | Storage | Price/mo | Order |
| --- | --- | --- | --- | --- | --- |
| Limited Time Special | Xeon E3-1230 V3 (4C/8T) | 32 GB DDR3 | 1 TB SSD | $599 | [Grab the $599 10Gbps plan](https://my.racknerd.com/cart.php?a=add&pid=746&aff=11397) |
| E-2136 | Xeon E-2136 (6C/12T) | 32 GB DDR4 | 1 TB NVMe | $799 | [Order the E-2136 plan](https://my.racknerd.com/cart.php?a=add&pid=747&aff=11397) |
| Dual E5-2630 V4 | 2× E5-2630 V4 (20C/40T) | 64 GB DDR4 | 1 TB NVMe | $950 | [Order the dual E5-2630 V4](https://my.racknerd.com/cart.php?a=add&pid=748&aff=11397) |
| Dual E5-2695 V4 | 2× E5-2695 V4 (36C/72T) | 128 GB DDR4 | 2× 1 TB NVMe | $1,399 | [Order the dual E5-2695 V4](https://my.racknerd.com/cart.php?a=add&pid=749&aff=11397) |
| EPYC 7642 | EPYC 7642 (48C/96T) | 128 GB DDR4 | 2× 1 TB NVMe | $1,699 | [Order the EPYC 7642](https://my.racknerd.com/cart.php?a=add&pid=750&aff=11397) |
| EPYC 7702P | EPYC 7702P (64C/128T) | 128 GB DDR4 | 2× 1 TB NVMe | $1,999 | [Order the EPYC 7702P](https://my.racknerd.com/cart.php?a=add&pid=751&aff=11397) |

The $599 entry plan is tagged "Limited Time Special" on the official page. Yes, the E3-1230 V3 is 2013-era silicon with DDR3 memory. For a bandwidth-bound workload — mirroring, IPTV relay, CDN origin, proxy aggregation — it still saturates 10Gbps without breaking a sweat, because the CPU was never the bottleneck. That's exactly why it's the plan to grab first if your specs allow it.

The math on stepping up: going from the standard line's 1Gbps port to a 10Gbps dedicated port costs about 4.3× the money ($139 → $599) for 10× the sustained ceiling. The rule of thumb from detailed third-party comparisons: if your workload stabilizes at 1Gbps and stays under roughly 50TB per month, a 10Gbps plan is mostly buying redundancy you won't use. Once you're serving thousands of concurrent viewers — 5,000 streams at 2.5Mbps is about 12.5Gbps of aggregate demand — the upgrade pays for itself.

### 20Gbps and 40Gbps unmetered tiers

The same chassis are available with bigger pipes, priced as port upgrades on identical hardware. Verified pricing from the current catalog:

| Chassis | 10Gbps | 20Gbps | 40Gbps |
| --- | --- | --- | --- |
| Xeon E3-1230 V3 | $599/mo | $1,499/mo | $2,799/mo |
| Xeon E-2136 | $799/mo | $1,699/mo | $2,999/mo |
| Dual Xeon E5-2630 V4 | $950/mo | — | $3,150/mo |

20Gbps fits multi-region streaming backbones and heavy mirroring; 40Gbps is for data ingestion and high-concurrency CDN edges. Honestly assess your sustained throughput before jumping tiers — at 20Gbps and above, the bottleneck in most setups shifts from the network to CPU, RAM, and disk, and doubling a port you can't feed wastes money every month. 👉 [Check RackNerd's full unmetered lineup, including the 20Gbps tier](https://bit.ly/RacKnerd)

RackNerd also runs rotating specials outside the main catalog. Early-2026 listings showed 1Gbps unmetered configurations including a Xeon E3-1240 V3 with 32GB RAM in New York at $64.95/month and a Ryzen 7600 with 64GB RAM in Utah at $109.95/month. These come and go with hardware inventory, so treat them as opportunistic grabs rather than a stable product line. 👉 [Browse RackNerd's current specials page](https://bit.ly/RacKnerd)

## The real cost: promo code math and where the price lands

One detail most comparison posts skip: RackNerd publishes a promo code, **15OFFDEDI**, that takes 15% off bare metal dedicated servers for the lifetime of the service, and it applies on top of the listed prices.

What that does to the 10Gbps line:

- $599 → **$509.15/month** (saves about $1,078 per year)
- $799 → $679.15/month
- $950 → $807.50/month
- $1,999 → $1,699.15/month

The code surfaced in RackNerd's own promotional listings and has been carried in third-party guides since; whether it's active on any given day is confirmed at checkout, so apply it before paying and check the final figure. There's no setup fee on the unmetered line — $0 setup was part of the original promo terms — and the plans are billed monthly, so you're not committing to a long contract to get the pricing.

Two caveats belong next to any RackNerd price. First, prices move with hardware inventory; configurations rotate as older stock sells out. Second, promotional prices and standard catalog prices can differ noticeably, which a competing provider's own review page pointedly calls out ("our prices may be higher than RackNerd's promotional offers, but they are transparent and do not change drastically"). That's a fair trade-off to weigh: RackNerd is cheap, and cheap means the number you see today isn't contractually frozen.

## How RackNerd stacks up against the unmetered specialists

For context, the unmetered niche has a handful of established players. ZetServers sells dedicated unmetered ports from 1 up to 200Gbps. NovoServe offers 2, 5, 10, and 50Gbps unmetered options aimed at enterprise traffic. Maple-Hosting positions premium unmetered bandwidth from 100Mbps to 20+Gbps, and Unmeterd runs more than 15,000 servers out of Amsterdam and Frankfurt on its own global network. NexonHost targets European streaming and gaming workloads with EPYC builds.

These specialists generally position themselves at the premium, enterprise-grade end of the market — dedicated account handling, SLA-backed commitments, and newer hardware generations. RackNerd's pitch is explicitly value pricing on older-generation silicon. Third-party reviewers state the flip side plainly: RackNerd isn't built for buyers who need SLA guarantees, dedicated account managers, or elastic scaling to 128-core machines on demand. If procurement requires those, the European specialists are the better fit. If you're paying out of your own budget for bandwidth, the calculation changes.

## Who each track is actually for

A quick decision map based on the verified specs:

- **Websites, game servers, dev/staging, small SaaS:** Standard 1Gbps line, $139–$199 plans. Unmetered would be overpaying.
- **Continuous video relay, regional VPN node, moderate mirroring:** The 1Gbps unmetered specials when available ($64.95–$109.95/month), or jump to 10Gbps if you need headroom.
- **Streaming to thousands of concurrent viewers, CDN origin, large VPN clusters, AI training data pipelines:** 10Gbps line. Start at $599 ($509 with the code); move to dual-Xeon or EPYC tiers when CPU becomes the constraint, not before.
- **Multi-region streaming backbone or 40Gbps ingestion:** 20/40Gbps tiers on the same chassis, $1,499–$3,150/month.
- **Self-hosted VPS farm:** The virtualization node builds with 29 or 61 IPs.

## FAQ

**Is RackNerd's 10Gbps port actually dedicated?**
Yes. The 10/20/40Gbps unmetered servers are sold as 100% unshared dedicated ports with no fair-use clause, and the company's stated goal in launching the line was to counter the industry practice of labeling shared ports "unmetered." The standard 1Gbps line is metered by quota instead (35–200TB), which is a different product.

**How long does deployment take?**
RackNerd's official figure is "typically deployed in under 48 hours" for bare metal. Third-party reviews describe manual provisioning in the 24–72 hour range, so if your timeline is tight, confirm stock with sales before ordering.

**Where are the unmetered servers located?**
The 10Gbps line is offered in Los Angeles, New Jersey, London, and Montreal. RackNerd operates 20 datacenter locations overall across North America, Europe, and Asia, and its Los Angeles DC-02 includes Asia-optimized routing (China Telecom, CN2, China Unicom mixes) relevant for APAC-facing traffic.

**Can I reinstall the OS myself?**
Yes. Every dedicated server includes IPMI/KVM console access, so you can mount a custom ISO, reinstall, and power-cycle remotely without filing tickets. Custom partitioning is available too.

**Do the promo code and listed prices stack?**
15OFFDEDI applies at checkout on top of the listed bare metal price and persists for the life of the service. Promotions and catalog prices can shift with hardware inventory, and prices are subject to change — verify the final figure on the order page before committing.

## Before you click order

Match the plan to sustained throughput, not peak bursts: a 35TB quota absorbs most "I need unmetered" impulses once you do the daily math (roughly 1.2TB per day), while genuinely saturated 24/7 traffic justifies the dedicated-port line. Pick the location from the order form before paying, since availability varies by chassis. And if the E3-1230 V3 spec sheet covers your workload, take the $599 entry plan while the "Limited Time Special" tag is still attached — that's the cheapest verified door into a true dedicated 10Gbps pipe. 👉 [Order the 10Gbps unmetered entry plan](https://my.racknerd.com/cart.php?a=add&pid=746&aff=11397)
