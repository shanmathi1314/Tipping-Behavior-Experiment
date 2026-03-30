# Tipping Behavior Experiment

This repository contains an academic project completed for **BA 830 at Boston University**. The project examines whether higher default tip suggestions influence user tipping behavior in a simulated restaurant checkout setting.

## Project Overview

Digital payment systems often display suggested tip options, which may act as behavioral anchors. This project studies whether increasing those default tip percentages leads users to select higher tips.

We conducted a **randomized survey experiment** using a simulated restaurant payment scenario for a fixed **$16 meal**.

Participants were randomly assigned to one of two groups:
- **Control Group:** 15%, 18%, 20%, plus custom option  
- **Treatment Group:** 18%, 20%, 25%, plus custom option  

The primary outcome measured was the **tip percentage selected**. Additional demographic and behavioral variables were collected to improve estimation and explore differences across users.

## Research Question

How do higher default tip suggestions affect the tip percentage selected in a simulated restaurant checkout?

## Methodology

- Designed and implemented a randomized experiment using **Qualtrics**
- Cleaned and processed survey data to remove incomplete and invalid responses
- Conducted **Exploratory Data Analysis (EDA)** to understand patterns
- Estimated treatment effects using:
  - OLS regression
  - Regression with covariates
  - Heterogeneity analysis across user groups

Covariates included age, years lived in the U.S., service industry experience, and dining frequency.

## Key Findings

- Increasing default tip options did **not significantly change** average tipping behavior  
- Most responses clustered around **15%–18%** across both groups  
- The estimated treatment effect was close to zero  

## Business Insights

These findings suggest that simply increasing default tip percentages may not effectively influence user behavior.

More impactful strategies may include:
- Social norm messaging (e.g., “Most users tip 20%”)
- Interface and UX design improvements
- A/B testing different checkout experiences

## Academic Context

This project was completed as part of **BA 830 (Business Analytics)** at **Boston University** as a team-based academic project.

## Team Members

- Linh Le  
- TzuHsuan Liu  
- Kang Ni  
- Shanmathi Sivakumar  
- Hanchao Tang  

## Tools Used

- Python  
- pandas  
- statsmodels  
- Qualtrics  
- Google Colab  
