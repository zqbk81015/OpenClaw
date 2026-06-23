# TOOLS.md - 本地工具笔记

技能定义工具_如何_工作。这个文件是放_你的_特定信息 —— 只有你的设置才有的东西。

## 飞书技能

已安装的飞书技能：

| 技能 | 用途 | 路径 |
|------|------|------|
| feishu-doc | 飞书文档读写 | `~/.openclaw/plugin-skills/feishu-doc/SKILL.md` |
| feishu-drive | 飞书云存储文件管理 | `~/.openclaw/plugin-skills/feishu-drive/SKILL.md` |
| feishu-perm | 飞书权限管理 | `~/.openclaw/plugin-skills/feishu-perm/SKILL.md` |
| feishu-wiki | 飞书知识库导航 | `~/.openclaw/plugin-skills/feishu-wiki/SKILL.md` |

## 记忆系统

自定义技能：`.openclaw/skills/memory-system/SKILL.md`

- 每日日志：`memory/YYYY-MM-DD.md`
- 长期记忆：`MEMORY.md`

## 放在这里的东西

比如：

- 摄像头名称和位置
- SSH 主机和别名
- TTS 首选语音
- 扬声器/房间名称
- 设备昵称
- 任何环境特定的信息

## 示例

```markdown
### 摄像头

- living-room → 主区域，180° 广角
- front-door → 入口，动作触发

### SSH

- home-server → 192.168.1.100, user: admin

### TTS

- 首选语音: "Nova" (温暖，略带英式)
- 默认扬声器: 厨房 HomePod
```

## 为什么分开？

技能是共享的。你的设置是你的。把它们分开意味着你可以更新技能而不会丢失笔记，分享技能而不会泄露你的基础设施。

---

添加任何有助于你工作的东西。这是你的备忘单。

## 相关

- [Agent workspace](/concepts/agent-workspace)
