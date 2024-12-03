# Introduction
This is a repository which contains a qmd and csv for a diabetes study. The goal of the repository is to store that data and the qmd code in a way that it is accessible for viewers.

## Implementation
In this analysis, the relationship between glucose and insulin levels and diabetes risk was analyzed using a dataset of health metrics. Firstly, the data was loaaded and glucose and insulin were categorized into quartiles using ntile() from dplyr. Then exploratory data analysis (EDA) was copnducted and the data was visualized using boxplots, density plots, scatter plots, and a combined diabetes rate plot. Challenges included ensuring proper transformations, such as applying the log() function to insulin to handle outliers effectively.

### Conclusion
The analysis showed that both glucose and insulin levels correlate with diabetes risk. Higher levels of both biomarkers were linked to a higher likelihood of diabetes, with glucose showing a more direct impact. The diabetes rate increased in higher quartiles of both glucose and insulin, indicating their combined influence on diabetes risk.

#### Contact
For any questions, please contact at the following:
Email: rnl148@psu.edu
