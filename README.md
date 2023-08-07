<h2 align="center">
Causal Analysis for Marketing Project
</h2>  

Welcome to the Causal Analysis for Marketing Project repository. In this project, we delve into the realm of causal inference using advanced statistical techniques to uncover the causal relationships between variables within the domain of marketing and customer behavior.

## Project Highlights

**Understanding Causal Analysis**: Causal inference involves identifying whether changes in one variable lead to changes in another. Our focus is to determine the extent of a treatment's impact on a specific outcome while considering other influential factors.

**Applied on Bank Marketing Data**: We leverage a Bank Marketing dataset containing customer information, campaign details, and subscription outcomes. This dataset offers a rich ground for exploring causal effects on customer subscription behaviors.

## Dataset Description
The dataset includes details such as customer age, job, marital status, education, housing and personal loan status, contact information, campaign attributes, and outcome of previous marketing campaigns. With a careful selection of variables, we assess the causal effects of different features on customer subscription decisions.


## Methodology
Our approach involves rigorous preprocessing, outlier removal, and feature engineering to prepare the dataset for causal inference techniques.

1. Encoding Treatment Variable: We create a binary "Contact" variable, indicating if a customer received a significant contact based on the number of contacts performed and contact duration.

2. Treatment Effect Calculation: By comparing subscribers' mean between the treatment (contacted) and control (not contacted) groups, we calculate the treatment effect. Our result indicates the positive impact of being contacted on subscription likelihood.

3. T-Test and Effect Size Analysis: Employing a t-test, we determine the statistical significance of the mean difference. Additionally, Cohen's d-effect size measurement helps quantify the magnitude of the difference between contacted and non-contacted groups.

## Interpretation and Implications
Our findings suggest that being contacted significantly increases the likelihood of subscribing to a service. With a treatment effect of 2.8%, the analysis implies the effectiveness of marketing contacts in driving subscriptions. This conclusion is supported by the t-test's p-value and Cohen's d-effect size.

## Limitations and Considerations
Causal analysis demands careful consideration of confounding variables and assumptions. While our analysis highlights causal effects within this specific dataset, it's important to interpret results within the context of the data and methodology used.

## Further Exploration
To explore the complete analysis process and findings, including visualizations and detailed code, please refer to my [Colab Notebook](https://github.com/shardulchavan/Crash_Course_in_Causality/blob/main/Crash_Course_in_Causality.ipynb) and [Medium article](https://medium.com/@chavan.shardul360/forecasting-climate-change-an-exploratory-time-series-data-analysis-approach-32ccc6ab7421)
