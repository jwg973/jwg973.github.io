---
layout: post
title:  "Identifying Millionaire Next Door Estate Gifts"
date:   2026-06-20 11:12:50 -0700
categories: insights, planned-giving
---

## The Biggest Gifts We Don't See Coming

When I first worked in private higher ed, I was surprised by the frequency of sizable estate gifts from alumni, and occasionally from someone who lived down the street, or who once babysat the president when he was a child. A subset of these gifts are surprisingly large: millions of dollars from individuals who lived modestly and quietly, embodying the "Millionaire Next Door" archetype. Some had inherited the funds at a point in life when they had no use for them, or didn't feel they had a right to spend them, according to contact reports.

These gifts often arrive as a complete surprise, both in timing and magnitude, challenging our assumptions about who is capable of making a significant impact. If they happen without our efforts, what might happen if we actively sought to identify and engage these donors?

## When Wealth Screening Fails Us

Wealth screening can be useful in many ways, but the reliance of traditional models on real estate — often real estate *alone* — can completely miss accumulated wealth. Moving is a hassle and we like our gardens, so many of us don't upgrade our primary residence with every increase in wealth. As prospects move into their 80s and 90s, this can mask serious wealth when there are no other indicators to catch it.

Newer models that estimate net worth using income, savings, investments, and other assets give a more directionally accurate picture. But the bigger leap isn't in estimating wealth, it's in understanding the *disposition* of that wealth: not just what someone has, but what they intend to do with it. We sometimes learn the names of donors' children through contact reports, but most "presence of children" demographic indicators are designed for marketing diapers, not for predicting how many grandkids' tuition someone is paying.

That gap between what wealth screening suggests and the actual impact of these large bequests is what inspired me to explore how we might predict and engage these donors more effectively.

## Three Signals

**Net worth** Look beyond lifestyle indicators toward quiet wealth: acquired investment properties (particularly if you can distinguish inherited properties from those purchased at market price), trust ownership, and — if you've saved the data over the decades — historical wealth screenings of alumni *parents*, which can flag a likely inheritance.

**Family structure** This is often the biggest distinction between a large bequest and a token gift. Donors worried about leaving "too much" to their heirs are usually well beyond "millionaire next door" territory already. Most people with "regular" seven-figure wealth still feel responsible for their children's and grandchildren's wellbeing — it's the donors who never married and never had children who are most likely to leave substantial gifts to institutions or causes instead. To find them: look for "no children" data (including adult children), possible marital history through name changes (or the lack of one) and property ownership, and — that crucial "P'12" indicator — giving to K-12 or higher education institutions other than your own.

**Planned giving likelihood** Classically measured by the frequency and length of annual giving, though machine learning models may offer better signals for a specific institution. Engagement with planned giving events and materials helps too, but some donors will show no indicators at all, having simply written your organization into their will.

Put together: accumulated or inherited wealth that won't show up in lifestyle indicators, a lack of heirs (a difficult null hypothesis to test), and planned giving flags that may or may not exist. What can we make of that?

## From Signals to a Shortlist

Most organizations need to work these signals in bulk rather than through manual research. Quiet wealth can be assessed through net worth estimates, trust ownership, and multiple properties. Data appends can flag who likely has no direct heirs. Planned giving intention is the real black box, and also the one area where we, as fundraisers, actually have influence.

What I built combines these signals into a scoring model that prioritizes outreach and surfaces high-potential estate gift prospects: 
- Alumni or other close affinity + 
- Modeled or suspected net worth above a chosen threshold (I used $2M) + 
- An apparent lack of heirs

This was sorted by planned giving likelihood.

I also added an aspirational bequest rating of roughly 30% of estimated net worth, with a clear note to fundraisers on its source and methodology. In practice, some donors with no heirs give 50% or more to a single institution, but I'd rather stay *somewhat* conservative on a number that flows into projections.

## Did It Work?

This was a hard model to validate as we don't typically include deceased records in data appends, and net worth and "presence of heirs" are both relatively new data products. But the approach held up where it mattered. Gift officers ran discovery conversations with this pool to check three things: 1. did the person actually appear to have no heirs, 2. did they have capacity for a significant gift, and 3. did they show any inclination toward planned giving?

The results were encouraging, turning up sizable bequest prospects from both "classic" estate candidates with decades of consistent giving, and from infrequent or non-donors who'd never shown up on anyone's radar before.

## Gaining Trust and Adoption

Compared to the black box of some machine learning models, this one was easy to explain, and planned giving from otherwise modest donors was already a familiar pattern on this team, which made buy-in straightforward. The list came with enough context to work with, not just a score: planned gift likelihood, number of properties, lifetime giving stats. That let gift officers sort and prioritize the pool together, rather than just trusting a number - and, as always, spot the records missing a phone number or email address.

## What I'd Try Next Time

I'd start the whole project with a strong partner on the gift planning team, rather than bringing them in later — both to sanity-check it from a fundraising perspective and to make sure it didn't cross wires with another initiative already underway.

I'm also interested in moving earlier: could a planned giving program flag "no heirs by age 50" and start marketing the *idea* of a bequest well before any of these signals mature? We probably can't influence whether someone spends or saves a late-in-life inheritance — but we might be able to remind them of their affinity for our institution, and the importance of putting their wishes in writing, both in a will and with us directly. The 7-figure bequests are exciting to find this fiscal year, but any bequest is worth consistent marketing efforts.

And, difficult as it would be politically, I'd hold back a test set — a group identified by the model but left alone — to see whether any of them made a bequest anyway, untouched by our outreach. Would a future fundraiser override that test, unconvinced by any appeal to the scientific method? I predict so.

[^1]: [It's Time to Rethink the Great Wealth Transfer](https://imarketsmart.com/learn/its-time-to-rethink-the-great-wealth-transfer/)