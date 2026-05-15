# AI-Powered Personalized Recommendations and Consumer Impulse Buying

## Research Overview

This repository contains data and analysis code for a research project examining the relationship between AI-powered personalized recommendation systems and consumer impulse buying behavior in e-commerce platforms.

## Research Questions

1. Do the core features of AI personalized recommendations (accuracy, real-time responsiveness, and emotional interaction) have a significant positive impact on consumers' impulse buying behavior?

2. Does consumer psychology and cognition play a mediating role between AI personalized recommendations and impulse buying?

3. Do consumers' impulsive traits moderate the relationship between AI personalized recommendations and impulse buying?

## Repository Structure

```
├── README.md                           # Project overview
├── data/
│   └── survey_data.csv                # Survey data (N=200)
├── notebooks/
│   └── data_analysis.ipynb            # Data analysis code
└── docs/
    └── data_description.md            # Variable descriptions and codebook
```

## Data Collection

- **Method**: Online survey via third-party survey service and personal network distribution
- **Sample Size**: 200 valid responses
- **Target Population**: Online shoppers aged 18+ who have experience with AI recommendation systems
- **Data Collection Period**: May 2025

## Variables

### Independent Variables
- AI Recommendation Accuracy (3 items, 5-point Likert scale)
- Real-time Responsiveness (3 items, 5-point Likert scale)
- Emotional Interaction (3 items, 5-point Likert scale)

### Mediating Variables
- Perceived Personalization (3 items, 5-point Likert scale)
- Emotional Resonance (3 items, 5-point Likert scale)
- Privacy Concerns (3 items, 5-point Likert scale)

### Dependent Variable
- Impulse Buying Behavior (4 items, 5-point Likert scale)

### Moderating Variable
- Impulsive Traits (4 items, 5-point Likert scale)

### Control Variables
- Age, Gender, Occupation, Income, Shopping Frequency

## Analysis Methods

- Descriptive Statistics
- Reliability Analysis (Cronbach's Alpha)
- Correlation Analysis
- Data Visualization

## Requirements

```
python >= 3.7
pandas >= 1.3.0
numpy >= 1.21.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
scipy >= 1.7.0
```

## How to Run

1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Open `notebooks/data_analysis.ipynb` in Jupyter Notebook or Google Colab
4. Run all cells

## Author

Momoe
May 2025

## License

This project is for academic purposes only.
