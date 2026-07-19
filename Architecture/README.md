# Architecture

This folder contains the system architecture diagrams, workflow diagrams, and solution architecture for the AI Supply Chain Control Tower.
# Architecture

## Overview

This folder contains the architecture diagrams for the AI Supply Chain Control Tower.

The solution demonstrates how workflow automation, business intelligence, and executive decision support can be integrated into a unified supply chain platform.

## Components

- Google Sheets
- n8n Workflows
- JavaScript
- Executive Decision Center
- Power BI
- Gmail Notifications

## Architecture Diagrams

- System Architecture
- Data Flow
- Workflow Architecture
# System Architecture

```mermaid
flowchart TD

A[Google Sheets] --> B[n8n Workflows]

B --> C[Inventory Intelligence]
B --> D[Supplier Risk Intelligence]
B --> E[AI Procurement Advisor]
B --> F[Warehouse Intelligence]
B --> G[Demand Planning Intelligence]
B --> H[Logistics Intelligence]

C --> I[Executive Decision Center]
D --> I
E --> I
F --> I
G --> I
H --> I

I --> J[Power BI Dashboard]
I --> K[Gmail Notifications]
```
# Data Flow

```mermaid
flowchart LR

A[Operational Data]

A --> B[Google Sheets]

B --> C[n8n Workflow Automation]

C --> D[JavaScript Processing]

D --> E[Business KPIs]

E --> F[Executive Decision Center]

F --> G[Power BI]

F --> H[Email Alerts]
```
# Workflow Architecture

```mermaid
flowchart TB

A[Inventory Intelligence]

B[Supplier Risk Intelligence]

C[AI Procurement Advisor]

D[Warehouse Intelligence]

E[Demand Planning Intelligence]

F[Logistics Intelligence]

A --> G[Executive Decision Center]
B --> G
C --> G
D --> G
E --> G
F --> G

G --> H[Executive Recommendations]
```
