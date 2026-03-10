# 🧪 Engineering Labs & Project-Based Learning

### Module 3: Information Architecture & Content Planning

Project-based learning transforms technical writing from theory into applied engineering. The exercises below simulate real documentation challenges encountered in software companies, startups, and product teams. Every lab requires learners to analyze systems, structure knowledge, and produce documentation artifacts used by **software engineers, product managers, and technical writers**.

These projects are intentionally designed to resemble work performed in real organizations.

---

# Project-Based Learning Philosophy

The labs follow four engineering principles used in modern documentation teams.

**1. Documentation as Infrastructure**

Documentation is treated as a structured system, similar to software architecture.

Learners design:

* documentation systems
* navigation structures
* knowledge repositories
* documentation pipelines

---

**2. Cross-Functional Documentation**

Projects simulate collaboration between:

* engineers
* product managers
* support teams
* technical writers

Documentation must serve **multiple audiences simultaneously**.

---

**3. Problem-Driven Learning**

Each lab begins with a realistic problem scenario such as:

* a chaotic internal wiki
* missing API documentation
* poor onboarding for developers
* unstructured product documentation

Learners solve the problem using **information architecture techniques**.

---

**4. Deliverable-Driven Training**

Every project produces real artifacts:

* documentation blueprints
* information architecture maps
* structured documentation repositories
* product documentation systems

---

# Engineering Lab 1

# Documentation System Audit

## Objective

Learn to evaluate an existing documentation system and redesign its structure using information architecture principles.

This exercise simulates work performed by **technical writers joining a company with disorganized documentation**.

---

## Scenario

A growing SaaS company has accumulated documentation across multiple platforms:

* GitHub READMEs
* internal wikis
* Google Docs
* Notion pages
* scattered API references

Developers cannot easily locate documentation.

Support teams repeatedly answer the same questions.

Product managers struggle to maintain release notes.

Your task is to **audit the documentation system and redesign the architecture**.

---

## Step 1: Documentation Inventory

List all documentation sources.

Example:

```id="htqpl8"
Documentation Sources

GitHub READMEs
API documentation site
Engineering wiki
Product requirement documents
Customer help center
Release notes
Onboarding guides
```

Create a structured inventory spreadsheet.

Columns include:

| Document     | Location         | Owner       | Audience       | Status   |
| ------------ | ---------------- | ----------- | -------------- | -------- |
| API Docs     | docs.company.com | Engineering | Developers     | Active   |
| Feature Docs | Notion           | Product     | Internal Teams | Outdated |

---

## Step 2: Identify Structural Problems

Analyze documentation weaknesses.

Common issues include:

**Content duplication**

Multiple guides explaining the same feature.

---

**Navigation confusion**

Users must search multiple platforms to find answers.

---

**Outdated information**

Documentation not updated after product changes.

---

**Audience mismatch**

Developer documentation mixed with customer documentation.

---

## Step 3: Map Current Architecture

Create a diagram showing how documentation currently exists.

Example structure:

```id="j7m7nh"
GitHub
   README
   Setup Guide

Notion
   Product Specs
   Roadmaps

Help Center
   Customer FAQs
```

Visualize fragmentation.

---

## Step 4: Redesign Documentation Architecture

Propose a unified documentation structure.

Example solution:

```id="23rua9"
Documentation Portal

Product Overview
Getting Started
Developer Documentation
API Reference
Integration Guides
Troubleshooting
Release Notes
```

---

## Deliverable

Produce a **Documentation Audit Report** including:

* documentation inventory
* structural problems
* redesigned architecture
* migration plan

---

# Engineering Lab 2

# Designing a Product Documentation Architecture

## Objective

Design a structured documentation system for a new software product.

This simulates work performed by **technical writers during product launches**.

---

## Scenario

You are documenting a **cloud-based collaboration platform** used by engineering teams.

Core product features include:

* team workspaces
* real-time messaging
* API integrations
* analytics dashboards

The documentation system must support:

* developers
* administrators
* end users

---

## Step 1: Identify User Roles

Different users require different documentation.

Example roles:

```id="vuvcmy"
Developers
Administrators
End Users
Support Engineers
```

---

## Step 2: Identify User Goals

Each role has unique goals.

Example:

**Developers**

* integrate APIs
* configure webhooks
* build automation

---

**Administrators**

* manage users
* configure permissions
* monitor system usage

---

**End Users**

* create projects
* communicate with team members
* track tasks

---

## Step 3: Create Documentation Structure

Design a documentation portal structure.

Example:

```id="krbnib"
Documentation Portal

Getting Started
Product Overview
User Guides
Administrator Guides
Developer Documentation
API Reference
Integrations
Troubleshooting
Release Notes
```

---

## Step 4: Define Topic Types

Apply topic-based authoring.

Example:

Concept topics

```id="nn6l6s"
What is a Workspace
How Messaging Works
Understanding Integrations
```

Task topics

```id="de0mna"
Create a Workspace
Invite Team Members
Configure Webhooks
```

