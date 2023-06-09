# Project Overview Statement

## Problem/opportunity

Our sales revenue decreased by 30% due to a drop in our home delivery business.
The reason seems to be an increase in the service quality of the major competitor.
## Project Goal

Increase sales by becoming more competitive in the delivery business.
## Project Objectives

Implement a software system composed of the following subsystems:

## Pizza Factory Locator

Determine how many factories will be needed and their location.

- Business value:
  - Optimize factory locations to make delivery more efficient.
- Assumptions:
  - Availability of the geographic data.
  - Availability of the modeling tool.
- Risks and obstacles
  - Features and requirements are not clearly defined.
  - There is not a clear vision for the solution.
  - High possible cost for system implementation.

## Order Entry

- Business value
  - Automation of order placement.
- Assumptions
  - Possibility of reusing existing commercial software.
- Risks and obstacles
  - The single location that receives telephone orders can be a bottleneck and a single point of failure.

## Order Submit
Assign the order to a store, factory or pizza van.
- Business value
  - Automation of order transmission. 
- Risks and obstacles
  - Requirements are not clearly defined.
  - The logistics are not clear.
- Note
  - This subsystem can be part of the Order Entry subsystem. 
  This could simplify the design of the whole system.

## Logistics
Manage the delivery of an order through a van.
- Business value
  - Increment the efficiency of order delivery. This is directly connected to the Project Goal.
- Assumptions
  - It's possible to track the vans in real time.
- Risks and obstacles
  - The complexity of determining the right van is high.

## Routing
Subsystem used by vans to determine the best route to a destination.
- Business value
  - Make transit easier and more efficient.
- Assumptions
  - Van pilots are used to this kind of systems.
  - Street traffic and status is updated regularly and possibly real-time.
- Risks and obstacles
  - There are no significant obstacles since there are many GPS technologies already available on the market.

## Inventory Management

- Business value
  - Automation of item management.
  - Decrease the risk of human error.
  - Produces data that can be utilized later in some data science applications.
- Assumptions
  - There are COTS software solutions suitable for this subsystem already available in the market.


## Success Criteria

The system improves our delivery service by:

- Deliver unbaked pizza in 30 minutes or less
- Deliver baked pizza in 45 minutes or less
