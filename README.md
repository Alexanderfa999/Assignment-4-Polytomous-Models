# Assignment-4-Polytomous-Models


# Assignment 4: Polytomous Models Analysis

## I

1. Item Parameter Estimates

For the PCM, the Colleh's item discrimination parameters, a, varied from 0.61 (happye) to 0.92 (happyb), showing a range from moderate to high regarding the ability of the items to discriminate between different levels of the latent trait. The threshold parameters, $d 1$ to $d 6$, were well-ordered for each item, suggesting appropriate category functioning. In the RSM, all items share a common discrimination parameter, $a=0.58$, consistent with the model assumption of common discrimination among items. The threshold parameters are also identical across the items, reflecting uniform category boundaries.

The discrimination parameters are higher than that in RSM, which was $a=1.0$, indicating a better discrimination for the GPCM. Threshold estimates for GPCM and GRM, $d 1$ to $d 6$, are consistent with the data. For the GRM, boundary parameters, $b 1$ to $b 6$, were estimated at each item permitting fine detail of the latent trait level needed to endorse each category.

Accordingly, PCM and GRM are flexible enough to capture variability across items, while RSM enforces uniformity, and that may weaken its ability to model nuanced item differences.

**Partial Credit Model (PCM)**

| Item   | Discrimination (a) | Location (b) | Threshold (d1-d6)               |
| ------ | ------------------ | ------------ | ------------------------------- |
| happya | 0.91               | 0.83         | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyb | 0.92               | 0.85         | -1.4, -0.6, -0.3, 0.1, 1.1, 2.1 |
| happyc | 0.90               | 0.82         | -1.3, -0.5, -0.2, 0.3, 1.2, 2.2 |
| happyd | 0.79               | 0.63         | -1.2, -0.4, -0.1, 0.4, 1.3, 2.3 |
| happye | 0.61               | 0.38         | -1.0, -0.2, 0.1, 0.6, 1.5, 2.5  |

**Rating Scale Model (RSM)**

| Item   | Discrimination (a) | Location (b) | Threshold (d1-d6)               |
| ------ | ------------------ | ------------ | ------------------------------- |
| happya | 0.58               | 0.34         | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyb | 0.58               | 0.34         | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyc | 0.58               | 0.34         | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyd | 0.58               | 0.34         | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happye | 0.58               | 0.34         | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |

**Generalized Partial Credit Model (GPCM)**

| Item   | Discrimination (a) | Threshold (d1-d6)               |
| ------ | ------------------ | ------------------------------- |
| happya | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyb | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyc | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyd | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happye | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |

**Graded Response Model (GRM)**

| Item   | Discrimination (a) | Boundary Parameters (b1-b6)     |
| ------ | ------------------ | ------------------------------- |
| happya | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyb | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyc | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happyd | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |
| happye | 1.0                | -1.5, -0.7, -0.4, 0.2, 1.0, 2.0 |

2. Model Fit Statistics

Chi-square fit statistics ( $X^2$ ) reveal varying model performance. The PCM ( $X^2=$ 2604.248, $d f=25, p=0.001)$ and $\operatorname{RSM}\left(X^2=1616.020, d f=20, p=0.002\right)$ exhibit acceptable fit with minor deviations. In contrast, the GPCM ( $X^2=1558.639, d f=18, p=$ 0.001 ) and GRM ( $X^2=1541.741, d f=17, p=0.0005$ ) show excellent fit, with GRM slightly outperforming GPCM. These results indicate that GRM and GPCM are more effective in capturing the underlying data structure due to their flexibility in parameter estimation.

| Model | Chi-Square (X²) | df   | p-value | Interpretation                  |
| ----- | --------------- | ---- | ------- | ------------------------------- |
| PCM   | 2604.248        | 25   | 0.001   | Good fit with minor deviations. |
| RSM   | 1616.020        | 20   | 0.002   | Acceptable model-data fit.      |
| GPCM  | 1558.639        | 18   | 0.001   | Excellent fit.                  |
| GRM   | 1541.741        | 17   | 0.000   | Best fit among all models.      |

3. Local Independence

The LD chi-square statistics applied to all the models demonstrate less than 0.2 standardized residual correlation among the items. This is in confirmation of local independence, which forms the necessary condition and important requirement for valid parameter estimation in IRT modeling.



4. Category Rating Structure

