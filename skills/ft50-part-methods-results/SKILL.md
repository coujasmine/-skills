---
name: ft50-part-methods-results
description: 用于评审并润色 Methods、Results 与 Robustness 部分，校验研究设计是否支撑理论命题（测量一致性、层级匹配、因果识别），检查结果解释是否回扣机制，设计完整稳健性方案，并输出 polished 英文改写版本。基于 AMJ/SMJ/OrgSci/JBR 等顶刊实证论文写作范式。
---

# Part: Methods, Results & Robustness Analysis

## 目标
让方法服务理论，结果讲述故事，稳健性体系化消除疑虑。完成诊断后，直接输出符合 FT50 标准的英文改写版本。

---

## Phase 1: 诊断评审

### Methods 检查
1. 样本与理论对象匹配（主体、情境、层级）。
2. 构念测量与定义一致（反映式/形成式区分）。
3. 识别策略处理内生性（FE/IV/匹配/滞后/CFA/DID/RDD 等）。
4. 模型与机制一致（避免只跑净效应，须体现中介/调节链条）。
5. 变量测量是否提供足够的 construct validity 证据。

### Results 检查
1. 结果是否按理论命题顺序报告（base model → main effects → interactions → full model）。
2. 是否先解释实质性发现（substantive finding），再报统计数字。
3. 交互效应是否做了 simple slope test 或 marginal effect 分析。
4. 异质性/边界结果是否真正对应理论边界。
5. 中介分析是否采用了当前推荐方法（bootstrapping、Monte Carlo）。

### Robustness 检查
1. 是否有内生性纠正（至少一种：2SLS/CFA/PSM/Heckman/反向因果检验）。
2. 是否有替代测量检验（核心自变量和因变量各至少一种替代测量）。
3. 是否有替代模型规格检验（FE vs RE、不同滞后期、不同聚类标准误）。
4. 可选加分项：伪造检验（falsification test）、遗漏变量偏差检验（ITCV）、子样本分析。

### 红线
- 结果能显著但无法解释机制：判"统计成立，理论不足"。
- 因果语言但无因果识别策略：判"语言越界"。
- 稳健性仅有一种且未覆盖内生性：判"稳健性不足"。

### 诊断输出模板
- 设计风险清单：
- 结果解释缺口：
- 稳健性体系评估（✓已覆盖 / ✗缺失）：
  - 内生性纠正：
  - 替代测量：
  - 替代模型规格：
  - 反向因果：
  - 子样本/边界：
- 红线检查：通过/不通过 + 原因

---

## Phase 2: 英文润色改写

### 强制规则
1. 最终改写内容必须是英文；不输出中文句子作为正文。
2. **绝对不改变**原始实证结果、变量关系方向、效应符号、统计显著性和核心识别策略。
3. 只改语言表达、结构组织和结果解释的清晰度。
4. 结果报告必须先写实质性发现（substantive finding），再写统计数字。
5. 稳健性分析必须完整撰写，不能仅以一两句话带过。

---

### Methods 专用句式模板

#### A. 研究设计概述（Design Summary）
- `We test our arguments using [design] based on [sample/context].`
- `Our empirical setting is [context], which is appropriate because [theoretical advantage for identification].`
- `We empirically test [theory/model] using longitudinal data from [N] [units] (SIC code [X]) between [start year] and [end year].`
- `To test the hypotheses outlined above, the key challenge is to [methodological challenge], which we address by [approach].`

#### B. 样本与数据（Sample and Data）
- `Our sample frame consists of [population] between [start year] and [end year].`
- `We collected data from multiple sources. First, we obtained [data type] from [database]. Second, we collected [data type] from [database].`
- `The final sample contains [N] firm-year observations relating to [N] unique firms.`
- `We analyze our hypotheses using a [random/stratified/full] sample of [N] [firms/companies] over the period [start]–[end].`
- `We supplement the [primary data] with data from a variety of databases such as [database list].`
- `Events such as mergers, delisting, and missing data resulted in some firms not having complete data, yielding an unbalanced panel of [N] firm-year observations.`

##### 样本选择偏差处理
- `We tested for sample-inclusion bias by comparing the characteristics of the included and excluded firms using the Kolmogorov-Smirnov two-sample test. Across all archival variables, the results showed no statistically significant difference.`
- `To choose firms randomly, we used a random-number generator to assign a random value to each remaining firm, choosing the [N] highest values for inclusion.`

#### C. 因变量（Dependent Variable）
- `We measure the dependent variable, [DV], based on [specific operationalization] using data from [source].`
- `Following prior research (e.g., [citation]), we operationalize [DV] as [specific formula/measure].`

