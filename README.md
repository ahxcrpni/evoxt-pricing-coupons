# VPS coupon codes: does Evoxt have a working one, which plan is cheapest, and what actually moves the bill (full plan and add-on table)

There is no Evoxt coupon code you can verify as working. Evoxt's own plan and pricing pages carry one price per plan, with no promo banner and no code field to paste into, and the coupon roundups ranking for this search are listing sales that have already closed or haven't opened yet. The cheapest plan Evoxt lists is **VM-0.5 at $2.99/month** for 1 vCore, 512 MB RAM and 5 GB of storage.

Four things move your final bill more than any code will: which plan you pick, what you bolt on afterwards, the network tier of your region, and how you pay.

> **Quick pick:** for one low-traffic site, a VPN endpoint or a test box, VM-0.75 at $4.99/month (1 vCore, 1 GB RAM) is about the smallest thing worth installing a control panel on. Add Docker, a panel and a database and VM-1.5 at $6.95/month gives you 2 vCores, 2 GB RAM and 20 GB of disk for $1.96 more. 👉 [Check Evoxt's plan list and current prices](https://bit.ly/EvoXt)

## Evoxt's full plan list, with prices

These are the plans Evoxt publishes, in the order they appear, with the monthly price in USD.

| Plan | vCPU, RAM, disk | Price (USD/month) | Who it suits | Order |
| --- | --- | --- | --- | --- |
| VM-0.5 | 1 vCore, 512 MB, 5 GB | $2.99 | A single tiny service, a DNS node, a tunnel endpoint | [Order VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 vCore, 1 GB RAM | $4.99 | One low-traffic site or a personal VPN with a panel | [Order VM-0.75](https://bit.ly/EvoXt) |
| VM-1.5 | 2 vCores, 2 GB, 20 GB | $6.95 | Docker, a panel plus a small database | [Order VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 vCores, 4 GB, 30 GB | $11.99 | A few sites, a small Postgres, a Java app | [Order VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 vCores, 4 GB, 30 GB | $14.99 | Build jobs and anything that wants cores more than RAM | [Order VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 vCores, 8 GB, 60 GB | $23.99 | Multi-site hosting, a CI runner, a mid-size database | [Order VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 vCores, 8 GB, 60 GB | $29.99 | Parallel workloads that fit inside 8 GB | [Order VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 vCores, 16 GB, 80 GB | $47.99 | The last stop before you should be pricing a dedicated box | [Order VM-8](https://bit.ly/EvoXt) |

Two things worth knowing before you treat $2.99 as the annual figure. Evoxt's billing terms run from monthly up to three years, so the checkout total for a longer term is the number to compare, not the monthly sticker. You can also top up account credit and let it apply to future invoices, which keeps a prepaid balance covering renewals.

Every VM includes automatic weekly offsite backup at no cost. There is a separate paid backup plan priced by your VM's disk size if you want more than the weekly copy.

### Add-ons, and what they cost per month

| Add-on | Price |
| --- | --- |
| Extra IPv4 address | $3/month |
| Extra vCore | $3/month |
| Extra 1 GB RAM | $2/month |
| Extra transfer, standard regions | $3/TB |
| Extra transfer, premium network | $12/TB |
| Extra transfer, premium plus | $24/TB |
| Paid backup plan | Priced by VM disk size |

## Building a plan from add-ons costs more than buying the next plan up

Start with VM-0.5 at $2.99. Add 1 GB of RAM for $2 and one vCore for $3 and you're at $7.99/month for 2 vCores, 2 GB RAM and 5 GB of disk. VM-1.5 is $6.95 for the same 2 vCores and 2 GB, plus 20 GB of disk. The plan above is $1.04 cheaper and carries 15 GB more storage.

The pattern repeats one tier up. VM-2 is $11.99 for 2 vCores and 4 GB. Two extra vCores cost $6, taking you to $17.99, while VM-3 is $14.99 for 4 vCores and the same 4 GB.

There is one case where the arithmetic nearly flips. VM-3 plus 4 GB of RAM lands at $22.99, a dollar under VM-4 at $23.99. VM-4 also doubles disk from 30 GB to 60 GB. Pay the dollar.

Add-ons earn their price in two situations: you've outgrown the largest plan, or you need something no plan bundles, like a second IP or more monthly transfer. 👉 [Start with VM-1.5 at $6.95/month](https://bit.ly/EvoXt)

## Your region changes the transfer price by 4x

Evoxt runs nine standard locations: United States, United Kingdom, Canada, Germany, Poland, Amsterdam, Japan (Tokyo), Malaysia and Australia. Hong Kong and Japan (Osaka) sit on the premium network, and Malaysia has a premium option as well.

The plan price isn't where the region bites. Extra transfer is $3/TB in standard regions, $12/TB on premium, and $24/TB on premium plus. Five extra terabytes on a premium-network box costs $60/month, which is more than VM-8 costs before you add anything. If you're serving heavy traffic out of Hong Kong or Osaka, price the transfer before you fall in love with the plan.

Picking the wrong region isn't fatal. Evoxt changes the IP or the server region free through a support ticket.

## Payment method: free but slow, or instant with a fee

Evoxt takes credit and debit cards, PayPal, Bitcoin, USDt on Tron, Alipay and account credit.

Bitcoin and USDT carry no fee but typically take about an hour to confirm, and that hour delays deployment. Card fees depend on your issuer and billing currency. PayPal charges a fee. Alipay is generally the cheaper route for buyers in China. Account credit has no fee and supports auto-pay, so a topped-up balance covers the next invoice without you doing anything.

On a $2.99 invoice a percentage fee stings proportionally more than on a $47.99 one, but in absolute terms it's small change either way. The cost that actually bites is the one-hour crypto confirmation when you're deploying to fix something that's already down. 👉 [Pick a region and deploy](https://bit.ly/EvoXt)

## What the coupon roundups are showing this week

The pages ranking for "vps coupon" are mostly a calendar of sales, and early November is a dead spot on that calendar.

OrangeVPS ran 50% off eligible yearly VPS plans from 8 to 10 October 2026, Singapore time. That discount was recurring for eligible yearly plans, which is unusually generous, and it ended a month ago. HyperHost Solutions closed its Halloween sale on 7 November 2026 at 23:59 GMT, with 50% off recurring on eligible UK KVM VPS plans and UK VPS from £1.50/month during the sale. That closed two days ago. EDIS Global's Black Friday hasn't opened: 25% off annual VPS orders at eight European and US locations plus an 11+1 month structure, running 24 November to 6 December 2026, with a 1 TB traffic credit per new VPS instead of the usual 100 GB. HostDare lists recurring discounts on its Japan, Los Angeles and Bulgaria ranges, but the page carries no dates, so there's no way to tell whether those are current.

None of that puts a working code in your hand today. It does tell you something about timing: if you can wait two weeks, the Black Friday window is when the real discounts land, and you should read whether the discount is recurring or first-term only, whether annual billing is required, and whether orders placed with a code lose refund rights. Several of the sales above attach exactly those conditions.

## Questions people ask before checkout

**Is there an Evoxt coupon code right now?**
Evoxt's plan and pricing pages don't list a promo code or a discount banner. If a third-party page claims one, run the checkout total with and without it before you believe the number.

**Will the price jump after the first term?**
The plan list shows one monthly price per plan, with no separate first-term and renewal column, so there's no teaser rate waiting to expire. What grows the bill is whatever you attach: an extra vCore at $3/month, 1 GB of RAM at $2/month, an extra IP at $3/month, extra transfer at $3 to $24 per TB, and the optional paid backup plan. Those keep billing for as long as you keep them.

**Where do I enter a coupon at checkout?**
There's no public promo field to hunt for. The deploy flow does ask for a 5% affiliate code if someone referred you, and that field is for referral attribution rather than a discount you'll find listed on a deals page.

**Can I stack two discounts?**
There's no public Evoxt coupon to stack, so the question mostly answers itself. The referral field is a single field.

**Can I change region or IP after ordering?**
Yes, and it's free. Open a ticket and Evoxt moves the IP or the server region for you.

**What about refunds?**
Evoxt's plan and pricing pages don't state a money-back window. If you're about to prepay a year or three, get the answer in writing from support first, because a long prepay is exactly the situation where a refund policy matters.

**Does Evoxt run Windows?**
Yes. The deploy flow offers Linux, Windows with RDP on port 3389, and one-click installs for VPNs, server management tools and development environments. Windows won't run usefully on 512 MB, so start at VM-1.5 or above if that's your plan.

**Is Evoxt managed?**
The plan page sells you a VM, a control panel with monitoring, firewall rules, IP management and cloning, plus OS installs. Nothing there describes a managed service, so budget your own sysadmin time.

## Which plan fits your case

One blog, a dev test box or a VPN endpoint: VM-0.5 if you're comfortable on the command line, VM-0.75 if you want a panel running. There's no reason to go higher for a single low-traffic site, and the add-on arithmetic above shows that upgrading beats padding the small plan.

A panel plus Docker plus a database: VM-1.5 at $6.95, or VM-2 at $11.99 when the database starts caching.

Several sites or steady traffic: VM-4 at $23.99 is the first plan where disk stops being the thing you fight.

Windows, or parallel jobs that need cores: VM-6 and VM-8, and check the transfer rate for your region before you commit, because that's the line item that can outgrow the plan.

Three things to confirm at checkout, in this order: the region and its network tier, the total for the billing term you picked rather than the monthly figure, and the fee and delay attached to your payment method. Those three decide what you actually pay. 👉 [Deploy the Evoxt plan you picked](https://bit.ly/EvoXt)
