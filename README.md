 ## README

### Project Title: **Effects of Age, Gender, and Environmental Factors on Marathon Performance**

### Overview:
This project analyzes the impact of age, gender, and various environmental factors (such as temperature, humidity, and solar radiation) on marathon performance. Specifically, it examines how these variables interact to affect marathon finish times and investigates how WBGT (Wet Bulb Globe Temperature) flag categories, which represent different heat risk levels, influence race outcomes.

### Data:
The dataset used in this analysis contains the following key variables:
- **Finish**: Marathon finish time in seconds.
- **Age**: Age of the marathon runner.
- **Sex**: Gender of the runner (M for Male, F for Female).
- **Flag**: WBGT flag category based on heat risk levels (White, Green, Yellow, Red).
- **Environmental Variables**: Includes weather factors such as wet bulb temperature, dry bulb temperature, humidity, wind speed, and solar radiation.

### Objectives:
1. **Examine the effects of increasing age on marathon performance** in both men and women.
2. **Analyze the influence of environmental conditions on marathon performance**, with a focus on how factors such as WBGT and other weather conditions impact runners.
3. **Evaluate the interactions between age, gender, and weather factors** to determine their combined effects on marathon performance.
4. **Investigate whether WBGT flag categories are associated with significant differences in marathon finish times**.

### Methods:
- **Correlation Analysis**: Explored relationships between environmental factors and marathon finish times.
- **Quadratic Polynomial Regression**: Modeled the non-linear relationship between age and marathon finish time, stratified by gender.
- **ANOVA and Tukey’s HSD Test**: Tested for significant differences in marathon finish times across WBGT flag categories and performed pairwise comparisons between flag categories.

### Key Findings:
- Marathon finish times increase steadily with age for both men and women, particularly after age 30.
- Men generally finish marathons faster than women across all age groups.
- Higher wet bulb temperature and humidity are strongly associated with slower marathon finish times.
- ANOVA results showed a significant overall difference in finish times across WBGT flag categories, with Red flag conditions (higher heat risk) leading to slower performances compared to White flag conditions (lower heat risk), though this difference was not statistically significant in the pairwise Tukey HSD test.

### Files:
- **Project1.pdf**: Final report containing detailed analysis, visualizations, and conclusions.
- **final_marathon.csv**: Dataset used for the analysis.
- **R Markdown Files**: Code used to generate plots, perform statistical tests, and conduct the overall analysis.

### How to Run the Code:
1. Ensure that you have R installed with the necessary libraries:
   - `ggplot2`
   - `dplyr`
   - `readr`
   - `car`
2. Load the dataset using `read.csv()` or `readr::read_csv()` into your R environment.
3. Execute the provided R Markdown file (`.Rmd`) to generate plots and analysis results.

### Contact:
For further questions or clarifications, please contact Morgan Cunningham at morgan_cunningham@brown.edu.