#### D. 自变量（Independent Variable）
- `We calculated our independent variable, [IV], by following the [citation] method for [approach].`
- `[Construct] was operationalized as [measure], following [citation].`
- `We measure [IV] using [specific data/approach], which captures [what the variable reflects].`

##### 文本分析类变量的构建（Text-Based Measures）
- `To develop [measure], we follow the general approach to computer-aided text analysis described by [citation].`
- `We take both deductive and inductive approaches to generate the list of keywords indicating [construct].`
- `To validate the keyword measure, we recruited [N] [experts] who independently rated [N] transcripts and found a significantly high correlation between the keyword-based measures and manual ratings (r = [value]; p < [value]).`
- `We conduct a sentiment analysis to rule out the possibility that [construct] merely reflects [alternative explanation].`

#### E. 调节变量（Moderating Variables）
- `To assess [moderator concept] for testing Hypothesis [n], we employ [operationalization].`
- `[Moderator] was measured dichotomously: firms with [condition] were coded as 1, and firms without as 0.`
- `We specify [moderator] as the linear combination of [component A] and [component B].`

#### F. 中介变量（Mediating Variables）
- `To test [mediation hypothesis], we measure [mediator] as [operationalization].`
- `[Mediator] was collected from [source] and operationalized as [specific measure].`
- `Because collecting [mediator data] in a longitudinal, cross-sectional research design is challenging, we turn to [data source], following recent studies (e.g., [citation]).`

#### G. 控制变量（Control Variables）
- `We include control variables to rule out factors whose effects on [DV] might be confounded with those of our covariates.`
- `We controlled for [variable] because [theoretical reason for inclusion] (e.g., [citation]).`
- `Because [theoretical reason], we control for [variable], measured as [operationalization].`
- `At the firm level, we controlled for firm size ([operationalization]), firm age ([operationalization]), and [other controls].`
- `We also controlled for [CEO/board/industry characteristics] that prior research suggests may affect [DV].`
- `Finally, we included a set of [year/industry] dummies to capture unobservable [time/industry] heterogeneity.`

#### H. 估计方法与内生性处理（Estimation and Endogeneity）
- `To test our hypotheses, we used a [fixed-effect/random-effect/OLS] regression model to capture unobservable [firm/individual] heterogeneities.`
- `A Hausman test yielded a statistically significant result, which suggests that the use of fixed effects was more appropriate than a random-effects specification.`
- `Standard errors are clustered at the [firm/industry] level to account for non-independence of errors (Petersen, 2009).`
- `To reduce the threat of multicollinearity, we mean-centered the key continuous predicting variables. We obtained the variance inflation factors for all variables, and none was above [threshold], indicating that multicollinearity is unlikely to threaten our results.`

##### 内生性纠正方法
- **Control Function Approach (CFA)**:
  - `We followed recent studies (e.g., [citation]) and used a control function approach to test for any endogeneity bias. Like an instrumental variable approach, CFA relies on an instrument that is theoretically unrelated to the dependent variable but significantly predicts the endogenous variable. However, it is more efficient than the traditional IV approach for testing higher-order variables, such as non-linear or interactive effects.`
  - `We used the industry average value of [endogenous variable], excluding the focal firm's value, as an instrument, as the industry average indicates an industry trend that will not affect a particular firm's [DV] but will likely influence [endogenous variable].`

- **Two-Stage Least Squares (2SLS)**:
  - `To mitigate potential endogeneity concerns, we tested the hypothesized relationships using two-stage least squares models.`
  - `In the first stage, we used [instrument variables] to compute the predicted value for [endogenous variable]; in the second stage, we used the predicted value in the regression analyses.`
  - `We performed two postestimation tests: (1) an F-test to rule out weak instruments (F = [value]; p < [value]), and (2) Sargan's χ² test for overidentifying restrictions (χ² = [value], p = [value]), confirming instrument validity.`

- **Propensity Score Matching (PSM)**:
  - `We implement a propensity score matching analysis to identify the net effect of [IV] on [DV] by comparing only nearly identical [units] with high versus low levels of [IV].`
  - `We conduct 1:1 matching without replacement with a caliper radius of [value], ensuring that we only match firms with a propensity score difference less than [value].`

- **Heckman Selection**:
  - `To address potential selection bias, we employed a Heckman two-stage procedure. In the first stage, we estimated a probit selection model. We then computed the inverse Mills ratio and included it in the main model.`

