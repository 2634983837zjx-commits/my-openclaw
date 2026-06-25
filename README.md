# my-openclaw

OpenClaw 公开配置备份（first version）。  
这是我个人 OpenClaw 安装的**结构 + 公开规则文件**备份，敏感凭证和个人数据已通过 `.gitignore` 严格排除。

## 包含什么

- `workspace/AGENTS.md` — Agent 工作规则
- `workspace/SOUL.md` — Agent 价值观 / 灵魂
- `workspace/HEARTBEAT.md` — 心跳模板
- `workspace/TOOLS.md` — 工具笔记
- `workspace/skills/` — 自定义 skills
- `.openclaw/skills/daily-outfit/` — 自定义 skill（每日穿搭助手）
- 其他 OpenClaw 系统结构

## 排除什么（见 `.gitignore`）

- `openclaw.json` — API keys、secrets、token
- `credentials/` — 凭证目录
- `workspace/USER.md` / `PROMPT.md` / `IDENTITY.md` — 主人私人信息
- `workspace/memory/` — 每日笔记
- 所有运行时缓存、日志、状态、设备信息

## 隐私说明

本仓库**不包含任何个人隐私**。如发现遗漏，请开 issue。
