---
layout: default
title: Information architecture
nav_order: 5
---

# Information architecture

## Migrating and reworking content migration

### Context

The way of customising the HCL Connections UI changed with the 8.0 release (which had a UI redesign). Developers decided to house the new content in a Git repository to enable developers and users to create pull requests. Due to a lack of alignment, the documentation was outdated and the new repository was hard to reach for customers looking to the documentation for guidance.

### Contribution

Speaking with the developer to learn the background of the separate Git repository, we agreed it was best to migrate the new content from Git to the documentation site, thereby also transferring ownership of the content. Some of the reasons for this decision included lack of content governance and standards. I organised the effort in the following way, the end goal being to merge the two sets of content into a single comprehensive source of truth.

*Filter content.* I first audited the existing documentation, keeping close communication with the developer to identify which customisations/content no longer applied and why.

*Build the puzzle.* Once I identified which content to keep, I found a place for each one in the developer’s Git repository and cleaned up the content along the way. I found the repository overall felt disjointed, having a weak structure, inconsistent writing, and a format that was not user friendly— for instance, the file names made it hard to gauge the context of the content at a glance.

|Before|After|
|------|-----|
|[Connections UI Docs](https://github.com/HCL-TECH-SOFTWARE/connections-ui-docs) on Git, developer-written|[Customizing the user interface](https://opensource.hcltechsw.com/connections-doc/v8-cr4/admin/customize/t_admin_common_customize_main.html) on the HCL Connections 8.0 documentation|

The resolution of this support/customer ticket not only reduced our case backlogs but also addressed a key area for Support.

### Skills and tasks

- Copyediting
- Information architecture
- Content migration
- Messaging: transition from legacy to new approaches
- Markdown and Git documentation


