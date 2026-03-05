# Smart Money Scoring Methodology

## Score Calculation

Total Score = Weighted sum of 6 factors (0-100 each)

### Factor 1: Trading P&L (Weight: 25%)
| Score Range | Criteria |
|------------|---------|
| 80-100 | Consistent profits >50% over 90d, positive Sharpe ratio |
| 60-79 | Net profitable, win rate >55%, good risk-adjusted returns |
| 40-59 | Breakeven or slightly profitable, mixed results |
| 20-39 | Net loss, but some winning trades show skill |
| 0-19 | Significant losses, no clear edge |

### Factor 2: Early Entry (Weight: 20%)
| Score Range | Criteria |
|------------|---------|
| 80-100 | Frequently in first 5% of buyers for tokens that 10x+ |
| 60-79 | Often early (first 20%), good hit rate on new protocols |
| 40-59 | Sometimes early, sometimes late, average timing |
| 20-39 | Usually late to trends, buys after major pumps |
| 0-19 | Consistently buys tops, last-in pattern |

### Factor 3: Risk Management (Weight: 20%)
| Score Range | Criteria |
|------------|---------|
| 80-100 | Uses stop-losses, diversified, never all-in, manages leverage well |
| 60-79 | Generally careful, some diversification, limits exposure |
| 40-59 | Mixed discipline, occasional oversized positions |
| 20-39 | Poor risk control, concentrated bets, high leverage |
| 0-19 | Reckless, all-in trades, liquidation history |

### Factor 4: Protocol Selection (Weight: 15%)
| Score Range | Criteria |
|------------|---------|
| 80-100 | Only blue-chip audited protocols, avoids scams |
| 60-79 | Mostly reputable protocols, rare risky interactions |
| 40-59 | Mix of good and questionable protocols |
| 20-39 | Frequent interaction with unaudited/risky contracts |
| 0-19 | History of interacting with known scam/rug contracts |

### Factor 5: Consistency (Weight: 10%)
| Score Range | Criteria |
|------------|---------|
| 80-100 | Steady performance across bull/bear, low variance |
| 60-79 | Good in one market condition, decent in others |
| 40-59 | Performance varies significantly by market condition |
| 20-39 | Only profitable in bull markets |
| 0-19 | Erratic, no consistent pattern, looks like gambling |

### Factor 6: On-Chain Hygiene (Weight: 10%)
| Score Range | Criteria |
|------------|---------|
| 80-100 | Gas-efficient, uses limited approvals, revokes old approvals |
| 60-79 | Generally clean, reasonable gas management |
| 40-59 | Some unlimited approvals, average gas awareness |
| 20-39 | Many unlimited approvals, wasteful gas usage |
| 0-19 | Dangerous approval patterns, likely exposed to approval exploits |

## Rating Thresholds

| Score | Rating | Copy-Trade Suitability |
|-------|--------|----------------------|
| 85-100 | Legendary 🏆 | HIGH — with caution, never blindly |
| 70-84 | Expert 🧠 | MEDIUM-HIGH — selective following |
| 55-69 | Skilled ⭐ | MEDIUM — study patterns, don't copy |
| 40-54 | Average 📊 | LOW — nothing to learn here |
| 0-39 | Novice 🌱 | NOT RECOMMENDED |

## Wallet Type Classification Criteria

| Type | Primary Signal | Secondary Signals |
|------|---------------|-------------------|
| 🐋 Whale | Portfolio >$1M | Large single trades, moves markets |
| 🧠 Smart Money | Consistent alpha | Early entries, high win rate, good risk mgmt |
| 🏦 Institution | Multi-sig wallet | Systematic trades, large AUM, known labels |
| 🤖 Bot/MEV | >50 tx/day | Sandwich patterns, arb, consistent tiny profits |
| 🏛️ DAO Treasury | Governance contract | Proposal execution, multi-sig, treasury ops |
| 💎 Diamond Hands | Avg hold >6mo | Low tx frequency, accumulation pattern |
| 🔄 Active Trader | >5 swaps/week | Position rotation, trend following |
| 🌱 Retail | Portfolio <$10K | Follows trends, inconsistent size, FOMO patterns |
| 🌾 Yield Farmer | Frequent farm entries | Moves between protocols chasing yield |
| 🎨 NFT Trader | >50% NFT activity | Mint participation, floor sweeps, flip patterns |
