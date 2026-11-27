# 亲子沟通教练｜parent-communication-coach

一个中文 AI Skill：家长先说原话，AI 在后台陪练一轮亲子沟通——考后怎么开口、孩子拒谈怎么办、吵完怎么修复。AI 不联系孩子、不诊断、不批改，只陪家长练。

## 怎么装

这个技能只有一个 `SKILL.md` 文件，没有脚本、不联网，任何支持 SKILL.md 技能格式的 AI 工具都能用。

**第 1 步（所有工具通用）**：新建一个文件夹，名字必须是 `parent-communication-coach`，把本仓库的 `SKILL.md` 放进去。
> 注意：从 GitHub 点 “Download ZIP” 解压出来的文件夹会叫 `parent-communication-coach-main`，要把 `-main` 删掉。

**第 2 步：按你用的工具放到对应位置**

| 你用的工具 | 放到哪里 | 怎么调用 |
|---|---|---|
| Codex（CLI / App） | `~/.agents/skills/` | 新对话输入 `$parent-communication-coach 开始陪练` |
| Cursor 等读 `~/.agents/skills/` 的工具 | `~/.agents/skills/` | 直接描述需求，或点名技能 |
| Claude Code | `~/.claude/skills/` | 输入 `/parent-communication-coach`，或直接描述需求 |
| Claude App / 网页版 | 把文件夹压缩成 zip，在设置的技能页上传 | 直接描述需求，Claude 会自动调用 |
| 其他支持 SKILL.md 的工具 | 该工具的技能目录 | 按该工具说明 |

`~` 指你的用户主目录（Mac：`/Users/你的用户名`；Windows：`C:\Users\你的用户名`）。放好后**新开一个对话**才会生效。

## 边界

只用匿名事实和必要的一两句对话，不需要提供姓名、学校、成绩单或录音。示例均为虚构。

Math1Road · 教数学的陈老师｜讲座《我是怎么用AI辅助孩子学习的》配套材料
