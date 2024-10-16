# Implementing Site Reliability Engineering

**Product ID**: 32704
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: ISRE
**Vendor Code**: CM
**Vendor Name**: CPrime
**URL**: [Course Link](https://www.fastlaneus.com/course/cprime-isre)

## Objective
- Identify what SRE is and what it is not.
- Compares SRE to DevOps.
- Understand the difference between service-level indicators (SLI), service-level objectives (SLO), and service-level agreements (SLA).
- Develop the technical and professional skills an SRE needs.
- Determine what makes up a good SRE team.
- Practice common ceremonies like blameless postmortems and production readiness reviews.
- Gain an understanding of error budgets and how to calculate reliability costs.
- Embed SREs within development teams to increase operational stability.

## Essentials
nan

## Audience
This site reliability engineering training course is perfect for anyone in the IT/SDLC field looking to implement SRE teams and practices in their organization.

Professionals who may benefit include:



- Software Engineers
- Systems Engineers
- Network Engineers
- Technical Program Managers
- Anyone in an IT Leadership role
- CIOs / CTOs
- Anyone involved with IT infrastructure
- IT Operations Staff

## Outline
Part 1 – Introduction


- 1. Introduction
- 2. The Production Environment at Google, From the Viewpoint of an SRE
- 3. Exercise: Mapping Your Production Environment
Part 2 – Principles


1. Embracing Risk



- Managing Risk
- Measuring Service Risk
- Risk Tolerance of Services
- Motivation for Error Budgets
2. Service-Level Objectives



- Service Level Terminology
- Indicators in Practice
- Objectives in Practice
- Agreements in Practice
- Exercise: Setting Service-Level Objectives
3. Eliminating Toil



- What Is Toil?
- Why Less Toil is Better
- What Qualifies as Engineering?
- Is Toil Always Bad?
4. Monitoring Distributed Systems



- Definitions
- Why Monitor?
- Setting Reasonable Expectations
- Symptoms Versus Causes
- Black Box Versus White Box
- The Four Golden Signals
- Worrying About Your Tail
- Choosing an Appropriate Resolution for Measurements
- As Simple as Possible, No Simpler
- Tying These Principles Together
- Monitoring for the Long Term
5. The Evolution of Automation at Google



- The Value of Automation
- The Value for Google SRE
- Use Cases for Automation
- Automate Yourself Out of a Job
- Soothing the Pain: Applying Automation to Cluster Turnups
- Borg: Birth of the Warehouse-Scale Computer
- Reliability is the Fundamental Feature
6. Release Engineering



- The Role of a Release Engineer
- Philosophy
- Continuous Build and Deployment
- Configuration Management
7. Simplicity



- System Stability Versus Agility
- The Virtue of Boring
- I Won't Give Up My Code!
- The "Negative Lines of Code" Metric
- Minimal APIs
- Modularity
- Release Simplicity
Part 3 – Practices

1. Practical Alerting



- Time-Series Monitoring Outside of Google
- Instrumentation of Applications
- Exporting Variables
- Collection of Exported Data
- Storage in the Time-Series Arena
- Rule Evaluation
- Alerting
- Sharding the Monitoring Topology
- Black-Box Monitoring
- Maintaining the Configuration
2. Being On-Call



- The Life of an On-Call Engineer
- Balanced On-Call
- Feeling Safe
- Avoiding Inappropriate Operational Load
3. Effective Troubleshooting



- Theory
- In Practice
- The Magic of Negative Results
- Making Troubleshooting Easier
- Exercise: Distributed System Troubleshooting
4. Emergency Response



- What to Do When Systems Break
- Test-Induced Emergency
- Challenge-Induced Emergency
- Process-Induced Emergency
- Don't Repeat the Past—Learn From It
5. Managing Incidents



- Unmanaged Incidents
- Managed Incidents
- When to Declare an Incident
- Elements of Incident Management Process
6. Postmortem Culture: Learning from Failure



- Google's Postmortem Philosophy
- Collaborate and Share Knowledge
- Introducing a Postmortem Culture
- Exercise: Blameless Postmortem
7. Tracking Outages



- Escalator
- Outalator
8. Testing for Reliability



- Types of Software Testing
- Creating a Test and Build Environment
- Testing at Scale
9. Software Engineering in SRE



- Why is Software Engineering Within SRE Important?
- Auxon Case Study
- Intent-Based Capacity Planning
- Fostering Software Engineering in SRE
10. Load Balancing at the Front End



- Load Balancing Using DNS
- Load Balancing at the Virtual IP Address
11. Load Balancing in the Datacenter



- Identifying Bad Tasks: Flow Control and Lame Ducks
- Limiting the Connections Pool with Subsetting
- Load-Balancing Policies
12. Handling Overload



- The Pitfalls of "Queries Per Second"
- Per-Customer Limits
- Client-Side Throttling
- Criticality
- Utilization Signals
- Handling Overload Errors
- Load from Connections
13. Addressing Cascading Failures



- Causes of Cascading Failures and Designing to Avoid Them
- Preventing Server Overload
- Slow Startup and Cold Caching
- Triggering Conditions for Cascading Failures
- Testing for Cascading Failures
- Immediate Steps to Address Cascading Failures
14. Managing Critical State: Distributed Consensus for Reliability



- Motivating the Use of Consensus: Distributed Systems Coordination Failure
- How Distributed Consensus Works
- System Architecture Patterns for Distributed Consensus
- Distributed Consensus Performance
- Deploying Distributed Consensus-Based Systems
15. Distributed Periodic Scheduling with Cron



- Cron Jobs and Idempotency
- Cron at Large Scale
- Building Cron at Google
16. Data Processing Pipelines



- Origin of the Pipeline Design Pattern
- Initial Effect of Big Data on the Simple Pipeline Pattern
- Challenges with the Periodic Pipeline Pattern
- Trouble Caused by Uneven Work Distribution
- Drawbacks of Periodic Pipelines in Distributed Environments
- Introduction to Google Workflow
- Stages of Execution in Workflow
- Ensuring Business Continuity
17. Data Integrity: What You Read Is What You Wrote



- Data Integrity's Strict Requirements
- Google SRE Objectives in Maintaining Data Integrity and Availability
- How Google SRE Faces the Challenges of Data Integrity
- 1T Versus 1E: Not "Just" a Bigger Backup
- Knowing that Data Recovery Will Work
- Case Studies
- General Principles of SRE as Applied to Data Integrity
18. Reliable Product Launches at Scale



- Launch Coordination Engineering
- Setting Up a Launch Process
- Developing a Launch Checklist
- Selected Techniques for Reliable Launches
- Development of LCE
- Exercise: Develop a Production Readiness Review
Part 4 – Management

1. Accelerating SREs to On-Call and Beyond



- You've Hired Your Next SRE, Now What?
- Initial Learning Experiences: The Case for Structure Over Chaos
- Creating Stellar Reverse Engineers and Improvisational Thinkers
- Reverse Engineering a Production Service
- Five Practices for Aspiring On-Callers
- On-Call and Beyond: Rites of Passage and Practicing Continuing Education
2. Dealing with Interrupts



- Managing Operational Load
- Factors in Determining How Interrupts Are Handled
- Imperfect Machines
3. Embedding an SRE to Recover from Operational Overload



- Phase 1: Learn the Service and Get Context
- Phase 2: Sharing Context
- Phase 3: Driving Change
4. Communication and Collaboration in SRE



- Communications: Production Meetings
- Collaboration Within SRE
- Case Study: Viceroy
- Collaboration Outside SRE
- Case Study: Migrating DFP to F1
5. The Evolving SRE Engagement Model



- SRE Engagement: What, How, and Why
- The PRR Model
- The SRE Engagement Model
- Production Readiness Reviews: Simple PRR Model
- Evolving the Simple PRR Model: Early Engagement
- Evolving Services Development: Frameworks and SRE Platform
Part 5 – Conclusions


- 1. Lessons Learned From Other Industries
- 2. Conclusion

## Summary
Learn SRE best practices from an industry-expert and begin automating, monitoring , troubleshooting, and improving your systems.
The site reliability engineer role has been around for over 15 years now. And as the ubiquitousness of distributed systems increases, the demand for this role will continue to increase. However, many companies and technologists have not had exposure to the tenets of the SRE role, and there is often a lot of misunderstanding as to what this role is. Unlike traditional operations roles, the site reliability engineer puts additional focus on reducing human intervention by designing and implementing automation.

This three-day course will walk through the book Site Reliability Engineering: How Google Runs Production Systems, edited by Betsy Beyer, Chris Jones, Jennifer Petoff, and Niall Richard Murphy. During the course, you will learn about Google's approach to service management, gain an understanding of the basics of site reliability engineering, and get an introduction to advanced topics.

You'll look at real-world examples and code samples of how companies are using SRE to ensure that their services are exactly as reliable as they need to be. And finally, we'll cover the cultural and human aspects of site reliability that drive successful implementation.

## Course Duration
3 days

## Last Changed
2024-08-22T19:47:32.000Z
