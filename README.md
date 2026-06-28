# Educational Attainment and Urban Poverty: Bangalore

A Python-based analysis of the education-employment disconnect in Bangalore using economic theory and real data.

## Research Question

Why does Bangalore — with an 88% literacy rate and rapidly rising education levels — continue to face persistent urban poverty and underemployment?

## Theoretical Frameworks Applied

- **Human Capital Theory** (Becker) — education raises productivity and wages
- **Job Signalling Theory** (Spence) — degrees signal ability to employers  
- **Wage-Schooling Locus** (Mincer) — more schooling = higher earnings

All three frameworks are tested against Bangalore's actual labour market data — and all three show significant deviations.

## Charts Produced

| Chart | What it shows |
|---|---|
| `chart1_lfpr_wpr.png` | LFPR & WPR by education level — diploma spike vs graduate dip |
| `chart2_regression.png` | OLS regression: LFPR predicts WPR (R² = 0.99) |
| `chart3_mys_wpr.png` | Rising schooling, falling employment (2018–2023) |
| `chart4_wage_schooling.png` | Theory vs Bangalore reality — non-monotonic locus |
| `chart5_skill_mismatch.png` | Primary survey: 71.4% report education-job skill gap |

## Key Findings

- Diploma holders have **87.8% LFPR** vs only **62.2% for graduates** — vocational training outperforms formal degrees
- Mean Years of Schooling rose from 6.98 to 7.46 (2018–2023), yet WPR *fell* from 53.1% to 40.1%
- 71.4% of survey respondents feel a mismatch between education and job requirements
- The Wage-Schooling Locus is **non-monotonic** in Bangalore — contradicting Mincer's model

## Data Sources

- MoSPI — Periodic Labour Force Survey (PLFS) Annual Reports
- Karnataka State Statistics / Karnataka Economic Survey 2022-23
- Primary survey, March 2025 (n = 28, stratified purposive sampling)

## How to Run

```bash
pip install pandas matplotlib scipy numpy jupyter
jupyter notebook education_urban_poverty.ipynb
```

## Academic Context

Originally submitted as a group assignment for ECO209-4 (Public Economics) at Christ (Deemed to Be University), Bengaluru. This version extends the original work with Python visualizations and a structured analytical framework.
