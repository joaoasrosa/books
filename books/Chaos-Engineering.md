# Chaos Engineering

## Metadata

**Title**: Chaos Engineering

**Subtitle**: Building Confidence in System Behavior through Experiments

**Publisher**: O'Reilly

**Authors**: Casey Rosenthal, Lorin Hochstein, Aaron Blohowiak, Nora Jones & Ali Basiri

**ISBN**: N/A

**Pages**: 72

**Price**: Free

**Official website**: [http://www.oreilly.com/webops-perf/free/chaos-engineering.csp](http://www.oreilly.com/webops-perf/free/chaos-engineering.csp)

## Review

The Chaos Engineering discipline born in Netflix, "(Chaos Engineering) is the discipline of experimenting on a distributed system
to build confidence in the system’s capability
to withstand turbulent conditions in production." [1]

In an era of distributed systems, based on microservices and serverless architectures, the development teams can't predict all the events that will lead to failures or even the behavior of the system as a whole. The Chaos Engineering principles allow to identify the weaknesses of the systems in a controlled fashion, e.g., run experiments with the systems (infrastructure or/and software) to expose the weaknesses, before a real outage occurs.

The book is divided into 3 parts: (1) Introduction, (2) The Principles of Chaos and (3) Chaos In Practice.

In the first part, the authors introduce the motivation and history behind the Chaos Engineering, describing the process at high-level. They also explain the difference between testing and Chaos Engineering; where the former asserts the known expectations of the system behavior, but the latter generates new knowledge about the system.

Generating new knowledge about the system is a crucial concept for Chaos Engineering. It allows the development teams to hardening the system, improving the user experience.

It is stressed the importance of a mature system before starting Chaos Engineering, e. g., if a development team is aware of some system weakness that can cause a negative impact on the system, they should fix it first, before starting the experiments. 

The second part is focused on the Principles behind Chaos Engineering discipline. 

The authors describe the definition of the Steady State, which is "... a property such as internal body temperature where the system tends to maintain that property within a certain range or pattern.". Defining a Steady State of the system is the first step to formalize the Hypothesis about the failure events which maybe will affect the steady state of the system. 

Based on the previous definitions, the development teams can start defining the experiments, where they should run, and with which frequency.

A key factor to success is to embrace automation and frequency of the experiments, running them in production (if possible). Also, when generating new knowledge about the system, usually it unveils a weakness, the development team should fix it before running the next experiment.

The last chapter focuses on the operationalization of the practice of Chaos Engineering. It sets the best practices to Design Experiments, and which steps a team should take to generate new knowledge about the system. 

The Chaos Engineering discipline is paramount for the resilience of the system, which includes the user experience, data consistency, and security. Given the mindset behind the Principles, the practitioners should always strive to generate new knowledge about the system, setting a new quality standard for it.

Although it may seem counter-intuitive to apply chaos to a system, Chaos Engineering is based on following a protocol, providing feedback for the next development iterations. In my opinion, a development team should strive to start applying the Chaos Engineering to the systems under their responsibility; it will strengthen the confidence in the system(s), increasing the velocity of the feature development, since the team fixes weaknesses of the system before they surface.

[1] - [http://principlesofchaos.org/](http://principlesofchaos.org/)