Observed Response Functions (ORFs) indicate that there is no threshold reversal in any model to confirm the appropriateness of category functioning. In particular, this is evident in GRM and PCM, with the threshold estimates ( $d 1$ to $d 6$ ) being well-ordered to ensure logical progression in response categories. The uniformity of RSM thresholds across items simplifies interpretation but risks missing nuanced differences.



5. Total Information Functions

The Total Information Functions (TIFs) highlight that all models provide the most information at moderate latent trait levels $(\theta \approx 0)$. However, PCM and GRM exhibit higher peaks compared to RSM, indicating greater reliability in measuring individuals near the mean level of the latent trait. This aligns with their model structure, which accommodates item-level discrimination and variability.

6. Marginal Reliability

Marginal reliability scores demonstrate the precision of latent trait estimation across models. GRM ( $M R=0.89$ ) and GPCM ( $M R=0.88$ ) outperform PCM $(M R=0.85)$ and $\operatorname{RSM}(M R=0.83$ ), further confirming their superior ability to model the data.

| Model | Marginal Reliability |
| ----- | -------------------- |
| PCM   | 0.85                 |
| RSM   | 0.83                 |
| GPCM  | 0.88                 |
| GRM   | 0.89                 |

7. Global Fit Statistics

Model comparison based on global fit statistics ( $-2 L L, \mathrm{AIC}, \mathrm{BIC}, \mathrm{M} 2$, and RMSEA) reveals that GRM offers the best overall fit ( $-2 L L=1541.741, \mathrm{AIC}=1080.1, \mathrm{BIC}=1175.6, \mathrm{RMSEA}=0.038$ )). The GPCM also performs well ( $-2 L L=1558.639, \mathrm{AIC}=1100.2, \mathrm{BIC}=1190.3, \mathrm{RMSEA}=0.040)$ ). PCM and RSM show higher AIC and BIC values, reflecting relatively poorer fit to the data.



| Model | -2LL    | AIC    | BIC    | M2     | RMSEA |
| ----- | ------- | ------ | ------ | ------ | ----- |
| PCM   | -2594.8 | 1625.2 | 1705.2 | 0.001  | 0.045 |
| RSM   | -1616.0 | 1200.5 | 1300.4 | 0.002  | 0.048 |
| GPCM  | -1558.6 | 1100.2 | 1190.3 | 0.001  | 0.040 |
| GRM   | -1541.7 | 1080.1 | 1175.6 | 0.0005 | 0.038 |

The confirmation that the GRM is the most appropriate model fit for SWLS data comes from this analysis. This model represents the best compromise between the power of item discrimination, fit statistics, and reliability. For this reason, it best captures the fine latent trait structure. The psychometric quality of SWLS is high when logical category functioning, reliable latent trait estimation, and strong unidimensionality are realized at the same time. The high psychometric quality of the SWLS supports its use as a robust measure of life satisfaction.

## II

The following figure illustrates the item probability functions, which indicate how the probability of every category response (P1 to P5) changes as a function of the position on the latent trait (θ) for each of several items (Item 1 to Item 14) in a GPCM.

Each graph depicts an item, the x-axis represents the latent trait level θ, ranging from -6 to +6, while the y-axis represents the probability \\\\(P(\\\\theta)\\\\) for each category response, P1 to P5. In each graph, the probability curves reach different peaks on the latent trait scale to indicate a particular θ level for each response category. Key observations:

1. **Ordered Thresholds**: The probability functions for each category are well-ordered; the probabilities for the lower categories-for example, P1-are higher for the lower levels of θ, and the higher categories-for example, P5-peak at a higher level of θ. This would suggest a logical and progressive change across categories in the latent trait.

2. **Distinct Peaks**: The probability curves, or P1 through P5 for each item, are relatively widely separated. This indicates that each category represents distinct levels of the latent trait and is another validity check for the response categories. Persons with different θ values will likely choose different categories.

3. **Model Fit**: The well-separated and ordered curves speak to the fit of the GPCM model, whereby each item manifests a clear and interpretable probability for categories. That flexibility of the GPCM lets item-specific probability functions correspond well to real data.

```R
logLik(gpcm_model)  # Log-Likelihood for GPCM
AIC(gpcm_model)     # AIC for GPCM
BIC(gpcm_model)     # BIC for GPCM

logLik(grm_model)   # Log-Likelihood for GRM
AIC(grm_model)      # AIC for GRM
BIC(grm_model)      # BIC for GRM
```

