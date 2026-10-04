# buy private proxies: real per-IP and per-GB prices, plan-by-plan, and how to avoid paying for shared IPs

"Private proxy" gets used for at least three different things. Sometimes it means a dedicated IP nobody else touches. Sometimes it means any paid proxy, as opposed to one scraped off a free list. And sometimes it just means residential, because the marketing team liked the word.

That ambiguity costs money. People buy a 10-IP shared datacenter package expecting isolation, then wonder why their accounts keep tripping fraud checks. Others overpay for static dedicated IPs they'll never need.

So before the pricing tables, it's worth separating what you're actually buying — because for most of the jobs people search under this keyword, the answer isn't a classic per-IP-per-month dedicated proxy at all.

## What "private" actually means, and the two models you're choosing between

**Model one: dedicated IP rental.** You rent a specific IP (or a block), usually billed monthly, and nobody else routes traffic through it. Datacenter and static ISP proxies work this way. Predictable, easy to reason about, and the priciest per unit — Oxylabs, for example, starts its private datacenter line around $6.75/month per IP and its ISP proxies around $16/month.

**Model two: exclusive allocation from a shared pool.** You buy a chunk of residential IPs or bandwidth that only your account can use, but the underlying IPs rotate. There's no monthly clock; you spend a balance. Cheaper per unit, better geo coverage, and IP reputation tends to be cleaner because residential IPs don't live in known datacenter ranges.

If your work is account management on platforms that fingerprint IP ranges, long sessions, or anything where a permanent IP is a hard requirement, model one is what you want. If your work is data collection, ad verification, price monitoring, SERP checks, or geo-testing, model two does the job for a fraction of the cost — and that's the category 9Proxy plays in.

## Where 9Proxy sits

9Proxy is a Hong Kong-registered residential proxy provider that's been running since 2023. It advertises **20M+ residential IPs across 90+ countries**, HTTP/SOCKS5 support, targeting down to country, state, city, ZIP, and ISP, and 99.95% uptime. Those are vendor figures, not independently audited numbers — worth saying out loud, because every provider in this space quotes its biggest pool number.

The part that actually differentiates it is the billing shape. You buy a balance, not a subscription. Nothing auto-renews. IP-based packages don't expire at all, and GB-based packages hold their traffic for **180 days** instead of the 30-day windows most competitors use.

On Trustpilot the company holds an "Excellent" rating at **4.6/5**, and the reviews skew toward scraping workflows, multi-account management, and support responsiveness. One reviewer complained that they'd assumed they were buying rotating proxies, bought the cheapest package, and couldn't get a refund — a reminder that this is a balance-based purchase, so a trial request up front is worth the email.

