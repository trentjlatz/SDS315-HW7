# HW7: Arm Folding & GOTV Campaign Analysis

This project uses real-world data to estimate causal effects in two settings:

1. **Arm Folding and Gender:**  
   A study of whether men and women differ in the way they fold their arms (left arm on top vs. right), using confidence intervals and hypothesis testing.

2. **GOTV (Get Out the Vote) Campaign:**  
   An analysis of whether receiving a political call increases the likelihood of voting in the 1998 U.S. election. This includes:
   - Observational comparison
   - Identification of confounders
   - Matching to estimate a causal effect

## Tools & Techniques
- R (`dplyr`, `MatchIt`, `ggplot2`, `mosaic`)
- Confidence intervals
- Hypothesis testing
- Matching for causal inference (5:1 nearest neighbor)

## Key Finding
After adjusting for prior voting, age, and party affiliation using matching, we find a statistically significant positive effect of receiving a GOTV call on voting in 1998.

## Run it yourself
Clone the repo, open `HW7.Rmd`, and knit to PDF or HTML.

