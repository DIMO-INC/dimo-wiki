---
title: Home Page
description: 
published: true
date: 2020-11-11T06:15:22.372Z
tags: 
editor: markdown
---

![transparent_logo.png](/transparent_logo.png =150x)
# Digital Infrastructure for Moving Objects Knowledge Graph
![citybrain.png](/citybrain.png)

## What is the Knowledge Graph?
<div style="margin-left: 30px;">
  
**Navigating the Graph - Types and Tags**
  [People]
  [Orgs]
  [Devices]
  [Functions]
  [Projects]
  - [Zones]
  - [Project] Instances
  
  [Events]
  - Example [Event] Type - Claims
  - [Event] Streams
  
  [Deals] 

  **[Tasks] & Graph Requests**
  [Badges]
  - [Project] Badges - Seed, Sapling TREE
  - [Zone] Badges
  - [Device] Badges
  - [Badge] [Tasks]
  
</div>


**Building Knowledge Graph Credentials**

Creating & Verifying an Account
- New User Account Signup
- Apply for a Curator Role
- Step 1 - Join Community, Read Docs
- Step 2 - Explore Knowledge Graph & Projects
- Step 3 - Get your First [Badge] By Completing or Funding a [Task]
- Step 4 - Invite a Team and Start Building a [Project] together

Contribution Protocols
- Sources
- Adding [Organizations] [Devices] + [Functions]
- Adding [Event] Streams
-- Add timeline [events], tagging [organizations], [projects], [people], [functions], Adding Data from a Primary Source
-- Adding [Jobs] from [Organizations] and [Projects]



- Terms Index
--Visualization & Data Summarizing Tools In Airtable

# What is the Knowledge Graph?
The DIMO Knowledge Graph is a system for tracking connections between the digital and physical world.
![Knowledge Graph](/knowledge_graph.png)
It’s made up of basic building blocks or “Objects”

![Knowledge Graph](/devices_icon.png =110x) ![Function Icon](/function_icon.png =110x) ![People Icon](/people_icon.png =110x) ![Company](/orgs_icon.png =110x) ![Badge](/badges_icon.png =110x) ![Project](/projects_icon.png =110x)

These entities can be linked together to describe complex systems & relationships.

[Events] & [Relations]


All updates to the knowledge graph are tracked in [Events].


These updates can be simple, like updating the value on a sensor [device] from 70 → 71 degrees F.

They can also describe complex situations like as complicated as an update to a [function] linked a [device], based on a policy [function] set by an [organization] in a specific [project].

![Knowledge Graph](/policyupdate.png)

## Navigating the Graph - Types and Tags
All DIMO Knowledge Graph objects are organized by [type] and [tag].

**Type** - is the broadest description associated with the [object]

[Device] Types are listed

![vehicle_icon.png](/vehicle_icon.png) ![storage_icon.png](/storage_icon.png) ![access-control_icon.png](/access-control_icon.png) ![sensor_icon.png](/sensor_icon.png) ![robot_icon.png](/robot_icon.png) ![computers_icon.png](/computers_icon.png)

Types tell users what they can expect to find in a particular knowledge graph [object].

For example, a [device] with [type] “Home Appliance” can be expected to have the following fields:
- “Power Source” (acceptable values - Battery, 120v outlet, Solar, etc)
- “Network Connection” (acceptable values - None, Wifi, Cell, LoRA WAN, etc)

An iRobot Roomba S9 is an example of a [device] has multiple [types]. It’s both a Home Appliance and a Robot. It contains data that describes Robot qualities like “Actuators”, “Sensors”, and “Compute”, and Home Appliance qualities like “room”, “Hub”, and “Network”.

Types are able to enumerate any knowledge graph data type, and can only be updated by a Graph administrator (more on user roles here). Any user can suggest updates to types by submitting a pull request or entering a task in the “Requests” section of the Graph Roadmap.

Tags - are able to give a more detailed description of the [object], providing more free-form labels and associations with other parts of the knowledge graph. They allow [users] to more easily find and group [devices] appropriately.

For example, ‘Home appliances’ which will have many subgroups [tags] within it, vacuum, microwave, dishwasher, refrigerator, washer/dryer, etc.



### [People] Type

[People] with DIMO accounts can add to the knowledge graph. Typically this is done while designing, developing, maintaining, and upgrading DIMO [Projects].

