---
layout: post
title:  "Developing Trust in Fundraising Data"
date:   2026-06-28 17:12:50 -0700
categories: insights, data governance
---

## A Sinking Feeling

Once, a few weeks into a new job, I got a pretty straightforward request: "Jon, can your team get us the Q2 board report?"

A sudden pit of dread in my stomach. Of course we can produce a report - *but what if no one trusts it?* Because this team had no data dictionary, no practice of documenting data sources, and no established process for data validation. How could *I* trust the data, let alone the board?

We did of course produce the report, but the experience highlighted the importance of building trust in data through clear definitions, documentation, and validation processes. It was not a pleasant experience to deliver a report like this, not knowing how it would be received: Would it match what they were used to? Would the executive team have a dozen questions about the data? Do they prefer bar charts instead of lines?

## Start with Shared Definitions

A complete data dictionary is a very useful thing to reference and share internally, but it's not always feasible to share with external users, or easy enough to provide context on a single report. I always advocate for including a summary of definitions, filters, and data lineage directly on a report. This means everyone interpreting the data starts from the same understanding, and no assumptions are unstated.

> The questions we want are "Why did this change?" or "How do you plan to continue this success?" - not "What does 'dollars raised' mean?"

Fundraising definitions can be pretty straightforward, but consistency on things like pledges and payments, in-kind vs cash, received vs deposited, and recognition of planned gifts will build familiarity and trust over time. We always have a layer of translation between fundraising and finance, and repetition will build strength there - we don't *match*, we *reconcile*. Different numbers for different purposes.

## Validate and Document

For organizations on the left end of the data maturity scale, *who* created a report is often the indicator of trust: If Patricia delivered it, we know it's good because she is extremely diligent and knows this report is important. If Jon is the only one around when I need it, maybe I will wait until Patricia is back.

As we develop our data maturity, we shift from individual ownership of a *product* (a report, dashboard, or dataset), to ownership of *the process to develop a product*. This means establishing standardized procedures, validation checks, and documentation practices that ensure consistency and reliability, regardless of who is producing the report. Then, any member of the insights team can produce the product; they will know what query to run, what filters to check, which outliers to remove, what report to validate against, and what type of annotations should be added. Ideally there's a checklist.

We can also be explicit about the level of validation. With the rise of self-service reporting and accessible data warehouses (lakehouses if you're fancy), users need to be able to distinguish between the levels of validation. There are 3 levels typical for data-mature organizations, which many business intelligence tools support with official tagging.

### 1. Certified
Certified, including whatever gold star or badge your BI tool uses, indicates that the data has been thoroughly validated and is considered reliable for decision-making. Board reports on fundraising progress, individual metrics, and other key performance indicators typically fall into this category. If a program might get additional investment or a staff member's performance evaluation is on the line, this product deserves our highest level of attention. The data lineage must be pristinely documented, and outputs checked against finance reports and other certified data. And yes, this does become a bit of a chicken-and-egg situation when you're first starting; I'd recommend validating against your 990 to start.

Certified products should be developed to the point where we don't rely on clunky formulas that require manual edits. The dataset, report, or dashboard must be reviewed by the senior data leader to ensure standards of documentation, design, and reliability are met.

### 2. Promoted
Promoted indicates that the data has undergone some level of validation and is considered reliable for most decision-making purposes, but it may not have the same level of scrutiny as certified data. These reports are suitable for internal use and operational decision-making, where the impact of potential errors is lower. Promoted data should still have documented lineage and validation checks, but the requirements are less stringent than for certified data.

### 3. Unpromoted
Unpromoted data has not undergone formal validation and should be used with caution. These reports are typically used for exploratory analysis, ad-hoc queries, or internal experimentation. Users should be aware of the potential for errors and understand that the data may not be fully reliable for decision-making purposes. Documentation and lineage may be minimal or absent, and validation checks are not guaranteed. Users should be trained to request validation or clarification when using unpromoted data for critical decisions.

## Train Your Users
Training users on the different levels of data validation is crucial to ensuring they use the data appropriately. Users should understand the implications of using certified, promoted, and unpromoted data, and be equipped to make informed decisions based on the reliability of the data they are accessing. If you use a data warehouse, make sure that users are aware of the tagging system and know how to interpret the validation levels when accessing reports and dashboards. If you keep a library of reports and datasets, show this tagging there.

I've found that constant communication is as important for maintaining trust as the initial training sessions. If a new certified report is released, share an update - and a link - in your newsletter or internal communication channels. If a promoted or unpromoted report is upgraded, celebrate that achievement and inform users of the improvement. One of my favorite moments at work recently was when we shared a chart about restricted vs. unrestricted donations by region with the whole fundraising team, and a colleague who wouldn't normally look at this kind of information was suddenly *data curious* and had several follow-up questions.

## Conclusion
You will likely still have "oh crap" data requests every once in a while. But if you build a foundation of trust, validation, and communication, you'll have fewer. Over time, you should also be building up a library of reliable, well-documented reports and datasets so that something like the Q3 board report is ready before it's asked for. Assuming those are designed well to meet the evergreen needs of the organization, you'll then be properly doing ad-hoc work at the unpromoted, exploratory level, and doing scheduled maintenance on certified and promoted products.

If you're just getting started with building or rebuilding your reporting infrastructure, my friend Chris Cannon has some great recommendations for baseline reports in his book *An Executive's Guide to Fundraising Operations*. There you'll find a solid list of 5-10 products to build first, in addition to a ton of great advice on data hygiene, CRM maintenance, prospect development, and more. These days you can also find Chris at https://generositycollaborative.org.