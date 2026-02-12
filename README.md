# Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights

This project demonstrates the ability to move beyond dashboards into decision grade health intelligence, integrating registry operations, data quality science, and epidemiological insight into a single analytical narrative.

Portfolio Project Overview
This project presents a registry-grade analytical review of a simulated population-based cancer registry using Power BI and supporting statistical analysis in Python. The objective is to demonstrate registry performance monitoring, data quality auditing, and epidemiological insight generation consistent with international cancer registry standards (IARC/WHO-aligned thinking).
The analysis is designed as a GitHub-ready portfolio artifact, suitable for:
•	Cancer Registry Officer / Data Analyst roles
•	Health Information Systems & M&E roles
•	Public Health & Epidemiology analytics portfolios
________________________________________
Dataset Summary
•	Records: 10,000 cancer cases
•	Geography: Multi state registry simulation (Nigeria)
•	Unit of analysis: Individual cancer case (transaction-level)
•	Core domains: Demographics, diagnosis, staging, treatment initiation, and quality assurance flags
Key Variables
•	Demographics: Age, Sex, State
•	Clinical: Cancer Site, Stage at Diagnosis, Basis of Diagnosis
•	Registry Operations: Facility Level, Abstracted By, QA Review Status
•	Data Quality Flags: Completeness, Plausibility, Consistency, Backlog, Record Validity
________________________________________
Power BI Report – Page-by-Page Analytical Readout
Page 1: Registry Performance Overview
Purpose: Executive snapshot of registry health.
Key Visuals & Insights
•	Total Registered Cases: 10,000
•	Treatment Initiation Rate: High (>85%), indicating reasonable linkage between diagnosis and care
•	QA Review Coverage: Reveals operational throughput of registry quality processes
Insight:
Despite high case volumes, QA review does not scale linearly with registrations, suggesting structural review bottlenecks rather than data entry failure.
________________________________________
Page 2: Data Completeness Assessment
Purpose: Measure conformity with minimum dataset standards.
Statistical Findings
•	Stage completeness shows the highest incompleteness burden
•	Demographic fields (Age, Sex) exceed 95% completeness, aligning with registry best practice
Operational Insight:
Stage incompleteness reflects clinical documentation gaps, not abstraction failure—indicating a need for upstream clinician engagement.
________________________________________
Page 3: Data Validity & Plausibility
Purpose: Identify biologically and temporally implausible records.
Key Results
•	Age plausibility violations are rare (<1%)
•	Sex–Cancer site inconsistencies are minimal, confirming strong rule-based validation
Interpretation:
High plausibility compliance confirms that automated validation rules are effective and abstraction training is adequate.
________________________________________
Page 4: QA Backlog & Operational Risk
Purpose: Highlight latent data quality risk.
Findings
•	QA Backlog Flag prevalence indicates pending review workload
•	Weak correlation between backlog and record invalidity (r = −0.51)
Statistical Insight:
The negative correlation suggests backlog accumulation is process driven, not quality driven—cases are waiting, not failing.
________________________________________
Page 5: Epidemiological Profile
Purpose: Generate public health relevant insights.
Observed Patterns
•	Late-stage (III–IV) diagnoses dominate case mix
•	Breast and lung cancers are leading sites
Public Health Interpretation:
The stage distribution signals systemic delays in diagnosis, supporting the need for early detection programs rather than registry-side intervention alone.
________________________________________
Regression & Correlation Analysis
Correlation Matrix (Selected Variables)
•	Record Validity vs QA Backlog: r = −0.51 (moderate inverse)
•	Age vs Incompleteness: r ≈ 0.00 (no relationship)
Regression Model
Outcome: Overall Incomplete Flag
Predictors: QA Backlog Flag, Record Validity Flag
Results
•	R² ≈ 0.00
•	No statistically significant predictors (p > 0.05)
Interpretation:
Data incompleteness is structural and upstream, not explained by QA delays or validity flags. This supports a systems level intervention rather than micro level data cleaning.
________________________________________
Registry Maturity Assessment
Dimension	Assessment
Case Capture	Strong
Demographic Quality	Very Strong
Clinical Depth (Stage)	Weak
QA Governance	Moderate
Epidemiological Usefulness	High
________________________________________
Key Recommendations
1.	Strengthen clinical documentation workflows for staging
2.	Introduce risk based QA prioritization rather than volume-based review
3.	Use backlog metrics as operational KPIs, not data quality KPIs
4.	Leverage registry outputs for early detection policy advocacy
________________________________________
Tools & Skills Demonstrated
•	Power BI (DAX, data modeling, visual storytelling)
•	Data Quality Framework Design
•	Epidemiological reasoning
•	Correlation & regression interpretation
•	Registry performance reporting

