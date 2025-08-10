# VehicleEmission-ML-Regression-Model
**Author:** Kashaf Fatima  
**Description:**  
This project implements a **Multiple Linear Regression** model to predict vehicle CO₂ emissions based on engine size and fuel consumption.  
It includes **exploratory data analysis (EDA)**, **feature scaling**, **model training and evaluation**, and **visualizations** such as histograms, an animated regression line, and an interactive 3D regression plane.

---

## Features

- **Data Loading & Preprocessing**
  - Dataset: [FuelConsumptionCo2.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%202/data/FuelConsumptionCo2.csv)
  - Selection of relevant features
  - Standardization using `StandardScaler`

- **Exploratory Data Analysis**
  - Histograms with KDE overlays
  - Feature distribution visualizations

- **Modeling**
  - Multiple Linear Regression with `sklearn`
  - Evaluation metrics:
    - Mean Absolute Error (MAE)
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
    - R² Score

- **Visualizations**
  - Animated regression line (Matplotlib + FuncAnimation)
  - Interactive 3D regression plane (Plotly)
  - Static plot exports

---

## Output Files

Saved in the `assets/` folder:
- `histograms.png` – Feature distributions
- `vehicle_emission_animation.mp4` – Animated regression line
- `vehicle_emission_animation.gif` – GIF version of the regression line animation
- `3d_regression_plane.png` – Static image of the interactive 3D regression plane

---

## How to Run

### Clone this repository
```bash
git clone https://github.com/Kashaffatimaaa/VehicleEmission-ML-Regression-Model.git
cd VehicleEmission-ML-Regression-Model

Install dependencies
bash

pip install -r requirements.txt

Dependencies:

numpy

pandas

matplotlib

seaborn

scikit-learn

plotly

kaleido (for saving static Plotly images)

ffmpeg (for saving animations)

Make sure to install and configure ffmpeg on your system and update the mpl.rcParams['animation.ffmpeg_path'] in the script.

Run the script
bash
python vehicle_emission_regression.py

License

This project is licensed under the MIT License.