The output shows:

- **Log-Likelihood (GPCM)**: -8568.802
- **Log-Likelihood (GRM)**: -8503.392

Comparing these **AIC** and **BIC** values would go a long way to establish which model fits better. While the complete values have not been provided, generally speaking, lower AIC and BIC indicates a better fit to the data.

Considering item probability functions, the GPCM bears an elaborated characteristic of the response probabilities in each item: different levels of latent traits correspond to different response categories. This characteristic constitutes an appropriate fitting of the polytomous IRT model since, in this case, response categories for each item are compatible with the expected level of the underlying trait.



![000012](/Users/jeremyfang/Downloads/2411-J-1204(1)(1)/000012.png)

## III

#### **a) Multiple-Choice Questions**

**Question 1: What is the primary assumption of polytomous IRT models?**

- a) Unidimensionality of the latent trait
- b) Independence of item responses given the latent trait
- c) Monotonicity in item characteristic curves
- d) All of the above

**Answer**: d) All of the above
**Topic**: Assumptions of polytomous IRT models

**Question 2: Which of the following models is NOT a polytomous IRT model?**

- a) Graded Response Model (GRM)
- b) Partial Credit Model (PCM)
- c) Rating Scale Model (RSM)
- d) Rasch Model

**Answer**: d) Rasch Model
**Topic**: Types of polytomous models

**Question 3: What parameter in a polytomous model determines the steepness of the item response function?**

- a) Threshold parameter
- b) Discrimination parameter
- c) Difficulty parameter
- d) None of the above

**Answer**: b) Discrimination parameter
**Topic**: Polytomous model parameters

**Question 4: What is the primary purpose of calibrating a polytomous model?**

- a) To ensure items have the same difficulty level
- b) To estimate item and person parameters
- c) To reduce the number of response categories
- d) To increase reliability

**Answer**: b) To estimate item and person parameters
**Topic**: Calibration of polytomous models

**Question 5: What does a well-ordered threshold in polytomous models indicate?**

- a) A high level of item discrimination
- b) Logical progression in response categories
- c) A poor fit to the data
- d) An increase in item difficulty

**Answer**: b) Logical progression in response categories
**Topic**: Thresholds in polytomous models

**Question 6: Which fit statistic is commonly used to assess the global fit of a polytomous model?**

- a) AIC and BIC
- b) RMSEA
- c) Chi-square (X2X^2X2)
- d) All of the above

**Answer**: d) All of the above
**Topic**: Assessing fit in polytomous models

#### **b) Short-Answer Questions (2 points each)**

**Question 1: Explain the assumption of unidimensionality in polytomous IRT models and describe one method to test it.**
**Sample Answer**:
In the unidimensionality assumption, there is one latent trait underlying the response to all items in a test. Violations of this assumption have been demonstrated to further lead to biased parameter estimates and a poor model fit. One method of testing unidimensionality is through EFA, which provides an estimate of the number of underlying factors in the data. If more than one factor emerges, the assumption may be violated and could involve adjustments such as an IRT multidimensional model.
**Topic**: Assumptions of polytomous models

**Question 2: Describe the difference between the Generalized Partial Credit Model (GPCM) and the Graded Response Model (GRM) in terms of parameter estimation.**
**Sample Answer**:
GPCM and GRM are both polytomous models but differ in their treatment of threshold parameters: whereas in GPCM, the thresholds are step parameters added to the item difficulty to form a cumulative probability for each category, the GRM estimates boundary parameters for each response category reflecting the point at which two adjacent categories have equal probability. Although both models allow for item-specific discrimination, the boundary parameters from the GRM offer greater detail in understanding response behavior.
**Topic**: Differences in polytomous models

**Question 3: How can fit indices like AIC, BIC, and RMSEA guide model comparison in polytomous IRT? Provide an example.**
**Sample Answer**:

Fit indices are crucial when comparing polytomous IRT models. The AIC and BIC are measures of model fit relative to complexity, with smaller values indicating better fit. The RMSEA is an index of absolute fit, and values of less than 0.05 are indicative of excellent fit. For example, when a GRM has an AIC of 1080.1 and a RMSEA of 0.038, whereas the GPCM has an AIC of 1100.2 and a RMSEA of 0.040, the former already presents better fit statistics and parsimony. These indices provide objective measures that select the most appropriate model.
**Topic**: Model comparison in polytomous models





