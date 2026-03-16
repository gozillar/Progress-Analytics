# Student Attainment & Progress Analytics (Multi-School Assessment Project)
This project analyzes student attainment and academic progress across a cluster of six schools using both internal formative assessments and external standardized tests. The goal of the analysis was to monitor whether students were making the expected academic progress throughout the school year, identify learning gaps early, and provide school leaders with actionable insights to guide instructional interventions.

The analysis was implemented in Power BI and integrates multiple assessment data sources to track baseline performance, expected progress trajectories, and actual student growth over time.

Although the context is education, the analytical methods used here are applicable to performance monitoring, KPI tracking, and cohort analysis in many industries such as HR analytics, product analytics, customer success, and operations.

## Problem Statement
School leaders and instructional teams needed a reliable way to answer several critical questions:

* Are students progressing at the expected rate during the school year?
* Which students or cohorts are falling behind expected progress benchmarks?
* Are improvements seen in internal classroom assessments reflected in standardized tests?
* Which schools, classes, or grade levels require targeted academic intervention?
* How well do baseline assessments predict future performance?

Without a centralized analytics solution, these insights were difficult to obtain quickly across multiple schools and assessment systems.

## Key Business Questions

The dashboard and analysis were designed to answer the following core questions.

1. Baseline Performance

  * What is the starting academic level of students at the beginning of the school year?
  * How does baseline performance vary by:
      * School
      * Grade level
      * Subject area
      * Assessment type

2. Expected vs Actual Progress
  * Are students meeting the expected growth projections?
  * How does actual progress compare to benchmark progress targets?

3. Cohort Progress Tracking
  * Which student cohorts are improving, stagnating, or declining?
  * Are there consistent performance trends within:
     * Schools
     * Grades
     * Subject areas

4. Early Identification of Risk
  * Which students are not on track to meet expected progress benchmarks?
  * How early in the year can risk be detected?

5. Assessment Alignment
  * Do improvements in internal formative assessments translate to improvements in external standardized assessments?

## Analytical Framework

The analysis follows a baseline → progress → evaluation framework.

1. Baseline Measurement

Students take standardized tests at the start of the school year to establish a performance baseline.

This baseline provides:

* Initial attainment level
* Projected growth targets
* Expected year-end outcomes

2. Progress Monitoring

Throughout the school year, progress is monitored using:

* Internal formative assessments
* Interim standardized assessments

These checkpoints allow educators to determine whether students are:
* On track
* Ahead of expectations
* At risk of falling behind

3. Growth Evaluation

Student progress is evaluated against:

* Expected MAP growth projections
* Internal benchmark expectations

Termly and yearly progress targets

## Key Metrics & Indicators

The dashboard tracks several key performance indicators.

### Attainment Metrics

Measures current academic performance.

Examples:

* Assessment stage level
* MAP RIT score
* Grade-level proficiency

### Growth Metrics

Measures academic progress over time.

Examples:

* Score improvement from baseline
* Growth relative to expected MAP projections
* Progress across internal stage benchmarks

### Progress Status Indicators

Students are categorized based on performance trends:

* Above Expected Progress
* Meeting Expected Progress
* Below Expected Progress

This classification helps identify students who require additional academic support.

## Dashboard Capabilities

The Power BI dashboard enables stakeholders to:

### Performance Monitoring

* Track attainment and progress across schools
* Compare grades and subjects

### Cohort Analysis
* Monitor specific student groups
* Evaluate trends within schools

### Early Intervention
* Identify students falling behind expected progress
* Prioritize targeted academic support

### Cross-Assessment Comparison
* Evaluate alignment between internal and standardized assessments

## Technical Implementation

The project was built using Power BI with a structured data modeling approach.

### Data Preparation

* Cleaning and harmonizing multiple assessment datasets
* Standardizing student identifiers across sources
* Structuring data into relational tables

### Data Modeling

A star schema was used to support efficient reporting:

Fact tables:
* Assessment results
* Progress measurements

Dimension tables:
* Student
* School
* Grade
* Assessment type
* Time period

### Calculations

Custom metrics and KPIs were implemented using DAX, including:

* Growth calculations
* Progress benchmarks
* Performance classification indicators

### Visualization

Interactive dashboards were built to allow users to filter by:

* School
* Grade
* Assessment
* Time period
* Student cohort

## Analytical Insights

Examples of insights generated through this analysis include:

* Identifying schools where literacy progress was slower than projected
* Detecting grade levels where math attainment lagged behind reading
* Identifying students who showed strong classroom progress but weaker standardized performance
* Highlighting cohorts that required early intervention support

## Impact

This analysis enabled school leaders to:

* Monitor academic progress in near real time
* Allocate instructional support more effectively
* Identify struggling students earlier
* Evaluate whether interventions were improving outcomes

By turning raw assessment data into actionable insights, the project helped schools make data-informed decisions to support student achievement.

## Future Improvements

Potential enhancements include:

* Predictive models for identifying at-risk students earlier
* Automated data pipelines for assessment ingestion
* Longitudinal analysis across multiple academic years
* Intervention effectiveness tracking
