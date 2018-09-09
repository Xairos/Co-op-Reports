# Introduction

In January 2018, I joined the Production Engineering team at ecobee for my final 8 months of co-op. The PE team maintains the reliability of the production systems, using core principles from engineering (compared to traditional operations). 

The term "Production Engineer" is used at companies such as Facebook, but is a relatively uncommon term in the software engineering field. Thus, around June, the team rebranded to Site Reliability Engineering (SRE). The principles and role remained the same, but the responsibility of maintaining "Site Reliability" became self-evident in the name.

![ecobee Logo][ecobee-logo]

ecobee is a major player in the smart home space, with multiple smart thermostat products. Other products include a smart light switch, which I had the opportunity to help launch. Reducing carbon footprints and saving energy are core values to ecobee.

# Milestones and Major Projects

I learned an incredible amount during my time at ecobee. Monitoring and on-call were two of the major topics I undertook during my terms.

## Monitoring

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

# Most Important Goals

## Get a well-rounded understanding of the responsibilities of a Production Engineer.

My action plan for this goal was to:
    
1. Read Google's Site Reliability Engineering book
2. Enter the on-call rotation to respond to server instability when it occurs, and
3. Help with a continuous integration / delivery project

In hindsight, my action plan for this goal was overloaded. I was able to achieve it, though, in part due to the excitement I had to internalize the responsibilities of the role.

Reading Google's SRE book was by far the most useful of the three components, the book was perscriptive and incredibly applicable to the role. It contains a large amount of detail on the philosophy to tackle various SRE topics, such as monitoring (just to pick one). I recommend it to developers interested in reliability topics, and I *highly* recommend it to Production Engineers / SREs.

## Learn the failure response process for end-user-facing services.

This goal was the other half of my on-call aspirations, as I wanted to become a highly effective on-call responder. It turns out that *learning effective on-call by jumping into a rotation does not yeild desirable results*. In reponse to getting paged about an incident, I found myself falling into a fear-based response pattern. Internally I would be panicking, and thus thinking less clearly. I dreaded the next time an alert would come up, because I would feel the panic again.

In my first four months, I did not acquire the calm, rational approach (and other methodologies) that on-call necessitates. Towards the end of my term, I read the SRE book's chapter on effective on-call, which kicked off my quest to learn to do on-call properly.

### On-call, done right

On-call rotations are an unfortunate but necessary part of running critical software in production. There are several pitfalls that are easy to fall into, some of which I had fallen into myself, in retrospect. Some of the consequences of an ineffective rotation are serious, affecting the health (mental, emotional, etc) of your on-call members.

I spent much of my time at ecobee being on-call, learning how to be effective, and eventually training teams on how to run rotations. I have a lot to say about how to do on-call, but my short-form breakdown is as follows:

1. Always think about the users. The user experience is what on-call is trying to maintain. If there isn't a customer impact, it isn't even an incident.

2. Follow a response procedure. A procedure will also help with calm, rational thinking.
    1. Determine an incident severity by determining the customer impact. This determines many facets of the response, such as urgency, or whom to contact.
    2. Resolve the customer impact. *Don't seek to resolve the root cause until the bleeding is stopped.*

Given that teaching others is one of the best ways to solidify learning, I took on my next goal:

## Train the SmartBuildings team to self-manage an on-call rotation.

I was a member of the SmartBuildings product squad for most of my time at ecobee. One of the critical parts of launching the service into production was forming an on-call rotation. This was the first squad where none of the members had been on-call before (besides myself).

Given the opportunity to make my understanding of on-call concrete, I took on the task of training the squad to run an effective rotation.

My largest takeways were:
* Building a training session takes a large amount of planning time to be effective.
* Ensuring that the squad understood that they have ownership and control over the rotation maximized the effectiveness of the training.

# Conclusion

I'm incredibly proud of what I learned and accomplished at ecobee. Out of all my co-op experiences, I learned the most as an SRE at ecobee, and I found it difficult to select just a few topics for this reflection. I'm always excited to discuss the topics I learned about SRE, and as a result of the co-op, I'm pursuing an SRE role after graduation. Co-op has enabled me to discover the parts of software engineering I find most exciting, and it turns out that one of them is SRE.

[ecobee-logo]: ecobee-logo.png "ecobee Logo"