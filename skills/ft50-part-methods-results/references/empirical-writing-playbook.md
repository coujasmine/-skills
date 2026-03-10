# Empirical Writing Playbook: Methods, Results & Robustness

> Extracted from AMJ, SMJ, Organization Science, JBR top-tier empirical papers.
> Sources: Wang (JBR 2024), Rhee (AMJ 2024), Eklund & Mannor (AMJ 2021), Tuggle et al. (SMJ 2010), Tuggle et al. (SMJ 2024), Pan et al. (OrgSci 2025).

---

## 1. Methods Section: Structural Blueprint

### 1.1 Canonical Section Order
Top-tier empirical papers follow a remarkably consistent structure:

1. **Design overview** (1–2 sentences linking design to theory)
2. **Sample & data** (sources, period, N, construction process, attrition)
3. **Dependent variable** (operationalization + source + citation)
4. **Independent variable(s)** (operationalization + validation if novel)
5. **Moderating variables** (one paragraph each)
6. **Mediating variables** (one paragraph each, including data challenges)
7. **Control variables** (grouped by level: firm → CEO → board → industry)
8. **Estimation approach** (model choice justification + diagnostics)
9. **Endogeneity strategy** (identification + instrument justification)
10. **Model specification** (formal equation when possible)

### 1.2 Real Sentence Patterns by Subsection

#### Design Overview
- "We empirically test the role of [concept] using longitudinal data from [N] [units] between [year] and [year]." (Rhee AMJ 2024)
- "To test the hypotheses outlined above, the key challenge is to develop an appropriate measure of [construct] that can be applied across a wide range of industries." (Eklund AMJ 2021)
- "To test our theory, we employ [context] as a context of [theoretical construct] and [measure] as a proxy for [outcome]." (Wang JBR 2024)

#### Sample & Data
- "Our sample frame consists of [population] between [year] and [year]. We collected data from multiple sources." (Wang JBR 2024)
- "We analyze our hypotheses using a random sample of [N] S&P 500 companies over the period [year]–[year]." (Eklund AMJ 2021)
- "In total, [N] publicly traded firms' [transcripts/data] were analyzed for this study. We analyzed these for the years [year] through [year]." (Tuggle SMJ 2010)
- "We collected CEO and board data for all S&P 1500 firms from [year] to [year]." (Pan OrgSci 2025)
- "The final sample consists of [N] firm-year observations over the period [year]–[year], which is [N] less than the potential value of [N]; this is due to [reasons for attrition]." (Eklund AMJ 2021)

#### Variable Operationalization
Pattern: Definition → Operationalization → Data source → Citation → Formula (if applicable)

- "Following prior research (e.g., [citation]), we operationalize [construct] as [specific formula]." (Wang JBR 2024)
- "[Construct] was operationalized as [measure], following [citation]." (multiple papers)
- "We calculated our independent variable, [IV], by following the [citation] method for unobtrusive measures, assigning a [unit] an aggregate score based on the following [N] indicators: (1)..., (2)..., (3)..., and (4)..." (Tuggle SMJ 2024)
- "We measure [construct] using [approach]. Standard deviation is a measure of how dispersed data are in relation to its mean. Thus, high standard deviations indicate [interpretation A] and low standard deviations suggest [interpretation B]. For intuitive interpretation, we reverse the score." (Rhee AMJ 2024)

#### Novel Measure Validation (Critical for Text-Based Measures)
AMJ/SMJ papers with novel measures invest heavily in validation:

1. **Expert validation**: "We recruited [N] [experts] who independently rated [N] transcripts. We found a significantly high correlation (r = [value]; p < [value])."
2. **Alternative explanation check**: "We conduct a sentiment analysis... Our results reveal that [keywords] do not significantly deviate from [comparison group]."
3. **Construct vs. personality check**: "I examined whether [measure] reflects personality by checking temporal consistency... I find that [measure] varies during tenure, aligning with [theory] rather than [trait explanation]."
4. **Topic modeling validation**: "We employ topic modeling to rule out the concern that keywords represent a disciplined communication approach rather than genuine attention."

#### Control Variables — Justification Patterns
Best practice: Every control has a theoretical reason, not just "because prior research included it."

