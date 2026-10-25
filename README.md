# Hybrid Machine Learning Framework for Animal-Level Live-Weight Forecasting

## Overview

This repository supports the research manuscript entitled:

**Hybrid Machine Learning Framework for Animal-Level Live-Weight Forecasting in Grazing-Based Production Systems**

The research investigates hybrid machine learning architectures for forecasting individual cattle live weight under irregular observation conditions in grazing-based production systems.

The study integrates animal demographic information, automated live-weight observations, and lagged environmental predictors into structured forecasting datasets.

## Research Objectives

The research addresses four primary objectives:

1. Develop a hybrid machine learning framework for animal-level live-weight forecasting using structured livestock observations.
2. Compare hybrid forecasting architectures based on predictive accuracy and computational efficiency.
3. Evaluate forecasting robustness across prediction horizons and observation densities.
4. Investigate the contributions of biological and environmental predictors to forecasting performance.

## Dataset

The research uses livestock observations collected between 2022 and 2024 at Charles Sturt University Farm, Wagga Wagga, Australia.

The modelling dataset contains:

- 683 cattle after data preprocessing and quality control.
- 19,264 weekly observations.
- Animal demographic variables, including age, genotype, and sex.
- Automated live-weight observations.
- Lagged environmental variables, including rainfall and temperature.

## Forecasting Architectures

Four hybrid machine learning architecture families are investigated:

- **Residual hybrid architectures:** Base machine learning models combined with neural networks for residual correction.
- **Stacked hybrid architectures:** Multiple base learners integrated through neural-network meta-learning.
- **Cascade hybrid architectures:** Sequential learning components incorporating intermediate model predictions.
- **Ensemble-assisted architectures:** Ensemble learning integrated with neural-network components.

Comparative forecasting approaches include persistence, Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU). ARIMA is separately evaluated using aggregated herd-level observations.

## Forecasting and Evaluation

Forecasting horizons include 1, 2, 4, 8, 12, and 24 weeks.

Model evaluation includes animal-disjoint hold-out testing and forecasting performance measures such as R², RMSE, MAE, NSE, KGE, and PBIAS, as applicable.

Animal-level predictions are also aggregated into weekly herd-level trajectories for separate evaluation.

## Data and Model Availability

The research datasets and forecasting models are maintained in Google Drive.

Access is restricted and may be granted to researchers upon reasonable request, subject to approval and applicable data-sharing conditions.

**Dataset access:** [Google Drive Dataset Link]

**Model access:** [Google Drive Model Link]

Researchers should contact the corresponding author to request access.

## Reproducibility

The manuscript describes model development and evaluation using Python, Scikit-learn, TensorFlow, and XGBoost.

Access to the underlying datasets and implementation files is subject to the stated sharing conditions.

## Corresponding Author

**Muhammad Riaz Hasib Hossain**

Charles Sturt University, Australia

Email: muhossain@csu.edu.au

## Publication

**Manuscript:** Hybrid Machine Learning Framework for Animal-Level Live-Weight Forecasting in Grazing-Based Production Systems

**Journal:** Computers and Electronics in Agriculture

**Publication status:** Manuscript under revision.

## Citation

Full bibliographic information and a DOI will be added following publication.

## License and Usage

No open-source license is currently assigned to this repository.

Permission to access restricted research materials does not automatically grant permission to redistribute, modify, or commercially reuse those materials.
