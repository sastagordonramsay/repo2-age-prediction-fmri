# Predicting Age from Multi-Subject Resting-State ROI Functional Connectivity

## Overview

This project builds a machine learning pipeline to predict participant age from resting-state fMRI functional connectivity patterns.
Using atlas-based ROI signals extracted from fMRI scans, connectivity matrices were generated and used as features in a predictive model.

---

## Dataset

* Nilearn Developmental fMRI Dataset
* 30 subjects
* Resting-state scans
* Age metadata available

---

## Methods

* Data download with Nilearn
* ROI extraction using Harvard-Oxford atlas
* Functional connectivity matrices
* Feature engineering
* Ridge Regression
* 5-fold cross-validation

---

## Repository Files

* `01_data_download.ipynb`
* `02_roi_extraction.ipynb`
* `03_age_prediction.ipynb`

---

## Skills Demonstrated

* Python
* Neuroimaging analysis
* Functional connectivity
* Machine learning
* Scientific workflows

---

## Example Output

### ROI Functional Connectivity Matrix

![Connectivity Heatmap](figures/Heatmap.png)

---

## Results

The pipeline successfully:

* Downloaded and processed multi-subject resting-state fMRI data
* Extracted ROI time series from atlas-defined cortical regions
* Generated subject-level functional connectivity matrices
* Built a Ridge Regression framework for age prediction
* Implemented 5-fold cross-validation for evaluation
* Established a reproducible foundation for future predictive experiments

Quantitative performance metrics should be reported directly from the latest notebook outputs after rerunning the final model.