- "We include control variables to rule out factors whose effects on [DV] might be confounded with those of our covariates." (Rhee AMJ 2024)
- "Because [theoretical reason], we control for [variable], measured as [operationalization]." (Pan OrgSci 2025)
- "We controlled for [variable] because [reason] (e.g., [citation])." (Tuggle SMJ 2024)
- **Grouping pattern**: Firm controls → CEO controls → Board controls → Industry/environment controls (Tuggle SMJ 2024, Pan OrgSci 2025)

#### Estimation Approach
- "We employed a fixed-effects panel methodology to analyze the data. A Hausman test yielded a statistically significant result, which suggests that the use of fixed effects was more appropriate than a random-effects specification." (Tuggle SMJ 2010)
- "Standard errors are clustered at the firm level to account for non-independence of errors (Petersen, 2009)." (Eklund AMJ 2021)
- "The winsorized dependent variable [DV] is continuous and normally distributed, thus Ordinary Least Squares regression analyses are used." (Eklund AMJ 2021)
- "To test Hypotheses [1, 2, 4], we modeled our data using linear regression with firm and year fixed effects and adjusted robust standard errors." (Tuggle SMJ 2024)
- "To test Hypothesis [3], we conducted a mediation analysis using structural equation modeling with bootstrapping." (Tuggle SMJ 2024)

#### Endogeneity — Justification Patterns
Best practice: Name the specific threat → justify the strategy → explain instrument validity.

- "Endogeneity may potentially bias our results, as there might be other omitted variables that can influence both [IV] and [DV]. To address this issue, we [strategy]." (Wang JBR 2024)
- "[IV] is an endogenous choice, which leaves open the possibility of omitted variable bias." (Eklund AMJ 2021)
- "An endogeneity issue may arise for two reasons. The first is driven by reverse causality... The second is driven by unobserved variables..." (Rhee AMJ 2024)
- "We used the industry average value of [endogenous variable], excluding the focal firm's value, as an instrument, as the industry average indicates an industry trend that will not affect a particular firm but will likely influence [endogenous variable]." (Wang JBR 2024)

---

## 2. Results Section: Reporting Blueprint

### 2.1 Canonical Reporting Order
1. Descriptive statistics & correlation table
2. Multicollinearity diagnostics (VIF)
3. Progressive model presentation (controls → main → interactions → full)
4. Hypothesis-by-hypothesis reporting
5. Substantive interpretation of key findings
6. Interaction plots + simple slope tests (for moderators)
7. Mediation results with confidence intervals

### 2.2 Real Sentence Patterns

#### Descriptive Statistics
- "Table [n] provides descriptive statistics and bivariate correlations among the variables." (Tuggle SMJ 2010)
- "All variables used to construct interaction terms were centered prior to calculating interaction terms." (Tuggle SMJ 2010)
- "To test for the presence of multicollinearity, we followed procedures outlined by [citation]. The largest variance inflation factor was [value], well below the commonly accepted threshold of 10." (Tuggle SMJ 2010)
- "We computed variance inflation factors for all models; these were less than 10 for all regressions, indicating that multicollinearity was not a concern." (Tuggle SMJ 2024)

#### Progressive Model Reporting
- "Table [n] presents the results of our analyses. Models [a] and [b] include only the control variables." (Tuggle SMJ 2010)
- "Models [c]–[d] progressively display the results of the hypotheses tests." (Tuggle SMJ 2010)
- "Model [n] reports our base regression model, containing only those control variables we expected to impact our analyses when predicting [DV]. Model [n+1] adds our independent variable, [IV]." (Tuggle SMJ 2024)

#### Hypothesis Testing — The Gold Standard Pattern
**Pattern: State H → Reference model → Report coefficient → Substantive interpretation → Verdict**

- "Hypothesis [n] proposes that [relationship]. [Model reference] shows that [variable] is [direction] related to [DV] (β = [value], p < [value]). This result indicates that [substantive interpretation]. Therefore, Hypothesis [n] is supported." (Wang JBR 2024)
- "Hypothesis [n] predicted the [positive/negative] direct relationship between [IV] and [DV]. The results suggest a [direction] relationship (coefficient, p < [value]). Thus, Hypothesis [n] is [strongly] supported." (Tuggle SMJ 2024)
- "The interaction term [X × M] in model [n] is [direction] and significant (b = [value], p < [value])." (Pan OrgSci 2025)

#### Interaction Effects — Full Reporting
**Must include: coefficient → plot → simple slope test → interpretation**

