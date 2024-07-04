# Weather Prediction Project

This project uses machine learning techniques to predict weather conditions based on various input features such as temperature, dew point, humidity, wind speed, visibility, and pressure.

## Project Description

The main objective of this project is to categorize weather conditions and predict them using a RandomForestClassifier. The data is preprocessed to balance the classes, and features are scaled for better model performance. The project includes:

- Data preprocessing to categorize weather conditions.
- Feature scaling using StandardScaler.
- Training a RandomForestClassifier.
- Evaluating the model using accuracy score and classification report.
- Predicting weather conditions based on user input.

## Installation

To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn

You can install the required libraries using pip:

pip install pandas numpy scikit-learn

#Usage
1]Prepare the Dataset:
Download the Weather_Data.csv file and place it in the project directory.

2]Run the Script:
Open a terminal or command prompt.
Navigate to the project directory.
Run the script using Python:
python weather_prediction.py

3]Provide User Input:
The script will prompt you to enter the following weather features:
Temperature (in Celsius)
Dew Point Temperature (in Celsius)
Relative Humidity (in %)
Wind Speed (in km/h)
Visibility (in km)
Pressure (in kPa)
After entering the values, the script will predict and display the weather condition.

#Project Structure
weather_prediction.py: The main script that includes data preprocessing, model training, and prediction logic.
Weather_Data.csv: The dataset used for training the model (make sure to download and place this file in the project directory).


#License
This project is open-source and available under the MIT License.

#Contact
If you have any questions or suggestions, feel free to contact the project author.
