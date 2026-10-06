# AI-Based Cyclone Detection, Intensity Estimation and Trajectory Prediction

An AI/ML system for cyclone detection, intensity estimation and
trajectory prediction over the North Indian Ocean.

## Project Components

1. Cyclone Detection
2. Cyclone Intensity Estimation
3. Cyclone Trajectory Prediction
4. Integrated Analysis Pipeline

## Dataset

The project uses:
- IBTrACS
- ERA5 reanalysis data

The datasets are not stored directly in this repository.

## Current Progress

### Intensity Estimation
- IBTrACS + ERA5 data merged
- Chronological train/validation/test split
- Random Forest intensity model developed
- Feature engineering performed
- Final test evaluation completed

### Cyclone Detection
- Positive cyclone samples prepared
- Balanced negative/background samples generated
- ERA5 feature extraction in progress

### Trajectory Prediction
- Planned

## Data Split

| Split | Years |
|---|---|
| Training | 2000–2018 |
| Validation | 2019–2021 |
| Testing | 2022–2025 |