- **反向因果检验**:
  - `To address the possibility of reverse causality, we conduct an analysis with [IV] in year t as a dependent variable and [DV] in year t−1 as an independent variable. We find no significant relationship, suggesting that [DV] in previous years does not predict [IV] in subsequent years.`

---

### Results 专用句式模板

#### A. 描述性统计（Descriptive Statistics）
- `Table [n] provides descriptive statistics and bivariate correlations among the variables.`
- `All variables used to construct interaction terms were centered prior to calculating interaction terms.`
- `To test for the presence of multicollinearity, we followed procedures outlined by [citation]. The largest variance inflation factor was [value], well below the commonly accepted threshold of 10, indicating multicollinearity is not an issue.`

#### B. 主效应报告（Main Effects）—渐进式模型报告
- `Table [n] presents the results of our analyses. Models [a–b] include only the control variables. Models [c–d] progressively display the results of the hypotheses tests.`
- `Model [n] reports our base regression model, containing only control variables. Model [n+1] adds our independent variable, [IV].`
- `Hypothesis [n] proposes that [IV] is [positively/negatively] associated with [DV]. [Model reference] shows that [IV] is [positively/negatively] related to [DV] (β = [value], p < [value]). This result indicates that [substantive interpretation]. Therefore, Hypothesis [n] is supported.`
- `The results suggest a [positive/negative] relationship between [IV] and [DV] ([coefficient value], p < [value]). Thus, Hypothesis [n] is [strongly] supported.`

##### 实质性解释（Substantive Interpretation）
- `These results demonstrate that compared to a [unit] with [IV] of 1 SD below the mean, a [unit] with [IV] of 1 SD above the mean will experience a [X]% [greater/lower] [outcome].`
- `Translating into practical implications, one standard deviation increase in [IV] is associated with a [specific dollar/percentage change] in [DV].`

#### C. 交互效应报告（Interaction Effects）
- `Hypothesis [n] proposes that [moderator] [amplifies/mitigates] the [positive/negative] association between [IV] and [DV]. [Model reference] shows that the [two-way/three-way] interaction of [variables] is [positively/negatively] related to [DV] (β = [value], p < [value]).`
- `This result indicates that the [relationship/effect] of [IV] on [DV] is [stronger/weaker] when [moderator condition].`
- `We plot this result in Figure [n]. As the figure shows, [description of interaction pattern].`
- `A simple slope test supports our hypothesis: [IV] is [positively/negatively] associated with [DV] when [moderator is high] (b = [value], p < [value]) but [not significant / weaker] when [moderator is low] (b = [value], p = [value]).`

##### 三元交互效应
- `The three-way interaction of [X], [M1], and [M2] is [positively/negatively] related to [DV] (β = [value], p < [value]). This result indicates that the two-way interaction of [X] and [M1] is [weakened/strengthened] when [M2 condition].`

#### D. 中介效应报告（Mediation Effects）
- `To test the mediating effect, we adopted the [method name] approach outlined by [citation].`
- `Using [N] bootstrapped samples, we find the direct effect of [IV] on [DV] positive and significant (b = [value], SE = [value], p = [value], 95% bias-corrected CI = [lower, upper]).`
- `Its indirect effect through [mediator] is also positive and significant (b = [value], SE = [value], p = [value], 95% CI = [lower, upper]).`
- `The absence of zero within the confidence interval confirms the mediation effect.`
- `When controlling for [mediator], the coefficient for [IV] is reduced from [value] to [value], suggesting [mediator] as a partial mediator.`

#### E. 控制变量结果简要提及
- `Of the control variables, the results show that [variable] significantly predicts [DV] (β = [value], p < [value]).`
- `The other control variables show no statistically significant effect on [DV].`

---

### Robustness Analysis 专用句式模板（关键增补）

#### 总体框架
稳健性分析应按体系化方式组织，覆盖以下维度（至少3个）：

##### 维度一：内生性纠正（Endogeneity Correction）
（见 Methods 中的识别策略，此处报告结果）
- `To address potential endogeneity, we [employed strategy]. The results, summarized in [Model/Table reference], were consistent with the original findings.`
- `As a further check, we [alternative endogeneity approach]. Our conclusions remain unchanged.`

##### 维度二：替代测量（Alternative Measures）
- `In the main analysis, we used [measure A] to operationalize [construct]. As an alternative, we used [measure B], following [citation]. [Model/Table reference] shows that our results were not sensitive to this alternative measure, confirming the robustness of our findings.`
- `We also considered alternative operationalizations of [DV/IV]. Specifically, we replaced [original measure] with [alternative measure]. The results did not differ substantively.`

