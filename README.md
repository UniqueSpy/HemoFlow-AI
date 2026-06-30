# HemoFlow AI 🩸

AI-powered healthcare coordination platform built for UiPath AgentHack 2026 using UiPath Apps, AI Agents, and Human-in-the-Loop automation for intelligent blood supply management.

---

# Inspiration

During COVID-19, we observed that hospitals struggled the most with oxygen and blood availability, especially plasma. We wanted to create a solution that enables hospitals to support each other through intelligent coordination and fast decision-making.

Inspired by the idea:

*"A friend in need is a friend indeed."*

HemoFlow AI creates a chain of connected hospitals where hospitals help one another during emergencies through a centralized ecosystem.

---

# Problem Statement

Hospitals often face:

* Blood shortages
* Delayed request processing
* Lack of inventory visibility
* Manual coordination between hospitals
* Slow transfer approval processes

These delays can directly affect patient care and emergency response.

---

# What HemoFlow AI Does

HemoFlow AI enables hospitals to:

✅ Raise blood requests
✅ Search inventory across hospitals
✅ Approve or reject requests
✅ Escalate urgent cases
✅ Track transfer status
✅ Receive AI-powered operational recommendations
✅ Monitor inventory risks
✅ Support Human-in-the-Loop decision making

---

# Key Features

## Approval Center

* Approve request
* Reject request
* Escalate request
* Hospital-specific visibility logic
* Human decision workflow

### Approval Logic

**Approve**

* Request accepted
* Transfer ID generated
* Transfer process initiated

**Reject**

* Request removed only for rejecting hospital
* Other hospitals can still approve

**Escalate**

* Makes request visible to all hospitals
* Higher priority handling

---

## Transfer Tracking

After approval:

* Unique Transfer ID generated
* Track transfer lifecycle
* View hospital details
* View transfer status timeline

Transfer stages:

* Request Raised
* Approved
* Blood Prepared
* In Transit
* Delivered

---

## AI Insights Panel

AI analyzes:

* Inventory shortages
* Transfer risks
* Urgent requests
* Transfer priorities
* Operational bottlenecks
* Blood demand patterns

Provides concise operational recommendations.

---

# System Architecture

Hospital User

↓

UiPath Apps

↓

RPA Workflow

↓

AI Agent Flow

↓

Fetch Operational Data Tool

↓

AI Analysis & Recommendation Engine

↓

Approval / Transfer Actions

---

# UiPath Components Used

* UiPath Apps
* UiPath AI Agents
* UiPath Data Service
* UiPath Orchestrator
* UiPath Workflows
* Human-in-the-Loop Automation
* Agentic AI
* Workflow Orchestration

---

# Agent Type

HemoFlow AI uses:

**Low-code Agents**

with workflow-based orchestration and Human-in-the-Loop decision making.

---

# Repository Structure

```text
HemoFlow-AI
│
├── Approval-Center
├── Dashbaord
├── LoginValidation
├── README.md
└── LICENSE
```

---

# Setup Instructions

### Step 1

Clone repository

```bash
git clone <repository-url>
```

### Step 2

Import workflows into UiPath Automation Cloud.

### Step 3

Configure Data Service entities:

* Hospital Details
* Inventory
* Blood Requests
* Transfer Records
* Request Visibility

### Step 4

Publish workflows into Orchestrator.

### Step 5

Configure AI Agents and connect workflow tools.

### Step 6

Bind workflows inside UiPath Apps.

### Step 7

Run application and start raising requests.

---

# Challenges We Faced

* Integrating AI Agents with workflow tools
* Managing process deployment dependencies
* Designing decentralized approval logic
* Creating hospital-specific visibility rules
* Connecting Apps with workflow orchestration

---

# Accomplishments We're Proud Of

* AI-powered operational recommendations
* Human-in-the-Loop approval workflows
* Transfer tracking system
* Intelligent healthcare coordination
* Centralized hospital collaboration ecosystem

---

# What We Learned

* Agentic AI architecture
* UiPath AI Agents
* Workflow orchestration
* Enterprise automation design
* Healthcare coordination workflows

---

# What's Next

Future improvements:

* Predictive blood shortage forecasting
* Real-time transfer updates
* Donor management integration
* Hospital network analytics
* Integration with real healthcare systems

---
Note: The license applies only to original solution code and does not extend to UiPath proprietary tools, SDKs, activities, or platform components.
