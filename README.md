# gate alpha: what the 0.8% fee, the Alpha Points ladder, and airdrop tiers mean before you start trading

If you searched "gate alpha" because someone told you it's a free way to buy early on-chain tokens, you're working from a 2025 version of the story. The part that changed is the part that costs you money, and almost none of the guides still ranking for this topic mention it.

So let's go through what Gate Alpha is today, what the fee page actually charges, how the Alpha Points ladder translates into real numbers over its 15-day window, and where the whole arrangement stops being worth the effort.

## What Gate Alpha is, in one paragraph

Gate Alpha launched in May 2025 as an on-chain token venue living inside a normal Gate exchange account. You deposit USDT to your spot account, search a token, and buy it with the same order ticket you'd use for BTC. No Web3 wallet, no seed phrase, no manual bridging, no repeated token approvals. Cross-chain routing is handled for you.

Chain coverage has grown well past the launch set of Ethereum, Solana, BNB Chain and Base. Gate's February 2026 airdrop announcements list support for SOL, ETH, Gate Layer, BNB Chain, Base, SUI, ARB, World Chain, AVAX, Polygon, LINEA, ZK, OP and Berachain, with more being added. Gate has also said it aggregates launchpads like Pump.fun, Bonk.fun and Believe, which is how tokens show up on Alpha within minutes of going live elsewhere.

Two things follow from "no wallet," and both matter:

- Your Alpha positions sit in Gate's custody, in its hot wallets. You're trusting the exchange's security and its terms, not a self-custodied key.
- You can't take an Alpha token out to a DEX and trade it there. What Gate lists is what you can trade, and Gate has explicitly reserved the right to delist tokens.

## The 0.8% fee almost nobody mentions

Gate's own fee overview page now carries a column for Alpha trading, and it reads **0.8%**. The same number appears at VIP 0 and at VIP 16. It never drops.

Put that next to the standard spot rate of 0.10% at VIP 0 and the gap is easy to see: an Alpha trade costs about eight times a base-tier spot trade, and unlike spot fees, no amount of volume or GT holdings will move it.

This contradicts a lot of published material, including Gate's own older Learn articles, which describe a permanent zero-fee policy introduced on 29 May 2025. That campaign existed. It is not what the fee page shows today. If you're planning a strategy around "Zero fees," you're planning around a page that hasn't been updated, and your cost estimate is off by 0.8% of every rotation you make.

### What 0.8% does to a points-farming plan

This is where the fee stops being trivia. Alpha Points are earned partly through daily trading volume, and volume is charged at 0.8%. Run the ladder against the fee and you get a price tag per point:

| Daily Alpha volume | Points per day | Points over 15 days | 15-day volume | Fee at 0.8% |
| --- | --- | --- | --- | --- |
| $4 | 1 | 15 | $60 | ~$0.48 |
| $16 | 3 | 45 | $240 | ~$1.92 |
| $64 | 5 | 75 | $960 | ~$7.68 |
| $128 | 6 | 90 | $1,920 | ~$15.36 |
| $1,024 | 9 | 135 | $15,360 | ~$123 |

The arithmetic is straightforward: because the trading ladder doubles the volume requirement for each additional point, the cheapest points are always the first ones. Going from 1 point a day to 9 points a day multiplies your fee bill by roughly 256 while multiplying your points by 9.

If your goal is a points balance in the 130–180 range that recent GT airdrops have required, the cheapest route is steady volume at the $512–$1,024 a day rung, which lands you around 8–9 points daily and roughly 135 points in the rolling window. That's about $123 in fees every 15 days, plus the opportunity cost of trading tokens you may not want to hold.

There's a detail worth checking on the live page before you build anything on this: the Alpha Points page states that trades in the Alpha market count toward volume whether you buy or sell, while several older Gate guides say only buys count. If both legs count, a $4 buy and a $4 sell counts as $8 of daily volume for about six cents in fees. Confirm it in the app, because the difference between those two readings is large.

## Alpha Points: the rules as the product page states them

The points system went live on 29 July 2025. Points aren't cash and can't be swapped for tokens or rebates. They're an eligibility filter: they decide whether you can claim Alpha airdrops and subscribe to TGEs, and they get spent when you claim.

There are three sources.

**Asset points.** Daily snapshot of eligible assets in your Gate account, converted at USD market value:

- $100 to just under $1,000: 1 point per day
- $1,000 to just under $30,000: 2 points per day
- $30,000 and above: 3 points per day

Eligible means Alpha account balances plus tokens listed on Gate's spot market. Balances sitting in other account types, like the unified account or margin account, are excluded, and unlisted tokens don't count. Holding $30,000 in eligible assets produces 45 points in a window with zero trading, which is a meaningful chunk of a tier-2 airdrop requirement.