##### 维度三：替代模型规格（Alternative Specifications）
- `Although we used [model type] as our main analyses, we also leveraged the advantages of [alternative model] to check the robustness of our findings. The results remain consistent with the [original model] results.`
- `As a robustness test, [alternative lag/clustering/estimation approach] are also examined. We obtained results similar to the main results.`
- `We also tested our models using [quantile regression / GEE / multilevel modeling]. Our findings remain robust.`

##### 维度四：反向因果/时间结构（Reverse Causality / Temporal Structure）
- `To rule out the possibility of reverse causality, we conducted an analysis with [IV] at time t as a dependent variable and [DV] at time t−1 as an independent variable, together with the full set of controls. We find no significant relationship, alleviating reverse causality concerns.`
- `We consider alternative temporal gaps by lagging [n] years to observe how [IV] in year t−[n] is associated with [DV] in year t. Our findings remain robust.`

##### 维度五：伪造检验（Falsification Tests）
- `As a falsification test, we examine the impact of [IV] on [outcome that should NOT be affected]. We find [IV] has no main effect on [unrelated outcome], strengthening the argument that [IV] specifically affects [theorized DV] rather than [alternative mechanism].`
- `These non-findings confirm that what drives our main results is [theorized mechanism] rather than [alternative explanation].`

##### 维度六：子样本/边界分析（Subsample / Boundary Analyses）
- `Subsample analyses reveal that the relationship holds for [group A] but not [group B], suggesting [theoretical interpretation].`
- `To ensure our results are not driven by [specific subset], we re-estimated the model after excluding [subset]. The results remain substantively unchanged.`
- `We explored whether the effect changes across [time periods / contexts / subgroups]. Our data indicates that [pattern].`

##### 维度七：遗漏变量偏差（Omitted Variable Bias Tests）
- `We conducted an ITCV test to explore whether our results suffer from omitted variable bias (Busenbark et al., 2022). The results indicate that an omitted variable would need to overturn the relationship in [X]% of cases to bias our results. The partial correlations of all included controls are below this threshold, alleviating concerns about omitted variable bias.`

##### 维度八：Construct Validity 检验
- `To validate [measure], we recruited [N] [experts] who independently rated [N] [units]. We found a significantly high correlation between the [automated/keyword] measures and manual ratings (r = [value]; p < [value]), providing empirical support for the validity of [measure].`
- `We also conducted a [sentiment analysis / topic modeling analysis] to rule out the concern that [alternative explanation]. Our analysis reveals [finding that rules out the concern].`

#### 稳健性分析报告总结句
- `Taken together, these robustness checks corroborate our main findings and provide confidence that the results are not artifacts of specific modeling choices or measurement decisions.`
- `Across all robustness checks, our core findings remain qualitatively and quantitatively consistent, supporting the theoretical arguments developed in this study.`

---

### Supplementary / Additional / Post-Hoc Analyses 句式模板

这类分析用于扩展理论理解，超出假设检验范围但为论文增添深度：

- `In supplementary analyses, we also provide new insights into [additional theoretical implication].`
- `Although we did not hypothesize [indirect moderation / additional effect], our theoretical model implies it may exist. To test this, we explored [analysis].`
- `We also explored whether [additional pattern]. Our data indicates that [finding], providing evidence that [theoretical interpretation].`
- `In a post-hoc analysis, we find that when [condition], the [effect] on [DV] [pattern], highlighting [theoretical insight].`

---

### 高频误用替换（Methods, Results & Robustness 场景）

