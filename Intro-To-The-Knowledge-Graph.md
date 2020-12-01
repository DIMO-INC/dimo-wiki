---
title: Intro To The Knowledge Graph
description: 
published: true
date: 2020-12-01T06:04:58.961Z
tags: 
editor: markdown
---

![transparent_logo.png](/transparent_logo.png =150x)
# Intro to the DIMO Knowledge Graph
The DIMO Knowledge Graph tracks connections between the digital and physical world.
![Knowledge Graph](/knowledge_graph.png)


## [Objects] 
The Knowledge Graph is organized by [Objects] - whenever you see a word in Brackets like [this], you know you're dealing with a DIMO [object]. 

[Objects] can be linked together to describe complex systems & relationships. This page provides an overview of each [object] type, along with examples of how they're used. 

Name | Icon | Description
 --- | --- | ---
[Projects] |[![Project](/projects.png =50x)](#[Projects]) | Systems of [orgs], [people], [functions], [devices] that are designed to achieve a measurable outcome.   
[Functions] |[![Function Icon](/functions.png =50x)](#Function)|Combinations of [Events] [People] [Devices] - [Function]s produce [Events]
[People] | [![People Icon](/people.png =50x)](#[People]) 
[Badges] | [![Badge](/badge.png =50x)](#Badges) 
[Events] | [![Knowledge Graph](/event.png =50x)](##Events) | Updates to the knowledge graph are tracked in [Events] linked to one or more [opbjects]. 
[Devices] | [![Knowledge Graph](/devices.png =50x)](##[Devices])|Hardware that can be owned by [orgs], [people], or [projects]. [Devices] typically have [interfaces] that allow them to interact with [functions] and produce [events]. 


When creating [Projects], it's helpful to create higher level constructions out of the [objects] above. Here are some examples: 

Name | Icon | Description
--- | --- | ---
[Orgs] | ![Company](/company.png =50x) | Multiple [people] working together on something. 
[Tasks]| ![Task](/task.png )|[Tasks] are created when [people] or [orgs] send request [Events] to [functions], creating a specific job to be done.  
[Deals] | ![Deals](/deal.png =50x) | Groups of [tasks] that can be bundled together and fulfilled by [orgs] or [people] for a set price.
[Interfaces]| ![Interface](/interface.png =50x) |[People] interact with [Functions] through [Interfaces], which are combinations of [devices] and [functions]. 

## Navigating the Graph - Types and Tags
All DIMO Knowledge Graph objects are organized by [type] and [tag].

**Type** tell users what they can expect to find in a particular knowledge graph [object].


These are the different types of [Devices] (so far) 
![vehicle_icon.png](/vehicle_icon.png) ![storage_icon.png](/storage_icon.png) ![access-control_icon.png](/access-control_icon.png) ![sensor_icon.png](/sensor_icon.png) ![robot_icon.png](/robot_icon.png) ![computers_icon.png](/computers_icon.png)


For example, a [device] with [type] “Home Appliance” can be expected to have the following fields:
- “Power Source” (acceptable values - Battery, 120v outlet, Solar, etc)
- “Network Connection” (acceptable values - None, Wifi, Cell, LoRA WAN, etc)
- "Capability" (Acceptable values - cooking, cleaning, storage, etc.) 

An iRobot Roomba S9 is an example of a [device] has multiple [types]. It’s both a Home Appliance and a Robot. It contains data that describes Robot qualities like “Actuators”, “Sensors”, and “Compute”, and Home Appliance qualities like “room”, “Hub”, and “Network”.

Any user can suggest updates to types by submitting a pull request or entering a task in the “Requests” section of the Graph Roadmap.

**Tags** - are able to give a more detailed description of the [object], providing more free-form labels and associations with other parts of the knowledge graph. They allow [users] to more easily find and group [devices] appropriately.

For example, ‘Home appliances’ which will have many subgroups [tags] within it, vacuum, microwave, dishwasher, refrigerator, washer/dryer, etc.

## Using the Knowledge Graph 

DIMO uses a number of tools to collect and organize information. Airtable is the most accessible for beginners. With a valid DIMO account, you can access the public DIMO database here, and start to build your own extensions to the graph. 

### Examples of Projects in the DIMO Airtable**
  
[[Events](https://airtable.com/shryKKrkt7g5DZl9y)] we're tracking. You can filter based on your interest to get lists like: 

- Elon Musk List (Tesla + Boring Company + SpaceX) Project [Events]
- Waymo Project [Events]
- [Projects] coming up for Bid Soon (or past projects that you can FOIA) 

- Public Agency [[Deal]](https://airtable.com/shrzktHuYjqpQMfHf) & [[Project](https://airtable.com/shrhVLXNuwWrt72rt)] Gallery pages. We're going to be building these out significantly.


  





