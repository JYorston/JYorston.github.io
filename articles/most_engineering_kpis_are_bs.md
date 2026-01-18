---
layout: default
title: "Why Most Software Engineering KPIs are Bullshit and What to Do About it in 2024"
date: 2023-12-01
excerpt: "The often inevitable truth of becoming an engineering leader is that you get further and further away from the code."
---

# Why Most Software Engineering KPIs are Bullshit and What to Do About it in 2024
---

#### Most engineering KPIs are bullshit. 

The often inevitable truth of becoming an engineering leader is that, eventually, you will have to start providing metrics on the health, productivity, and output of your teams. In startups, this question typically stems from the CEO, the argument - *"We need a clear way to measure progress"*. A reasonable enough request, why should Engineering not be held accountable in the same way, as perhaps a sales team is?

Unfortunately, this is quite a complex question; it's one that I have struggled to articulate in executive meetings and to the wider business in the past. Nevertheless, over the years, I have always given my answer with the same opening line. 

*"Most engineering KPIs are bullshit."*

To explain why, I turn to McKinsey's foray into measuring developer productivity. Their article released in August of 2023 titled *"Yes, you can measure software developer productivity"* ruffled a few feathers, to say the least. 

Now, I would recommend reading McKinsey's article. It certainly offers a perspective. A perspective that I argue is misguided and aimed clearly at non-technical people who have never had to actually build or run a high-performing engineering team. But, (and it's a big but), the fact this article exists demonstrates that, to date, CTOs, and Engineering leaders have not been very good at answering these sorts of questions.

Lets draw some comparisons to another department that are quite good at answering the productivity question. Sales. Sales, at it's core boils down to impact- How much did the individual or team close in deals? and "How has this affected the company target for the year". There are layers to this; it could be a new business, retained business...etc. I'm not a sales expert, but I've worked closely with a lot of salespeople in my time, and generally, their level of accountability is high. In return, executives know where sales stand at any point, as it's relatively simple to understand the department's overall performance. 

In the search to provide engineering metrics, engineering leaders (and sometimes non-technical executives) have often made the poor choice to measure output rather than impact. Some examples: Story points delivered per sprint, pull requests submitted. That's because these metrics are much easier to measure and provide at least an answer compared to the much more nuanced and complex to answer "What was the impact of this work?". 

#### Most engineering KPIs are bullshit. 

Yes, these are bullshit metrics. They tell you nothing, and crucially, they miss the mark on measuring impact. Additionally, I'd cite Goodharts law here. As soon as you create these metrics, then people will game them. Have a read about what happened at Uber when they started to use metrics like this. 

Now, there are a few frameworks that are well respected in the engineering world: DORA, SPACE and, more recently, DevEx. These are useful tools to answer the KPI question, and indeed the recent DevEx paper has a section explicitly discussing KPIs. I encourage everyone to read them, and they have certainly informed and changed my opinion slightly in 2023. In fact, the Mckinsey Article uses DORA and SPACE as the basis for its methodology, with some interesting additions. But that also highlights the danger of using these tools in isolation - after all, a bad carpenter always blames his tools!

So, how do you measure engineering productivity, and what sort of KPIs should you set?

In 2024, this is my answer:

First of all, separate engineering health metrics to KPIs. The DORA, SPACE and DevEx frameworks give good ideas on how to set good health metrics. Examples: Cycle Time, Bug Rate, Engineer Sentiment. Watch these closely; high metrics here indicate a healthy engineering setup but don't necessarily mean that the work that is produced is moving the needle for the business. 

Next, set KPIs that measure business impact. It's very hard to tell you what these should be as they will be specific to each company. But, a general philosophy could be to measure each potential product or engineering change in terms of $ value for the company. Then, measure if the work delivered on that and how it compared against a different task. 

Amazon has a variation of this in their "Customer Obsession" mindset. It's not measured in dollars but instead value to the customer. Choose metrics that align with the vision of your business. 

By aligning KPIs to business value, it becomes easier for everyone in the organisation to understand the progress being made. This approach also ensures a high level of accountability for the work that is being done. With KPIs based on business value, executives can easily track how engineering is impacting the company and use this information to make informed decisions about investment and performance. The CTO and engineering leaders can monitor the separate health metrics and improve these as they see fit. Having both sets of metrics high indicates a truly high-performing engineering department.  


So, to conclude. Most engineering KPIs are bullshit - but they don't have to be!

Software engineering is still a young field. Internet companies as a concept are at most 30 years old. Software engineering is the lifeblood of all of these organisations, and we're still learning what it means to build and measure engineering effectively. 

If your organisation is using output-based metrics to evaluate engineering performance, I urge you to reconsider, tie engineering into your vision and measure its progress against actual business impact. 

--- 

References: 

McKinsey Paper - [Yes, you can measure software developer productivity](https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/yes-you-can-measure-software-developer-productivity)

Uber - [Measuring Developer Productivity](https://newsletter.pragmaticengineer.com/p/uber-eng-productivity)

Amazon - [Customer Obsession](https://aws.amazon.com/executive-insights/content/the-imperatives-of-customer-centric-innovation/)


Frameworks: [DORA ](https://docs.gitlab.com/ee/user/analytics/dora_metrics.html), [SPACE](https://queue.acm.org/detail.cfm?id=3454124), [DevEx](https://queue.acm.org/detail.cfm?id=3595878)


