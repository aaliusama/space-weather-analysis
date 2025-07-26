# Space Weather Analysis

This project investigates the relationship between solar activity and geomagnetic storm severity.  
By studying time–series data on solar flares, coronal mass ejections (CMEs) and geomagnetic storms collected via NASA's Space Weather API from January 2021 to December 2023, the analysis explores whether strong solar flares and high‑speed CMEs are associated with more intense geomagnetic storms on Earth.

## Project Overview

The notebook performs several types of analysis:

- **Data retrieval** – Uses Python to query NASA's Space Weather API and assemble a dataset of solar flare intensity, CME speed and geomagnetic storm indices over the specified period.
- **Exploratory analysis** – Visualises the distributions and temporal trends of each variable using Pandas and Matplotlib.
- **Correlation analysis** – Computes pairwise correlation coefficients to assess linear relationships between solar flare intensity, CME speed and geomagnetic storm strength.
- **Time‑series and cross‑correlation** – Applies rolling means and cross‑correlation to explore how changes in solar activity precede or coincide with geomagnetic disturbances.

## Files

- `space_weather_analysis.ipynb` – Jupyter notebook containing the full analysis, with code and visualisations.

## Usage

Clone or download the repository and open the Jupyter notebook to follow the analysis. Ensure you have a recent Python environment with NumPy, Pandas and Matplotlib installed. Running the notebook will fetch the latest data from NASA's API and reproduce all charts and statistical measures.

