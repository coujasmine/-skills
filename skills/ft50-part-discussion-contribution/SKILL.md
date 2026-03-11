---
name: ft50-part-discussion-contribution
description: 用于统筹论文 Discussion、Limitations/Future Research 与 Conclusion 的诊断评审与英文润色改写；默认联动改写三个子部分，确保三者使用同一个理论口径、同一个 claims 边界与同一个语气轨迹。基于 AMJ/SMJ/OrgSci 等顶刊 Discussion 写作范式。
---

# Part: Discussion, Limitations & Conclusion Orchestrator

## 目标
把三个收束部分当作一条连续链整体改写——Discussion 展开、Limitations 收边界、Conclusion 定调——而不是拆成三个彼此独立的小任务。完成诊断后，直接输出符合 FT50 标准的英文改写版本。

## skill 的角色
这个 skill 是"总导演"，不是"路由器"。它必须先统一主命题，再约束三个子部分围绕同一个理论口径、同一个 claims 边界、同一个语气轨迹展开。

## 三个子部分的分工
- **Discussion**：负责展开——回答研究问题、解释结果、展开 literature conversation、提出 practical implications。
- **Limitations and Future Research**：负责收边界——限定 strongest claim 的适用范围，指出当前不能再往前走到哪里。
- **Conclusion**：负责定调——把全文压回一个更高层次、更稳的 proposition，并完成最后收束。

---

## Phase 1: 诊断评审

### 改写前必须建立的 3 个锚点
在开始任何诊断或改写前，先明确以下三句。如果写不清，说明三个部分还不能开始联动改写。

1. **Core proposition**：这篇论文最后到底要让读者带走什么命题？
2. **Strongest defensible claim**：基于当前研究设计，最强但仍站得住脚的主张是什么？
3. **Broader significance**：这个命题为什么对更大的理论或管理问题重要？

### Discussion 检查
1. 是否以 study-level answer 开篇（用 1–2 句直接回答研究问题，而非重复统计结果）。
2. 是否按假设/研究问题顺序逐一讨论发现，每个发现都有实质性解释（不只是"H1 is supported"）。
3. 是否展开了与先前文献的对话（conversation-based contribution），而非仅罗列"consistent with [citation]"。
4. 对意外发现或不支持假设的结果，是否给出了合理的理论解释。
5. 理论贡献是否清晰且具体（不是空泛的"extends the literature"），是否明确了对哪个理论对话/辩论做了推进。
6. 实践启示是否具体可操作（不是泛泛的"managers should pay attention to..."），是否与样本边界一致。

### Limitations and Future Research 检查
1. 是否针对 Discussion 中的 strongest claim 做边界限定（而非另起话题）。
2. 是否区分了"设计层面的局限"（如样本、测量、因果推断）和"理论层面的边界"（如适用情境、机制前提）。
3. 每个局限是否附带了对应的 future research direction（不是空洞的"future research should explore..."）。
4. 是否避免了自我贬低（不能把自己的研究写垮）。
5. Future research 建议是否具体到可以指导一篇新论文的设计。

### Conclusion 检查
1. 是否以压缩版 core proposition 开篇（不是重新写摘要）。
2. 是否回扣 Discussion 开头的 study-level answer（echo 而非另起）。
3. 是否在更高层面说明了"为什么这个发现对更大的领域重要"。
4. 是否避免引入任何 Discussion 中未铺垫的新论点或新理论。
5. 长度是否控制在 1 段（短论文）至 2–3 段（长论文），不超过半页。

### 跨段一致性检查（7 条核心规则）

#### 规则 1: One Proposition Rule
Discussion、Limitations、Conclusion 必须服务于同一个 core proposition。

禁止：Discussion 说 mechanism A → Limitations 改谈 measurement B → Conclusion 升华到完全不同的理论主张 C。

#### 规则 2: Same Conversation Rule
Discussion 中对话的核心 literatures，Conclusion 必须延续同一套理论口径。

禁止：Discussion 用 attention-based view → Conclusion 突然换成 broad corporate governance slogan。Conclusion 可以升层级，但不能换频道。

#### 规则 3: Claim Discipline Rule
Discussion 提出的 strongest claim，Limitations 只能限定其边界，不能将其改写为另一种更弱、更模糊、甚至不同类型的 claim。

正确关系：
- Discussion: `what we can claim`
- Limitations: `how far that claim travels`
- Conclusion: `why that claim matters`

错误关系：Discussion 说因果逻辑 → Limitations 改口成只是相关性描述 → Conclusion 又回到强因果口吻。

