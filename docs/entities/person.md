---
layout: default
title: Person
nav_order: 6
has_children: false
parent: Entities
categories: entity
---

# Person

This pattern was last updated **22/09/2020**, this is version **0.1**

Experimental
{: .label .label-yellow }

## Description
The person entity is an individual that interacts in one way or another in the Food and or Feed chain.

### Related entities
The list of related entities will be expanded upon as related entities are documented.

[Operator](/enterprise-data-models/entities/operator.html)

### Entity diagram
NA

### Synonyms
*   Employee
*   Contractor
*   Customer
*   Inspector
*   Auditor
*   Member of the Public

### What it is not
Person entity should not be used to identify a group of people, nor should it be used to describe a thing.

## Key properties
The key properties are the entities include;

*   First Name
*   Last Name
*   Email address

## Contextual properties
A person can wear many different hats within any industry, for example a Food Hygiene Officer can be an employee of a Competent Authority, they could be contracted out to assist another organisation and have a contractor number, they could be the inspector to a local takeaway, and the Auditor to a food processing company, they are a customer/consumers to grocery store, they may even be a producer and run a small farm.  A person is recorded by many different organisations in many different ways.

## Unique identifiers
The unique identifier for Person will vary depending on the role the Person is fulfilling at any stage of their interaction with the Food and Feed industry. It is the responsibility of the organisation recording the Person details to decide what that should be.  For example;

*   An employee could have their staff number as a unique identifier
*   A customer may have their email address used as a unique identifier
*   A contractor may have contractor id used as a unique identifier

## Reference data
NA
