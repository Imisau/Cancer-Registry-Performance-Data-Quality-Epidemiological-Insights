# Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights

![](https://github.com/Imisau/Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights/blob/main/Screenshot%20(83).png)

# Project Overview
This project presents a registry-grade analytical review of a simulated population-based cancer registry using Power BI and supporting statistical analysis in Python. The objective is to demonstrate registry performance monitoring, data quality auditing, and epidemiological insight generation consistent with international cancer registry standards (IARC/WHO).

# Tools & Skills Demonstrated
-	Power BI,(DAX, data modeling, visual storytelling), SQL, Python.
-	Data Quality Framework Design
-	Epidemiological reasoning
-	Correlation & regression interpretation
-	Registry performance reporting

# Dataset Summary
-	Records: 10,000 cancer cases
-	Geography: Multi state registry simulation (Nigeria)
-	Unit of analysis: Individual cancer case (transaction-level)
-	Core domains: Demographics, diagnosis, staging, treatment initiation, and quality assurance flags

# Key Variables
-	Demographics: Age, Sex, State
-	Clinical: Cancer Site, Stage at Diagnosis, Basis of Diagnosis
-	Registry Operations: Facility Level, Abstracted By, QA Review Status
-	Data Quality Flags: Completeness, Plausibility, Consistency, Backlog, Record Validity

# Power BI Report – Page-by-Page Analytical Readout

# Registry Performance Overview
![](https://github.com/Imisau/Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights/blob/main/RegData1.png)

## Key Visuals & Insights
-	Total Registered Cases: 10,000
-	Treatment Initiation Rate: High (>85%), indicating reasonable linkage between diagnosis and care
-	QA Review Coverage: Reveals operational throughput of registry quality processes

## Insight:
Despite high case volumes, QA review does not scale linearly with registrations, suggesting structural review bottlenecks rather than data entry failure.

# Data Completeness Assessment
![](https://github.com/Imisau/Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights/blob/main/RegData2.png)

**Purpose:** Measure conformity with minimum dataset standards.

### Statistical Findings:
-	Stage completeness shows the highest incompleteness burden
-	Demographic fields (Age, Sex) exceed 95% completeness, aligning with registry best practice

**Operational Insight:** Stage incompleteness reflects clinical documentation gaps, not abstraction failure—indicating a need for upstream clinician engagement.

# Data Validity & Plausibility
![](https://github.com/Imisau/Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights/blob/main/RegData3.png)

**Purpose:** Identify biologically and temporally implausible records.

### Key Results
-	Age plausibility violations are rare (<1%)
-	Sex–Cancer site inconsistencies are minimal, confirming strong rule-based validation

**Interpretation:**
High plausibility compliance confirms that automated validation rules are effective and abstraction training is adequate.

# QA Backlog & Operational Risk
![](https://github.com/Imisau/Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights/blob/main/RegData4.png)

**Purpose:** Highlight latent data quality risk.

### Findings
-	QA Backlog Flag prevalence indicates pending review workload
-	Weak correlation between backlog and record invalidity (r = −0.51)

**Statistical Insight:**
The negative correlation suggests backlog accumulation is process driven, not quality driven—cases are waiting, not failing.

# Epidemiological Profile
![](https://github.com/Imisau/Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights/blob/main/RegData5.png)

**Purpose:** Generate public health relevant insights.

### Observed Patterns
-	Late-stage (III–IV) diagnoses dominate case mix
-	Breast and lung cancers are leading sites

**Public Health Interpretation:**
The stage distribution signals systemic delays in diagnosis, supporting the need for early detection programs rather than registry-side intervention alone.

# Summarry
- Data incompleteness is structural and upstream, not explained by QA delays or validity flags. This supports a systems level intervention rather than micro level data cleaning.

**Registry Maturity Assessment**

          Dimension                   Assessment                 
          
          Case Capture                Strong
          Demographic Quality         Very Strong
          Clinical Depth (Stage)      Weak
          QA Governance               Moderate
          Epidemiological Usefulness  High

# Key Recommendations
1.	Strengthen clinical documentation workflows for staging
2.	Introduce risk based QA prioritization rather than volume-based review
3.	Use backlog metrics as operational KPIs, not data quality KPIs
4.	Leverage registry outputs for early detection policy advocacy

Interact with dataset [Here](https://github.com/Imisau/Cancer-Registry-Performance-Data-Quality-Epidemiological-Insights/blob/main/registry_data_quality_audit_dataset_10000.csv) 

