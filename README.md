# 🦞 Clawdbot Workspace

> 这是 Clawdbot（小龙虾）的专属工作空间，用于存储经验、笔记和工作文件。

---

## 📖 关于我

我是 Clawdbot，一只热情的小龙虾！我是 OpenClaw 的 AI 助手，帮助用户处理各种任务。

- **名字**：小龙虾 (Clawdbot)
- **签名**：🦞
- **工作目录**：`C:\Users\lenovo\.openclaw\workspace`

---

## 💡 经验教训

### 文件发送权限问题

**问题**：从 D 盘等非 workspace 目录直接发送文件到飞书可能会遇到权限问题

**解决方法**：
1. 先将文件拷贝到工作区的 tmp 目录：`C:\Users\lenovo\.openclaw\workspace\tmp\`
2. 然后从 tmp 目录发送文件

**原因分析**：
- OpenClaw 的文件发送功能可能对非工作区目录的文件有限制
- 拷贝到 tmp 目录后，文件有了正确的路径权限，可以正常发送

**适用场景**：
- 发送本地视频、图片、文档等文件到飞书群聊

---

### 文件路径使用错误

**问题**：读取文件时路径嵌套错误，使用了 `.openclaw\workspace\MEMORY.md` 导致路径变成 `C:\Users\lenovo\.openclaw\workspace\.openclaw\workspace\MEMORY.md`

**正确做法**：
- 工作目录已经是 `C:\Users\lenovo\.openclaw\workspace`
- 直接使用相对路径 `MEMORY.md` 或绝对路径 `C:/Users/lenovo/.openclaw/workspace/MEMORY.md`
- 避免重复使用 `.openclaw\workspace` 前缀

**记录时间**：2026-03-17

---

## 👤 用户偏好

- **文件操作规则**：默认只操作本地文件（如播放、打开、编辑等）
- 涉及飞书/外部发送时，注意文件发送权限问题

---

## 🛠️ 可用技能

| 技能 | 用途 |
|------|------|
| `agent-browser` | 浏览器自动化，签到、填表、截图 |
| `clawdhub` | 搜索、安装、发布技能 |
| `github` | GitHub 仓库、Issues、PRs 管理 |
| `feishu-doc` | 飞书文档操作 |
| `feishu-drive` | 飞书云存储管理 |
| `tavily-search` | 网页搜索、提取、爬取 |
| `summarize` | URL 或文件摘要 |
| `weather` | 天气查询 |
| `pdf` | PDF 操作 |

---

## 📝 更新日志

### 2026-03-18
- 🎉 仓库创建
- 📝 初始经验教训记录

---

> 由 🦞 Clawdbot 维护
