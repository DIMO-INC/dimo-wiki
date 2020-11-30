---
title: Intro To The Knowledge Graph
description: 
published: true
date: 2020-11-30T20:17:53.018Z
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


### [People] 

The most basic account, which can own or fill one or more roles within specific [Projects], [Functions], [Orgs], [Devices].

![product-designer_icon.png](/product-designer_icon.png) ![service-operator_icon.png](/service-operator_icon.png) ![author_icon.png](/author_icon.png) ![graph-curator_icon.png](/graph-curator_icon.png) ![support_icon.png](/support_icon.png) ![investor_icon.png](/investor_icon.png)

[People] with **verified** DIMO accounts can add to the knowledge graph and create private sub-graphs. Typically this is done while designing, developing, maintaining, and upgrading DIMO [Projects].

### [Orgs]
[Orgs] are multiple [people] working together on something. Like [people] [Orgs] can be associated with [Projects][Devices][Functions] and assigned [Badges] based on [Events].

[People ] and [functions] can follow an [Org] here to be updated as [Events] are associated with their accounts.

![hardware_icon.png](/hardware_icon.png) ![media_icon.png](/media_icon.png) ![telecom_icon.png](/telecom_icon.png) ![software_icon.png](/software_icon.png) ![investor_icon.png](/investor_icon.png) ![finance_icon.png](/finance_icon.png)


### [Devices]

[People] and [Orgs] import [Devices] to the knowledge graph so they can be added to [functions] in [projects] 


![vehicle_icon.png](/vehicle_icon.png) ![storage_icon.png](/storage_icon.png) ![access-control_icon.png](/access-control_icon.png) ![sensor_icon.png](/sensor_icon.png) ![robot_icon.png](/robot_icon.png) ![computers_icon.png](/computers_icon.png)


### [Functions] 

The DIMO platform offers [Functions] for a variety of repeatable tasks across the following categories. 


![verification_icon.png](/verification_icon.png) ![phone-app_icon.png](/phone-app_icon.png) ![network_icon.png](/network_icon.png) ![parking_icon.png](/parking_icon.png) ![storage_icon.png](/storage_icon.png) 

### [Projects] 
The whole point of DIMO is to enable [Projects] that move things around. [Projects] are systems of [orgs], [people], [functions], [devices] that are designed to achieve a measurable outcome. [Deals] are a specific type of [function] that can be used to fund and build [projects] by specifying [tasks] that need to be completed to successfully launch a new instance of a [project]. 

Here’s an example of current and potential [projects] that we’re tracking.
- Automated Valet Parking System (Current)
- [The Boring Company] building a tunnel system under [Las Vegas]


![iot_icon.png](/iot_icon.png) ![transit_icon.png](/transit_icon.png) ![shared-mobility_icon.png](/shared-mobility_icon.png) ![smart-city_icon.png](/smart-city_icon.png) ![smart-house_icon.png](/smart-house_icon.png) ![testing_icon.png](/testing_icon.png)

Like most other DIMO [objects], [Projects] can either be a "template" or an "instance"

