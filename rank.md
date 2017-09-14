# Rank Software
## Introduction
Summary here, what did I learn from Rank in a sentence or two. There's a sensitive nature to some of this, but I'll talk about what I can.

![Rank Logo][rank-logo]  
Rank Software is a product company, with a security solution that brings the power of big data and machine learning to human analysts. This way, analysts can maximize the security of their deployment by having full knowledge of the important behaviours of their system. The primary user-facing component is VASA (Virtual Advisor to Security Analysts), a dashboard that presents actionable information to the user (usually a security analyst). The user can glean information from the system both passively and actively, and information being used by the system is available via powerful search and analysis workflows.

### Inner workings
In a deployment, the core software is placed on a cluster of machines within the network under analysis. Several data sources, including network traffic, are then fed into the machine cluster for indexing, analysis, and alert generation. The software running on the cluster uses a slew of analysis methods (including machine learning algorithms) to identify anomalous and malicious behaviour on the network. Results of the analysis are presented to an analyst via the VASA dashboard, where they can perform actions and further analysis themselves.

This differs from an antivirus in two major ways:
1. Antivirus software is primarily based on pattern matching to find strings that exist in known malicious binaries. Modern antiviruses also use some behaviour-based recognition, such flagging a program that is modifying a certain set of files. Machine learning allows for the formation of a network "baseline" of normal behaviour, drastically increasing the probability of catching a zero-day or targeted attack.
2. Given the wide range and volume of data available to the system, pattern recognition and behaviour analysis can be performed in a much larger context.

## Ben Rottke, Cybersecurity Intern.
Given the startup size of Rank, the development team comprised most of the company. I was part of this development team, and had the opportunity to work on the same class of tasks as my coworkers. Exceptions included machine learning and frontend dashboard work.

## Major projects, and what I learned.


# Work Term Goals

### 1. I would like to improve my presentational skills, specifically with respect to verbal communication. In running a presentation, I want to maximize the audience's understanding of the purpose and inner workings of my solution.

For several hours leading up to the scheduled presentation, I prepared content topics that I would present on into detailed breakdowns. This proved to be incredibly useful. The presentation became an informal demonstration and walkthrough of the API I had written, and I was able to get through the content I had prepared successfully and on time.

I also received some specific feedback from my manager, where one point highlighted the “tell-show- tell” presentation technique. My shortcoming was not making sure everyone was on the same page before demonstrating a feature, so talking about what I was about to show (the first “tell”) would solve this problem.

### 2. Rank's product is backed by machine learning. I would like to gain a basic, well-rounded understanding of machine learning, in order to better internalize our product's problem domain.

By the end of the work term, I was successful in reading 7 papers spanning a few ML (machine learning) topics. This proved to be a fairly effective method of gaining domain knowledge and understanding the problems that exist within the product space, perhaps second to actually developing ML applications in my own time.

Reading academic papers was a new experience, and I learned that there are methods of reading these papers to maximize one’s understanding of them (in short, not simply reading sequentially).

In reading the papers, I was surprised at the frequency of which the same domain-related hurdles would come up in different papers. True to form, some of these topics would come up in the workplace, and they became great sources of discussion to further my understanding. I will certainly be applying this method in the future.

### 3. My final project at Rank will be timeboxed by the end of my co-op term in August. My goal is to manage my time effectively to complete this final project in its entirety.

This goal was intentionally vague, since at the time, the topic and time available for the final project were to be determined. In the end, the task was to evaluate the effectiveness of an ML algorithm in production. The task itself was originally estimated at 4 weeks, but there were only about 1 ½ weeks remaining in the work term. To remediate this, I re-evaluated the goal and built a schedule that mapped each day to my approximate progress.

Breaking the task down into a solidified and fine-grained schedule aided me in providing concrete daily progress updates. It also helped keep me from deviating from the task or getting stuck, and made it clear when I was ahead of schedule. I used this time ahead as an opportunity to branch out of the core task to try an interesting evaluation mechanism, which ended up providing great value to the final report.

# Wrap-up
At Rank, I saw how quality software is written.

[rank-logo]: rank-logo.png "Rank Logo"
