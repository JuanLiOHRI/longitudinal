# Predictive analytics (longitudinal cohort, repeated measures)

## Files

Code, data variable sheet, and slides for this presentation. Real patient data is not publically available.

## Contents and resources

### Linear Mixed Models:

1. https://rpubs.com/alecri/review_longitudinal 

2. https://cran.r-project.org/web/views/MixedModels.html 

### Survival analysis:
1. https://stats.oarc.ucla.edu/wp-content/uploads/2025/02/survival_r_full.html

2. https://www.sthda.com/english/wiki/survival-analysis-basics

3. https://www.emilyzabor.com/survival-analysis-in-r.html

4. https://rpkgs.datanovia.com/survminer/

### Cumulative case/dynamic control ROC (!! Inconsistent results, need to discuss)

1. `survivalROC`: https://datascienceplus.com/time-dependent-roc-for-survival-prediction-models-in-r/ 

2. The tidymodels approach for survival analysis:

  - https://www.tidyverse.org/blog/2024/04/tidymodels-survival-analysis/

  - No data splitting: https://www.tidymodels.org/learn/statistics/survival-metrics/

  - With data splitting and workflow: https://www.tidymodels.org/learn/statistics/survival-case-study/

  - `roc_auc_survival`: https://yardstick.tidymodels.org/reference/roc_auc_survival.html 
