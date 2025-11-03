# Statistical-Book-Case-Study
This project applies core statistical methodologies to analyze a sample dataset of books, focusing on the relationships between their physical attributes. The analysis demonstrates key techniques, including data transformation, assumption testing, and the correct application of parametric and non-parametric hypothesis tests.

# Data Explanation
* Subject: Characteristics of a small sample of books (implied from a library or collection).
* Size: N = 30 books.
* Variables: PAGE (Number of Pages), WEIGHT (Weight in grams), and TYPE (Type of book), which is a categorical variable with three groups: Religious, Story, and Science.
* Initial Finding: Exploratory Data Analysis (EDA) confirmed that the WEIGHT variable was positively skewed, informing the need for non-parametric and transformation techniques.

# Project Files 1
* File Name: A Case Study.sav & A Case Study.spv
* Purpose: Contain the raw data used for all analyses.
* Format: SPSS Data File (Proprietary)
* Accessibility: Require IBM SPSS software.

# Project File 2
* File Name: A Case Study1.pdf
* Purpose: The comprehensive Statistical Report detailing the methodology, results, and conclusions for all objectives.
* Format: PDF (Accessible)
* Accessibility: Easily viewed by all.

# Summary of Key Findings
​The statistical analysis addressed six specific objectives, yielding the following main conclusions:

1.
* Objective: Prediction: Page vs. Weight
* Method Used: Simple Linear Regression (after log transformation of WEIGHT)
* Main: Using the model WEIGHT = e^(4.26 + 0.01{PAGE}), a book weighing 200 grams is predicted to have 103.8 pages.

2.
* Objective: Test: Median Weight vs. 200g
* Method Used: Non-Parametric Test (Wilcoxon Signed-Rank Test)
* Main: The median weight of the books is not significantly different from 200 grams (p=0.894). This confirms the methodological choice due to non-normal data.

3. 
* Objective: Test: Pages by Book Type
* Method Used: One-Way Analysis of Variance (ANOVA)
* Main: There is no statistically significant difference in the average number of pages across the three types of books (Religious, Story, Science) (F=0.540, p=0.589).

4.
* Objective: Test: Mean Pages vs. 100
* Method Used: One-Sample t-test
* Main: Based on the mean of 98.07 pages, the analysis likely found that the average number of pages is not statistically less than 100 pages.
