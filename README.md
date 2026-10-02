# ✈️ Airport Passenger Experience Analysis

## Overview

This project analyzes passenger experiences with airport self-service technologies (SSTs), including self-check-in kiosks, self-bag drop systems, mobile check-in applications, biometric boarding, and automated passport control/e-gates.

The analysis is based on an anonymized survey of **80 airport passengers** and explores passenger satisfaction, technology usage, reliability, perceived time savings, assistance requirements, and future service preferences.

The project was developed from research conducted in the field of **Aviation Management**, with a focus on passenger experience and airport service technology.

---

## 🎯 Objectives

The analysis explores:

- Passenger use of airport self-service technologies
- Ease of use and perceived time savings
- Reliability of self-service systems
- Passenger requirements for human assistance
- Overall passenger satisfaction
- Future preferences for self-service and human-assisted services
- Relationships between passenger experience factors and satisfaction
- Differences in satisfaction across passenger groups
- Passenger suggestions for improving airport SSTs

---

## 📊 Dataset

The analysis uses survey responses from:

**80 airport passengers**

Variables include:

- Age group
- Travel frequency
- Self-service technologies used
- Ease of use
- Perceived time savings
- Reliability
- Assistance needed
- Overall satisfaction
- Future service preference
- Open-ended improvement suggestions

> **Privacy:** The respondent-level dataset is not included in this public repository. The notebook demonstrates the complete analysis workflow while keeping individual survey responses private.

---

## 🛠️ Tools and Methods

The analysis was conducted in **Python** using:

- pandas
- matplotlib
- scipy
- Descriptive statistics
- Frequency and percentage analysis
- Data visualization
- Spearman rank-order correlation
- Kruskal-Wallis tests
- Basic thematic analysis of open-ended responses

Non-parametric statistical methods were used because the primary survey measures were ordinal.

---

## 📈 Key Findings

### Self-Service Technology Usage

**Self-bag drop** was the most commonly reported technology, used by **46 respondents (57.5%)**.

Other commonly reported technologies included:

- Mobile check-in / airline apps — **52.5%**
- Automated passport control / e-gates — **48.8%**
- Self-check-in kiosks — **46.2%**
- Biometric boarding — **43.8%**

Respondents could report using more than one technology, so percentages do not sum to 100%.

### Passenger Satisfaction

Passenger satisfaction was mixed:

- Very satisfied — **23.8%**
- Satisfied — **16.2%**
- Neutral — **20.0%**
- Dissatisfied — **23.8%**
- Very dissatisfied — **16.2%**

### Reliability and Human Assistance

**35.0%** of respondents rated the technologies as **not reliable**, while **31.2%** considered them very reliable.

Human assistance also remained important: **35.0%** of respondents reported that they could not use the technology without help.

### Future Service Preferences

Passenger preferences were divided:

- Not sure — **31.2%**
- Use self-service technologies more — **27.5%**
- Use a mix of self-service and human-assisted services — **26.2%**
- Return to human-assisted service — **15.0%**

---

## 🔬 Statistical Analysis

Spearman rank-order correlations were used to examine relationships between overall satisfaction and:

- Ease of use
- Time saved
- Reliability
- Assistance requirements
- Travel frequency
- Age group

None of these relationships were statistically significant at **p < .05** in this sample.

Kruskal-Wallis tests were also conducted to examine differences in satisfaction across age groups, travel-frequency groups, reliability categories, assistance requirements, perceived time savings, and future service preferences.

No statistically significant group differences were identified at **p < .05**.

These results should be interpreted as exploratory findings rather than evidence that these factors have no relationship with passenger satisfaction.

---

## 💬 Passenger Suggestions

Among the written responses, recurring improvement themes included:

- Improving on-screen instructions
- Ensuring staff are available nearby to assist passengers
- Adding more language options
- Improving biometric-gate speed

Among substantive improvement suggestions, **improving screen instructions was the most frequently reported theme**.

---

## 💡 Interpretation

The results demonstrate a varied passenger experience with airport self-service technologies.

Although SSTs were widely used, this sample did not provide statistically significant evidence that the individual factors examined were associated with overall satisfaction.

The descriptive findings nevertheless highlight practical areas for passenger-service design, particularly:

- Clearer on-screen instructions
- Accessible human assistance
- Multilingual interfaces
- Reliable self-service systems
- Efficient biometric processing

The findings illustrate the importance of considering both **technology performance and human support** when designing passenger-facing airport services.

---

## ⚠️ Limitations

This project is based on a sample of **80 respondents** and should be interpreted as an exploratory analysis rather than as representative evidence for all airport passengers.

The survey measures are self-reported, and the statistical analysis identifies associations rather than causal relationships.

---

## 📁 Repository Contents

`Airport_Passenger_Experience_Analysis.ipynb`  
Complete Python analysis including data preparation, visualizations, descriptive analysis, statistical tests, and interpretation.

`README.md`  
Project overview, methodology, key findings, and limitations.

The respondent-level Excel dataset is intentionally excluded for privacy and research-ethics reasons.

---

## 👤 Author

**Jawwad**  
Aviation Management | Passenger Experience | Airport Technology | Data Analysis
