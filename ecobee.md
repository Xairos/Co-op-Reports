# ecobee

# Who

- ecobee (yes, with a lowercase *e*) is a major player in the smart thermostat space
- value proposition is mostly 

# Milestones and Major Projects

A major pillar of validating the reliability of software in production is **monitoring**, which is the collection and aggregation of metrics about a system. Having metrics allows for building dashboards for introspection, alerting, analyzing trends, and more.

One of the first systems I was exposed to at ecobee was the thermostat backend's monitoring system. This monitoring and alerting system consisted of an stack of Grafana, Prometheus, AlertManager, and PagerDuty. This collection of tools is quite standard across many software organizations, with some organizations opting for cloud-based offerings to replace parts of the stack.

Over the two work terms, I've become a (self-declared) subject matter expert in monitoring methodology and systems. Due to my interest and developing knowledge on the topic, I had the opportunities to:
* build up entire monitoring stacks for a multiple teams
* build a connector for Prometheus to discover Amazon ECS services, now a critical component in the monitoring systems for two products
* monitor systems with CloudWatch (Amazon AWS) logging and alerting
* monitor systems with Stackdriver (Google Cloud Platform) logging and alerting
* learn PromQL to write and manipulate Prometheus queries 
* work in-depth with the Prometheus time series database

I'm proud to have this subject matter under my belt, and I'm very interested to gain experience with distributed tracing and large-scale logging in the future.

# Important Goals

### Get a well-rounded understanding of the responsibilities of a Production Engineer.

My action plan for this goal was to:
    
1. Read Google's Site Reliability Engineering book
2. Enter the on-call rotation to respond to server instability when it occurs and
3. Help with a continuous integration / delivery project

In hindsight, my action plan for this goal was overloaded. I was able to achieve it, though, in part due to the excitement I had to internalize the responsibilities of the role.

Reading Google's SRE book was by far the most useful of the three components, the book was perscriptive and incredibly applicable to the role. It contains a large amount of detail on the philosophy to tackle various SRE topics, such as monitoring (just to pick one). I recommend it to developers interested in reliability topics, and I *highly* recommend it to Production Engineers / SREs.

### Learn the failure response process for end-user-facing services.

This goal was the other half of my on-call aspirations, as I wanted to become a highly effective on-call responder. It turns out that *learning effective on-call by jumping into a rotation does not yeild desirable results*. In reponse to getting paged about an incident, I found myself falling into a fear-based response pattern. Internally I would be panicking, and thus thinking less clearly. I dreaded the next time an alert would come up, because I would feel the panick again.

In my first four months, I did not acquire the calm, rational approach (and other methodologies) that on-call necessitates. Towards the end of my term, I read the SRE book's chapter on effective on-call, which kicked off my quest to learn to do on-call properly.

### Bring a squad's architecture to Kubernetes.

This goal was intended to be a project that I would take on in my own time, in an attempt to both learn Kubernetes through hands on experience, while simulataneously gaining in-depth knowledge of a squad's infrastructure. 

The quarterly hackathon (Hack the Hive) turned out to be an excellent opportunity to attempt this goal.

# Conclusions

I'm incredibly proud of what I learned and accomplished at ecobee.
