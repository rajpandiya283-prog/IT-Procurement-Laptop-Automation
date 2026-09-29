# Phase 3 – Project Design

## System Design

The project is designed to automate the Standard Laptop procurement process in ServiceNow.

## Process Flow

1. User selects the Standard Laptop service from the Service Catalog.
2. User places the laptop request.
3. The request goes through the approval process.
4. After approval, the Flow Designer flow is triggered.
5. The flow creates a Catalog Task.
6. The Catalog Task is assigned to the Hardware group.
7. The task contains the required short description and description.

## Flow Design

The Flow uses:
- Service Catalog trigger
- Create Catalog Task action
- Requested Item record
- Short Description
- Description
- Assignment Group – Hardware
- Approval – Approved

## Expected Output

A Catalog Task is automatically created for the approved Standard Laptop request and assigned to the Hardware group.
