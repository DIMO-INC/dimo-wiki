---
title: Graph Tasks-Test Github Add
description: Building the DIMO Knowledge Graph
published: false
date: 2020-11-16T00:04:29.453Z
tags:
editor: markdown
---

# Graph Builder [Tasks]

Adding information about [Organizations], [Devices], [Users], [Events], [Projects].

### Sources
Each piece of information added to the graph must include a citation and a link to an existing [object] in the graph.


</br>

### Adding [Organizations] [Devices] + [Functions]

1. Search from the existing [organization] list to avoid duplicates added.
1. Find the organization's official website.
1. Pull out other related links, social media and channel as required (twitter, linkedin, youtube, github)
1. Identify [Org] Type
1. Link [Org] [Functions] & [Devices] Based their advertised product and services.
-- If there are more than 10 functions or devices, take a representative sample and post a task on the Graph Development Tasks Board with Type “Bulk Import”

1. Attach the [organization]'s logo from its official Twitter.
1. Read the official website and related articles to find out other required fields in the database:
	- Job board (or contracts page - anywhere services are purchased)
	- Projects - what have they / are they working on?
  	- [devices]
  	- Services Page
  	- How can you contact them? Email, customer service, etc.

1. Link with other [organizations] that have direct partnership/project involvement.

Common Sources of Information:

- [Org](https://theorg.com/explore) Information from TheOrg.com
- [Orgs][Devices][Functions] updates from [CB Insights] or [Crunchbase](https://www.crunchbase.com/)
- [Job] [Sites](https://www.welcometothejungle.com/en/)
- [RSS Feeds]
	-Github repositories
  -Industry News
  -IoT System updates [Tesla Supercharger Stations](https://supercharge.info/changes)

### Adding [Event] Streams

Add timeline [events], tagging [organizations], [projects], [people], [functions],

1. Read the document(s), decide they would add value to the DIMO network graph
1. Make sure the document is properly indexed in the [Events] table
  	- Fill out required time, author, in the timeline database
1. Link to DIMO entities where possible
 	- [organizations], projects, people, investors, [devices], services/functions, predictions
1. Link as many applicable connections as needed, submit to the Knowledge graph for approval
1. Respond if there are any proposed changes

### Adding Data from a Primary Source
DIMO Provides: [This URL] that points to the primary source, in this case it is the Robot Report Podcast, Episode 6

The data is pulled into [This Record], and other linked records are created and updated:

[Organizations]: Gatik, 6 River Systems, Shopify (as Parent organization of 6 River Systems) [People]: Chris Cacioppo (Co-founder & CTO - 6 River Systems), Gautam Narang (Co-founder and CEO - Gatik)

Graph Builder Tasks:

- Check [People] mentioned in the document against [People] table
- Check [organizations] Mentioned against [organizations] Table (including the company that is publishing the article.
- Include any [Devices], [Functions], [Project Templates] or [Project Instances] mentioned

Add these items if they are not included. If they are included, you can just tag the existing record in the Event record you’re creating

### Adding [Jobs] from [Organizations] and [Projects]

- Find the organization Job Board and pull out the link.
- Identify the location where jobs are listed with as much data as possible.
- Add a sample of the data to the [Jobs] table
- Link with the Hiring [Organization] and [Project] (if applicable)
- Update the Status of the organization on the “Jobs Tracking Status” board
- Note: If you add the links to other records, some fields will be automatically generated from existing knowledge graph content.
