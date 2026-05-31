# FUTURE_DS_Task2

# Telco Customer Churn Analysis

## Overview
Analysis of customer churn patterns using IBM Telco Customer Churn dataset. Identifies key drivers of churn and provides actionable retention recommendations for subscription-based businesses.

## Key Findings

### Churn by Contract Type
| Contract | Churn Rate |
|----------|------------|
| Month-to-month | 43.1% |
| One year | 11.3% |
| Two year | 2.8% |

**Insight**: Month-to-month customers churn at 15x the rate of two-year contracts.

### Churn by Tenure
| Tenure | Churn Rate |
|--------|------------|
| 0-1 month | 62% |
| 2-3 months | 50% |
| 4-6 months | 48% |
| 7-12 months | 45% |
| 13-24 months | 42% |
| 25-48 months | 38% |
| 49+ months | 32% |

**Insight**: 62% of churn happens within the first month.

### Churn by Payment Method
| Payment Method | Churn Rate |
|----------------|------------|
| Electronic check | 45.1% |
| Mailed check | 18.9% |
| Bank transfer (auto) | 16.7% |
| Credit card (auto) | 15.2% |

**Insight**: Electronic check payers are 3x more likely to churn than auto-pay customers.

### Top Risk Segments
| Segment | Churn Rate |
|---------|------------|
| New customers (0-3 months) | 58.5% |
| Month-to-month + Fiber optic | 54.5% |
| Month-to-month + Electronic check | 53.6% |
| No security or tech support | 48.8% |

## Executive Recommendations

### Critical (30 days)
- **Month-to-month contracts**: Offer 10-15% discount for annual commitment
- **First-month churn**: Implement "First 30 Days Success Program" with automated onboarding
- **Electronic check payers**: Provide $5-10 credit for enabling auto-pay

### High Priority (60 days)
- **Fiber optic customers**: Investigate service quality vs. DSL
- **No security/tech support**: Bundle security with 30-day free trial
- **New customer drop-off**: Automated email sequence for first 30 days

### Strategic
- Make annual contract default option with month-to-month as premium (+20%)
- Create loyalty rewards at 6, 12, 18-month milestones
- Implement churn risk scoring for proactive retention offers

## Financial Impact (per 1,000 customers)

| Action | Churn Reduction | Annual Savings |
|--------|----------------|----------------|
| Convert 20% of month-to-month to annual | -8.6% | ~$74,000 |
| Reduce first-month churn by 50% | -31% | ~$267,000 |
| Convert 30% of electronic check to auto-pay | -9% | ~$77,000 |
| **Combined impact** | **-48.6%** | **~$418,000** |

*Based on average monthly charge of $74.40*

## Files
- `Customer_Churn.csv` - Raw dataset
- `Customer_Churn_cleaned.csv` - Cleaned dataset
- `churn_analysis.py` - Python analysis code
- `telco_churn_analysis_dashboard.png` - Dashboard visualization

