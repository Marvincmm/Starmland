---
name: example-skill
description: 示例技能，演示 SKILL.md 的标准结构；当用户要求演示如何编写一个新 Skill 时使用。
---

# Example Skill（示例技能）

## 用途

演示一个标准 Skill 文件的完整结构，作为编写新 Skill 的模板。

## 触发条件

- 用户要求"写一个新的 Skill"
- 用户想了解 SKILL.md 的格式规范

## 工作流程

1. 复制本文件作为模板起点
2. 修改 frontmatter 中的 `name` 和 `description`
3. 按实际用途改写「用途 / 触发条件 / 工作流程」三个小节
4. 删除本说明段，保存到 `skills/<新技能名>/SKILL.md`

## 注意事项

- `name` 必须是小写字母、数字和连字符
- `description` 决定 Agent 何时加载此技能，务必写清"做什么 + 何时用"
- 步骤要具体可执行，避免空话
