# Starmland 🌌

个人的一体化项目：**个人网站 + 在线工具集 + AI Agent Skills 集合**。

## ✨ 在线访问

GitHub Pages：`https://marvincmm.github.io/Starmland/`（需在仓库 Settings → Pages 中开启）

## 📁 项目结构

```
Starmland/
├── index.html              # 个人网站主页（关于我 + 技能展示）
├── skills.html             # AI Skills 展示页
├── tools/
│   ├── index.html          # 工具导航
│   ├── json-formatter.html # JSON 格式化 / 压缩 / 校验
│   ├── timestamp.html      # 时间戳 ⇄ 日期互转
│   ├── base-converter.html # 2/8/10/16 进制互转
│   ├── calculator.html     # 计算器
│   ├── countdown.html      # 倒计时
│   └── lucky-draw.html     # 今日抽签
├── skills/                 # AI Agent Skills 集合（SKILL.md 格式）
│   ├── README.md
│   └── example-skill/
│       └── SKILL.md
└── assets/
    └── css/style.css       # 共享样式（深色星空主题）
```

## 🧰 工具列表

| 工具 | 功能 |
|---|---|
| JSON 格式化 | 格式化、压缩、语法校验 |
| 时间戳转换 | 当前时间戳、双向转换 |
| 进制转换 | 二/八/十/十六进制互转 |
| 计算器 | 四则运算 |
| 倒计时 | 目标日期倒计时 |
| 今日抽签 | 随机运势小娱乐 |

## 🤖 Skills

`skills/` 目录存放 AI Agent 可用的 Skill 文件（遵循 SKILL.md 规范），见 [skills/README.md](skills/README.md)。

## 🔧 如何维护

1. 修改本地文件后：`git add . && git commit -m "描述" && git push`
2. 新增工具：复制 `tools/` 下任一页面改造，并在 `tools/index.html` 和本表登记
3. 新增 Skill：在 `skills/` 下新建文件夹放 `SKILL.md`