- "We plot this result in Figure [n]. As the figure shows, [description of pattern]." (Wang JBR 2024)
- "A simple slope test also supports our hypothesis: the [effect] is stronger when [condition A] (b = [value], p < [value]) than when [condition B] (b = [value], p < [value])." (Pan OrgSci 2025)
- "To further explore the nature of the interaction, we plotted the interaction graph (Figure [n])." (Pan OrgSci 2025)

#### Marginal Effects at Different Levels
- "Table [n] presents the marginal effects of [IV] on [DV] by different levels of [moderator]." (Rhee AMJ 2024)
- "The coefficient of [IV] [increases/decreases] as [moderator] moves from Mean−2SD ([value]) to Mean+2SD ([value])." (Rhee AMJ 2024)

#### Mediation Reporting — Best Practice
- "When controlling for [mediator], the coefficient for [IV] is reduced from [value] to [value], suggesting [mediator] as a partial mediator." (Rhee AMJ 2024)
- "Using [N] bootstrapped samples, we find the direct effect positive and significant (b = [value], SE = [value], p = [value], 95% CI = [lower, upper]). Its indirect effect through [mediator] is also positive and significant (b = [value], SE = [value], p = [value], 95% CI = [lower, upper])." (Rhee AMJ 2024)
- "We adopted the Monte Carlo method for assessing mediation approach. Using [N] replications, the indirect effect is [value] and the bias-corrected 95% confidence interval ([lower]; [upper]) does not include zero, indicating significant mediation." (Pan OrgSci 2025)

#### Control Variable Results
- "Of the control variables, the results show that [variable] significantly predicts [DV] (β = [value], p < [value])." (Wang JBR 2024)
- "The other control variables show no statistically significant effect on [DV]." (Tuggle SMJ 2010)

#### Practical Significance Translation
- "These results demonstrate that compared to a CEO with a [IV] score of 1 SD below the mean, a CEO with a score of 1 SD above the mean will experience a [X]% greater [outcome]." (Tuggle SMJ 2024)
- "Translating into practical implications, one standard deviation increase in [IV] is associated with a $[N] million [increase/decrease] in [outcome]." (Pan OrgSci 2025)

---

## 3. Robustness Analysis: Complete Toolkit

### 3.1 Dimension Coverage Matrix
Top-tier papers typically cover 3–7 of the following dimensions:

| Dimension | Frequency | Priority |
|-----------|-----------|----------|
| Endogeneity correction | Nearly universal | Must-have |
| Alternative measures | Very common | Must-have |
| Alternative model specs | Very common | Must-have |
| Reverse causality test | Common | Strongly recommended |
| Falsification test | AMJ-level papers | Recommended |
| Subsample / boundary | Common | Recommended |
| Omitted variable bias (ITCV) | Growing trend | Recommended |
| Construct validity tests | For novel measures | Context-dependent |

### 3.2 Real Sentence Patterns by Dimension

#### Endogeneity Correction Results
- "To address potential endogeneity, we [strategy]. The results, summarized in [Model/Table], were consistent with the original ones." (Wang JBR 2024)
- "Our conclusions remain unchanged after employing [strategy]." (multiple papers)
- "We performed two postestimation tests to assess the validity and strength of the instrument variables. First, [F-test for weak instruments]. Next, [Sargan's test for overidentification]." (Pan OrgSci 2025)
- "After conducting 1:1 matching and creating a matched sample, the results remain consistent." (Rhee AMJ 2024)

#### Alternative Measures
- "In the main analysis, we used [measure A]. As an alternative way to measure [construct], we used [measure B]. [Table reference] shows that our results were not sensitive to this alternative measure, confirming the robustness of our findings." (Wang JBR 2024)
- "For robustness, we estimated our models with an alternatively operationalized measure of [construct]. The results did not differ substantively." (Tuggle SMJ 2024)
- "We extend the [time window] and compute the [alternative measure]. Our findings are robust to the use of this alternative measure." (Rhee AMJ 2024)

#### Alternative Model Specifications
- "Although we used fixed effects models as our main analyses, we also leveraged the advantages of random effects models with robust standard errors and GEE models to check the robustness of our findings. The results remain consistent." (Pan OrgSci 2025)
- "As a robustness test, non-lagged values of [IV] are also examined. We obtained results similar to the main results." (Eklund AMJ 2021)
- "We used quantile regression analysis at 25th percentile increments. We found completely consistent results for our hypothesized relationships." (Pan OrgSci 2025)

