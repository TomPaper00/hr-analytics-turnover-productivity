# HR Analytics: Uncovering Turnover & Productivity Drivers

##  What's this project about?
I started this data analysis project to answer a common business question: do classic HR investments (like increasing the budget, adding reward systems, or implementing training programs) actually improve employee productivity and reduce turnover? 

Taking the perspective of an HR Consulting firm, I built multiple regression models (Linear and Logistic) to find out. 

**Spoiler alert:** The reality is much messier than a perfect correlation.

> **Note on Data Privacy:** The original dataset (`case2_dataset.csv`) is not included in this repository to comply with academic and data privacy guidelines. However, you can find the full methodology, the R source code, and the final analytical report below.

##  Tech Stack
* **Language:** R
* **Reporting:** Quarto / RMarkdown
* **Libraries:** `dplyr`, `tidyr`, `ggplot2`, `knitr`
* **Models built:** Multiple Linear Regression, Logistic Regression

##  What I found (The "Investment Paradox")
Instead of forcing the data to show a perfect correlation that didn't exist, I focused on what the weak metrics were actually telling us:
1. **Money isn't a magic wand:** Traditional HR levers (Budget, Rewards, Skills Programs) showed a very low ability to explain productivity outcomes ($R^2$ ~0.04). 
2. **Turnover is structural:** The risk of employees leaving was much more closely linked to demographic and structural conditions (like Stress Levels) rather than a lack of financial rewards or training.
3. **The real takeaway:** Investing blindly in standard HR programs doesn't guarantee results. Analytics should be used to spot these inefficiencies, showing management where qualitative diagnostics and cultural changes are needed instead of just throwing budget at the problem.

##  How to navigate this repo
* `INL1_CARTA_TOMMASO.pdf`: Start here. This is the final, formatted report containing the EDA, data visualizations, the modeling strategy, and the final business recommendations.
* `INL1_CARTA_TOMMASO.qmd`: The raw Quarto source code. You can check this out to see my data cleaning process, standardizations (Z-scores), and the actual R code used to build the models and plots.
