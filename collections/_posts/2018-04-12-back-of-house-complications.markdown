---
layout: post
title:  "Back of house complications"
blurb: "Uninterruptible Power Supplies (UPS) are typically associated with Back of House meaning the location is often in a far corner of a room or in a different location altogether. Therefore, the need to monitor the environment of the UPS together with its on-board power metrics is as important as the data centre itself."
page-description: "Uninterruptible Power Supplies (UPS) are typically associated with Back of House meaning the location is often in a far corner of a room or in a different location altogether. Therefore, the need to monitor the environment of the UPS together with its on-board power metrics is as important as the data centre itself."
image: /images/blog/back-of-house-complications/back-of-house-complications.jpeg
permalink: /news/back-of-house-complications/
date:   2018-04-12 10:27:49 +0000
published: 1
---

Data centres are commonly associated with "Front of House" and Uninterruptible Power Supplies (UPS) are typically associated with "Back of House" meaning the location is often in a far corner of a room or in a different location altogether. Therefore, the need to monitor the environment of the UPS together with its on-board power metrics is as important as the data centre itself.

Regardless of when a power failure happens, facility staff must be informed immediately that something has failed. Many UPS systems come with an integral or optional NIC (network interface card) that can send alerts via email or SMS notifications. Worryingly, what if email or SMS messages are blocked or mobile phones are out of signal when an alert happens? More on this later!

It's a fact that UPS failures have for a long time been a top cause of IT related unplanned downtime. It's easy to ignore a UPS until you need it, and when you need it, you really need it.

Many do not realise that a UPS and its associated battery banks is in fact highly sensitive to environmental conditions and as such manufacturers emphasise strict operating condition guidelines. Step outside of these and you can find your UPS warranty has been voided.

Since developing OmniWatch's real-time UPS dashboard, the majority of our customers have extended monitoring to include their UPS systems.

Knowing the amount of run time left on a UPS and knowing the load balances of different phases as the server room evolves over years is important. It's surprising the amount of Spook customers that didn't know the substantial difference on three phase power loads before comparing them on their OmniWatch dashboard.

![omniwatch-ups-monitoring-dashboard](/images/blog/back-of-house-complications/ups-monitoring-dashboard.png)

Designing a location suitable for a UPS is key. Consideration must be given to cooling; surge protection and regular maintenance. Battery replacement protocols should be incorporated into the design too.

## Location, location, location

We are not pessimists but we feel it's always a good stance to take when considering the location of a UPS room. The most likely cause of a problem with a UPS is human error and as such the location should minimise unauthorised access. The complication is that in the event of a catastrophic failure, replacement parts may need to be maneuvered with ease and speed. Large UPS systems housed in confined rooms cannot fit through a normal doorway.

## Surge protection

Whilst the UPS is designed to protect the downstream power load in the event of a power outage, the UPS itself should be protected with a Surge Protection Device (SPD). Like all other electrical equipment modern UPS systems are sensitive to transient over-voltages too. Events like lightening or utility supply switching or sudden power loss are all events a UPS needs to steer. Many modern UPS systems have an integral SPD but an external SPD is recommended especially for locations with poor power quality issues.

## Cooling

Adequate cooling for a UPS room or location helps ensure the reliability of the equipment. Whilst a UPS can tolerate relatively high temperatures for short periods of time most manufacturers recommend an ideal operating temperature to be 25°C (77°F) or lower. As a guide, for every 10°C (18°F) increase in operating temperature may reduce the longevity of UPS components by half.

Cooling redundancy needs to be factored into the design of a UPS room too. If there is only a single air cooler installed what happens if this fails or if it needs to be shut down for maintenance purposes?

## Battery protocols

Apart from human error being the most likely reason for a UPS error, battery failures are the second most common cause of UPS downtime. Because battery issues often go undetected until batteries are needed, monitoring the health of the batteries can be a positive step to avoiding a potential failure.

A battery monitoring system can be added on to the battery strings to compare the UPS battery characteristics over time to predict when they will fail. Typically valve-regulated lead-acid (VRLA) batteries carry a 10-year warranty period.

The number of batteries for each UPS system is directly proportional to the load and amount of run time required of them. The more batteries needed the more potential points of failure exist as it only takes one battery failure to bring down an entire UPS system.

## Monitoring and measuring is king

By now you will have read some key points to take into account when installing UPS systems but without real-time monitoring and measuring none of the above is meaningful. It's fairly straightforward to capture key UPS metrics if there is a NIC attached but without the infrastructure to support it and without knowing in real-time the various UPS metrics is senseless.

## OmniWatch on-demand reports

A UPS can collect data temporarily on its on-board data-logger and the amount of available data depends on the time frame it is set to harvest the readings (e.g. 15 minutes, hourly, daily etc.). Unfortunately, after a short period of time the information is overwritten by the latest set of values.

OmniWatch collects the data from all sensors in perpetuity. This means the trend data for every sensor can be interrogated for audits, planned maintenance, measurement against Key Performance Indicators (KPIs) and load balancing exercises too.

An example of how useful OmniWatch's On-Demand Reports are is when one of our customers UPS manufacturers threatened to void their warranty by implying the operating environment of the UPS had been breached.

The UPS batteries had a 10-year warranty period. They became faulty after 6 years. They needed proof, under audit, of the environmental operating condition of the UPS. OmniWatch was able to publish an On Demand Report for the whole six-year period clearly confirming matters and proving it was within the manufacturers guidelines. Once proven, the batteries were replaced free of charge and the warranty was not effected.

## Communications

Finally, for those who have been using NICs to monitor their UPSs, consideration must be given to what happens if there's a communications problem at the same time as the UPS error. The majority of UPS alerts happen when power is relied upon to power critical IT kit. It just takes one router, switch or other network component that should be fed power from the UPS side that has inadvertently been installed on a non-UPS side for all this to fail.

Fortunately OmniWatch's 3-tier alarm escalation procedure takes this into account. In the event that emails and SMS messages fail, a member of our 24/7 UK based call centre calls key client personnel to ensure they are aware of the problem.

> The biggest benefit of OmniWatch is the comfort that whatever time of day or night, we will receive telephone calls from a human to alert us to problems, nothing else we have found will give us this service, and like most busy IT Professionals we will sleep through an email or SMS message at 3am.

SevenC3 - Richard Sacré, IT Director

That's one of the many reasons we have one of the most loyal customer bases in the industry, many of whom have been clients for over a decade. See for yourselves by visiting our industry sectors.
