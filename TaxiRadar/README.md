# TaxiRadar

**TaxiRadar** is a machine learning project that predicts high-demand taxi pick-up locations in real-time, using a combination of historical data, real-time weather, and traffic information. The project is designed to assist taxi drivers in optimizing their routes and increasing their pick-up efficiency by suggesting nearby locations with high demand.

## Project Overview

- **Model Used**: Random Forest Regression and LSTM models
- **Accuracy Achieved**: Over 90%
- **Key Features**:
  - Predicts taxi demand based on historical and real-time data
  - Visualizes the top locations with predicted high demand
  - Calculates distance from the current location to suggested high-demand locations

## Demo

![image](https://github.com/user-attachments/assets/a8b63376-d882-4073-b039-7a5fdeb6e0b7)
![image](https://github.com/user-attachments/assets/da3d994d-0ab5-4236-92f1-e206b1d67b49)
![image](https://github.com/user-attachments/assets/1a84559b-ca8e-4e10-ae0a-475a6a94a49e)


## Dataset

The dataset used for this project contains historical taxi demand data, including:
- Date and Time
- Pick-up Latitude and Longitude
- Weather and Traffic data

The dataset was preprocessed to create features such as:
- Month, Day, Hour, Minute, Day of Week
- 2-hour time intervals

## Project Files

- `TaxiRadar.ipynb`: The main Jupyter notebook containing the code for data preprocessing, model training, prediction, and visualization.
- `combinedTaxiDemandSingapore.csv`: The dataset used in the project (not included due to size).
- `taxi_demand_model.joblib`: The trained machine learning model (not included due to size; see below for download instructions).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TaxiRadar.git
   cd TaxiRadar
2.Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```  

3.Download the pre-trained model and dataset:

- Model: `taxi_demand_model.joblib`
- Dataset: `combinedTaxiDemandSingapore.csv`
- Place the downloaded files in the project directory.

## Model Deployment
To deploy the model, you can integrate the trained model into a web application or mobile app. The model file taxi_demand_model.joblib can be loaded using joblib in Python for predictions.

## Contributing
If you would like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes.
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature-branch).
- Open a pull request.

## Acknowledgments

- Special thanks to Dr. Wee Kek Tan for mentorship and guidance during the project.
- Thanks to the National University of Singapore for the research internship opportunity.

## Contact
For any questions or suggestions, feel free to contact:

- **Name**: Sagar Beotra
- **Email**: sagarbeotra5@gmail.com

