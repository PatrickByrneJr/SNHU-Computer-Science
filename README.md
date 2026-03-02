CS 230 – Software Design Portfolio Artifact
The Gaming Room – Draw It or Lose It
Project Overview

The Gaming Room was the client for this project. They had an existing Android-based game, Draw It or Lose It, and wanted to expand it into a web-based application accessible across multiple platforms, including desktop and mobile devices. The system needed to manage games, teams, and players while enforcing unique naming rules and maintaining a centralized service for object creation. The design also needed to support scalability and future cloud deployment.

This document outlines the system architecture, domain model, platform evaluation, and deployment recommendations required to transition the game into a distributed, web-based environment.

------------------------------------------------------------------------------------------------------------------------------------

Strengths in This Design

One of my strongest contributions was clearly connecting business requirements to technical decisions. Rather than just describing features, I explained why specific design patterns—such as inheritance and the singleton service model—were appropriate for maintaining centralized control and enforcing naming constraints.

I also evaluated multiple operating systems (Linux, Windows, macOS, and mobile platforms) from both technical and cost perspectives. This broader systems-level thinking reflects real-world decision-making beyond just writing code.

------------------------------------------------------------------------------------------------------------------------------------

Value of the Design Process

Working through the design document before implementation was extremely valuable. It clarified object relationships, service responsibilities, and scalability requirements before development began. In practice, investing time in design reduces rework and produces cleaner, more intentional code.

The process also helped me think about distributed systems, concurrency, and persistence early—considerations that become critical in production environments.

------------------------------------------------------------------------------------------------------------------------------------

Areas for Improvement

If I were to revise one section, I would expand the distributed systems and concurrency discussion within the architecture overview. While scalability and database constraints were addressed in the recommendations, incorporating more detail earlier in the document would strengthen the overall flow.

Adding a simple architectural diagram to illustrate client-server interactions would also enhance clarity for stakeholders.

------------------------------------------------------------------------------------------------------------------------------------

Interpreting User Needs

The client’s primary needs were cross-platform accessibility, consistent naming enforcement, centralized game management, and scalability. I translated these into a layered architecture with a shared service model, structured domain entities, and a Linux-based cloud deployment recommendation.

Designing with the user’s needs in mind is essential. Technical design must support real-world usage patterns, performance expectations, and long-term maintainability—not just functional correctness.

------------------------------------------------------------------------------------------------------------------------------------

Design Approach and Future Strategy

My approach focused on structured problem breakdown:
*Define business requirements
*Model domain entities
*Centralize service logic
*Evaluate deployment platforms
*Plan for scalability and security

In future projects, I will continue using requirement mapping, UML modeling, and platform evaluation early in the process. Designing for scalability and statelessness from the beginning ensures smoother transitions into distributed environments.

------------------------------------------------------------------------------------------------------------------------------------

Repository Link:
https://github.com/PatrickByrneJr/SNHU-Computer-Science.git

------------------------------------------------------------------------------------------------------------------------------------

This artifact demonstrates my ability to translate business requirements into scalable technical architecture while applying object-oriented design principles and strategic platform evaluation.
