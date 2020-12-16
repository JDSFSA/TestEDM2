---
layout: default
title: Enrolment
nav_order: 4
has_children: false
parent: Entities
categories: entity
---

This model was last updated on **16/09/2020**, this is version **1.0**

Stable
{: .label .label-green }

##### Model created
07/01/2020

### Description
Enrolment is an FSA record of an Establishment to register or seek approval to perform food and feed related activities or be part of a recognised scheme.  

Enrolment is a combination of entities; [Scheme](/enterprise-data-models/entities/scheme.html), [Competent Authority](/enterprise-data-models/entities/competent-authority.html), and [Establishment](/enterprise-data-models/entities/establishment.html). A change in either of these may require a new application for Enrolement.

Enrolment in new schemes does not necessarily impact on existing schemes you are enrolled in.

### Related entities
[Scheme](/enterprise-data-models/entities/scheme.html), [Competent Authority](/enterprise-data-models/entities/competent-authority.html), and [Establishment](/enterprise-data-models/entities/establishment.html) are child entities of Enrolment.

[Establishment](/enterprise-data-models/entities/establishment.html) are enrolled in [schemes](/enterprise-data-models/entities/scheme.html), which means they can carry out [activities](/enterprise-data-models/entities/activity.html), and/or are subject to [interventions](/enterprise-data-models/entities/intervention.html) and [enforcements](/enterprise-data-models/entities/enforcment.html) that are carried out by a [Competent Authority](/enterprise-data-models/entities/competent-authority.html).

### Unique Identifiers
The preferred unique identifier for Enrolment in the FSA is the enrolment reference number

### Entity diagram
![enrolment](/enterprise-data-models/entities/diagrams/enrolement.png)


### What it is not
Not all reference numbers relate to activities or schemes.

### Synonyms
*   Register number
*   Enrolment number
*   Activity Registration
*   Scheme Registration

## Key Properties
The key properties are the entities [Scheme](/enterprise-data-models/entities/scheme.html), [Competent Authority](/enterprise-data-models/entities/competent-authority.html), and [Establishment](/enterprise-data-models/entities/establishment.html) please see the definition for these entities.

## Reference data
*   [activities register](https://data.food.gov.uk/codes/organisation/_activities)
*   [Enrolment](link to enrolment Status)

## Further Information
*   Enrolments are concurrent and consecutive.  They have a start and end date and cannot be modified. If an establishment is removed from a scheme the status will be changed appropriately and an end date will be recorded.  Establishments can request to re-enroll provided they meet the criteria.  New enrollment documentation will be required and a new UID will be generated.
*   Link to the [FHRS scheme](https://ratings.food.gov.uk/)
*   Link to the [shellfish classification scheme](https://www.food.gov.uk/business-guidance/shellfish-classification).

### Owner
Food Standards Agency
