# Capstone Project Hub: The "Office Apocalypse" Algorithm

## Overview

This project develops a machine learning model to predict the likelihood of long-term vacancy for commercial office buildings in New York City, addressing the "office apocalypse" caused by the shift to remote and hybrid work post-COVID-19.

## Problem Statement

The COVID-19 pandemic has fundamentally altered work culture, popularizing remote and hybrid models that significantly reduce the demand for traditional office space in NYC. This threatens to create a "commercial vacancy crisis," potentially leading to billions of dollars in lost property value, decreased city tax revenue, and the decay of business districts that rely on office worker foot traffic.

## Goal

To develop a robust machine learning model that accurately predicts the likelihood of long-term vacancy for commercial office buildings in NYC, providing actionable insights for urban planning and real estate strategy.

## Key Features

- **Interactive Dashboard**: Track project progress across multiple phases with dynamic task management.
- **Project Documentation**: Comprehensive overview of methodology, datasets, and team information.
- **Model Demo**: Interactive tool to simulate vacancy risk predictions based on building features.
- **Results Visualization**: Showcase final model performance and key insights.

## Datasets Used

- **PLUTO and MapPLUTO**: Building-level data including year built, zoning, and square footage.
- **ACRIS**: Property transaction data for financial history.
- **DOB Permit Issuance**: Building permits signaling investment and renovation.
- **Storefront Vacancy Data**: Ground-truth labels for storefront vacancy.
- **MTA Turnstile Data**: Proxy for neighborhood economic activity and foot traffic.
- **NYC Legally Operating Businesses**: Insights into commercial ecosystems.

## Methodology

1. **Data Acquisition & Integration**: Merge data from multiple sources using BBL identifiers.
2. **Feature Engineering**: Create 20+ engineered features capturing building age, transactional history, geospatial factors, etc.
3. **Modeling**: Train baseline (Logistic Regression) and advanced models (XGBoost, Random Forest).
4. **Evaluation**: Use temporal train-test split with AUC, Precision, and Recall metrics.
5. **Interpretation**: Apply SHAP for model explainability.

## Team

- **Ibrahim Denis Fofanah**: Project Lead & Data Scientist
- **Bright Arowny Zaman**: Data Lead
- **Jeevan Hemanth Yendluri**: Modeling Lead

## Usage

This is a static HTML application. Simply open `index.html` in a web browser to explore the dashboard.

## Repository Structure

- `index.html`: Main application file
- `presentattion/index.html`: Presentation slides
- Other HTML files: Backups and variations

## Technologies Used

- HTML5, CSS3 (Tailwind CSS)
- JavaScript (Vanilla JS)
- Git for version control

## License

This project is for educational purposes as part of a Master's degree capstone project.

## Contact

For questions or collaboration, please reach out to the team members listed above.

---

*This project is part of the Master of Data Science program at Peace University.*