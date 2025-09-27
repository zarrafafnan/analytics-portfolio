# 🚨 Toronto Robbery Regression: Data-Driven Crime Insights for Urban Safety

## Executive Summary
This project uses Kaggle's Toronto Robbery data (2014–mid-2022) to uncover how location types and geography impact robbery rates, guiding public safety policy using multiple regression analysis.

## Key Findings
| Variable         | Coefficient | Impact/Interpretation                              | p-value   |
|------------------|-------------|---------------------------------------------------|-----------|
| HighCrimeZone    | -3.8        | Fewer robberies in high-crime zones—potentially due to policing or reporting differences | 0.0021    |
| PremApartment    | -4.6        | Apartment buildings are significantly safer        | 0.0083    |
| PremCommercial   | 19.8        | Commercial areas show increased robbery risk        | 0.0001    |
| PremOutside      | 55.2        | Outdoor/public spaces are the highest risk         | 0.0001    |
| Intercept        | 18.8        | Baseline expected robberies                        | 0.0001    |

## Methodology
- Multiple regression in SAS
- Dummy encoding of categorical predictors
- Aggregated/cleaned by time and location
- Diagnostic checks: good sample size, minimal multicollinearity, residuals not normal but model robust
- Model explains ~64% of variance in robbery counts (R² ~ 0.64)

## Business Recommendations
- Prioritize patrols in commercial/outdoor spaces
- Improve safety with lighting, visibility, surveillance in high-risk places
- Replicate successful safety measures from apartments/high-crime zones
- Study reporting bias and investigate underreported areas

## Limitations & Next Steps
- Reporting bias may affect findings
- Residual non-normality—caution with extremes/outliers
- Missing richer contextual variables (e.g. socioeconomic, police response)
- Future work: add more predictors, validate across time, benchmark interventions

## Data & Files
- [Kaggle Dataset](https://www.kaggle.com/datasets/hayawi/toronto-robbery-2014-to-20220630)
- Analysis file: `3010U_final_assignment.pdf`
