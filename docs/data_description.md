# Data Description and Codebook

## Overview

This document provides detailed descriptions of all variables in the survey dataset.

**Dataset**: survey_data.csv  
**Sample Size**: 200 respondents  
**Data Collection**: May 2025  
**Missing Data**: None (all questions required)

---

## Variable List

### Demographic Variables

| Variable Name | Description | Type | Values | Notes |
|--------------|-------------|------|--------|-------|
| `ID` | Respondent ID | Numeric | 1-200 | Unique identifier |
| `Gender` | Gender | Categorical | 1=Male, 2=Female, 3=Other | - |
| `Age` | Age group | Categorical | 1=<18, 2=18-25, 3=26-35, 4=36-45, 5=46+ | - |
| `Occupation` | Occupation | Categorical | 1=Student, 2=Employee, 3=Freelancer, 4=Civil Servant, 5=Self-employed, 6=Other | - |
| `Income` | Monthly disposable income (CNY) | Categorical | 1=<2000, 2=2000-5000, 3=5001-8000, 4=8001-12000, 5=>12000 | - |
| `Shopping_Freq` | Online shopping frequency | Categorical | 1=Almost daily, 2=2-3 times/week, 3=Once/week, 4=2-3 times/month, 5=Once/month or less | - |

---

### AI Recommendation Features

**Scale**: 5-point Likert scale (1=Strongly Disagree, 5=Strongly Agree)

#### A. Recommendation Accuracy (RA)

| Variable | Item | Description |
|----------|------|-------------|
| `RA1` | Q7 | AI recommendation systems can accurately identify my shopping needs |
| `RA2` | Q8 | AI-recommended products usually match my interests and preferences |
| `RA3` | Q9 | AI recommendation systems understand my shopping habits |

#### B. Real-time Responsiveness (RT)

| Variable | Item | Description |
|----------|------|-------------|
| `RT1` | Q10 | AI recommendation systems respond quickly to my browsing behavior |
| `RT2` | Q11 | Recommendation content updates immediately based on my real-time actions |
| `RT3` | Q12 | AI recommendations capture my current shopping needs in a timely manner |

#### C. Emotional Interaction (EI)

| Variable | Item | Description |
|----------|------|-------------|
| `EI1` | Q13 | AI recommendation systems make me feel warm and friendly |
| `EI2` | Q14 | AI recommendation copy and expressions resonate with me emotionally |
| `EI3` | Q15 | AI recommendation systems feel like communicating with a friend who understands me |

---

### Psychological Cognition

**Scale**: 5-point Likert scale (1=Strongly Disagree, 5=Strongly Agree)

#### D. Perceived Personalization (PP)

| Variable | Item | Description |
|----------|------|-------------|
| `PP1` | Q16 | I feel AI recommendations are customized specifically for me |
| `PP2` | Q17 | AI recommendations make me feel valued by the platform |
| `PP3` | Q18 | AI recommendation systems understand my unique needs |

#### E. Emotional Resonance (ER)

| Variable | Item | Description |
|----------|------|-------------|
| `ER1` | Q19 | AI-recommended products often touch my emotions |
| `ER2` | Q20 | I feel pleased when seeing AI-recommended products |
| `ER3` | Q21 | AI recommendations evoke emotional connections with products |

#### F. Privacy Concerns (PC)

| Variable | Item | Description |
|----------|------|-------------|
| `PC1` | Q22 | I worry that AI recommendation systems collect too much personal information |
| `PC2` | Q23 | AI recommendations make me feel my privacy is violated |
| `PC3` | Q24 | I feel uneasy about AI recommendation systems using my data |

---

### Impulse Buying Behavior (IB)

**Scale**: 5-point Likert scale (1=Strongly Disagree, 5=Strongly Agree)

| Variable | Item | Description |
|----------|------|-------------|
| `IB1` | Q25 | I often buy products I didn't plan to buy because of AI recommendations |
| `IB2` | Q26 | I often place orders immediately when seeing AI-recommended products |
| `IB3` | Q27 | AI recommendations make me feel "I need to buy it now" |
| `IB4` | Q28 | I buy AI-recommended products without sufficient consideration |

---

### Impulsive Traits (IT)

**Scale**: 5-point Likert scale (1=Strongly Disagree, 5=Strongly Agree)

| Variable | Item | Description |
|----------|------|-------------|
| `IT1` | Q29 | I am an impulsive person |
| `IT2` | Q30 | I often make impromptu decisions when shopping |
| `IT3` | Q31 | I find it hard to resist buying temptations |
| `IT4` | Q32 | I often shop on a whim |

---

## Data Quality

### Screening Criteria

Respondents must meet all of the following criteria:
- Age 18 or above
- Have online shopping experience
- Have used AI recommendation features on e-commerce platforms

### Quality Control

- Minimum response time: 60 seconds
- IP restriction: One response per IP address
- Device restriction: One response per device
- Logic check: Responses must be internally consistent

---

## Composite Scores

For analysis, composite scores can be calculated by averaging items within each construct:

- **Accuracy Score** = Mean(RA1, RA2, RA3)
- **Real-time Score** = Mean(RT1, RT2, RT3)
- **Emotional Interaction Score** = Mean(EI1, EI2, EI3)
- **Perceived Personalization Score** = Mean(PP1, PP2, PP3)
- **Emotional Resonance Score** = Mean(ER1, ER2, ER3)
- **Privacy Concerns Score** = Mean(PC1, PC2, PC3)
- **Impulse Buying Score** = Mean(IB1, IB2, IB3, IB4)
- **Impulsive Traits Score** = Mean(IT1, IT2, IT3, IT4)

---

## Notes

- All Likert scale items range from 1 (Strongly Disagree) to 5 (Strongly Agree)
- Higher scores indicate stronger agreement with the statement
- For Privacy Concerns, higher scores indicate greater concern
- Missing data: None (all questions were required)

---

**Last Updated**: May 2025