#### 规则 4: Tone Descent Rule
三个部分的语气必须连续下降：
- Discussion：展开、解释、对话（最丰富）
- Limitations：收边界、降噪音、控主张（中等）
- Conclusion：压缩、提炼、定调（最简洁）

#### 规则 5: No New Logic Late Rule
Limitations 和 Conclusion 不得引入 Discussion 中没有建立的新机制、新理论主张或新对话对象。

可以：缩短、提炼、限定、升层级。不能：新增 mediator、换理论 stream、凭空上升到全新规范命题。

#### 规则 6: Last-Paragraph Echo Rule
Conclusion 必须是对 Discussion 开头的 echo，而不是另起一段。

理想关系：
- Discussion 开头: `This study shows that ...`
- Conclusion 末段: `Taken together, this suggests that ...`

#### 规则 7: Practical-Boundary Alignment Rule
如果 Discussion 给了 management/governance implications，Limitations 不能把边界写得与这些实践建议直接冲突。Conclusion 也不能写成对所有组织都成立的口号。

### 红线
- Discussion 无 study-level answer 开篇（直接跳入统计结果复述）：判"缺主干回答"。
- 三个部分的理论口径不一致（Discussion 谈理论 A，Conclusion 换到理论 B）：判"理论口径断裂"。
- Limitations 把 Discussion 的 strongest claim 改写为完全不同类型的 claim：判"claim 纪律违反"。
- Conclusion 引入 Discussion 中未建立的新机制或新理论主张：判"后段越界"。
- Practical implications 与样本边界直接冲突（如启示面向所有企业，但样本仅含大型上市公司）：判"启示-边界冲突"。
- Discussion 仅罗列"consistent with [citation]"而无实质性理论对话：判"贡献缺失"。

### 诊断输出模板
```
## Diagnostic Report

### 锚点确认
- Core proposition: [一句话]
- Strongest defensible claim: [一句话]
- Broader significance: [一句话]

### Discussion 评估
- Study-level answer 开篇：✓/✗
- 按假设顺序逐一讨论：✓/✗
- Literature conversation 质量：✓/✗（是否超越"consistent with"层面）
- 意外发现/不支持结果的解释：✓/✗/不适用
- 理论贡献具体性：✓/✗
- 实践启示可操作性：✓/✗
- 启示与样本边界一致性：✓/✗

### Limitations and Future Research 评估
- 是否围绕 strongest claim 做边界限定：✓/✗
- 设计局限 vs 理论边界 区分：✓/✗
- 每个局限附带具体 future research direction：✓/✗
- 是否避免自我贬低：✓/✗

### Conclusion 评估
- 压缩版 core proposition 开篇：✓/✗
- 回扣 study-level answer（echo）：✓/✗
- 更高层面的 significance 阐述：✓/✗
- 长度控制：✓/✗
- 无新论点引入：✓/✗

### 跨段一致性评估
- One Proposition Rule：✓/✗
- Same Conversation Rule：✓/✗
- Claim Discipline Rule：✓/✗
- Tone Descent Rule：✓/✗
- No New Logic Late Rule：✓/✗
- Last-Paragraph Echo Rule：✓/✗
- Practical-Boundary Alignment Rule：✓/✗

### 红线检查：通过/不通过 + 原因

### 结构性修改建议（3–8 条，按优先级排序）
1. ...
2. ...
3. ...
```

---

## Phase 2: 英文润色改写

### 强制规则
1. 最终改写内容必须是英文；不输出中文句子作为正文。
2. **绝对不改变**原始实证结果、变量关系方向、效应符号与统计显著性。
3. 只改语言表达、论证结构、理论对话深度和跨段一致性。
4. Claim 强度必须与研究设计匹配（相关设计不用因果语言）。
5. 三个部分必须按 Discussion → Limitations → Conclusion 顺序改写，不可颠倒。
6. 每段保留"topic sentence → evidence/logic → implication"结构。

---

### Discussion 专用句式模板

#### A. Study-Level Answer 开篇（Discussion 第一段）
Discussion 必须以直接回答研究问题开头，而非重复统计结果。

- `This study set out to examine [research question]. Our results indicate that [core finding in substantive terms], suggesting that [theoretical interpretation].`
- `The central aim of this study was to investigate [research question]. Our findings reveal that [core finding], which advances our understanding of [theoretical domain] by [specific contribution].`
- `Drawing on [theory], we examined [research question]. The findings demonstrate that [core finding], offering new insight into [specific theoretical puzzle].`
- `We proposed and tested the argument that [core proposition]. Consistent with our theorizing, [core finding in substantive terms].`