Reference topics

```id="bb25b5"
Webhook API Reference
User Permission Matrix
Supported Integrations
```

---

## Step 5: Design Navigation System

Define navigation components.

Example:

```id="f1qgu0"
Sidebar navigation
Search system
Breadcrumb navigation
Role-based documentation sections
```

---

## Deliverable

Produce a **Documentation Architecture Blueprint** containing:

* user role analysis
* documentation structure
* topic classification
* navigation design

---

# Engineering Lab 3

# API Documentation System Design

## Objective

Build a structured documentation system for a REST API.

This exercise reflects real work performed by **technical writers collaborating with backend engineers**.

---

## Scenario

An engineering team has built a payment processing API.

Developers want to integrate the API into their applications.

Documentation must include:

* authentication instructions
* endpoint documentation
* example requests
* troubleshooting guides

---

## Step 1: Identify API Documentation Components

Standard API documentation includes:

```id="84qk6y"
API Overview
Authentication
Endpoints
Request/Response Examples
Error Codes
Rate Limits
SDKs
```

---

## Step 2: Document API Endpoints

Example endpoint documentation:

```id="mk9c1h"
POST /payments

Description:
Creates a payment transaction.

Parameters:
amount
currency
customer_id

Example Request:
POST /payments
{
  "amount": 200,
  "currency": "USD"
}
```

---

## Step 3: Create Integration Guides

Develop tutorials for developers.

Example:

```id="th8gws"
Integrating Payments with Node.js
Integrating Payments with Python
Integrating Payments with Java
```

---

## Step 4: Add Troubleshooting Documentation

Common problems developers face:

* authentication failures
* invalid request parameters
* rate limits

Example troubleshooting guide:

```id="asqddj"
Error: Invalid API Key

Cause:
Incorrect API key configuration.

Solution:
Verify API key in environment variables.
```

---

## Deliverable

Produce a **complete API documentation system**.

---

# Engineering Lab 4

# User-Journey Documentation Mapping

## Objective

Learn to structure documentation based on how users interact with products.

---

## Scenario

A new developer is joining a software team.

Documentation must guide them through:

* setting up development environment
* understanding system architecture
* contributing code

---

## Step 1: Map the Developer Journey

Example:

```id="uk6g1o"
Account Setup
Development Environment Setup
Codebase Overview
Running the Application
Submitting Pull Requests
Deployment Process
```

---

## Step 2: Identify Documentation for Each Stage

Example:

**Stage: Development Setup**

Required documentation:

```id="qgl5np"
Installing dependencies
Configuring databases
Running development servers
```

---

## Step 3: Design Documentation Flow

Structure documentation sequentially.

Example:

```id="u98kkh"
Developer Onboarding Guide

1 Setup Account
2 Install Development Tools
3 Clone Repository
4 Run Application
5 Explore Codebase
```

---

## Deliverable

Produce a **Developer Onboarding Documentation System**.

---

# Engineering Lab 5

# Building a Documentation Repository (Docs-as-Code)

## Objective

Teach technical writers to manage documentation using Git workflows.

---

## Scenario

Documentation will be hosted in a Git repository.

Writers must structure documentation for scalability.

---

## Step 1: Create Repository Structure

Example:

```id="l1zh1f"
docs/

getting-started/
installation.md
quickstart.md

guides/
workspace-guide.md
integration-guide.md

api/
authentication.md
payments-api.md
errors.md
```

---

## Step 2: Write Structured Markdown Documentation

Example topic:

```id="7q7gbf"
# Install the Application

## Prerequisites
Node.js installed
PostgreSQL installed

## Installation Steps
1 Clone repository
2 Install dependencies
3 Configure environment variables

## Verification
Run the application server.
```

---

## Step 3: Implement Documentation Navigation

Using a documentation generator:

Examples:

* MkDocs
* Docusaurus
* Sphinx

Example navigation:

```id="bovpcc"
nav:
  - Getting Started:
      - Installation
      - Quickstart
  - Guides:
      - Workspace Guide
      - Integration Guide
```

---

## Deliverable

Produce a **Git-based documentation repository**.

---

# Capstone Project

# Build a Complete Documentation System

Students apply all skills from the module.

---

## Scenario

You are hired as the technical writer for a startup building an **AI-powered project management platform**.

Your task:

Design the entire documentation system.

---

## Required Components

Students must produce:

### Documentation Architecture

```id="aap3wj"
Product Overview
Getting Started
User Guides
Developer Documentation
API Reference
Integration Guides
Troubleshooting
Release Notes
```

---

### Topic-Based Content Model

Concept topics.

Task topics.

Reference topics.

---

### User-Journey Documentation

Documentation for:

* onboarding
* daily usage
* troubleshooting
* advanced workflows

---

### Documentation Repository

Git-based documentation system.

---

## Final Deliverables

Students must submit:

* documentation architecture blueprint
* documentation repository
* topic-based documentation model
* user-journey documentation map

---