Different project stakeholders will contribute information to ensure the initial configuration and ongoing operations are aligned with end user needs. A [person] can fill one or more roles within specific [Projects], [Zones], [Orgs], [Devices] they’re affiliated with.

![product-designer_icon.png](/product-designer_icon.png) ![service-operator_icon.png](/service-operator_icon.png) ![author_icon.png](/author_icon.png) ![graph-curator_icon.png](/graph-curator_icon.png) ![support_icon.png](/support_icon.png) ![investor_icon.png](/investor_icon.png)


### [Org] Type
[Org] is a higher level [DIMO] object - one that incorporates multiple [People]. Like people, [Orgs] can be associated with [Projects][Devices][Functions] and assigned [Badges] based on [Events].

If you’ve joined or created an [Org] during onboarding, great! You can also follow an [Org] here to be updated as [Events] are associated with their accounts.

**These [Organizations] have committed to the proposed [Cavnue Smart Road] [Project]**

![hardware_icon.png](/hardware_icon.png) ![media_icon.png](/media_icon.png) ![telecom_icon.png](/telecom_icon.png) ![software_icon.png](/software_icon.png) ![investor_icon.png](/investor_icon.png) ![finance_icon.png](/finance_icon.png)


### [Devices] Type

You can import [Devices] to the knowledge graph and associate them with your account in a couple of different ways:
- Selecting devices from existing or template [Projects]
- Connecting an [Inventory] from [Amazon],[BestBuy] or [SKU] order history
- From product databases attached to [Orgs] like [Autonomous Stuff]

Device types determine the requirements for inclusion in the DIMO knowledge graph, and (eventually) in a live [project]

![vehicle_icon.png](/vehicle_icon.png) ![storage_icon.png](/storage_icon.png) ![access-control_icon.png](/access-control_icon.png) ![sensor_icon.png](/sensor_icon.png) ![robot_icon.png](/robot_icon.png) ![computers_icon.png](/computers_icon.png)


### [Functions] Type
Combinations of [Events] [People] [Devices] - [Function]s produce [Events]

![verification_icon.png](/verification_icon.png) ![phone-app_icon.png](/phone-app_icon.png) ![network_icon.png](/network_icon.png) ![parking_icon.png](/parking_icon.png) ![storage_icon.png](/storage_icon.png) ![spacelink_icon.png](/spacelink_icon.png)

### [Interfaces] Type
[People] interact with [Functions] through [Interfaces]. [Interfaces] are combinations of [devices] and [functions]

![ios_icon.png](/ios_icon.png) ![macos_icon.png](/macos_icon.png) ![webapp_icon.png](/webapp_icon.png) ![android_app_icon.png](/android_app_icon.png) ![app_icon.png](/app_icon.png) ![ethernet_icon.png](/ethernet_icon.png)

### [Projects] Type
The whole point of DIMO is to enable [Projects] that move things around. [Projects] are systems of [orgs], [people], [functions], [devices]

Here’s an example of current and potential [projects] that we’re tracking.
- Automated Valet Parking System (Current)
- [The Boring Company] building a tunnel system under [Las Vegas]

Like most other DIMO [objects], [Projects] can either be a "template" or an "instance"

![iot_icon.png](/iot_icon.png) ![transit_icon.png](/transit_icon.png) ![shared-mobility_icon.png](/shared-mobility_icon.png) ![smart-city_icon.png](/smart-city_icon.png) ![smart-house_icon.png](/smart-house_icon.png) ![testing_icon.png](/testing_icon.png)

### [Projects] Template
[Project] Templates offered by Wunder Mobility, an [Org] Tracked in the DIMO knowledge graph.


### [Zones]
Live [projects] typically contain one or more references to physical locations that can be defined by addresses, zip codes, geo-JSON - these can be home to one or more [projects], and can be set up with administrative structures that are managed by [people]

### [Project] Instances
Combinations of [Project Templates] and [Zones]

A [Project Instance] must be associated with at least one [Zone], and inherits the policies of that [zone].

### [Event]
The knowledge graph to track [events] and associate them with their subjects & participants.

#### Claims

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

