---
layout: post
title:  "Your Data is an Asset - Protect It"
date:   2026-10-13 17:12:50 -0700
categories: [data-storage, data-security]
---

It's not on your balance sheet, but it may be in your insurance policies. What would you do if you suddenly lost your donor file? Your history of donations? Your program outcomes and client case files? These things are truly irreplaceable, and necessary for future revenue and good decision-making. There are a lot of data vendors, but none can sell you back your proprietary data. It's priceless.

You wouldn't leave your Beanie Baby collection on the front porch, so why is your precious data living in unprotected spreadsheets or a CRM that doesn't keep backups for more than 6 months? 

Data assets also require active maintenance and investments, but I'll cover that another time. It's also common for organizations to store vital information in the brains of their staff, which is another class of problem.

Step 1 is collecting the valuable data. Step 2 is preventing loss, theft, or destruction; controlling access; and keeping some version control. Step 3 is surfacing the polished, verified data you want people to use for decision making.

## You Can't Turn Back Time

Even if your systems have pristine transaction logging and audit trails, it will be difficult or impossible to recreate the state of your data at a prior point. 

Imagine if you or a future leader wanted to know: 
- What did your major gift pipeline look like in 2024, when you projected revenue that year?
- What was the opt-out status of Donor X in 2025?
- What were the demographics of your clients in 2017?
- How many contactable records did you have in 2022?

## Demystifying Data Repositories

The jargon here might suggest that you have to buy an expensive server or software to store and protect your data, or that only large organizations with in-house IT teams can do this. Neither is true! Let's run through some of the terms you'll see, and how you can apply the concept.

- **Data Warehouse**: As you might guess, this is a place to store data. It's safe and secure, and keeps the rain out. Some organizations define a warehouse as a place for only polished datasets ready to deploy. Either way, you'll likely see data tables with labeled columns and rows, and tables linked by ID. "Clean and rectangular" is what you're looking for. A warehouse is typically a database without a visual interface, requiring code (SQL) to navigate. You'll often hear *Postgres*, *Snowflake*, or *BigQuery*.

- **Data Lake**: Data lakes are a place where data is stored in its raw, unstructured form. Data types may need adjusting, tables may not be joined, etc. This data can serve as a backup or historical reference, which is why raw data is typically *not edited* - make a copy and save it elsewhere. Data lakes are more important for organizations with truly vast data, like health systems or ecommerce sites that track your every scroll. You can expect to see stuff like JSON, TXT, and image files, often in formats not designed for human reading (but AI tools can read them just fine). Commonly you'll hear about an *S3 bucket* here, which is descriptive: files are dumped in, and not tidied.

- **Lakehouse**: A faddish portmanteau. You can store both structured and unstructured data in the same place, and just manage the security and governance for the different types. The value proposition here is to add warehouse features like querying, version control, and table linking to a cheap data lake. This can simplify things and save money at larger data volumes.

- **Data Mart**: A data mart is a smaller slice of a warehouse, tailored to one function or team. Imagine the optical department at Costco. If you don't have dozens of siloed data teams, you can ignore this.

- **ETL/ELT**: Extract, transform, load, or the newer variant that transforms last. All you need to know is that this is the automated way to move data through a pipeline from system to system, or system to storage. This is great in a high-volume data environment, but *you don't have to automate this to get the benefit of protecting your data.*

> **My recommendation**: Most small and medium nonprofits will be well served with a single well-permissioned warehouse or disciplined shared drive for data storage. Don't overcomplicate things to start, or rush to buy software.
{: .block-tip }

## Your Next Steps

Start listing your most critical data: what would bring your organization to a halt, tank your revenue, or harm relationships if you lost it? List where it comes from, where it lives, and how often it changes.

Next, find a secure place to store it. That can be a cloud vendor specializing in this work, a dedicated server, or simply a network drive. Make sure this includes off-site backup. If you don't have high-volume data, you'll have much less to worry about with processing speed or storage limits. As long as you have backups, version control, and careful permissions, it's a good start.

Then make a plan to get the data there on a regular schedule. That can mean hiring a data engineer to build an ETL process. It can also mean assigning someone to export data and put it in the warehouse/lake/whatever each week. In either case, *also* assign someone to check that the process is working as expected and test your backups.

Last, *use* your stored data for reporting. Whether it's in Excel, Tableau, Looker, or Power BI, your monthly KPIs and quarterly board reports should all be using data from a protected store. It also gives you a regular check that your storage process is working.

## Good Governance

It is cheap and easy to store data in perpetuity. Don't forget to implement your data retention policies, though. Often, you should delete some data after a number of years. This is typically going to be personally identifiable information, not summary information about your programs or finances. Good data governance means consistent retention practices across your systems and files.

## That's It

Seriously. You can do much more with vendors and software and business intelligence tools - someday. But start by putting your assets in a safe place, and keeping the rain out. Aside from time, it's nearly free to take care of your priceless data.

In the future, your organization may have an amazing data analyst or swarm of AI agents who can digest your raw data and spin it into insights. That won't be possible if the data is left on the front porch.