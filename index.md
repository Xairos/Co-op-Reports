# Introduction.
What should you take away from this site? Short and sweet, I'm about to tell you.

# Jibestream
![Jibestream Logo][jslogo]  
Jibestream is a company of many mapping-related talents. At its heart, they provide an indoor navigation and mapping service through several products, spanning several SDKs across multiple platforms. Their clients also span multiple verticals, from mall corporations like Westfield and GGP, to government, such as The Pentagon.

### A typical client-side workflow
Let's say a mall is looking to add an indoor map into their existing app. If they turned to Jibestream, they would start by submitting architectural diagrams of their buildings to Jibestream’s mapping team, who in turn would convert the map into a vector representation for the mapping engine. Then, Jibestream would provide the mall with SDKs to implement map and navigation features that the mall would like to have in their app. Finally, mall managers could tweak almost all facets of navigation and mall features through Jibestream’s CMS (Content Management System).

# Ben Rottke, Backend Software Engineer
Over my 8 months at Jibestream, I worked with a team of 5 other developers on the backend development team. Our job was to write and rewrite the backend Java APIs that serve content for other Jibestream products. My responsibilities varied widely during my time, including being “on call” for bug-fixing work or backend support, developing relational database models for new features, and writing REST API endpoints for SDKs to communicate with, to name a few.

### Service to Product, Startup to Agile
At Jibestream, I was fortunate enough to learn about several stages of both a software development company, and shipping a software product, since the company was and is in several transition phases. Jibestream is moving away from a service-focused business model, where the company survives on large contracts with even larger clients. Even though they are delivering a product, primarily JEM (Jibestream Experience Manager, the CMS) and the SDKs, each deployment is tailored to the client. These custom client integrations were the largest time-sink for support work. Because of the widespread product “fragmentation”, maintaining each product in tandem quickly becomes a nightmare. Support is part of the clients’ contracts, but nevertheless becomes limiting for a small company looking to rapidly expand.

The logical step was for Jibestream to move away from a service-based model to delivering a SaaS product (Software as a Service). When I joined Jibestream in May, I began by fixing bugs and implementing minor features for the mature v3.3 of the CMS and backend platforms. Around July, our team’s work shifted to begin Jibestream’s first SaaS product, concisely titled **“4.0”**. Suddenly, I had the freedom to engineer a localization system, or completely reimplement authentication.


[jslogo]: js-logo.png "Jibestream Logo"
