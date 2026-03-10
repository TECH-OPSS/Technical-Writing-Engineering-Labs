# Practical Sessions — Module 3: Information Architecture & Content Planning

## **Session 1 — Documentation System Audit & Mapping**

**Objective:** Evaluate an existing documentation ecosystem and design a unified architecture.

**Scenario:** A SaaS company has fragmented documentation across GitHub, Notion, Google Docs, and internal wikis. Users and support teams struggle to find information.

**Tasks:**

1. **Inventory All Documentation**

   * Use a spreadsheet template: [GitHub README template](https://github.com/othneildrew/Best-README-Template)
   * Columns: Source, Owner, Audience, Status, Last Updated, Topics

2. **Analyze Structural Problems**

   * Identify duplication, outdated info, navigation issues, audience mismatch

3. **Visualize Current Architecture**

   * Use draw.io or Miro to map existing documentation

4. **Redesign Unified Architecture**

   * Apply modular and topic-based principles
   * Produce TOC draft, sidebar navigation, role-specific sections

**Deliverables:**

* Documentation Inventory Spreadsheet
* Diagram of current and proposed IA
* Audit report with actionable recommendations

---

## **Session 2 — Building a Product Documentation Architecture**

**Objective:** Design a full documentation system for a product using IA principles.

**Scenario:** A cloud-based collaboration platform with multiple user roles: Developers, Admins, End Users.

**Tasks:**

1. **Define Roles and Goals**

   * Map each role’s documentation needs: onboarding, task execution, troubleshooting

2. **Create a Modular Documentation Structure**

   * Sections: Product Overview, Getting Started, User Guides, Admin Guides, Developer Docs, API Reference, Release Notes

3. **Classify Topics**

   * Concept: “What is a Workspace?”
   * Task: “Create a Workspace”
   * Reference: “API Endpoints for Webhooks”

4. **Design Navigation**

   * Sidebar menus, breadcrumbs, anchor links, role-based TOC

**Practical Resources:**

* MkDocs Material for repository structure: [https://squidfunk.github.io/mkdocs-material/](https://squidfunk.github.io/mkdocs-material/)
* GitHub docs templates: [https://github.com/othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template)

**Deliverables:**

* Documentation architecture blueprint
* TOC and navigation design
* Sample topic-based documents

---

## **Session 3 — API & Developer Documentation**

**Objective:** Create structured API documentation and integration guides.

**Scenario:** Payment processing API to be integrated by developers in Node.js, Python, and Java.

**Tasks:**

1. **List API Components**

   * Overview, authentication, endpoints, errors, SDKs

2. **Document Endpoints**

   * Include parameters, request/response examples, and error handling

3. **Build Integration Guides**

   * Step-by-step tutorials for each language

4. **Add Troubleshooting Section**

   * Common errors, solutions, FAQs

**Practical Resources:**

* Swagger/OpenAPI: [https://swagger.io/tools/open-source/](https://swagger.io/tools/open-source/)
* Postman Collections: [https://www.postman.com/explore](https://www.postman.com/explore)

**Deliverables:**

* Fully documented API reference
* Language-specific integration guides
* Troubleshooting section

---

## **Session 4 — User-Journey Documentation Mapping**

**Objective:** Map documentation to a user journey and optimize for usability.

**Scenario:** Developer onboarding for an internal SaaS tool.

**Tasks:**

1. **Map Developer Journey**

   * Stages: Account setup → Environment setup → Explore codebase → Run app → Submit PR → Deployment

2. **Assign Documentation per Stage**

   * Installation guides, config docs, architecture overviews, workflow guides

3. **Create Sequential Flow**

   * Ordered guides reflecting the journey
   * Link each stage to modular topics

**Practical Resources:**

* User journey mapping templates: [https://miro.com/templates/user-journey-map/](https://miro.com/templates/user-journey-map/)
* Markdown-based documentation for each step

**Deliverables:**

* Developer onboarding documentation system
* Flowchart of journey-based documentation

---

## **Session 5 — Docs-as-Code Repository Setup**

**Objective:** Build a version-controlled documentation repository with modular structure.

**Scenario:** All documentation must live in a Git repository, ready for continuous deployment.

**Tasks:**

1. **Create Repository Structure**

   ```
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

2. **Write Topic-Based Documentation**

   * Concept, task, reference topics per earlier sessions

3. **Integrate with a Static Site Generator**

   * MkDocs Material, Docusaurus, or Sphinx

**Practical Resources:**

* MkDocs: [https://www.mkdocs.org](https://www.mkdocs.org)
* Docusaurus: [https://docusaurus.io/](https://docusaurus.io/)

**Deliverables:**

* Git-hosted documentation repository
* Searchable, modular, and navigable site

---

## **Capstone Session — Build an End-to-End Documentation System**

**Objective:** Combine all previous sessions into a single, shareable, production-ready documentation system.

**Scenario:** Startup building an **AI-powered project management platform**.

**Tasks:**

1. **Design Complete Documentation Architecture**

   * Product Overview, User Guides, Admin Guides, Developer Docs, API Reference, Integration Guides, Release Notes

2. **Implement Modular Topic-Based Content**

   * Concept, Task, Reference topics

3. **Map Content to User Journeys**

   * Onboarding → Daily Use → Advanced Features → Troubleshooting

4. **Set Up Docs-as-Code Repository**

   * Git version control
   * CI/CD pipeline for automatic deployment (Netlify, GitHub Pages)

**Deliverables:**

* Full documentation blueprint
* Git repository with structured documentation
* User-journey mapped guides
* Shareable site ready for internal or external use
---