**Trading points.** A daily volume ladder. The base rung is $4 of Alpha volume for 1 point, and the award increases by one point each time the volume doubles: $8 for 2, $16 for 3, $32 for 4, and so on up to a cap of 20 points per day at $2,097,152 of volume. The current page gives the example that $31 in a day earns 3 points and $33 earns 4, which matches the doubling thresholds.

**Special points.** Periodic token campaigns can pay bonus points or apply multipliers. Rules vary by announcement, so there's nothing general to plan around.

### The 15-day window is the whole game

Your displayed score is the sum of the last 15 days of daily points, minus points you've spent. That design choice matters more than any individual rule:

- The daily snapshot is taken at 07:59:59 UTC+8, and the score refreshes before 14:00 UTC+8. Trades completed after 08:00 count toward the next day.
- Points expire out of the window automatically. Two weeks of activity then two weeks of silence leaves you at zero, not at your earlier balance.
- Subaccount balances and volume are merged into the main account, but only the main account is eligible. Splitting activity across accounts doesn't multiply your score.

So the real target isn't a points balance. It's a maintenance rate. Tier 2 in the round-169 GT airdrop needed 165 points, which over 15 days means 11 a day. If you're holding $30,000 in eligible assets for 3 of those, the remaining 8 have to come from trading, which is the $512-a-day rung. Anyone who earns 90 points in a burst and then stops for ten days will find themselves below the threshold when the next announcement drops.

## Airdrops: short windows, spent points, no second chances

Three real examples show how the mechanics feel in practice.

The RION airdrop was open to users with 65 or more Alpha Points. The BTR airdrop on 27 August 2025 set a minimum of 125 points, deducted 12 points on claim, and gave each eligible user 60 BTR on a first-come-first-served basis.

The GT airdrop in round 169, in late February 2026, was tiered:

- 130 to 164 points: claim cost 11 points, reward 0.5 GT
- 165 to 179 points: claim cost 13 points, reward 1.3 GT
- 180 and above: claim cost 14 points, reward 2.6 GT

The claim window ran from 09:00 to 09:10 UTC. Ten minutes. Claiming required the app at version 7.20.0 or higher, or the web version if you hadn't updated. Unclaimed rewards are treated as forfeited, and credited rewards usually land in your Alpha account within about an hour. You can't pick your own tier, and each airdrop can only be claimed at one level.

Two practical consequences. First, points are consumable, so a 165-point balance that spends 13 points is a 152-point balance the next day, and the rolling window will keep eroding it. Second, a 10-minute window means airdrop participation depends on being reachable at the announced time. If that doesn't fit your life, the points you're paying fees to accumulate are worth less than the fee table suggests.

## Does the early-listing advantage hold up?

The pitch for Alpha is speed. A data review published by Cointelegraph China covering Gate Alpha's listings from late April to 20 July 2025 reported 1,285 tokens listed in that stretch, of which 335 qualified as hot tokens with peak FDV above $20 million. Ninety-eight, or 7.6% of all listings, met the outlet's "new blue chip" bar. It also reported that 96.15% of hot narrative leaders listed on Gate Alpha before comparable CEX Alpha sections, with an average lead of one to three days.

The same dataset contains the less comfortable half. Leader tokens averaged 69.23% of their narrative sector's market cap while accounting for 18.56% of the projects, so returns concentrated in a small number of winners rather than spreading across the list. The $20 million FDV threshold that defines a "hot" token is not a high bar by current standards, and the sample only covers a three-month window in a rising market for on-chain launches.

Gate's own published figures are cheerier and should be read as such. By November 2025, the company said it had run 103 airdrop rounds covering more than 30 tokens, with over 2 million participations, a single-round maximum reward of $446 and a single-user cumulative maximum above $6,400. Those are maxima. They are not what a typical participant earned, and no median was published.

None of this argues that early listings don't matter. It argues that a listing on Alpha is a sourcing signal, not a return. The tokens Gate fast-tracks include plenty that fade within weeks, and the risk screening Gate describes, contract checks, holder distribution analysis and insider-wallet detection, filters obvious problems rather than predicting price.

## Every VIP tier, since the fee structure shows up in this decision

Gate runs 17 VIP levels on its cross-exchange account fee schedule. Tiers are assigned automatically on whichever of three measures is highest: 30-day weighted trading volume, 14-day average GT holdings, or the VIP upgrade asset value. Volume counts at full weight for spot (including convert) and stocks, 40% for USDT/BTC perpetuals and USDT delivery futures, 20% for USD1 contracts and options, and 10% for CFDs. Upgrades that come from the volume track get a 60-day protection period, after which a tier can step down every 15 days if the volume isn't maintained.

