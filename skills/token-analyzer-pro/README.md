# 🪙 Token Analyzer Pro / 代币分析专家

> Institutional-grade crypto token analysis. Input a token name, get a full research report.
> 
> 机构级加密代币分析。输入代币名称，输出完整投研报告。

## Install / 安装

**Claude.ai:** Settings → Skills → Upload → drag `SKILL.md`

**Claude Code / Codex / Cursor:**
```bash
# Copy this folder to your skills directory
cp -r token-analyzer-pro/ .claude/skills/
```

## What You Get / 输出内容

- Tokenomics scorecard (5 dimensions, each /10) / 代币经济学评分
- On-chain health metrics / 链上健康度
- Risk matrix (contract / market / project / regulatory) / 风险矩阵
- Competitive positioning / 竞品对标
- Bull/bear/base case verdict / 看涨看跌结论

## Example Prompts / 示例

```
Analyze ARB (Arbitrum) — full investment research report
```
```
帮我分析 SOL（Solana），出一份完整的代币分析报告
```

## Files / 文件

```
token-analyzer-pro/
├── SKILL.md                              # Core instructions
└── references/
    ├── report-template.md                # EN/CN output templates
    └── valuation-frameworks.md           # 7 crypto valuation methods
```

## API / 付费接口

Don't want to use Claude? Call the API directly — $0.003/call:

```bash
curl -X POST https://web-production-1873.up.railway.app/api/skill/token-analyzer \
  -H "Content-Type: application/json" \
  -d '{"user_id": "your_id", "token": "ARB"}'
```

不想用Claude？直接调API — 每次¥0.02：[API文档 →](https://web-production-1873.up.railway.app/api/skills)

---

⭐ [More skills / 更多技能 →](https://github.com/ducquanghuy3-sys/ai-agent-skills)