[Orgs] and [People] can create [Project] Templates to [display their capabilities.](https://airtable.com/shroBTjnjbWRyb0gh)

### Events 
![Knowledge Graph](/event.png =75x)

Updates can be simple, like changing the value on a sensor [device] from 70 → 71 degrees F.

[Events] can also describe complex situations including other objects: 
- update to a policy [function] that is 
- linked to a [device] 
- set by an [organization] in a specific [project].
- tracked by a [Badge] that summarizes performance against a standard

![Knowledge Graph](/policyupdate.png)

### [Interfaces] 
[People] interact with [Functions] through [Interfaces]. [Interfaces] are combinations of [devices] and [functions]

![ios_icon.png](/ios_icon.png) ![macos_icon.png](/macos_icon.png) ![webapp_icon.png](/webapp_icon.png) ![android_app_icon.png](/android_app_icon.png) ![app_icon.png](/app_icon.png) ![ethernet_icon.png](/ethernet_icon.png)

### [Zones]
Live [projects] typically contain one or more references to physical locations that can be defined by addresses, zip codes, geo-JSON - these can be home to one or more [projects], and can be set up with administrative structures that are managed by [people]

### [Project] Instances
Combinations of [Project Templates] and [Zones]

A [Project Instance] must be associated with at least one [Zone], and inherits the policies of that [zone].

### [Event]
The knowledge graph to track [events] and associate them with their subjects & participants.

#### Prediction

An event can contain a statement from a [Person] or [Org] that references some time-bound information. For example -

![media_icon.png](/media_icon.png) ![funding_icon.png](/funding_icon.png) ![partnership_icon.png](/partnership_icon.png) ![product-launch_icon.png](/product-launch_icon.png) ![prediction_icon.png](/prediction_icon.png) ![mapupdate_icon.png](/mapupdate_icon.png)

A claim can be about project or financial performance:
- Want to see how often [Tesla] [GM] [Ford] have hit their production targets? Are their targets aggressive compared to each other?
- Which [Orgs] claim they’ll be able to offer automated delivery services at less than $1/mile by 2025?

Or - the “Claims” can be credentials issued by regulators to [Orgs],[People],[Projects],[Devices], or even [Functions]. Certain claims from verified accounts can be used to issue [badges]:

**- [California] [DMV] issued a [fully driverless] [permit] to [AutoX] on [September 20, 2020]**

One other common type of claim [event] is a “Billable” [event]. It can be submitted using a dedicated form that creates an [event] that gets assigned to the billing admin of a [project] or [task].

### [Event] Streams
There are many high-quality, reliable public [event] streams available today.

here are some we’ve compiled from publicly available sources:
- [Tesla Supercharger] [Status] (RSS Feed)
- [OSM] [Status]
- Transit Feeds

All [DIMO]-produced [Event] feeds are available as RSS, email, updates, or through our API with a paid account.

Don’t see a stream you need? Check out our [task] board to see if someone is working on it already, and submit a new [Task] request if it’s not on our roadmap.



### [Deals]
[Deals] are used to highlight and give specific information about the transactions that brought a [project] to life.

There are different methods of structuring a [Deal] 
- RFP from a Public Agency
- Private B2B contract
- Crowdfunded project or task
- Employment contract


### Deal [Types]
We’ve narrowed down the different kinds of deals to the following categories:

![deal-hiring_icon.png](/dealtype/deal-hiring_icon.png) ![insurance_icon.png](/dealtype/insurance_icon.png) ![bonding_icon.png](/dealtype/bonding_icon.png) ![contract_icon.png](/dealtype/contract_icon.png) ![finance_icon.png](/dealtype/finance_icon.png) ![integration_icon.png](/dealtype/integration_icon.png)



A well-crafted [Deal] will detail **performance targets** linked to existing [functions], [devices], [orgs], and [people] working on the [project].

[Deal] information will allow for the [project] to be tracked and reviewed based upon the initial target that was put in place. 

Public and Private Sector [Orgs] can use [Deal-Templates](/Deal-Templates) as an example of how to execute a certain [project] in another location. This produces a higher degree of certainty of outcomes because it enables transparency in [deal] terms, pricing, [functions], and reputation scoring of [orgs] and [people]. 

Example: Yolo County Transportation District’s 2018 RFP [Deal] Record
- Operate their fixed route bus services, their paratransit, and explore many other transit possibilities in the area.
- Transdev ultimately won the contract and is operating their fixed routes and paratransit, while also having outlined what other potential services would look like for Yolo County.


This [deal] can easily be used for by other [orgs] to find provider [orgs] for similar [functions], understand the pricing of these deals, use a similar [deal] template, or to explore new [functions].


### [Tasks] 
While building out projects and attaching them to the DIMO graph, you’ll frequently come across ideas for data sources that would be useful to add.

![community_icon.png](/tasktype/community_icon.png) ![data-collection_icon.png](/tasktype/data-collection_icon.png) ![graph-tooling_icon.png](/tasktype/graph-tooling_icon.png) ![integration_icon.png](/tasktype/integration_icon.png) ![marketing_icon.png](/tasktype/marketing_icon.png) ![schema_update_icon.png](/tasktype/schema_update_icon.png)

We’re tracking a running list of “Requests for Graph Data” [Here].

Examples of [event] streams that originated as [Graph Requests]:
 - The location and status of all the Tesla Superchargers in the world, including the number of plugs, available power, and available amenities”
- All of the commercially available robots that run on ROS, including the version, [type] of robot and cost (if available).
- All NHTSA Projects tracked in the AV TEST platform

Adding a [Task] or [Graph Request] creates an [event] when it’s accepted, and when the data/feed is actually published to the knowledge graph, payment or [badges] are issued according to the original agreement.

#### [Task] Templates:

- These are all of the [[tasks] we've confirmed](https://airtable.com/shrWuPpuUlE3MaTMy) that we're going to offer to members on our platform, including the base price we'll charge. Users will also be able to request any arbitrary [[tasks]](https://airtable.com/shr5ydIkHvmPUTN5E).

There are other ad-hoc [tasks] we're tracking that we've funded through Digital Infrastructure Services: 

- [Task]: [pull in the top 40 Infrastructure [projects] in the US](https://airtable.com/tblIc1j1lbieDf9sd/viwLhWQxSIbpvb6P9/recnVKuiC8uElP0cx) (at least as of 2017...)

- [Task]: pull in all of the [NHTSA-regulated AV [projects] ](https://airtable.com/shrARtAvT79gV3Dnj)

- [Task]: Maintain a list of all of the [Members of PAVE](https://airtable.com/shrTj2vbAH2CXKEY9) - a target AV industry group

### [Badges]

Example [Badges]

![security_icon.png](/security_icon.png) ![legal_icon.png](/legal_icon.png) ![compliance_icon.png](/compliance_icon.png) ![performance_icon.png](/performance_icon.png) ![proofs_icon.png](/proofs_icon.png) ![integration_icon.png](/integration_icon.png)

[Badges] bring order to the [DIMO] knowledge graph, by verifying the capabilities of [projects]. They can also represent real-world claims from regulatory or certification [orgs].

[Badges] are inherited from sub-components of a [Project], [Function], or [Device].

**Badge Types**

For example, if you have a [device] with a “Network Dependency’ badge that is included in a certain [function] (say, a Smart Lock), and the [function]+[Device] combination is used in a specific project, DIMO will assign the “Network Dependency” badge to that project to indicate that a specific [function] included in that project will not work if there is no network connection.

#### [Project] Badges - Seed, Sapling TREE
[Projects] are designed and built to different capability levels based on the basemap data, functionality available, and testing/verification performed.

Digital Infrastructure Inc. uses [badges] to certify all zones carrying commercial traffic on our network. We have developed a simple badging framework to describe how a project should function at each stage in a robotics project:

<table style="width: 100%;"><tbody><tr><th>Stage</th> <th>Functionality </th></tr> <tr><td>[Seed] </td> <td>Read-only - capable of supporting simple wayfinding applications or non-critical information gathering tasks. Useful for ODD compatibility research and site planning.</td></tr> <tr><td>[Sapling]</td> <td>Read-write capable [projects] - capable of supporting operational tasks according to predefined parameters. Useful for operational testing prior to commercial deployment. </td></tr> <tr><td>[TREE] Trusted Robotics Execution Environment </td> <td>Realtime digital twin capable of supporting high-uptime safety-critical applications. Monitoring infrastructure capable of verifying successful mission completion.</td></tr></tbody></table>


### [Zone] Badges
[Projects] that take place in a specific geographic area, or [Zone] inherit the [Badge] requirements of that zone. For example, AV projects in [Zone] California need to apply for a [Badge] permit from the [Org] California DMV in order to user [Device] Autonomous Vehicle in [Function] Public Ridehailing.


### [Device] Badges



### [Badge] [Tasks]
Certain [badges] require effort, expertise, or existing certification. An [org] or person can pay for the necessary verification of integration work required. We have existing task templates set up to achieve this:

- GTFS -RT Feed Set up with monitoring
- Smart Contract Audit
- Device Integration into IoT or Dispatch hub for multiple different [Orgs]
- Home Assistant
- Joyride
- EasyMile

## Using the Knowledge Graph 

DIMO uses a number of tools to collect and organize information. Airtable is the most accessible for beginners. With a valid DIMO account, you can access the public DIMO database here, and start to build your own extensions to the graph. 

### Examples of Projects in the DIMO Airtable**
  
[[Events](https://airtable.com/shryKKrkt7g5DZl9y)] we're tracking. You can filter based on your interest to get lists like: 

- Elon Musk List (Tesla + Boring Company + SpaceX) Project [Events]
- Waymo Project [Events]
- [Projects] coming up for Bid Soon (or past projects that you can FOIA) 

- Public Agency [[Deal]](https://airtable.com/shrzktHuYjqpQMfHf) & [[Project](https://airtable.com/shrhVLXNuwWrt72rt)] Gallery pages. We're going to be building these out significantly.


  