| Bad | Better | Reason |
|-----|--------|--------|
| `We used a questionnaire and did analysis.` | `We collected survey data and estimated [model], controlling for [key covariates].` | 模糊 → 精确 |
| `H1 is significant.` | `Results support H1: [substantive finding] (β = ..., p < ...).` | 统计优先 → 实质优先 |
| `See Table 2.` | `As shown in Table 2, [main substantive pattern].` | 空指向 → 内容引导 |
| `Our results confirm the theory.` | `Our results are consistent with the theory.` | 过度宣称 → 校准 |
| `X proves that Y causes Z.` | `X provides evidence that Y may causally affect Z.` | 因果越界 → 谨慎因果 |
| `The result is robust.` | `The effect is substantively unchanged when we [alternative specification].` | 空洞 → 具体 |
| `We controlled for many variables.` | `We include control variables to rule out factors whose effects on [DV] might be confounded with those of our covariates.` | 模糊 → 目的导向 |
| `We used instrumental variables.` | `We instrument [endogenous variable] with [instrument], which satisfies the exclusion restriction because [reason].` | 缺乏论证 → 完整论证 |
| `We did a robustness check.` | `To address potential endogeneity concerns, we employed [specific strategy]. The results, presented in [Table], are consistent with our main findings.` | 笼统 → 具体策略 |
| `The robustness checks confirm our findings.` | `Across all robustness checks, our core findings remain qualitatively and quantitatively consistent.` | 简单 → 系统性总结 |
| `We tested for endogeneity.` | `Endogeneity may potentially bias our results, as [specific threat]. To address this issue, we [strategy] (e.g., [citation]).` | 无动机 → 明确威胁 + 对策 |
| `Results are significant at the 5% level.` | `[Substantive finding in words] (β = [value], p < 0.05).` | 数字优先 → 含义优先 |
| `The interaction is significant.` | `The interaction term [X × M] is [positive/negative] and significant (b = [value], p < [value]). A simple slope test reveals that [interpretation].` | 不完整 → 含 slope test |
| `We did mediation analysis.` | `Using [N] bootstrapped samples, we find the indirect effect through [mediator] is significant (b = [value], 95% CI = [lower, upper]).` | 笼统 → 方法+结果 |

### Claim 强度校准
- 描述性证据：`shows`, `indicates`, `documents`
- 相关性推断：`is associated with`, `is linked to`, `correlates with`
- 机制一致推断：`is consistent with the mechanism that`, `suggests that [M] may explain`
- 因果语言（仅强设计：IV/RDD/DID）：`increases`, `reduces`, `causally affects`
- 有限因果：`may influence`, `appears to affect`, `is consistent with a causal interpretation`

---

### 执行流程

1. **诊断**：基于 Phase 1 诊断结果，确定 Methods 中的设计描述缺口、Results 中的解释缺口、Robustness 中的覆盖缺口。
2. **术语表**：统一变量名、方法名、统计表达。
3. **Methods 改写**：按以下顺序组织——
   - Design overview & empirical setting justification
   - Sample and data (sources, period, N, sample construction)
   - Dependent variable
   - Independent variable(s) + construct validation
   - Moderating / mediating variables
   - Control variables (grouped by firm/CEO/board/industry level)
   - Estimation approach + endogeneity strategy
   - Model specification (写出完整模型公式)
4. **Results 改写**：按理论命题顺序改写——
   - Descriptive statistics & correlations
   - 渐进式模型呈现（controls-only → main effects → interactions → full model）
   - 每条假设：先说实质发现 → 再报系数与显著性 → 判定结果
   - 交互效应附 simple slope test / marginal effect
   - 中介效应用 bootstrapping CI 报告
5. **Robustness 改写**：按体系化维度组织——
   - Endogeneity correction (结果报告)
   - Alternative measures
   - Alternative model specifications
   - Reverse causality / temporal robustness
   - Falsification tests (if applicable)
   - Subsample / boundary analyses
   - Omitted variable bias tests (if applicable)
   - 总结句
6. **Supplementary Analyses**（可选）：Post-hoc 发现、理论延伸分析。
7. **Claim 强度校准**：确保语言与识别策略匹配（相关设计不用因果语言）。

---

### 润色输出模板

1. `Polished Version`（英文，Methods、Results、Robustness 三部分分别输出）
2. `Key Edits`（英文，5-12条，说明主要改动与升级点）
3. `Word/Phrase Upgrades`（英文替换对照表）

---

## 完整输出结构

```
## Diagnostic Report
- 设计风险清单：
  1. ...
  2. ...
- 结果解释缺口：
  1. ...
- 稳健性体系评估：
  - 内生性纠正：✓/✗ [具体方法]
  - 替代测量：✓/✗ [具体方法]
  - 替代模型规格：✓/✗ [具体方法]
  - 反向因果：✓/✗
  - 伪造检验：✓/✗
  - 子样本/边界：✓/✗
  - 遗漏变量偏差：✓/✗
- 必做稳健性建议（按优先级排序）：
  1. ...
  2. ...
  3. ...
- 红线检查：通过/不通过 + 原因

## Polished Methods
[完整改写的英文 Methods 部分]

## Polished Results
[完整改写的英文 Results 部分，按假设顺序输出，含渐进式模型报告]

## Polished Robustness Analysis
[完整改写的英文稳健性分析部分，按维度体系化组织]

## Supplementary Analyses (if applicable)
[Post-hoc 分析或理论延伸发现]

## Key Edits
1. ...
2. ...
...

## Word/Phrase Upgrades
| Original | Revised | Reason |
|----------|---------|--------|
| ...      | ...     | ...    |
```