#### B. 逐假设讨论（Hypothesis-by-Hypothesis Discussion）
每个假设的讨论需先给实质性解释，再连接理论对话。

- `[Hypothesis finding]. This result is notable because it suggests that [mechanism/theoretical interpretation], extending prior work on [topic] (e.g., [citation]) by showing that [specific extension].`
- `Contrary to our expectations, we did not find support for Hypothesis [n]. One plausible explanation is that [theoretical reasoning]. This non-finding is consistent with [citation], who argued that [related argument]. Future research might explore [specific direction] to reconcile this tension.`
- `The [positive/negative] relationship between [IV] and [DV] aligns with our theoretical argument that [mechanism]. Importantly, this finding goes beyond prior work (e.g., [citation]) by demonstrating that [specific advance].`
- `An unexpected finding is the [pattern]. We speculate that this reflects [theoretical interpretation]. Although speculative, this interpretation is consistent with [citation]'s argument that [related reasoning].`

#### C. Literature Conversation（理论对话）
核心要求：不仅说"与XX一致"，而要说"我们对XX对话做了什么推进"。

- `Our findings speak to the ongoing debate on [topic]. While prior studies (e.g., [citation A]; [citation B]) have emphasized [prior focus], our results suggest that [new insight], thereby [reconciling / extending / challenging] this body of work.`
- `These results advance the [theory/literature] conversation in two ways. First, [contribution 1]. Second, [contribution 2].`
- `By documenting [finding], this study extends the [theoretical stream] beyond its traditional focus on [prior scope] to encompass [new scope].`
- `Our work complements [citation], who found [prior finding]. We build on this by showing that [extension or boundary condition], suggesting that the relationship is more [nuanced / contingent / robust] than previously theorized.`
- `Rather than viewing [construct A] and [construct B] as [prior framing], our findings suggest a more [nuanced/dynamic] relationship in which [new framing].`

#### D. Theoretical Contributions（理论贡献）
贡献陈述必须具体到"对哪个对话做了什么推进"。

- `This study makes [N] contributions to the literature. First, we contribute to [specific literature/debate] by [specific advance]. Prior work has [prior state], but our findings show that [new insight].`
- `Second, we extend [theory] by incorporating [new element]. While [theory] has traditionally focused on [prior focus], our work demonstrates that [extension].`
- `Third, our study responds to recent calls (e.g., [citation]) for research on [topic] by providing evidence that [specific finding].`
- `Our theoretical contribution lies in [specific advance]. By showing that [finding], we offer a more refined understanding of [construct/mechanism], one that accounts for [previously overlooked factor].`

#### E. Practical Implications（实践启示）
启示必须具体可操作且与样本边界一致。

- `Our findings have practical implications for [specific audience, e.g., boards of directors in large publicly listed firms].`
- `For managers, our results suggest that [specific actionable recommendation]. Specifically, [concrete guidance].`
- `These findings are particularly relevant for [specific context], where [condition that makes the finding actionable].`
- `From a policy perspective, our results imply that [specific policy implication], though we note that this implication is bounded by [sample/context limitation].`

---

### Limitations and Future Research 专用句式模板

#### A. 总起句
- `Despite these contributions, our study has limitations that also suggest fruitful avenues for future research.`
- `We acknowledge several limitations that qualify the interpretation of our findings and point to opportunities for future inquiry.`

#### B. 设计层面局限（Design Limitations）
每个局限后必须紧跟 future research direction。

- `First, our sample is drawn from [specific context, e.g., large U.S. publicly listed firms], which may limit the generalizability of our findings to [other contexts]. Future research could replicate our analysis in [alternative context] to test the boundary conditions of [core proposition].`
- `Second, although we took steps to address endogeneity concerns (e.g., [strategy]), we cannot rule out all threats to causal inference. Future studies could leverage [natural experiment / RDD / field experiment] to establish stronger causal evidence.`
- `Third, our measure of [construct] captures [what it captures] but may not fully reflect [broader concept]. Future research might employ [alternative measurement, e.g., survey-based measures / qualitative coding] to provide a more comprehensive assessment.`
- `Fourth, our data do not allow us to directly observe [unobserved mechanism]. While our results are consistent with [theorized mechanism], future research using [method, e.g., process-tracing / qualitative interviews / experimental designs] could provide more direct evidence of the underlying process.`

