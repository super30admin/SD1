# SD1


**Designing a URL Shortening service**

**What to be designed?**

1. URL shortening is used to create shorter aliases for long URLs. Shorter URLs take up less space and can save mistakes through typos in longer URLs.
2. Play around with shortening of URLs on tinyurl.com to understand the use case of shortened URLs.
3. URL shortening is used for optimizing links across devices, tracking individual links to analyze audience and campaign performance, and hiding affiliated original URLs.

**Feature Requirements**

Primary Features:

1. Generate a shorter and unique alias for a long URL. Shortened URL should be short enough to be easily copied and pasted into applications. Users should able to pick a custom short link for their URL.
2. When users access a short link, our service should redirect them to the original link.
3. Shortened URL Links will expire after a standard default timespan. Users should be able to specify the expiration time.

Secondary Requirements:

1. URL redirection should happen in real-time with minimal latency.
2. System should be highly available. If our service is down, all the URL redirections should not be failing.
3. Security: Shortened URLs should not be predictable.

Extended Features:
Analytics; e.g., how many times a redirection happened?
Our service should also be accessible through REST APIs by other services.

**TO DO : Follow the below framweork to design System. Mandatory upload of hand drawn photos of design.**

**Capacity Estimation and Constraints**

What will your estimations of scale? As a system design student you should be able to make intelligent assumptions based on real life systems. 

**System APIs**

**Database Design**

**Basic System Design and Algorithm**

**Data Partitioning and Replication**

**Caching**

**Load Balancing**

**Handling Edge cases in given system**



