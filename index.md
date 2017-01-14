# Introduction.
Working at Jibestream has been an incredible experience because of how much I have learned both about the business and engineering sides of working in the software development industry.

![Jibestream Logo][js-logo]  
Jibestream is a company of many mapping-related talents. At its heart, they provide an indoor navigation and mapping service through several products, spanning several SDKs across multiple platforms. Their clients also span multiple verticals, from mall corporations like Westfield and GGP, to government, such as The Pentagon.

### A typical client-side workflow.
Suppose a mall is looking to add an indoor map into their existing app. If they turned to Jibestream, they would start by submitting architectural diagrams of their buildings to Jibestream’s mapping team, who in turn would convert the map into a vector representation for the mapping engine. Then, Jibestream would provide the mall with SDKs to implement map and navigation features that the mall would like to have in their app. Finally, mall managers could tweak almost all facets of navigation and mall features through Jibestream’s CMS (Content Management System).

# Ben Rottke, Backend Software Engineer.
Over my 8 months at Jibestream, I worked with a team of 5 other developers on the backend development team. Our job was to write and rewrite the backend Java APIs that serve content for other Jibestream products. My responsibilities varied widely during my time, including being “on call” for bug-fixing work or backend support, developing relational database models for new features, and writing REST API endpoints for SDKs to communicate with, to name a few.

### Service to Product.
At Jibestream, I was fortunate enough to experience several stages of both a software development company and shipping a software product, since the company was and is in several transition phases. Jibestream is moving away from a service-focused business model, where the company survives on large contracts with even larger clients. Even though they are delivering a product, primarily JEM (Jibestream Experience Manager, the CMS) and the SDKs, each deployment is tailored to the client. These custom client integrations were the largest time-sink for support work. Because of the widespread product “fragmentation”, maintaining each product in tandem quickly becomes a nightmare. Support is part of the clients’ contracts, but nevertheless becomes limiting for a small company looking to rapidly expand.

The logical step was for Jibestream to move away from a service-based model to delivering a SaaS product (Software as a Service). When I joined Jibestream in May, I began by fixing bugs and implementing minor features for the mature v3.3 of the CMS and backend platforms. Around July, our team’s work shifted to begin Jibestream’s first SaaS product, concisely titled **“4.0”**. Suddenly, I had the freedom to engineer a localization system, or completely reimplement authentication.

### Startup to Agile.
Also during this period, the development teams were midway through transitioning to Agile software development. After mentioning my interest in the Agile process to my manager, he offered me the opportunity to be a scrum master for my team in the last months of my co-op term (October to December).

As a scrum master, I was responsible for keeping the story backlog groomed, organizing sprint meetings, mediating scrums, and running sprint retrospectives. It was intriguing to experience the early stages of Agile at an existing company, from vague user stories to missing sprint story-point targets. I learned a lot about both Agile and managerial perspectives by defending Agile processes when it seemed better to do things the easy way. Overall, I’m grateful for the opportunity, because I quickly became intimately familiar with a process used throughout the software development industry.

# Major Projects, and what I learned.
I worked on two major projects during my time at Jibestream. The first was a localization system, where an SDK could request a piece of data and the language it would like the data in (assuming an entry existed in that language). I was free to design every aspect of the system, from database modelling to API design, since localization was a brand-new feature for v4.0.

The project gave me in-depth exposure to technical concepts like relational data management, before I could be exposed to them academically. It also highlighted the importance of openness and continuous communication in software development to me. After picking an SQL prototype I had designed, partially through implementation I realized that it could not work in a relational database system. Since I had been continually communicating my progress to my team lead, when I revealed that I had to start from scratch, he reassured me that it was not an issue to extend the task.

# Wrap up
My understanding of the company became exponentially more broad as time went on, highlighting the value of an 8-month co-op term. After four months, I had fixed a couple bugs and written a couple new features. After 8, I had written an authorization server for a new login system.
![Knowledge over time][scope-graph]

My understanding of the company became exponentially more broad as time went on, highlighting the value of an 8-month co-op term. After four months, I had fixed a couple bugs and written a couple new features. After 8, I had written an authorization server for a new login system.

One of my goals was to become more exposed to the business side of software development. Through 1 on 1’s with my manager, I learned about how software development companies operate, and the various processes that drive them. I also had incredibly valuable experiences. I was happy to learn new technologies like Spring and PostgreSQL, but the value of learning these was matched by the Agile exposure from being a Scrum Master, or conveying OAuth 2 framework concepts in a presentation. Working at Jibestream was an incredible experience from several software development facets, and I’m extremely grateful to have had the opportunity to make an positive impact for the company.


[js-logo]: js-logo-2.png "Jibestream Logo"
[scope-graph]: knowledge.png "Knowledge over time"
