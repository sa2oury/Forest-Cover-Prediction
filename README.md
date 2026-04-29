# Forest Cover Type Classification Using Ensemble Learning

## Project Overview

This project compares the performance of two ensemble learning models on the Forest Cover Type dataset. The goal is to predict the forest cover type of a given area using cartographic and environmental features such as elevation, slope, hillshade, distance to hydrology, wilderness area, and soil type.

The project was completed as part of an ensemble learning assignment where two ensemble models must be implemented, evaluated, and compared using suitable metrics and visualizations.

## Dataset

### Dataset Name
Forest Cover Type Dataset / Covertype Dataset

### Dataset Description
The dataset contains cartographic variables collected from forest areas. Each record represents a land area, and the target variable is the forest cover type.

The dataset includes:

- 581,012 rows
- 54 input features
- 1 target column: `Cover_Type`
- 7 forest cover classes

### Feature Groups

The dataset contains three main groups of features:

1. Continuous cartographic features:
   - Elevation
   - Aspect
   - Slope
   - Horizontal Distance to Hydrology
   - Vertical Distance to Hydrology
   - Horizontal Distance to Roadways
   - Hillshade at 9am
   - Hillshade at Noon
   - Hillshade at 3pm
   - Horizontal Distance to Fire Points

2. Wilderness area features:
   - One-hot encoded binary columns representing wilderness areas

3. Soil type features:
   - One-hot encoded binary columns representing soil types

### Dataset Source

The dataset can be downloaded from:

```text
https://archive.ics.uci.edu/dataset/31/covertype