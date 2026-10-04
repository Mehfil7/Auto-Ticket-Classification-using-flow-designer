# Auto Ticket Classification using Flow Designer

## Overview
An automated IT Service Management workflow built in ServiceNow Flow Designer to automatically categorize, prioritize, and route school IT support tickets (Incidents).

## Features
- **Trigger**: Automatic execution upon new Incident record creation.
- **Conditional Logic**: Multi-branch IF/ELSE IF conditions based on ticket short descriptions and categories.
- **Automated Routing**: Dynamically assigns tickets to the appropriate support teams (e.g., Network, Hardware/Projector).
- **Notifications**: Automated email notifications and incident record updates.

## Project Contents
- `sys_remote_update_set_...xml`: Complete ServiceNow Local Update Set export.
- `sys_hub_flow_...xml`: Flow Designer XML definition.

## Deployment Instructions
1. Navigate to **System Update Sets > Retrieved Update Sets** in ServiceNow.
2. Click **Import Update Set from XML** and select the `.xml` update set file from this repository.
3. Preview and commit the Update Set to deploy the flow.
