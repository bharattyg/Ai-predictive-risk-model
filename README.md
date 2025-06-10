# Ai-predictive-risk-model
Predictive Patient Risk Models for Cyfuture AI Hackathon.
Predictive Patient Risk Models for Cyfuture AI Hackathon

## Overview
This project aims to predict hospital readmissions within 30 days and calculate patient risk scores using AI. Hospital readmissions cost billions annually and are often preventable. Our solution helps hospitals prioritize follow-up care for high-risk patients, reducing costs and improving outcomes.

## Problem Statement
- Unplanned hospital readmissions cost the U.S. healthcare system USD 15-20 billion annually.
- High readmission rates lead to worse patient outcomes and strain hospital resources.

## Solution
We use machine learning to predict readmission risk based on patient data such as:
- Age
- Diagnosis (e.g., diabetes, heart failure)
- Length of stay
- Prior admissions
The model outputs a risk score (e.g., 82.3%) and a prediction (Readmitted: Yes/No), enabling targeted interventions.

## Tech Stack
- **Language**: Python
- **Libraries**: pandas, scikit-learn, numpy, matplotlib, Streamlit (for demo)
- **Model**: Logistic regression or random forest for binary classification

## Dataset
- Currently using a synthetic dataset (`data/synthetic_patient_data.csv`) with 50 rows.
- Plan to use real-world data like MIMIC-III in the future.

## Project Structure
