# RikkaHub Skills

一套可以在 [RikkaHub](https://github.com/rikkahub/rikkahub) 中直接导入的轻量技能包（SKILL.md 格式，纯提示词，无脚本依赖）。

## 技能列表

| 技能 | 用途 |
|---|---|
| **cloudflare** | Cloudflare DNS / Workers / Pages / CDN 管理 |
| **context-manager** | 长对话上下文压缩与 token 优化 |
| **devops** | 部署自动化与基础设施管理 |
| **docker** | Docker 容器管理与故障排查 |
| **github** | GitHub 仓库分析、代码审查、部署说明 |
| **linux** | Linux 服务器运维、日志分析、性能排障 |
| **markdown** | 技术文档与 README 写作 |
| **mcp-builder** | 构建、配置、维护 MCP 服务器 |
| **network** | 网络延迟 / 路由 / 丢包分析 |
| **planner** | 任务规划与推理优化 |
| **security** | 安全审计与服务器加固建议 |
| **shell** | Bash 脚本编写与命令分析 |
| **skill-creator** | 创建、改进、维护 AI 技能 |
| **task-executor** | 高效任务执行与结果验证 |
| **tool-router** | 工具选择与 MCP 路由优化 |

## 完整导入 URL

GitHub 导入框里直接粘贴以下地址（一次一个技能）：

```
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/cloudflare
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/context-manager
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/devops
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/docker
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/github
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/linux
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/markdown
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/mcp-builder
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/network
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/planner
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/security
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/shell
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/skill-creator
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/task-executor
https://github.com/lll33lll/rikkahub-skills/tree/main/skills/tool-router
```

## 在 RikkaHub 中导入

**重要：RikkaHub 的 GitHub 导入一次只导入一个技能，且必须填到技能子目录**（它会在所填目录下直接找 `SKILL.md`，填仓库根地址会报「目录中未找到 SKILL.md」）。

1. 打开 RikkaHub → 设置 → 助手 → 扩展 → 技能
2. 点「+」→ **从 GitHub 导入**
3. 粘贴上面任意一条完整 URL
4. 导入后回助手设置 → 扩展 → 技能标签页 → 勾选启用

### 批量导入（一次装全部）

1. 手机浏览器打开：`https://github.com/lll33lll/rikkahub-skills/archive/refs/heads/main.zip`
2. 下载 zip 到手机
3. RikkaHub → 设置 → 助手 → 扩展 → 技能 → 「+」→ **从文件导入** → 选择该 zip
4. 会一次性导入压缩包内所有技能

### 备选：粘贴导入

仓库里点开任意 `skills/<名字>/SKILL.md`，复制全文 → RikkaHub 里选「手动添加」粘贴，效果相同。
