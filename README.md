# Pornography, Self-Control & Productivity Among Young Adults

### A Mediation and Developmental Analysis

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chukwuka%20Odey-blue)](https://linkedin.com/in/chukwuka-odey)
![Sample](https://img.shields.io/badge/Sample-250%20respondents-green)

---

## Headline Finding

> **Pornography use is linked to lower productivity — but only because it erodes self-control.**
>
> When self-control is accounted for, the direct effect of pornography on productivity disappears entirely.

---

## Study at a Glance

![Study Overview](dashboard/Infographics.png)

---

## The Mediation Model

![Mediation Model](figures/mediation.png)

---

## Research Objectives and Findings

A cross-sectional survey of **250 young adults (aged 18+)** from a culturally diverse international sample.

---

### Objective 1 — Pornography Consumption and Productivity

**Test:** Spearman's rank-order correlation

| Statistic | Value |
| :--- | :--- |
| Correlation (rs) | **-0.157** |
| p-value | **0.013** |
| Sample (N) | 250 |

Higher consumption is associated with slightly lower productivity, but the effect is small.

---

### Objective 2 — The Mediating Role of Self-Control

**Test:** Bootstrapped mediation analysis (5,000 resamples)

| Path | Beta | p-value | 95% CI |
| :--- | :--- | :--- | :--- |
| Path A: Porn to Self-Control | **-0.145** | < 0.001 | — |
| Path B: Self-Control to Productivity | **1.297** | < 0.001 | — |
| Direct Effect (c') | 0.032 | 0.681 | — |
| **Indirect Effect** | **-0.188** | — | **[-0.287, -0.098]** |

Self-control **fully mediates** the relationship. This is the study's most important finding.

---

### Objective 3 — Age of First Exposure

**Test:** One-way ANOVA with Tukey HSD post-hoc tests

| Outcome | F-statistic | p-value | Result |
| :--- | :--- | :--- | :--- |
| Self-Control | **F(4, 218) = 4.12** | **0.003** | Significant |
| Productivity | **F(4, 218) = 3.23** | **0.013** | Significant |
| Porn Consumption | F(4, 214) = 1.52 | 0.198 | Not significant |

**74% of respondents were first exposed before age 18.** Accidental online discovery was the most common pathway (27.2%).

---

### Objective 4 — Gender Differences

**Test:** Mann-Whitney U and Welch's t-tests

| Variable | Female M (SD) | Male M (SD) | p-value |
| :--- | :--- | :--- | :--- |
| Pornography Frequency | 0.85 (1.00) | 2.04 (1.70) | **< 0.001** |
| Self-Control | 3.12 (0.75) | 3.05 (0.77) | 0.485 |
| Productivity | 5.94 (1.91) | 6.28 (1.93) | 0.162 |

Males consume more, but outcomes are similar across genders.

---

## Hypotheses Summary

| Hypothesis | Result |
| :--- | :--- |
| **H1:** Pornography consumption is significantly related to productivity | Supported |
| **H2:** Self-control significantly mediates the relationship | Supported |
| **H3a:** Age of exposure is associated with self-control | Supported |
| **H3b:** Age of exposure is associated with productivity | Supported |
| **H3c:** Age of exposure is associated with current consumption | Not Supported |
| **H4a:** Gender differences in pornography consumption | Supported |
| **H4b:** Gender differences in self-control | Not Supported |
| **H4c:** Gender differences in productivity | Not Supported |

---

## Methodology

| Element | Detail |
| :--- | :--- |
| **Design** | Cross-sectional survey |
| **Sample** | 250 young adults (aged 18+) |
| **Measures** | Pornography frequency, self-control (alpha = 0.743), productivity, age of first exposure |
| **Analysis** | Python 3.x — pandas, numpy, scipy, statsmodels, pingouin |
| **Significance** | alpha = 0.05 |

---

## Repository Structure

- `data/` — Anonymised survey data
- `notebooks/` — Python analysis code
- `reports/` — Executive summary and manuscript
- `dashboard/` — Power BI dashboard and infographic
- `figures/` — Statistical figures

---

## Citation

Odey, C. (2026). *Pornography Consumption, Self-Control, and Daily Productivity Among Young Adults: A Cross-Sectional Mediation and Developmental Analysis*. GitHub.

---

## Contact

**Chukwuka Odey** — [LinkedIn](https://linkedin.com/in/chukwuka-odey)
