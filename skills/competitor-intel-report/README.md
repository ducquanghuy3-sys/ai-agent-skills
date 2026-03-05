# 🕵️ Competitor Intel Report / 竞品情报分析

> Company name → professional competitive intelligence you can act on.
>
> 输入公司名 → 输出可直接执行的竞品情报报告。

## Install / 安装

**Claude.ai:** Settings → Skills → Upload → drag `SKILL.md`

**Claude Code / Codex / Cursor:**
```bash
cp -r competitor-intel-report/ .claude/skills/
```

## What You Get / 输出内容

- Executive summary / 执行摘要
- Product feature matrix / 功能对比矩阵
- Pricing & monetization teardown / 定价策略拆解
- Go-to-market analysis / 获客模式分析
- Customer sentiment / 用户口碑
- SWOT matrix / SWOT矩阵
- Strategic recommendations / 攻防策略建议
- Monitoring plan / 持续监控方案

## Example Prompts / 示例

```
Competitive analysis: Notion vs Obsidian, help me find my angle as a note-taking app
```
```
竞品分析：飞书 vs 钉钉 vs 企业微信，我在做协作工具，帮我找切入点
```

## Files / 文件

```
competitor-intel-report/
├── SKILL.md
└── references/
    └── analysis-frameworks.md   # Porter's 5, JTBD, Blue Ocean, Moat
```

## API

```bash
curl -X POST https://web-production-1873.up.railway.app/api/skill/competitor-intel \
  -H "Content-Type: application/json" \
  -d '{"user_id":"your_id","target":"Notion","my_company":"我的笔记产品"}'
```

⭐ [More skills / 更多技能 →](https://github.com/ducquanghuy3-sys/ai-agent-skills)