#### C. 理论层面边界（Theoretical Boundaries）
- `Our theoretical framework assumes [assumption]. While this assumption is reasonable in [context], it may not hold in [alternative context] where [different condition applies]. Exploring [boundary condition] could reveal important contingencies.`
- `We focused on [specific aspect of the phenomenon]. However, [related aspect] may also play a role. Future research could integrate [related construct] to develop a more complete theoretical account.`

#### D. Future Research 方向收束
- `Collectively, these limitations offer a rich agenda for future research that can further illuminate [broader question].`
- `We hope these limitations serve as an invitation for future studies to [specific research agenda].`

---

### Conclusion 专用句式模板

#### A. 压缩版 Core Proposition 开篇
- `In this study, we drew on [theory] to examine [research question]. Our findings indicate that [compressed core proposition].`
- `This study investigated [research question] and found that [compressed core finding]. These results suggest that [theoretical implication in one sentence].`

#### B. Broader Significance 阐述
- `These findings carry broader implications for [theoretical domain / managerial practice]. By showing that [core finding], this study shifts attention from [old focus] to [new focus].`
- `More broadly, our work suggests that [higher-level theoretical insight], an insight that may extend to [adjacent domains].`

#### C. Echo 收束（最后一段回扣 Discussion 开头）
- `Taken together, our findings suggest that [echo of study-level answer in more compressed, elevated form].`
- `In sum, this study demonstrates that [compressed restatement], offering a foundation for future research on [broader agenda].`
- `We hope this study advances our collective understanding of [phenomenon] and encourages further inquiry into [specific direction].`

---

### 高频误用替换（Discussion, Limitations & Conclusion 场景）

| Bad | Better | Reason |
|-----|--------|--------|
| `H1 is supported.` | `Consistent with Hypothesis 1, [substantive finding in words] (β = ..., p < ...).` | 统计结论 → 实质性解释 |
| `Our results are consistent with [citation].` | `Our findings extend [citation] by showing that [specific advance beyond prior work].` | 被动一致 → 主动推进 |
| `This study fills a gap in the literature.` | `This study advances [specific debate] by providing evidence that [specific finding].` | 空泛 → 具体贡献 |
| `This study contributes to the literature.` | `This study contributes to [specific literature] by [specific mechanism: reconciling / extending / challenging].` | 无指向 → 有对话对象 |
| `Managers should pay attention to X.` | `For managers in [specific context], our results suggest [specific actionable guidance].` | 空洞建议 → 可操作且限定 |
| `Our study has several limitations.` | `Despite these contributions, our study has limitations that qualify interpretation and suggest avenues for future research.` | 机械开场 → 连接前文 |
| `Future research should explore X.` | `Future research could leverage [specific method/design] to test whether [specific hypothesis derived from our limitation].` | 空泛方向 → 可执行设计 |
| `This study is not without limitations.` | `We acknowledge several limitations that bound our findings.` | 双重否定 → 直接表述 |
| `In conclusion, this paper studied X.` | `In this study, we examined [research question] and found that [compressed core finding].` | 重复摘要 → 压缩命题 |
| `Our study makes important contributions.` | `Our study makes [N] contributions to [specific debate]. First, ...` | 自我评价 → 具体陈述 |
| `The results prove that X causes Y.` | `The results provide evidence consistent with the argument that X [is associated with / may influence] Y.` | 因果越界 → 校准 |
| `Despite many limitations, we believe ...` | `Although bounded by [specific limitation], our findings suggest that ...` | 自我贬低 → 限定不贬低 |
| `This study extends the literature in many ways.` | `This study advances [conversation] by demonstrating that [finding], which [reconciles / challenges / extends] prior accounts.` | 空泛数量 → 具体内容 |
| `We hope future research will address these issues.` | `These limitations offer a rich agenda: future studies could [specific design] to [specific goal].` | 被动希望 → 主动议程 |

### Claim 强度校准
Discussion 和 Conclusion 的语言必须与研究设计的因果推断能力匹配：

- 描述性证据：`shows`, `indicates`, `documents`
- 相关性推断：`is associated with`, `is linked to`, `correlates with`
- 机制一致推断：`is consistent with the mechanism that`, `suggests that [M] may explain`
- 因果语言（仅强设计：IV/RDD/DID）：`increases`, `reduces`, `causally affects`
- 有限因果：`may influence`, `appears to affect`, `is consistent with a causal interpretation`

