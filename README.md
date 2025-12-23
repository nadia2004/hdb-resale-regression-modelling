# HDB Resale Price Regression Model 
This project develops and validates a robust linear regression model to predict HDB resale prices using 2021 government data. The analysis focuses on feature selection, transformation, model diagnostics, and validation, with the goal of identifying key price drivers while ensuring model adequacy.

# Project Overview

This project analyzes 11,527 HDB resale transactions (2021) to understand the key drivers of resale prices. Using exploratory data analysis, feature selection, and log-linear regression, the model evaluates the impact of flat characteristics, location, and remaining lease while rigorously checking for violations of statistical assumptions to ensure model adequacy and reliable results. 

The final model has a strong predictive performance (R² ≈ 0.83) and satisfies all linear regression assumptions, making it both interpretable and statistically reliable.

# Key Insights (ranked by influence)
- **Flat model:** The most influential categorical predictor of resale price.
- **Town region (distance from central area):** Flats closer to central regions (CCR > RCR > OCR) command higher prices. Interestingly, this is a stronger predictor than flat type, meaning smaller flats in prime locations can cost more than larger flats in outlying areas.
- Flat type (number of rooms): Flats with more rooms generally have higher resale prices.
- Storey range: Higher-floor flats tend to sell for more.
- Remaining lease: Longer remaining lease moderately increases resale price; the limited impact is partly due to most flats having >40 years remaining.
- Flat size (floor area): Larger flats increase resale prices, though its effect is less pronounced than initially expected.

Overall, flat model, type, location, and floor are the primary determinants of resale price. 
