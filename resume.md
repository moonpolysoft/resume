# Cliff Moon

## Summary

I build things: software, teams and companies. My experience writing software runs the gamut from building greenfield products end to end, engineering distributed systems, tuning high scale software, and fighting the technical debt that rapid scaling inevitably accumulates. My experience building teams specializes in recruiting high potential individuals and creating an environment where they can rapidly level up.

## Experience

### LinkedIn - Staff Software Engineer - Performance Team
*August 2018 - Present*

I started on the performance team as something of a fixer. I quickly gained a reputation of being able to take at-risk projects and turn them around. The first of these was the real-time pipeline for Javascript crash reporting. Undocumented and inherited with minimal hand-off from a departing engineer, I was able quickly identify the missing pieces and design defects that would prevent it from handling production scale. I got the project back on track and was able to deliver it to stakeholders with minimal slippage from the original engineer's estimates. The capabilities delivered allowed web engineers better insights into error rates during canary deployments, allowing them to ship with confidence.

After that project I officially joined the Sitespeed team, which owns Real User Monitoring. As part of Sitespeed I've overhauled our entire data processing pipeline; one of the largest in both scale and complexity within LinkedIn. I worked with senior leadership to develop success metrics to track data availability and correctness, and used those to prioritize the upgrade of our 80+ data processing jobs. 

Building on that technical foundation, most recently I led a cross-functional team to provide insights into performance changes during A/B testing. Based on novel research, the project has driven a massive reduction in MTTD for a large class of performance problems. It's now being used as the basis for the "safe ramp" concept where various early operational signals can be used to prevent regressions during feature rollout. I gave a talk on this work at Monitorama 2023: https://vimeo.com/843997448

### UpGuard - VP of Engineering, CTO
*May 2017 - June 2018*

When I first started at UpGuard my mandate was to grow the team. I took over a hiring process that wasn't working properly, with barely any pipeline and no set out process. I quickly brought in tools to kick-start the hiring pipeline and wrote up interview loops meant to wholistically and fairly evaluate candidates. I conducted interview training with the entire team, preparing them to run the different loops of the interview process.

Shortly thereafter we went through a re-organization and I was promoted to CTO. The platform engineering team was folded into my group and I acquired responsibility for the uptime of our hosted instances as well as the kubernetes migration project for our on-premise deployments. I was able to help the platform team significantly improve the stability of our hosted instances, which were suffering from database corruption and data loss. I gave the team a process to follow for recovering the corrupted Postgres databases and they were able to recover data for our largest hosted customer almost complete. Meanwhile I identified the problematic tooling that was causing the corruption and fixed it. The result was that our platform team went from constantly fighting late night fires to being able to finish their kubernetes migration and monitoring efforts.

One of my last projects at UpGuard was to build a breach-seeking search engine. I split off a very small team to take on this greenfield effort. We were able to very quickly put together a distributed system using Orleans on top of GKS. By using other high-leverage technologies on the Google Cloud Platform, like Bigtable and Datastore we were able to ship a functioning breach search engine on only a few months.

### HBO's Silicon Valley, Season 5 - Technical Consultant
*October 2017 - March 2018*

Produced code screens, kanban boards, and running programs for use in the Silicon Valley TV show. Also consulted on the realism of a number of technical details in the plotline of the season.

### Thinair - Director of Engineering
*September 2016 - May 2017*

Thinair was a turnaround effort. I took over an engineering team that had built a lot of very interesting technology, but they were having trouble getting it into the hands of customers. While there I retooled a hiring process that previously had rejected practically every candidate, resulting in two key hires: a senior backend engineer and an SRE team lead. I resolved conflicts that were causing dysfunction in the team, and I removed engineering process that was causing unecessary friction. By December the team was hitting on all cylinders and we were able to deliver a complete product pivot by February.

### Opsee - CEO / Co-founder
*March 2015 - August 2016*

I implemented the prototype of our product, from backend to frontend, recruited a founding team and raised funding. From there, I built a well rounded and effective team to take the product vision from prototype to market. With the engineering team built out I shifted into sales & marketing, try to drive demand for our product. Ultimately, we built a product we were very proud of, and it had a small cadre of very passionate early users. Unfortunately, the progress we were able to show was not enough to raise another round of funding, and we made the difficult decision to shut down the company. After much self-reflection I decided to concentrate my own personal development around engineering leadership.

### Boundary - CTO / Co-founder
*2010 - February 2015*

At Boundary I implemented the prototype for the backend of the product, originally envisioned as a "Google Analytics for network data". I hacked together a prototype by repurposing the Cassandra storage engine with whole new read and write paths. The prototype got us funding and from there we built the team and developed our technology into a soft real-time streaming analytics system. We were the first commercial monitoring company to offer streaming analytics and streaming dataviz, giving customers unparalleled insights into their network infrastructure. At its peak, Boundary's streaming system was processing over a terabit of data per second, and over a million records per second for our largest customers.

### Powerset - Engineer
*2007 - 2010*

At Powerset I started as a ruby on rails engineer on their product team. My responsibility quickly expanded, however, after half my team quit, leaving us shorthanded in the run up to launch. Despite a dire deadline and crazed requirements like rebuilding our infrastructure from scratch in EC2 a week before launch, I managed to ship the product by the deadline. At Powerset I also wrote one of the first OSS implementations of Amazon's Dynamo paper, helping kick off the NoSQL movement.

### Chariot Solutions - Enterprise Architect
*2005 - 2007*

Chariot is a consulting shop specializing in IT Services for Enterprises in and around Philadelphia. Typically, we got called in whenever either the internal team, management or both had turned a project into an intractable morass. Rotating between contracts for Chariot gave me a great deal of insight into the failure modes for IT projects at a very early point in my career, and how best to turn them around if it was possible.

## Education

### University of Delaware 
*BS in CIS*

### Florida Institute of Technology
*Studied Computer Engineering*
