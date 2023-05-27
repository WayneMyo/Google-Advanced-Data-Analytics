* Two-sample z-tests are used for comparing two population proportions.
* Applications include comparing defect rates, side effects in medical trials, voter support, etc.
* Example case: Compare employee satisfaction between two offices.
* Steps to conduct a hypothesis test:
  * Step 1: State the null hypothesis and the alternative hypothesis.
    * Null hypothesis: No difference in proportions (e.g., same employee satisfaction).
    * Alternative hypothesis: Difference in proportions (e.g., different employee satisfaction).
  * Step 2: Choose a significance level (e.g., 5%).
  * Step 3: Find the p-value.
  * Step 4: Reject or fail to reject the null hypothesis based on p-value and significance level.
* To calculate the p-value:
  * Calculate the test statistic Z.
    * Z = (p_1 hat - p_2 hat) / sqrt[p_0 hat*(1-p_0 hat)*(1/n_1 + 1/n_2)].
    * p_1 hat and p_2 hat: sample proportions for first and second group.
    * n_1 and n_2: sample sizes for first and second group.
    * p_0 hat: pooled proportion (weighted average of the proportions from your two samples).
  * Find the area under the curve on both tails of the normal distribution corresponding to the z-score, this is your p-value.
* If p-value < significance level, reject the null hypothesis (i.e., there's a statistically significant difference in proportions).
* If p-value >= significance level, fail to reject the null hypothesis (i.e., no statistically significant difference in proportions).
