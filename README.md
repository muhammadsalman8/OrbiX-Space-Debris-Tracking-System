# OrbiX - Space Debris Tracking System

## Project Overview

OrbiX is a student team project focused on tracking space debris, analysing orbital movements, identifying close approaches between space objects, and presenting risk-screening information through a dashboard.

The project combines orbital data collection, database management, orbital propagation, data science, backend development, and frontend visualisation.

## Project Objectives

- Collect and manage orbital data.
- Propagate orbital positions using SGP4.
- Calculate distances between space objects.
- Identify potential close approaches.
- Analyse relative velocity and separation rates.
- Perform preliminary, project-defined risk screening.
- Generate analytical reports and visualisations.
- Present results through a web-based dashboard.

## Technologies Used

- Python
- Pandas and NumPy
- SciPy
- Matplotlib and Plotly
- SGP4
- MongoDB
- FastAPI
- React
- CesiumJS

## Team Responsibilities

| Member | Responsibility |
|---|---|
| Member 1 | Data Collection |
| Member 2 | Database Management |
| Member 3 | Orbit Propagation and Tracking |
| Member 4 | Data Science and Risk Analysis |
| Member 5 | FastAPI Backend Development |
| Member 6 | React and 3D Dashboard Development |

## Project Structure

`	ext
OrbiX-Space-Debris-Tracking-System/
|
|-- data/
|-- notebooks/
|-- reports/
|-- src/
|   |-- data_collection/
|   |-- database/
|   |-- orbit_tracking/
|   |-- data_analysis/
|   |-- backend/
|   |-- frontend/
|-- visualizations/
|-- README.md
|-- requirements.txt
|-- .gitignore
`

## Installation

Clone the repository:

`ash
git clone YOUR_REPOSITORY_URL
cd OrbiX-Space-Debris-Tracking-System
`

Create a virtual environment:

`ash
python -m venv .venv
`

Activate it on Windows:

`ash
.venv\Scripts\activate
`

Install dependencies:

`ash
pip install -r requirements.txt
`

## Data Science and Risk Analysis

The analytical workflow includes:

1. Orbital dataset inspection and cleaning.
2. Orbital data quality assessment.
3. Pairwise distance calculations.
4. Close-approach identification.
5. Relative velocity calculations.
6. Separation-rate analysis.
7. Preliminary risk categorisation.
8. Threshold sensitivity analysis.
9. Historical analysis of available prediction samples.
10. Statistical analysis and visualisation.
11. Dashboard-ready report generation.

## Current Dataset Scope

The initial analytical dataset contains:

- 580 unique space objects.
- 7 prediction timestamps.
- 10-minute sampling intervals.
- A total prediction window of 1 hour.

## Important Limitations

- Preliminary screening categories and distance thresholds are project-defined, not official safety standards.
- Sampled minimum separation is not necessarily the true continuous-time closest approach.
- Orbital element freshness and data quality require review.
- Distance-based screening does not calculate actual collision probability.
- Further validation and integration are required.

## Project Status

The initial data science and risk-screening workflow has been completed for the available dataset.

Further work includes updated orbital data, refined propagation, backend integration, frontend dashboard integration, and final system testing.

## Contributors

Six team members are collaborating on the OrbiX Space Debris Tracking System.
