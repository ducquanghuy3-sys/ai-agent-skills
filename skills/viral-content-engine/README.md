# 🔥 Viral Content Engine / 爆款内容引擎

> One topic → multi-platform viral content. 小红书, Twitter, LinkedIn, 公众号, Threads.
>
> 一个主题 → 多平台爆款内容，即发即用。

## Install / 安装

**Claude.ai:** Settings → Skills → Upload → drag `SKILL.md`

**Claude Code / Codex / Cursor:**
```bash
cp -r viral-content-engine/ .claude/skills/
```

## What You Get / 输出内容

- 📕 **小红书**: 种草笔记 + hooks + emoji排版 + 标签 + 封面建议
- 🐦 **Twitter/X**: 单条推文或完整Thread
- 💼 **LinkedIn**: 专业故事型帖子
- 📱 **公众号**: 长文 + 反转开头 + 金句
- 🧵 **Threads**: 轻松对话风格

Plus: 3 hook variants · posting time suggestions · A/B test plan

## Example Prompts / 示例

```
Create viral content about "AI productivity tools" for Xiaohongshu and Twitter
```
```
写一篇关于"远程办公效率"的小红书爆款笔记和LinkedIn帖子
```

## Files / 文件

```
viral-content-engine/
├── SKILL.md
└── references/
    ├── platform-algorithms.md   # How each platform's algo works
    └── hook-database.md         # 50+ hook templates per platform
```

## API

```bash
curl -X POST https://web-production-1873.up.railway.app/api/skill/viral-content \
  -H "Content-Type: application/json" \
  -d '{"user_id":"your_id","topic":"AI效率工具","platforms":["xiaohongshu","twitter"]}'
```

⭐ [More skills / 更多技能 →](https://github.com/ducquanghuy3-sys/ai-agent-skills)
