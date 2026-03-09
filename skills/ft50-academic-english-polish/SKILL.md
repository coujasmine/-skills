---
name: ft50-academic-english-polish
description: 用于将论文草稿润色为学术期刊英语（尤其是管理学/FT50风格），重点处理词汇精确性、句式规范、逻辑衔接、结论克制与按 part 改写。适用于用户强调“必须英文写作、关注单词和句式用法”的场景。
---

# FT50 Academic English Polish

## 何时使用
- 用户要求把论文内容改成更地道的学术英语。
- 用户特别强调用词、句式、语气、claim 强度控制。
- 需要按 Introduction/Theory/Methods/Results/Discussion 分段润色。

## 强制规则
1. 最终改写内容必须是英文；不要输出中文句子作为正文改写结果。
2. 不改变原始实证结果、变量关系与方向，只改语言表达与论证清晰度。
3. 避免过度断言：优先使用 calibrated claims（如 `is associated with`, `suggests`, `is consistent with`）。
4. 每个段落保留“topic sentence -> evidence/logic -> implication”结构。

## 执行流程
1. 快速识别文本所属 part（Introduction/Theory/Methods/Results/Discussion）。
2. 建立术语表：统一核心构念、变量名、方法名、统计表达。
3. 先做句级修复（语法、冗余、平行结构），再做段级重写（逻辑与衔接）。
4. 校准 claim 强度，使语言与证据层级匹配（相关/因果/机制）。
5. 输出按 part 组织的结果，并给“高频误用 -> 推荐替换”清单。

## 输出格式
1. `Polished Version`（英文，按段或按 part）
2. `Key Edits`（英文，3-8条，说明主要语言升级点）
3. `Word/Phrase Upgrades`（英文替换对照，聚焦词汇与句式）

## 参考文件（按需加载）
- 统一润色手册（句式模板 + claim 梯度 + 误用替换）：`references/language-polish-playbook.md`