👉 [Check 9Proxy's current signup rates and the 5% referred-user discount](https://bit.ly/9-Proxy)

## The full 9Proxy price list, in one place

9Proxy published a rare thing in May 2026: an open pricing-increase post announcing that IP-based and bundle prices would change on **June 1st, 2026**, and that GB-based pricing would stay put. IP rates moved from $0.015/IP at the floor to $0.018/IP. Bandwidth stayed at $0.68/GB at the top tier. That's why you'll find two different sets of numbers floating around in older reviews — anything quoting $20 for 100 IPs is pre-June 2026.

Here's the current lineup. Packages are purchased inside your account after signup, so plan selection happens in the dashboard, not at checkout on a public page.

| Package | Type | What you get | Price | Validity |
| --- | --- | --- | --- | --- |
| 100 IPs | Residential, IP-based | 100 IPs, unlimited bandwidth per IP | $24 | Balance never expires |
| 500 IPs | Residential, IP-based | 500 IPs, unlimited bandwidth per IP | $72 | Balance never expires |
| 1,000 IPs (+500 bonus) | Residential, IP-based | 1,500 IPs, unlimited bandwidth per IP | $126 | Balance never expires |
| 2,500 IPs | Residential, IP-based | Unlimited bandwidth per IP | $210 | Balance never expires |
| 5,000 IPs | Residential, IP-based | Unlimited bandwidth per IP | $360 | Balance never expires |
| 15,000 IPs | Residential, IP-based | Unlimited bandwidth per IP | $720 | Balance never expires |
| 25,000 IPs | Residential, IP-based | Unlimited bandwidth per IP | $863 | Balance never expires |
| 50,000 IPs | Residential, IP-based | Unlimited bandwidth per IP | $1,438 | Balance never expires |
| 100,000 IPs | Residential, IP-based | Unlimited bandwidth per IP | $2,300 | Balance never expires |
| 500,000 IPs | Residential, IP-based | Unlimited bandwidth per IP | $8,625 | Balance never expires |
| 5 GB | Residential, GB-based | Rotating IPs, pay per GB | $15 ($3.00/GB) | 180 days |
| 50 GB (+5 GB bonus) | Residential, GB-based | 55 GB | $105 ($2.10/GB) | 180 days |
| 100 GB | Residential, GB-based | Pay per GB | $150 ($1.50/GB) | 180 days |
| 200 GB | Residential, GB-based | Pay per GB | $200 ($1.00/GB) | 180 days |
| 1,000 GB | Residential, GB-based | Pay per GB | $800 ($0.80/GB) | 180 days |
| 2,000 GB | Residential, GB-based | Pay per GB | $1,500 ($0.75/GB) | 180 days |
| 3,000 GB | Enterprise GB | Team mode, shared bandwidth, logs | $2,160 ($0.72/GB) | No expiry |
| 6,000 GB | Enterprise GB | Team mode, shared bandwidth, logs | $4,200 ($0.70/GB) | No expiry |
| 10,000 GB | Enterprise GB | Team mode, shared bandwidth, logs | $6,800 ($0.68/GB) | No expiry |
| Starter Bundle | IP + GB | 100 IPs + 5 GB | $30 | GB portion 180 days |
| Popular Bundle | IP + GB | 1,500 IPs + 50 GB | $180 | GB portion 180 days |
| Pro Bundle | IP + GB | 5,000 IPs + 500 GB | $720 | GB portion 180 days |

A few things that table hides:

- The **IP-based tiers include unlimited bandwidth per IP**. That's unusual. Most providers bill residential traffic by the gigabyte regardless of how you bought IPs. If your jobs move a lot of data but don't need thousands of distinct addresses, the IP model is dramatically cheaper than it looks.
- The **GB-based tiers include a bonus at two levels** — 50 GB buys 55 GB, and the 1,000-IP tier ships with 500 extra IPs.
- **Enterprise GB tiers don't expire**, and they add team features: one owner plus up to five members, per-member traffic controls, activity logs, and internal bandwidth sharing with no expiration.
- Bundles are the discount vehicle. Starter at $30 versus buying 100 IPs ($24) and 5 GB ($15) separately saves you $9; Pro at $720 versus $360 + $800 separately saves $440.

👉 [Sign up and price the exact plan you need](https://bit.ly/9-Proxy)

## IP-based or GB-based: the decision comes down to one question

Do you need many different IPs, or do you need a lot of data through relatively few?

Broadly:

- **Rotation-heavy, low-data jobs → GB-based.** Each request pulls a few kilobytes. SERP checks, geo-verification, price sampling across a hundred cities, lightweight API polling. You rotate through the whole pool and never think about IP inventory.
- **Session-heavy or data-heavy jobs → IP-based.** Long scraping runs, anything where you hold a connection and stream a lot of bytes, workflows where the same IP needs to persist across multiple requests. The unlimited bandwidth means your cost doesn't move when your data volume does.

The Pro Bundle is the hedge if you genuinely don't know yet — 5,000 IPs and 500 GB together, which lets you route different jobs down different paths without buying twice.

Two limits worth planning around. First, GB traffic on non-Enterprise plans expires after 180 days. That's forgiving compared to monthly competitors, but it isn't infinite — buy volume only up to what you'll realistically spend in six months. Second, IP-based allocations keep their IPs live for **a few hours up to 24 hours per IP**, then they rotate. So this is *not* a static dedicated IP product. If you need an IP that never changes for months, 9Proxy isn't the right tool, and no amount of plan-shopping will fix that.

## What you actually get after you pay

Signup is a normal account creation, then you pick a package in the dashboard. Access comes through several routes, and which one you use depends on your stack:

- **Proxy Program** — a Windows client that routes traffic at the OS level. No per-application config, which matters for software that has no proxy settings of its own.
- **Proxy2Web** — nothing to install. Standard `user:pass` credentials, which is what you want for quick browser checks or an anti-detect browser.
- **ProxyHub / ProxyHub Lite** — mobile device management for switching and assigning proxies remotely.
- **Public API** — programmatic session control and usage stats for automated pipelines.
- **Direct SOCKS5** — drops into proxychains, Puppeteer, Selenium, Playwright, or a Python script without protocol conversion.

Inside the dashboard, the proxy generator lets you choose the authentication method (sub-user credentials or IP whitelisting), set sticky or rotating sessions, filter by country/state/city/ZIP/ISP, and export a `.txt` or `.csv` endpoint list. Code samples in several languages come pre-written.

The Windows-only desktop app is a real constraint. Mac users are limited to the credential-based routes. On macOS you can use Proxy2Web or the API without issue, but there's no equivalent desktop client.

👉 [Create your account and see the dashboard generator in action](https://bit.ly/9-Proxy)

## The honest limitations

Buying advice that only lists strengths isn't advice. Here's what to weigh against the price:

**The pool is smaller than the giants.** 20M+ residential IPs is respectable for the budget tier, but Bright Data, Oxylabs, and Decodo advertise 125M–150M+. For mainstream targets this rarely shows up in results. For narrow regional or rare-ISP targeting, it can.

**Streaming is hit or miss.** Independent reviews have noted that major streaming platforms often block 9Proxy's IPs. If Netflix access is your reason for buying, test before committing to a package.

**Residential IPs don't last forever.** iTWire noted a 60-second replacement window on dead IPs, and the replacement policy comes up repeatedly in user reviews as a genuine strength — you're not paying for proxies that come back dead. But you're still working with rotating residential addresses, not owned infrastructure.

**Refund policy is strict.** One Trustpilot reviewer reported being told no after buying the smallest package by mistake. The pattern in the reviews points the same direction: ask support for a trial first, and treat any purchase as final.

**Payment methods are broad**, which helps: credit cards, bank cards, crypto (USDT, BTC, ETH, LTC, DOGE), Alipay, Apple Pay, Google Pay. Some payment methods carry an extra 5% discount or a 5% product bonus.

**Trials exist but aren't guaranteed.** 9Proxy's own FAQ says a limited trial is available to new users depending on availability, and asks you to specify whether you want IP-based or GB-based access when you request it. Get that in writing before you buy 500 IPs.

## Referred users get 5% off

The referral structure is worth knowing if you're price-sensitive. 9Proxy runs a lifetime affiliate program paying up to 15% commission, and referred users get **5% off**. On the 100,000-IP tier that's over a hundred dollars, so it's not a rounding error at volume.

If you're starting small, the 5 GB tier at $15 is the cheapest way to actually test latency and success rates against your real targets, and the 180-day window means you don't lose the balance if a project stalls.

👉 [Start with the 5 GB package and test your own targets](https://bit.ly/9-Proxy)

## Quick answers

**Is 9Proxy a "private proxy" provider in the strict sense?**
Partially. IP-based plans give your account an exclusive allocation of residential IPs with unlimited bandwidth, but those IPs rotate rather than persisting as a permanent dedicated address. If you need one unchanging IP for months, look at static ISP or dedicated datacenter products instead.

**Do unused IPs expire?**
No. IP-based balances and bundle IP allocations are non-expiring. GB traffic holds for 180 days on standard plans, and Enterprise GB tiers have no expiration at all. Internal Enterprise team sharing also has no expiry.

**What's the minimum spend?**
$15 for 5 GB, or $24 for 100 IPs. Nothing recurring.

**Can I use it with anti-detect browsers?**
Yes — SOCKS5 and username/password authentication are supported, which is what those tools expect. The IP-whitelisting option covers setups that can't pass credentials.

**Does it work for multi-account management?**
It's one of the stated use cases, and reviewers describe using it that way. Assign a stable session per account and rotate between accounts rather than within them — that's a hygiene rule, not a 9Proxy feature.

**Is there a mobile proxy option?**
No. Coverage is residential and IPv4 only, and the datacenter line is listed as coming soon. If you need 4G/5G mobile IPs, that's a different provider.

## The short version

If you searched "buy private proxies" because you want to stop sharing IPs with strangers and stop paying for proxies that come back blacklisted, 9Proxy's IP-based tiers solve that at $24 for 100 IPs with unlimited bandwidth and no expiration. If your jobs are rotation-heavy and light on data, the GB tiers start at $15 and reach $0.68/GB at enterprise volume.

What it won't do is give you a permanent static IP, run natively on macOS, or guarantee streaming access. Price that in before you buy.

👉 [Check today's 9Proxy rates and claim the referred-user discount](https://bit.ly/9-Proxy)
