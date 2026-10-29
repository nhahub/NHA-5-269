# 3. Requirements Gathering

## 3.1 Stakeholder Analysis
* **HR Directors / CHRO:** Require high-level executive summaries of turnover rates, financial impact of attrition, and quarterly retention trends.
* **HR Generalists & Recruiters:** Need individual employee risk scores and automated insights to intervene proactively before resignations occur.
* **Department Managers:** Need visibility into team satisfaction levels, overtime hours, and salary distribution to maintain team stability.

## 3.2 User Stories & Use Cases
* **User Story 1:** As an HR Manager, I want to filter turnover rates by department and job role so that I can target high-turnover areas.
* **User Story 2:** As an HR Business Partner, I want to input employee performance and compensation parameters to get a flight-risk probability score.

## 3.3 Functional Requirements
* **FR-01:** The system must ingest and clean the historical IBM HR CSV dataset (1,470 records).
* **FR-02:** The system must compute turnover percentages across demographics, tenure, and compensation.
* **FR-03:** The system must generate predictive probability scores (0 to 100% risk) for employee attrition using Machine Learning models.
* **FR-04:** The system must provide interactive visualization widgets (slicers for Department, Gender, Job Role) via Power BI.

## 3.4 Non-Functional Requirements
* **Performance:** Processing and filtering dataset rows within 2 seconds.
* **Security & Privacy:** Data anonymization (stripping personal identifying attributes).
* **Usability:** Intuitive visual design and clean layout following standard Power BI dashboard UI/UX guidelines.
