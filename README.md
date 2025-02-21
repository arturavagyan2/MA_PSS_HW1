# Bass Model Analysis

## Project Overview
This project applies the **Bass Diffusion Model** to analyze and predict the adoption of innovations over time. The model estimates key parameters from historical data and forecasts future adoption trends.

## Repository Structure
- `data/` - Contains datasets used for analysis.
- `report/` - Contains the final report and markdown source file.
- `script/` - Python scripts for data analysis and modeling.
- `img/` - Visualizations generated during analysis.

## Requirements
To run the analysis, install the necessary dependencies:
```sh
pip install -r requirements.txt
```

## Running the Model
Execute the main Python script:
```sh
python bass_model.py
```

## Outputs
- Estimated Bass Model parameters (`p`, `q`, `M`).
- Graph showing observed vs. predicted adoption.
- Forecasted adoption for future years.