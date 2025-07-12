# Studying the Impact of Meditation Apps on Sleep Quality

## Overview

This project, conducted as part of the CS 535 course, investigates the impact of meditation mobile applications on sleep quality among a small cohort of participants. Using a mixed-methods approach, the study combines quantitative sleep metrics (e.g., sleep onset latency and sleep efficiency) with qualitative insights from participant interviews to explore the effectiveness of guided voice and music-based meditation techniques. The study was conducted over a 10-day period with a within-subjects quasi-experimental design, including baseline and intervention phases, and utilized smartwatch data and survey responses for analysis.

## Project Objectives

The primary objectives of this project were to:
1. Evaluate how meditation sessions before bed influence **sleep onset latency** and **sleep efficiency** over a short-term period.
2. Assess participants' **perceived sleep quality** on nights with and without app usage and its alignment with objective sleep metrics.
3. Investigate **user preferences** for meditation techniques (guided voice vs. music-based) and their alignment with sleep goals.

## Methodology

### Study Design
- **Type**: Convergent Parallel Mixed-Methods Design
- **Participants**: 4 young adults (ages 22–24, 2 males, 2 females) with no diagnosed sleep disorders.
- **Duration**: 10 days per participant, split into:
  - **Baseline Phase (Days 1–4)**: No meditation app usage, capturing normal sleep patterns.
  - **Intervention Phase (Days 5–10)**: Participants used a meditation app before sleep, with:
    - **Forced Modality Days**: Specific days for guided voice or music-based meditation.
    - **User Preference Days**: Participants chose their preferred meditation type.
- **Data Collection**:
  - **Pre-Study Survey**: Gathered demographic details, sleep patterns, and meditation experience.
  - **Daily Surveys**: Captured subjective sleep quality and meditation usage.
  - **Smartwatch Logs**: Recorded objective sleep metrics (sleep onset latency, sleep efficiency).
  - **Post-Study Interviews**: Semi-structured interviews to explore user experiences and preferences.
- **Analysis**:
  - **Quantitative**: Non-parametric tests (Wilcoxon Signed-Rank Test, Spearman Rank Correlation) due to small sample size (N=4).
  - **Qualitative**: Reflexive thematic analysis using Atlas.ti to identify themes from interview transcripts.
  - **Mixed-Methods Integration**: Triangulated quantitative trends with qualitative insights for a comprehensive understanding.

### Key Variables
- **Independent Variables**:
  - Meditation Condition: Baseline (no meditation) vs. Intervention (meditation app use).
  - Meditation Type: Guided Voice vs. Music-Based (within intervention phase).
- **Dependent Variables**:
  - Sleep Onset Latency (minutes).
  - Sleep Efficiency (%).
  - Self-Reported Sleep Quality (1–10 scale).
  - User Preference for Meditation Techniques.
  - Other Subjective Measures (e.g., feeling well-rested).

## Key Findings

### Quantitative Findings
- **Sleep Onset Latency**: Decreased from a median of 58.62 minutes (baseline) to 23.92 minutes (intervention), with a very large effect size (r=0.913), though not statistically significant (p=0.0625) due to low statistical power (N=4).
- **Sleep Efficiency**: Increased from a median of 81.35% (baseline) to 90.97% (intervention), with a very large effect size (r=0.913), but also not statistically significant (p=0.0625).
- **Meditation Type**: Guided voice meditation showed a descriptive advantage over music-based meditation for reducing sleep latency (p=0.0625, r=0.913).
- **Correlations**: Significant correlations between objective metrics and subjective sleep quality:
  - Lower latency correlated with higher self-reported quality (rho=-0.583, p<0.05).
  - Higher efficiency correlated with higher self-reported quality (rho=0.74, p<0.05).

### Qualitative Findings
Five main themes emerged from thematic analysis:
1. **Improved Sleep Quality**: Participants reported faster sleep onset, more solid sleep, and feeling more refreshed on meditation nights.
2. **Preference for Guided Voice**: All participants preferred guided voice meditation for its structure and focus, perceiving it as more effective.
3. **Pre-Sleep Relaxation**: Meditation induced calmness and reduced racing thoughts, facilitating sleep.
4. **Practical Barriers**: Challenges included time constraints, tiredness, and environmental noise.
5. **Positive Future Intentions**: Participants expressed interest in continuing meditation, with suggestions for app improvements (e.g., shorter sessions, auto-stop functionality).

### Mixed-Methods Integration
- **Convergence**: Quantitative trends (reduced latency, increased efficiency) aligned with qualitative perceptions of improved sleep quality.
- **Explanation**: Preference for guided voice was explained by its ability to enhance focus and reduce mind-wandering.
- **Context**: Qualitative insights highlighted relaxation as the primary mechanism and identified real-world barriers affecting app usage.

## Results and Visualizations
- **Box Plots**: Compare sleep onset latency and efficiency between baseline and intervention phases (`visualizations/fig1_latency_boxplot.png`, `visualizations/fig3_efficiency_boxplot.png`).
- **Paired Plots**: Show individual participant changes (`visualizations/fig2_latency_paired.png`, `visualizations/fig4_efficiency_paired.png`).
- **Correlation Analysis**: Visualize relationships between objective and subjective sleep metrics (`visualizations/fig7_correlation.png`).

## Limitations
- **Small Sample Size (N=4)**: Limits statistical power and generalizability.
- **Consumer-Grade Smartwatches**: Less precise than clinical polysomnography.
- **No Placebo Control**: Prevents definitive causal claims.
- **Order Effects**: Baseline always preceded intervention, potentially introducing bias.
- **Demographic Scope**: Limited to young adults (22–24 years), reducing applicability to broader populations.

## Future Work
- Replicate with a larger, more diverse sample to confirm findings.
- Extend study duration (e.g., 4–8 weeks) to assess long-term effects.
- Test participant-suggested app features (e.g., shorter sessions, auto-stop).
- Investigate physiological mechanisms (e.g., heart rate variability).
- Compare different guided meditation types (e.g., body scan vs. visualization).