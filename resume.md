# Cliff Moon

## Summary

20+ years building distributed systems, performance infrastructure, and engineering teams. Track record of turning ambiguous, high-stakes technical problems into shipped products — from real-time streaming analytics processing terabits per second to AI-powered operational intelligence. Co-founded Boundary (acquired by BMC) and was part of the team that launched Powerset (acquired by Microsoft). Deep expertise in performance engineering, data systems, and applied ML/AI for operational domains.

## Experience

### LinkedIn — Staff Software Engineer
**Aug 2018 – Present** | Remote

- Built the evaluation framework for Observe Agent, LinkedIn's AI-powered alert triage platform. Decided to drop noisy ground-truth evaluation and double down on criteria-based evals with an eval-driven development approach — first team at LinkedIn to ship evals in CI/CD, adopt pairwise evaluation, and run multi-turn evals. This methodology unlocked a plugin ecosystem where teams across LinkedIn contribute domain-specific knowledge into the agent.
- Led the latency reduction effort for Product Experience Monitoring (PEM), one of LinkedIn's highest-scale real-time pipelines (millions of records/sec) and the primary signal product teams use to determine whether their product is up or down. Drove the latency SLO from 20 minutes to 5 minutes by executing multiple technical tracks in parallel: optimizing core pipeline logic, re-architecting the system so latency-sensitive use cases could trade consistency for availability without affecting historical reporting, and completing a high-stakes migration from Samza to Flink. Led a cross-functional team spanning stream processing, site health, and observability.
- Drove adoption of performance regression detection during A/B testing across LinkedIn's experimentation platform (thousands of experiments/month). Built the infrastructure, then used it internally to proactively flag regressions to experiment owners — reducing MTTD from weeks to days. This became the foundation for LinkedIn's "safe ramp" concept, where early operational signals gate feature rollout. Presented at Monitorama 2023.
- Overhauled LinkedIn's Real User Monitoring data processing infrastructure, one of the largest pipelines at LinkedIn (80+ data jobs), serving performance metrics relied on by ~1,000 product engineers. Took data availability from an estimated ~90% to 99% by defining success metrics that didn't previously exist and using them to systematically prioritize upgrades.

### Upguard — CTO
**May 2017 – Jun 2018** | Mountain View, CA

- Diagnosed tooling causing database corruption and data loss on hosted instances, implemented Postgres recovery procedures, and restored data for the largest hosted customer — transforming the platform team from fighting fires to completing their Kubernetes migration.
- Led a greenfield breach-seeking distributed search engine built on Orleans and GKE, shipping a functioning product in a few months with a small team by leveraging Bigtable and Datastore.
- Rebuilt engineering and hiring processes from scratch, including structured interview loops and interviewer training.

### Selected Earlier Experience

- **Opsee — CEO & Co-Founder** (2015 – 2016): Founded a cloud-native monitoring platform. Built the prototype end-to-end, recruited the founding team, and raised seed funding (Heavybit).
- **Thinair — Director of Engineering** (2016 – 2017): Executed a complete turnaround of a stalled engineering team, delivering a full product pivot within five months.

### Boundary — CTO & Co-Founder
**2010 – 2015** | San Francisco, CA

- Built one of the first commercial streaming analytics systems for network monitoring, originally prototyped by repurposing the Cassandra storage engine with custom read/write paths. At peak, processing over a terabit per second and over a million records per second for the largest customers.
- Designed novel architecture for streaming OLAP over high-cardinality network flow data, delivering real-time dataviz that was first-of-its-kind in the monitoring space.
- Acquired by BMC.

### Powerset — Software Engineer
**2007 – 2010** | San Francisco, CA

- Shipped the public beta of a natural language search engine under extreme constraints — half the team quit pre-launch, and infrastructure was rebuilt from scratch on EC2 in the final week.
- Authored one of the first open-source implementations of Amazon's Dynamo paper, contributing to the early NoSQL movement.
- Acquired by Microsoft.

## Education

**University of Delaware** — BS in Computer Information Systems, 2001 – 2005

## Skills

Distributed Systems, Performance Engineering, Streaming Analytics, Data Engineering, Machine Learning, AI/LLM Evaluation, Technical Leadership

## Languages

Java, Scala, Python, Golang, Erlang, Clojure, C, Ruby, SQL

## Speaking & Thought Leadership

- **HBO's *Silicon Valley*, Season 5** — Technical consultant. Produced code screens, kanban boards, and running programs for the show; consulted on technical realism of the season's plotline.
- **Monitorama 2023** — [Performance Testing Experimentation At Scale](https://vimeo.com/843997448)
- **Strange Loop 2014** — [Ludicrous Speed: Designing for Performance on the JVM](https://www.youtube.com/watch?v=X1rWgshr3PY)
- **Erlang Factory 2013** — [Bottleneck Whack-A-Mole at Scale](https://www.youtube.com/watch?v=p7ZocmkXgWY)