#### Reverse Causality
- "I conduct an analysis with [IV] in year t as a dependent variable and [DV] in year t−1 as an independent variable. I find no significant relationship — that is, [DV] in previous years does not predict [IV] in subsequent years." (Rhee AMJ 2024)
- "I consider a temporal gap by lagging two years to observe how [IV] in year t−2 is associated with [DV] in year t." (Rhee AMJ 2024)

#### Falsification Tests
- "I explore the impact of [IV] on [unrelated outcome]. I find [IV] has no main effect on [unrelated outcome]. The non-finding strengthens the argument that [IV] benefits [theorized outcome] rather than [alternative mechanism]." (Rhee AMJ 2024)
- "These non-findings confirm that what [mediates/drives] our main results is [theorized mechanism]." (Rhee AMJ 2024)

#### Subsample / Boundary Analyses
- "We explored whether the [effect] changes across [time periods / contexts / subgroups]. Our data indicates that [pattern]." (Pan OrgSci 2025)
- "To ensure our results are not driven by [specific concern], we reran our primary analyses after [adjustment]. We again found completely consistent results." (Pan OrgSci 2025)

#### Omitted Variable Bias (ITCV)
- "We conducted an ITCV test following the steps suggested by Busenbark et al. (2022). The results indicate that an omitted variable would need to overturn the relationship in [X]% of currently significant cases to bias our results. The partial correlations of all included controls are below this threshold, alleviating concerns about omitted variable bias." (Pan OrgSci 2025)

#### Heckman Selection
- "To address potential selection bias, we employed a Heckman two-stage procedure. We first estimated a probit selection model, then computed the inverse Mills ratio and included it in the main model. The results were consistent with the original ones." (Wang JBR 2024)

### 3.3 Robustness Section Closing Patterns
- "Taken together, these robustness checks corroborate our main findings."
- "Across all robustness checks, our core findings remain qualitatively and quantitatively consistent, supporting the theoretical arguments developed in this study."
- "Our conclusions are robust to a wide variety of alternative specifications, measures, and endogeneity correction strategies."

---

## 4. Supplementary / Post-Hoc Analyses Patterns

These go beyond hypothesis testing to deepen theoretical insight:

- "In supplementary analyses, we also provide new insights into [additional implication]." (Eklund AMJ 2021)
- "Although we did not hypothesize [effect], our theoretical model implies it may exist. To test this, we explored [analysis]." (Pan OrgSci 2025)
- "We also explored whether the impact changes as [temporal/contextual dimension] evolves." (Pan OrgSci 2025)
- "In a post-hoc analysis, we find that when [condition], the [effect] on [DV] suffers, highlighting [key insight]." (Eklund AMJ 2021)
- "Interestingly, the [quantity/amount] of [construct] alone does not yield a main effect but only amplifies the benefits of [our focal construct]. This supports the argument that [theoretical implication]." (Rhee AMJ 2024)

---

## 5. Cross-Cutting Writing Principles

### 5.1 Progressive Disclosure
Always build from simple to complex: controls-only → main effects → two-way interactions → three-way interactions → full model.

### 5.2 Substantive-First Reporting
Never lead with statistics. The pattern is always:
- Wrong: "β = 0.119, p < .001"
- Right: "Narcissistic CEOs are associated with more positive risk-taking discussion tone (0.119, p < .001)"

### 5.3 Every Robustness Check Needs a Threat Story
Don't just say "we also checked X." Say "concern Y may bias results → we address it via X → results hold."

### 5.4 Interaction Effects Need Three Components
1. Coefficient and significance
2. Plot/figure
3. Simple slope test or marginal effect table

### 5.5 Mediation Needs Modern Methods
Avoid Baron & Kenny steps. Use:
- Bootstrapping with bias-corrected CIs
- Monte Carlo method for assessing mediation (MCMAM)
- Report both direct and indirect effects with CIs

### 5.6 Claim Calibration
Match language strength to identification strategy:
- OLS/FE without instruments: "is associated with", "is linked to"
- IV/2SLS/RDD/DID: can use limited causal language
- PSM: "the net effect of"
- Never: "proves", "confirms", "establishes causality"
