# 📝 SEO Article Architect / SEO文章架构师

> Keyword in → publish-ready, rank-ready article out. Google + Baidu optimized.
>
> 输入关键词 → 输出发布即排名的SEO长文。Google + 百度双优化。

## Install / 安装

**Claude.ai:** Settings → Skills → Upload → drag `SKILL.md`

**Claude Code / Codex / Cursor:**
```bash
cp -r seo-article-architect/ .claude/skills/
```

## What You Get / 输出内容

- Full article (1,500-4,000 words) / 完整文章
- Meta title (<60 chars) + meta description (<160 chars)
- Schema markup (FAQ / HowTo / Article / Review)
- Internal + external linking strategy / 内链外链策略
- Featured snippet optimization / 精选摘要优化
- Baidu-specific optimization for Chinese / 百度专项优化

## Example Prompts / 示例

```
Write an SEO article targeting "best project management tools 2026"
```
```
围绕"2026年最好用的项目管理工具"写一篇SEO优化文章
```

## Files / 文件

```
seo-article-architect/
├── SKILL.md
└── references/
    └── seo-checklist.md   # Google + Baidu technical SEO checklist
```

## API

```bash
curl -X POST https://web-production-1873.up.railway.app/api/skill/seo-article \
  -H "Content-Type: application/json" \
  -d '{"user_id":"your_id","keyword":"best project management tools 2026"}'
```

⭐ [More skills / 更多技能 →](https://github.com/ducquanghuy3-sys/ai-agent-skills)