**核心纪律**：Discussion 和 Conclusion 中使用的最强因果语言，不能超过 Methods 中识别策略所支撑的层级。

---

### 执行流程

1. **建立 3 个锚点**：写出 core proposition、strongest defensible claim、broader significance 各一句。
2. **诊断**：基于 Phase 1 检查清单，分别评估 Discussion / Limitations / Conclusion 的质量，再做跨段一致性检查。
3. **术语表**：统一核心构念、理论名称、claim 强度表达。
4. **改写 Discussion**（按以下顺序）：
   - Study-level answer 开篇（1–2 句直接回答研究问题）
   - 逐假设讨论（实质解释 + 理论对话，非统计复述）
   - 理论贡献（具体到对哪个对话做了什么推进）
   - 实践启示（具体可操作 + 与样本边界一致）
5. **改写 Limitations**（不另起炉灶）：
   - 围绕 Discussion 的 strongest claim 做边界限定
   - 区分设计局限 vs 理论边界
   - 每个局限附带具体 future research direction
6. **改写 Conclusion**（用与 Discussion 同一理论口径完成压缩收束）：
   - 压缩版 core proposition 开篇
   - Broader significance 阐述
   - Echo 收束（回扣 Discussion 开头的 study-level answer）
7. **跨段一致性终检**：
   - Core proposition 是否贯穿三部分
   - 理论口径是否一致（Same Conversation Rule）
   - Claim 强度是否前后一致（Claim Discipline Rule）
   - Practical implications 与边界是否冲突（Practical-Boundary Alignment Rule）
   - Conclusion 是否是 echo 而非新起点（Last-Paragraph Echo Rule）
   - 语气是否连续下降（Tone Descent Rule）
   - 无新逻辑引入（No New Logic Late Rule）
8. **Claim 强度校准**：确保 Discussion/Conclusion 中的因果语言不超过 Methods 识别策略所支撑的层级。

---

### 润色输出模板

1. `Polished Version`（英文，Discussion / Limitations and Future Research / Conclusion 三部分分别输出）
2. `Key Edits`（英文，5–10 条，说明主要改动与升级点）
3. `Word/Phrase Upgrades`（英文替换对照表）

---

## 完整输出结构

```
## Diagnostic Report

### 锚点确认
- Core proposition: [一句话]
- Strongest defensible claim: [一句话]
- Broader significance: [一句话]

### Discussion 评估
- Study-level answer 开篇：✓/✗
- 按假设顺序逐一讨论：✓/✗
- Literature conversation 质量：✓/✗
- 意外发现/不支持结果的解释：✓/✗/不适用
- 理论贡献具体性：✓/✗
- 实践启示可操作性：✓/✗
- 启示与样本边界一致性：✓/✗

### Limitations and Future Research 评估
- 围绕 strongest claim 做边界限定：✓/✗
- 设计局限 vs 理论边界 区分：✓/✗
- 每个局限附带具体 future research direction：✓/✗
- 避免自我贬低：✓/✗

### Conclusion 评估
- 压缩版 core proposition 开篇：✓/✗
- 回扣 study-level answer（echo）：✓/✗
- 更高层面的 significance 阐述：✓/✗
- 长度控制：✓/✗
- 无新论点引入：✓/✗

### 跨段一致性评估
- One Proposition Rule：✓/✗
- Same Conversation Rule：✓/✗
- Claim Discipline Rule：✓/✗
- Tone Descent Rule：✓/✗
- No New Logic Late Rule：✓/✗
- Last-Paragraph Echo Rule：✓/✗
- Practical-Boundary Alignment Rule：✓/✗

### 红线检查：通过/不通过 + 原因

### 结构性修改建议（3–8 条，按优先级排序）
1. ...
2. ...
3. ...

## Polished Discussion
[完整改写的英文 Discussion 部分]

## Polished Limitations and Future Research
[完整改写的英文 Limitations and Future Research 部分]

## Polished Conclusion
[完整改写的英文 Conclusion 部分]

## Cross-Part Consistency Notes
1. Core proposition 贯穿说明：[如何确保三部分口径一致]
2. Claim 边界处理：[如何处理 claim 强度与边界对齐]
3. Echo 收束说明：[Conclusion 如何回扣 Discussion 开头]

## Key Edits
1. ...
2. ...
...

## Word/Phrase Upgrades
| Original | Revised | Reason |
|----------|---------|--------|
| ...      | ...     | ...    |
```

只有当用户明确要求"诊断"或"review"时，才仅输出诊断报告部分而不做改写。
