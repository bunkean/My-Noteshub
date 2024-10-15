# Document Your Domain
Many engineers underestimate ==power== of diagram (conveying their ideas and thoughts and its ability to further your career)

- ==Power== of being able to turn words and thoughts into diagrams
```mermaid
---
title: First diagram using Mermaid
---
flowchart LR
a --> b & c --> d
```
- Biggest ==power== that comes from domain modeling is the ==collaboration==
  - How it ==brings everyone== on the journey and ultimately to the same destination
  - Ability to allow your domain and code ==to evolve== over time
- Document your domain
  - Documenting the ==important steps== with diagram
  - Domain modeling is the primary way of determining the ==important aspects== of a business
  - Landed on a ==culmination== of a few different ideas and were able to ==easily translate== the domain model into code
- Create domain model
  - Created ==collaboratively== by engineering, product, and business stakeholders to ensure all major parts of the business are ==aligned== on what the domain model looks like.
- ==Reference== it at any point
  - It’s very common for ==new requirements== to come along later

As we’re all== speaking the same language,== and the ==code flows easily== because we have a clear idea of how we should represent these ==business requirements== using our domain model.
## Determine the Important Entities
>Think of all the ==important entities== within your business.
>>An ==entity== represents a core concept within the business.
>>==Entities== are typically the phrases that are most used in the codebase(would contain ==entity== data and business logic) and in meetings.
## Document Our First Relationship
### Define Associations
```mermaid
classDiagram
Title -- Genre
```
> Associations are very loose ways to link two entities
> No “owner” of the relationship for associations
> Think of relationship as “using” one another rather than one owning the other
### Define Composite Relationships
```mermaid
classDiagram
Title -- Genre
Title *-- Season
Title *-- Review

Season *-- Episode
```
We now know two relationship types:
  * Associations, which are two entities that are loosely related and can exist independent of one another.
  * Compositions, which indicate two entities are tightly related and cannot exist independently of one another.

One more, though, sits between those two in terms of how closely related two entities are.
### Define Aggregate Relationships
```mermaid
classDiagram
Title -- Genre
Title *-- Season
Title *-- Review

Season *-- Episode

Title o-- Actor
```
>In an aggregate relationship, there’s ==still an owner==—the parent. However, the bond between them ==isn’t as strong as== a composite relationship, and if the parent were to be deleted, the child ==can still exist==.
## Document Your Own Domain
## What You’ve Learned
# Enhance Your Domain Model
## Define Inheritance
## Describe Relationships
## Add Multiplicity
## Add a Title
## Improve Readability
## Enrich Nodes with Links
## Enhance Your Domain Model
## What You’ve Learned
# Visualize Application and User Flows
## Define Actors and Participants
## Add Our First Interaction
## Show Branching Logic
## Display Asynchronous Messages
## Display Length of Interactions with Activations
## Add Additional Information with Notes
## Annotate Your Diagram with Sequence Numbers
## Create Dropdown Menus
## Visualize Your Own Application Flow
## What You’ve Learned
# Model Your Architecture
## Using the C4 Model
## Creating a System Context Diagram
## Add Nodes
## Connect Nodes
## Add Some Style
## Create Your Own System Context Diagram
## What You’ve Learned
# Detail Your System’s Containers
## Define the First Two Containers
## Create Clear Boundaries with Subgraphs
## Add Supporting Systems
## Improve Readability with Link Lengths
## Display Asynchronous Interactions
## Additional Arrow Types
## Create Your Own Container Diagram
## What You’ve Learned
# Structure Your Components and Code
## Code Diagram
## Leverage Flowcharts for Complex Flows
## What You’ve Learned
# Design Database Schemas
## Use Entity Relationship Diagrams
## Define Our First Entity
## Relate Entities
## Add Zero-to-Many Relationships
## Enrich Schemas with Keys
## Comment Your Columns
## Define Zero-or-One Relationships
## Describe Non-identifying Relationships
## Finalize Streamy’s ERD
## Design Your Database Schema
## What You’ve Learned
# Visualize Code Flows
## Use Sequence Diagrams to Understand Class Interactions
## Define Loops
## Show Parallel Processes
## What You’ve Learned
# Design and Refactor Your Applications
## Define Classes
## Show Dependencies with Relationships
## Refactor the Classes
## Introduce a Request Class
## Define Interfaces
## Create a Class Diagram
## What You’ve Learned
# Render Diagrams Using Native Support
## Leverage Native Mermaid Integrations
## Render Mermaid Within Markdown Files
## Where Should You Include Diagrams?
## What About Websites Without Native Support?
## Keep Diagrams Up-to-Date
## Render a Diagram on GitHub
## What You’ve Learned
# Create a Static Site with Mermaid Diagrams
## Devise a Plan of Action
## Learn the Basics of a GitHub Action
## Start by Defining the Events That Trigger the Action
## Check Out the Repository’s Code
## Convert Mermaid Markup to SVGs in Markdown
## Build Jekyll Artifacts
## Deploy to GitHub Pages
## Run the Action
## Render Diagrams on Page Load
## What You’ve Learned
# What You’ve Learned