**Example: Yolo County Transportation District’s 2018 RFP**
[Deal] Record(
- Operate their fixed route bus services, their paratransit, and explore many other transit possibilities in the area.
- Transdev ultimately won the contract and is operating their fixed routes and paratransit, while also having outlined what other potential services would look like for Yolo County.


This [deal] can easily be used for by other [orgs] to find provider [orgs] for similar [functions], understand the pricing of these deals, use a similar [deal] template, or to explore new [functions].


### [Tasks] & Graph Requests
While building out projects and attaching them to the DIMO graph, you’ll frequently come across ideas for data sources that would be useful to add.

![community_icon.png](/tasktype/community_icon.png) ![data-collection_icon.png](/tasktype/data-collection_icon.png) ![graph-tooling_icon.png](/tasktype/graph-tooling_icon.png) ![integration_icon.png](/tasktype/integration_icon.png) ![marketing_icon.png](/tasktype/marketing_icon.png) ![schema_update_icon.png](/tasktype/schema_update_icon.png)

We’re tracking a running list of “Requests for Graph Data” [Here].

Examples of [event] streams that originated as [Graph Requests]:
 - The location and status of all the Tesla Superchargers in the world, including the number of plugs, available power, and available amenities”
- All of the commercially available robots that run on ROS, including the version, [type] of robot and cost (if available).
- All NHTSA Projects tracked in the AV TEST platform

Adding a [Task] or [Graph Request] creates an [event] when it’s accepted, and when the data/feed is actually published to the knowledge graph, payment or [badges] are issued according to the original agreement.

### [Badges]

Example [Badges]

![security_icon.png](/security_icon.png) ![legal_icon.png](/legal_icon.png) ![compliance_icon.png](/compliance_icon.png) ![performance_icon.png](/performance_icon.png) ![proofs_icon.png](/proofs_icon.png) ![integration_icon.png](/integration_icon.png)

[Badges] bring order to the [DIMO] knowledge graph, by verifying the capabilities of [projects]. They can also represent real-world claims from regulatory or certification [orgs].

[Badges] are inherited from sub-components of a [Project], [Function], or [Device].

**Badge Types**

For example, if you have a [device] with a “Network Dependency’ badge that is included in a certain [function] (say, a Smart Lock), and the [function]+[Device] combination is used in a specific project, DIMO will assign the “Network Dependency” badge to that project to indicate that a specific [function] included in that project will not work if there is no network connection.

### [Project] Badges - Seed, Sapling TREE
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

# Building Knowledge Graph Credentials

[DIMO] is designed to unlock creativity at all layers in a [project]. A critical aspect of this is making it possible for anyone to contribute and get recognized for their work.


#### Creating & Verifying an Account
Anyone with an internet connection and a github account can contribute directly to a project or to the DIMO documentation, but to access badges and build a reputation score you need to create a DIMO account


#### New User Account Signup
Complete this form, and add detail to your account by linking existing credentials.


#### Becoming a Curator
The best way to build some credibility in the DIMO knowledge graph is to contribute to it.

We’ve set up a series of choose-your-own-adventure missions to get you familiar with the DIMO network graph.

It’s divided into 20 minute chunks - you can typically finish the first three exercises within an hour. After the 3rd stage your work will be submitted to an admin for approval

Fill out this form. If approved, you’ll be able to submit changes to the Knowledge Graph, and participate in the [Tasks] marketplace.


### Step 1 - Join Community, Read Docs
- Read the [DIMO Knowledge Graph Onboarding] (You’re doing that now).
- Create an account on Dimo.zone and join our Discord. Link your Discord username to your DIMO account to Link your status and permissions.
- If you want to receive tokens for contributions (and who doesn’t??!) Sign up for Metamask and add your address to your [person] or [org] account by copying it as pictured.

### Step 2 - Explore Knowledge Graph & Projects
- Familiarize yourself with the DIMO Knowledge Graph Onboarding Document (You’re reading it now), adding any questions as comments.
- Look through some of the template projects, functions, [devices], and [organizations] on the platform.
- See anything missing? Create a [task] to add some new data: [Link enables a user to submit requests for new entries to the knowledge graph, before they’re granted edit permissions to make changes themselves]

### Step 3 - Get your First [Badge] By Completing or Funding a [Task]
This is a list of [Tasks] that are good to get started with if you’re new to DIMO. Choose one from the “Unassigned” list and get busy! Some of these tasks also carry token awards too, and you can filter down to see only those tasks.
There are also a few ongoing tasks that anyone can do anytime. Here’s one:

- Read the overview of [Events] included above and - add an event and associate it with an [org], [project], or [function] we already have on the DIMO platform. Choose something you’re interested in.
- Are you a TSLA fan? Pull in some information about their product announcements, or the [Boring Company] tunnels in Las Vegas.
- Upset about how long the I5 widening is taking (or upset that it’s even happening..) add a project update and tag [LA Metro] and [CalTrans].


#### Creating and Funding a [Task]
Long on cash but short on time? You can build out any part of the graph by funding a task!

Many tasks already have templates supported by instructional Loom videos that can be repurposed for any domain.


### Step 4 - Invite a Team and Start Building a [Project] together
Hopefully once you have your first DIMO contribution [badge] assigned to your account you have started to think of a couple of [Projects] that you’d like to add.

- Invite a friend or 10 to the Discord - it’s more fun to build DIMO with other people who are interested in the same things. If you are here on behalf of an organization, you can build a knowledge graph with your colleagues.
- Once they’ve joined, make sure they fill out this form so your accounts are linked. Now you can build together.

# Contribution Protocols

Adding information about [Organizations], [Devices], [Users], [Events], [Projects].

### Sources
Each piece of information added to the graph includes a citation

Common Sources of Information:

1. https://theorg.com/explore - [Org] Information
1. https://www.crunchbase.com/ [Orgs][Devices][Functions]
1. https://www.welcometothejungle.com/en/ - [Jobs]
1. https://www.linkedin.com/ - [Jobs] [Organizations]
1. RSS Feeds like AV News or Tesla Supercharger Locations.

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

# Terms Index

<table><tbody><tr><th>Object / Term</th> <th>Description</th> <th>Types</th></tr> <tr><td>Zones</td> <td>Geographic areas with explicitly defined administrative control over right of way and other policies like account registration and data access. Zones can have one or more Project Instances.</td> <td></td></tr> <tr><td>Project Templates</td> <td>Specific combinations of Devices, Functions, and Interfaces. These can be based off of past, existing, or desired future systems, and customized by users to fit their specific geographic configuration or use-case. Users can create Instances that combine multiple zone templates, and expand / update their own templates over time.</td> <td></td></tr> <tr><td>Project Instances</td> <td>Project Templates that have been implemented in real Zones. To earn certified project status an administrator must get sign-off from all project partners, land owners, and a 3rd party verification service.</td> <td></td></tr> <tr><td>Devices</td> <td>An object that is tracked within the DIMO network that can participate in functions and be assigned to one or more zones, organizations, or users.</td> <td></td></tr> <tr><td>Function-Templates</td> <td>A ruleset that can be configured to a secific purpose within a zone or template. Functions take in messages and output transactions.</td> <td></td></tr> <tr><td>Interfaces</td> <td>A way for a user to interact with functions to create transactions.</td> <td></td></tr> <tr><td>Badges</td> <td>A specific functional ability that has been certified by a user or organization within a zone. Badges work best when they're attached to a 3rd-party verifiable service that can prove their accuracy on an ongoing basis.</td> <td></td></tr> <tr><td>People</td> <td>Unique digital representation of real-world people &amp; objects - Can be people, operators, dispatchers, vehicles, smart home devices. Accounts can transact with, associate with, and control other accounts.</td> <td></td></tr> <tr><td>Organizations</td> <td>A higher level [DIMO] object made up of multiple [People]. Like [people], [Orgs] can be associated with [Projects][Devices][Functions] and assigned [Badges] based on [Events].</td> <td></td></tr> <tr><td>Jobs</td> <td>Work that is required to design, build, operate, or maintain a Zone, Interface, Project, or Function. Jobs range from one-off tasks to ongoing engagements, and they can be completed by organizations or individuals.</td> <td></td></tr> <tr><td>Transactions</td> <td>Signed messages sent from one account to another that update the state of the DIMO knowledge graph. These can represent transactions, claims (scoping) about a market participant, policy updates, or any other arbitrary data exchange meant to change an existing object.</td> <td></td></tr></tbody></table>

## Visualization & Data Summarizing Tools In Airtable

You need to display a large amount of data and contextual information. Use cases include material management and supply chains, logistics structures, and value chains.

Display complex nonlinear structures, trees, and relationships:
- [vendor-supplier relationships]
- [Project administrative org charts]
- [Investor/owner relationships].

Giving the data a spatial context
- Where are certain technologies being used?
- Which [jobs] are available in which locations?