| VIP level | 30-day volume (USD) | Spot maker/taker | Paid in GT | Alpha fee | 24h withdrawal limit |
| --- | --- | --- | --- | --- | --- |
| VIP 0 | — | 0.1% / 0.1% | 0.09% / 0.09% | 0.8% | $3,000,000 |
| VIP 1 | 60,000 | 0.099% / 0.099% | 0.089% / 0.089% | 0.8% | — |
| VIP 2 | 120,000 | 0.098% / 0.098% | 0.088% / 0.088% | 0.8% | — |
| VIP 3 | 240,000 | 0.097% / 0.097% | 0.087% / 0.087% | 0.8% | — |
| VIP 4 | 500,000 | 0.095% / 0.096% | 0.086% / 0.086% | 0.8% | — |
| VIP 5 | 1,000,000 | 0.09% / 0.095% | 0.081% / 0.085% | 0.8% | $5,000,000 |
| VIP 6 | 3,000,000 | 0.085% / 0.09% | 0.076% / 0.081% | 0.8% | — |
| VIP 7 | 8,000,000 | 0.08% / 0.085% | 0.07% / 0.076% | 0.8% | — |
| VIP 8 | 20,000,000 | 0.075% / 0.08% | 0.06% / 0.072% | 0.8% | — |
| VIP 9 | 50,000,000 | 0.07% / 0.075% | 0.05% / 0.068% | 0.8% | $8,000,000 |
| VIP 10 | 100,000,000 | 0.04% / 0.058% | same as VIP | 0.8% | — |
| VIP 11 | 120,000,000 | 0.03% / 0.045% | same as VIP | 0.8% | — |
| VIP 12 | 240,000,000 | 0.02% / 0.037% | same as VIP | 0.8% | $10,000,000 |
| VIP 13 | 440,000,000 | 0.01% / 0.03% | same as VIP | 0.8% | $20,000,000 |
| VIP 14 | 800,000,000 | 0.008% / 0.023% | same as VIP | 0.8% | $30,000,000 |
| VIP 15 | 1,600,000,000 | 0% / 0.02% | same as VIP | 0.8% | $40,000,000 |
| VIP 16 | 3,000,000,000 | 0% / 0.0175% | same as VIP | 0.8% | $50,000,000 |

Two footnotes from that page are worth knowing. From VIP 10 upward, paying in GT stops producing a lower spot rate, so the token's fee benefit disappears exactly where volume gets large. And regular VIP users can't climb to VIP 15 or 16 through the standard tracks; accounts with at least 60% of volume coming through API, or those already at VIP 15/16, get reclassified as senior institutional users instead.

The one thing this table demonstrates for Alpha specifically: none of it changes your Alpha cost. [👉 Open a Gate account through the referral link](https://bit.ly/GateVIP) if you want to check your own tier and fee schedule once you're logged in, but don't sign up expecting VIP status to reduce Alpha fees. It doesn't.

## Getting set up without wasting the first week

The setup itself is quick, and the version requirements are the part people trip over.

1. Register an account and complete identity verification. KYC is required before you can receive any Alpha airdrop, and it isn't optional for reward claims even if you only want to trade.
2. Install the app at version 7.3.0 or higher for Alpha trading, 7.14.0 or higher to view Alpha Points, and 7.20.0 or higher for tiered airdrop claims. The claim flow is also available on web, which is worth remembering if you don't want to be tied to your phone during a 10-minute window.
3. Fund the spot account with USDT. Alpha trades settle out of spot balances, and selling returns USDT there without a manual transfer step.
4. Sign the innovative-trading disclaimer. First-time Alpha users have to accept a separate user agreement before trading. It exists because these tokens carry volatility and contract risk that listed spot pairs generally don't.
5. Decide your maintenance rate before you start, not after. If the goal is a 130–180 point range, the cheapest combination is usually a standing eligible balance plus low-rung daily volume, because the ladder rewards the first few dollars far more than the last few hundred.

[👉 Create the account with the referral link here](https://bit.ly/GateVIP). Gate's own announcement pages advertise signup rewards of up to $10,000 and a 40% referral commission, which are promotional terms rather than a reason to trade more than you'd otherwise.

## Who should skip this

Gate Alpha is a reasonable tool if you already trade on Gate, you want exposure to on-chain tokens without wallet management, and you're treating the fee as the price of convenience rather than a rounding error. The points system rewards consistency over enthusiasm, which suits people who are on the platform daily anyway.

It's a poor fit if any of the following apply:

- You're planning to farm points at high volume to chase tier-3 airdrops. At 0.8%, the fee bill scales faster than the reward tiers do, and Gate's published maximums are not typical outcomes.
- You need self-custody. Alpha holdings are in Gate's wallets, and the tokens aren't portable to a DEX.
- You're in a restricted region. Gate's airdrop announcements exclude the UK and other restricted locations from these services, and you should treat that as binding rather than as fine print.
- Multiple accounts look tempting. Mass subaccount registration, wash trading and self-trading are explicitly prohibited, and Gate states that different accounts belonging to the same verified user are treated as one.

One more thing worth saying plainly: the restricted-region list, the disclaimers, and the forfeiture rules for unclaimed rewards are all the same category of information. They're the parts of the terms that cost you money when you discover them late. Read them on the day you sign up, not on the day an airdrop appears in your feed.
