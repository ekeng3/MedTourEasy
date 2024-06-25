# MedTourEasy: Analyzing Death Age Difference of Right-Handers with Left-Handers

## Project Overview

This project investigates the potential relationship between handedness (left-handed vs. right-handed) and lifespan. Specifically, it aims to determine whether left-handed individuals tend to die earlier than right-handed individuals, using historical mortality data from the United States.

## Table of Contents

- [Project Overview](#project-overview)
- [About MedTourEasy](#about-medtoureasy)
- [About the Project](#about-the-project)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Implementation](#implementation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)
- [References](#references)

## About MedTourEasy

MedTourEasy is a global healthcare company providing informational resources and analytical solutions to our partner healthcare providers globally. Our mission is to empower patients and healthcare providers with data-driven insights to make informed decisions about global healthcare options.

## About the Project

The project explores age distribution data to investigate the claim that left-handed individuals die earlier than right-handed individuals. Using the Python programming language and Bayesian statistics, the study analyzes the probability of death at various ages for left-handed and right-handed individuals. The analysis focuses on data from two different years (1990 and 2018) to observe any changes over time.

## Objectives

The primary objectives of this project are:
1. To investigate whether the difference in average age at death between left-handed and right-handed individuals can be explained solely by changes in the prevalence of left-handedness over time.
2. To refute or support the claim that left-handed people die earlier than right-handed people.

## Methodology

The project employs a computational approach using publicly available historical death distribution data from the United States. The key steps are:

1. **Data Acquisition and Cleaning**:
   - Load data for left-handed rates and ages for males and females, and historical death distribution data.
   - Identify and remove missing values, and add new columns for birth year and mean left-handedness rates.

2. **Visualization**:
   - Visualize left-handedness rates versus age, and mean left-handedness rates versus birth year.
   - Examine the death distribution data.

3. **Analysis**:
   - Calculate and plot probabilities of being left-handed or right-handed at different ages of death.
   - Calculate and compare the mean age at death for left-handers and right-handers for the years 1990 and 2018.

4. **Reporting and Recommendations**:
   - Generate a comprehensive report documenting the analysis steps, code explanations, and findings.

## Implementation

### Language and Platform Used

- **Language**: Python
- **IDE**: Jupyter Notebook

### Data Collection and Importing

Data collection is systematic, gathering information from various sources to address specific questions, determine outcomes, and forecast future probabilities and patterns. The datasets used include:
- Death distribution data for the United States (1999)
- Left-handedness rates data digitized from a 1992 paper by Gilbert and Wysocki

### Packages Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib**: For data visualization.

## Results

The analysis revealed insights into the relationship between handedness and age at death. The overall left-handedness rates and average ages at death varied over time, influenced by various factors. Detailed results and visualizations are provided in the report.

## Conclusion

The study provides valuable insights into whether handedness impacts lifespan. It contributes to the broader understanding of factors influencing human longevity and sets the stage for future research in this area.

## Recommendations

- Further research should explore additional variables and investigate potential causal relationships.
- Extend the analysis to other populations and time periods to generalize the findings.

## References

1. Gilbert, A. N., & Wysocki, C. J. (1992). Hand Preference and Age in the United States. *Neuropsychologia*, 30(7), 601-608.
2. United States Mortality Data (1999). Retrieved from [data source].

---

This README provides an overview of the project, methodology, results, and recommendations. For a detailed analysis, including code and visualizations, please refer to the full report available in the repository.
