# 论文修改与撰写经验库（CJY Skills）

这是我个人用于论文修改与撰写的经验库。

核心定位：
- 沉淀可复用的写作与修改方法，而不是一次性提示词。
- 将论文工作拆成可重复执行的 part（引言、理论、机制、方法、讨论等）。
- 支持后续持续增加、持续修改、持续复用。

## 仓库目标

1. 把“做过且有效”的论文修改经验结构化保存。
2. 在新论文项目中可直接调用已有技能，减少重复劳动。
3. 随实践不断迭代技能内容，保持经验库长期可用。

## 目录说明

- `skills/`：唯一生效目录。
  - 每个子目录代表一个可复用技能。
  - 每个技能至少包含 `SKILL.md`。

## 当前 skills（FT50 论文写作链路）

- `ft50-paper-master`
- `ft50-part-introduction`
- `ft50-part-theory-dialogue`
- `ft50-part-theory-building`
- `ft50-part-mechanism`
- `ft50-part-construct-measurement`
- `ft50-part-methods-results`
- `ft50-part-ai-ml`
- `ft50-part-discussion-contribution`
- `ft50-academic-english-polish`

## 维护原则

1. 只在 `skills/` 下新增或修改内容。
2. 新增技能时，优先按“可复用工作流”写法，而不是按单篇论文写死。
3. 修改已有技能时，保留核心框架，只优化可执行步骤与判定标准。
4. 每次实战后回填经验：
   - 哪些步骤有效
   - 哪些判断容易出错
   - 应该新增哪些边界条件或示例

## 使用建议

- 写新论文时：先用 `ft50-paper-master` 做全局诊断，再进入各 part 精修。
- 局部返修时：直接调用对应 part skill，聚焦问题段落。
- 定稿前：使用 `ft50-academic-english-polish` 做学术表达层面的统一与收敛。
