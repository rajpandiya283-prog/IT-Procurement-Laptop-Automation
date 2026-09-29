# Phase 5 – Project Development

## Development Activities

The automation was developed using ServiceNow Flow Designer.

### Flow Configuration

- Flow Name: Standard laptop task
- Application: Global
- Run As: System user
- Trigger: Service Catalog
- Action: Create Catalog Task

### Catalog Task Configuration

- Requested Item Record: Selected
- Table: Catalog Task
- Short Description: Laptop need to Configured
- Description: Laptop need to Configured
- Assignment Group: Hardware
- Approval: Approved

### Flow Assignment

The Standard laptop task flow was assigned to the Standard Laptop service catalog item through the Process Engine configuration.

## Development Result

The configured flow creates a Catalog Task for the approved Standard Laptop service request and assigns the task to the Hardware group.
