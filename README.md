# MarkIt BI Project Documentation

## Table of Contents
- [1. Stakeholder Requirements Document](#1-stakeholder-requirements-document)
- [2. Project Requirements Document](#2-project-requirements-document)
- [3. Planning Document](#3-planning-document)
- [4. Questions & Considerations](#4-questions--considerations)

---

## 1. Stakeholder Requirements Document

### Stakeholders
- **Alice Shi**: Vice President of Sales
- **Matías Sosa**: Program Manager

### Team Members
- **Ariana Tirado**: Data Warehousing Specialist
- **Cornelia Vega**: Manager, Data Governance
- **Sam Winters**: Data Analyst

### Key Needs & Requirements
- Dashboard must be **accessible**: large print, text-to-speech alternatives.
- Insights to inform new-product design and platform improvements.
- Review data on:
  - Number of listings posted (daily, quarterly, yearly)
  - Number of sales completed (daily, quarterly, yearly)
  - Number of listings deleted (daily, quarterly, yearly)
  - Buyer search query behavior and its relationship to purchases
- Fields required:
  - Customer ID/username
  - Item category (e.g., clothing, household goods)
  - Date
- Visualizations:
  - Chart: Duration listings are online before completed sale
  - Chart: Number of searches vs. number of sales completed (for buyers)
- Timeline: **4-week completion**
- Roll-out plan:
  - Week 1: Dataset assignment, field/UserID validation
  - Week 2: SQL & ETL development
  - Week 3: Finalize SQL, dashboard design, peer review
  - Week 4: Dashboard development & testing

---

## 2. Project Requirements Document

### Background
MarkIt is a consumer-to-consumer online platform for buying and selling previously-owned items. The BI initiative aims to understand user behaviors to drive platform and product improvements.

### Project Goals
- Understand customer desires and what drives successful sales.
- Analyze platform usage by buyers and sellers:
  - Time spent on site
  - Most visited pages
  - Buyer search patterns
  - Seller listing behaviors
  - Buyer-seller contact methods
- Identify insights from search query data.
- Discover pain points in the sales process.

### Metrics & Data Requirements
- **Metrics**
  - Listings posted/completed/deleted (by day, quarter, year)
  - Listings' time-on-site before sale
  - Number of searches per buyer vs. sales completed
  - Search query breadth and purchase likelihood
- **Fields**
  - Customer ID/username
  - Item category
  - Date
- **Accessibility**
  - Dashboard must support large print and text-to-speech

### Deliverables
- Accessible dashboard with required charts and data fields
- SQL queries and ETL processes to support dashboard
- Documentation for stakeholders and users

---

## 3. Planning Document

### Timeline & Milestones

| Week | Activities & Deliverables                                       |
|------|-----------------------------------------------------------------|
| 1    | Dataset assigned; Validate field and UserID design              |
| 2    | Develop SQL queries and ETL pipelines                           |
| 3    | Finalize SQL; Design dashboard; Peer review of first draft      |
| 4    | Develop and test dashboard; Ensure accessibility requirements   |

### Roles & Responsibilities
- **Program Oversight**: Matías Sosa
- **Sales Insights & Input**: Alice Shi
- **Data Warehousing**: Ariana Tirado
- **Data Quality/Governance**: Cornelia Vega
- **Analytical Support**: Sam Winters

### Risks & Mitigation
- **Data quality issues**: Early involvement of Data Governance
- **Accessibility delays**: Prioritize accessibility in design
- **Tight timeline**: Weekly progress reviews and clear milestone tracking

---

## 4. Questions & Considerations

### Key Questions
- How do buyers and sellers interact with the platform?
- How do search queries relate to sales conversions?
- What insights from user activity and search can improve platform experience?

### Effectiveness of Metrics
- Metrics are relevant for tracking platform activity and user engagement.
- Visualizing listing lifespan and search-to-sale ratios will provide actionable insights for stakeholders.

### Organization & Grouping
- Requirements are grouped by stakeholder needs, data/metrics, and project timeline.
- Similar data points (listing metrics, search insights) are grouped for clarity.

### Next Steps
- Validate initial dataset and field design.
- Confirm dashboard accessibility features with stakeholders.
- Begin SQL and ETL development as per timeline.

---
