# AI Agent Skills 集合

本目录存放 **AI Agent 可加载的 Skill 文件**（如 Claude、TuriX 等支持 Skills 的智能体）。

## 📄 SKILL.md 规范

每个 Skill 是一个独立文件夹，其中必须包含一个 `SKILL.md`，结构如下：

```markdown
---
name: my-skill-name          # 技能名，小写字母和连字符
description: 一句话说明这个技能做什么、什么时候该触发它
---

# 技能标题

## 用途
这个技能解决什么问题。

## 触发条件
什么情况下 Agent 应该使用这个技能。

## 工作流程
1. 第一步
2. 第二步
3. 输出结果

## 注意事项
边界情况、限制等。
```

- `name`：只含小写字母、数字、连字符，不超过 64 字符
- `description`：写清楚"做什么 + 何时用"，Agent 依靠它判断是否加载
- 正文：写清步骤，让任何 Agent 都能照着执行

## ➕ 如何新增一个 Skill

1. 在 `skills/` 下新建文件夹：`skills/my-skill/`
2. 编写 `skills/my-skill/SKILL.md`（按上方规范）
3. 提交并推送：`git add . && git commit -m "feat: add my-skill" && git push`
4. 在网站的 [skills.html](../skills.html) 展示页登记一张卡片

## 📚 现有 Skills

| Skill | 说明 |
|---|---|
| [example-skill](example-skill/SKILL.md) | 示例：演示标准 SKILL.md 结构 |
