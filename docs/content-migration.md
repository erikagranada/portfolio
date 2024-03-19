---
layout: default
title: Content migration
nav_order: 5
---

# Information architecture: Migrating and reworking Markdown content

**Tools**: Markdown, GitHub, DITA, oXygen XML

**SMEs**: Squad lead, support engineer

## Context

The way of customising the HCL Connections UI changed with the 8.0 release (which had a UI redesign). Developers decided to house the guide in a separate Git repository to enable developers and users to create pull requests. Due to a lack of alignment and bandwidth, the documentation was outdated and the new repository was hard to reach for customers looking to the documentation for guidance.

## Contribution

Speaking with the developer to learn the background of the separate Git repository, we agreed it was best to migrate the new content from Git to the documentation site, thereby also transferring ownership of the content. Some of the reasons for this decision included lack of content governance and standards. 

My approach for this plan was as follows:

- I first audited the existing documentation, keeping close communication with the developer to identify which customisations/content no longer applied and why.

- Once I identified which content to keep, I created clear content groupings. I found the original content to be disjointed, structurally weak, inconsistent, and not user friendly.

- Lastly, I crafted a clearer and more cohesive support narrative for legacy approaches, leaving customers no room to wonder. I also integrated each piece of content to build interaction or informational flows where relevant, for example to connect related tasks or information.

### Outcome

|Before|After|
|------|-----|
|[Connections UI Docs](https://github.com/HCL-TECH-SOFTWARE/connections-ui-docs) on Git, developer-written|[Customizing the user interface](https://opensource.hcltechsw.com/connections-doc/v8-cr4/admin/customize/t_admin_common_customize_main.html) on the HCL Connections 8.0 documentation|

The resolution of this support/customer ticket not only reduced our case backlogs but also addressed a key area for Support.
