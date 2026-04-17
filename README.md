# Forecasting Dengue Transmission and Incidence in Bangladesh

This repository contains code, analysis workflows, and results for forecasting dengue transmission and incidence in Bangladesh using machine learning, probabilistic forecasting, and mechanistic modeling.

## Project overview
This project develops an integrated forecasting framework that:
- estimates the time-varying effective reproduction number (Rt),
- forecasts short-term Rt using machine learning models,
- generates dengue case forecasts using a probabilistic framework, and
- compares performance with a mechanistic SIRS model.

The analysis focuses on dengue surveillance data from the eight administrative divisions of Bangladesh.

## Main components
- **Rt estimation** using EpiNow2
- **Machine learning forecasting** using models such as LGBM and QRF
- **Probabilistic case forecasting** based on forecasted Rt values
- **Mechanistic baseline modeling** using a window-based SIRS model
- **Evaluation** across 1-, 2-, and 3-week forecast horizons

## Repository structure
- `data/` – input and processed data
- `src/` – modeling and utility scripts
- `notebooks/` – exploratory and analysis notebooks
- `results/` – model outputs and evaluation summaries
- `figures/` – plots and manuscript-ready figures
- `docs/` – manuscript drafts, notes, and supplementary materials

## Goals
- characterize dengue transmission dynamics in Bangladesh
- improve short-term forecasting of Rt and dengue incidence
- compare machine learning and mechanistic forecasting approaches
- support surveillance and early warning for dengue outbreaks

## Author
Md Sakhawat Hossain
