---
layout: "../../layouts/ExperienceLayout.astro"
title: "Eurofins"
---

# Eurofins Lancaster Laboratories Detail
## Background

I started at Eurofins shortly after my previous employer (AWE) changed ownership to join a newly formed SCRUM team working to develop a next-generation Laboratory Information Management System (LIMS) for the Biopharmaceutical testing division that is now being deployed across Europe. The LIMS tracks all incoming work, from when samples to be tested are received through invoicing, while being compliant with all government regulations and industry best practices. The program quickly scaled up to include several additional development teams and around 50 employees working directly on the new LIMS system.

While at Eurofins I have been able to learn a number of new technologies, help to guide the architecture of the system and recommend and implement numerous changes to make development easier and produce higher quality results.

Some of the items accomplished include:

- Consistently being a top contributor of new features to the project.
- Served as a development team lead for a team dedicated to improving the performance of the system (both .NET backend and - JavaScript/Angular frontend)
- Introduced, trained developers on and championed unit testing (client & server)
- Boosted the quality and impact of peer code reviews
- Implemented automation scripts to simplify manual developer tasks
- Mentored junior developers
- Actively engaged in architecture decisions
- Started and presented at developer lunch & learns
- Implemented a number of development patterns to dramatically reduce redundant code and improve performance

## Examples of Development work

Note: LIMS specific work intentionally not detailed as it is proprietary, but LIMS was developed primarily using C#, WebAPI, JavaScript, TypeScript, Angular (v1) and Bootstrap.

- Implemented a micro-service to handle printing
- Completed implementation of and maintained a SSDT package for building and deploying database changes
- Refactored solution to use shared libraries to increase code reuse
- Integrated with 3rd part line of business applications
- Refactored core class hierarchy to dramatically reduce effort to add new entities
- Implemented performance monitoring of solution, first with Performance Counters then with AppDynamics
- Made large performance improvements throughout the application stack.
    - Some common edit tasks caused the UI to be unresponsive for 30+ seconds when using large data sets, lag is no longer detectable
    - Dramatically reduced the amount of data passed between client and server
    - Implemented server-side paging pattern for grids with large data sets
    - Streamlined server implementation to substantially reduce database load