Statistical analysis of Spanish voting behavior using logistic, probit, ordinal, and multinomial regression in R.

# Voting Behavior Modeling in Spain

An R-based statistical analysis examining factors associated with voting
behavior in Spain, with particular attention to support for VOX and movement
across political blocs.

## Project Overview

This project uses survey data to examine how political attitudes,
demographic characteristics, and evaluations of government are associated
with voting behavior.

The analysis progresses from binary models to multicategory models while
testing whether the assumptions of each modeling approach are appropriate.

## Research Questions

The analysis examines whether voting behavior is associated with:

- Immigration attitudes
- Perceived cultural threat
- Government satisfaction
- Left-right ideology
- Education
- Age
- Gender
- Urban/rural residence

## Methods

Analysis was conducted in R using:

- Data cleaning and recoding
- Binary logistic regression
- Probit regression
- Predicted probabilities
- Cumulative link / ordinal regression
- Proportional-odds assumption testing
- Multinomial logistic regression
- Model interpretation and visualization

## Modeling Approach

The analysis began with binary logistic and probit models predicting
support for VOX.

An ordinal model was then used to examine movement across:

Left → Centre → Mainstream Right → VOX

Diagnostic testing indicated that the proportional-odds assumption did not
hold for all predictors. A multinomial model was therefore used to allow
relationships to differ across political groups.

## Key Findings

- Ideological self-placement was strongly associated with movement toward
  right-leaning political groups.
- Immigration anxiety was associated with VOX support in the binary model.
- Greater government satisfaction was associated with lower VOX support.
- Some demographic relationships weakened after political attitudes were
  controlled for.
- Model diagnostics showed that a single proportional-odds relationship
  was insufficient, motivating the multinomial specification.

## Skills Demonstrated

R • Statistical Modeling • Logistic Regression • Multinomial Regression •
Model Diagnostics • Data Visualization • Probability Interpretation •
Quantitative Research

## Project Files

- `analysis/` — R analysis
- `figures/` — selected visualizations
- `presentation/` — project presentation
- `paper/` — complete research paper
- `data/` — information about the source dataset

## Limitations

This is observational survey analysis and should not be interpreted as
establishing causal relationships. Future work could incorporate
longitudinal analysis and alternative model specifications.
