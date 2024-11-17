# Crop Recommendation System

## Overview
This Crop Recommendation System is designed to recommend crops based on the soil's nitrogen, phosphorus, and potassium content, as well as weather factors like temperature, humidity, and rainfall. It helps farmers and agriculturalists choose the most suitable crops for their land.

## Features
- Recommends crops based on soil and weather conditions.
- Uses machine learning algorithms to predict optimal crops.
- Provides an easy-to-use interface for inputting soil and weather data.

## Tech Stack
- **Python**
- **Flask** (for the web app)
- **Pandas** (for data processing)
- **Scikit-learn** (for machine learning)
- **NumPy** (for numerical operations)

## Requirements
Before running the system, make sure you have Python installed (Python 3.7+ is recommended).

### Python Libraries
You can install the required libraries using `pip`:

```bash
pip install -r requirements.txt
```

The `requirements.txt` should contain the following libraries:

```
Flask
pandas
scikit-learn
numpy
```

## How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/pratikneupane/crop-recom.git
cd crop-recommendation-system
```

2. **Set up a virtual environment** (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. **Install dependencies**:

```bash
pip install -r requirements.txt
```

4. **Run the Flask app**:

```bash
python app.py
```

5. Open your browser and go to `http://127.0.0.1:8000/` to access the application.

## Using the System
- Input the soil parameters (Nitrogen, Phosphorus, and Potassium levels).
- Enter weather parameters (Temperature, Humidity, and Rainfall).
- Click on "Get Recommendations" to receive crop suggestions.

## Data
The system uses a dataset of soil and weather conditions along with crop recommendations. The dataset is loaded and processed using Pandas. You can replace the dataset with your own if needed.

## Model
The machine learning model is trained using historical crop data and environmental conditions. It uses a decision tree (or any other suitable model) to predict the best crops for the given conditions.

## Example Input
Soil Data:
- Nitrogen: 50
- Phosphorus: 30
- Potassium: 40

Weather Data:
- Temperature: 28°C
- Humidity: 75%
- Rainfall: 120mm

## License
This project is licensed under the MIT License.
