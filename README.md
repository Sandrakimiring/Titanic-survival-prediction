# Titanic-survival-prediction
Welcome to the Titanic Survival Prediction App! This web application predicts whether a passenger survived the Titanic disaster based on various features. The app utilizes machine learning to make predictions and provides an intuitive interface for users to input passenger data.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Model Training](#model-training)
- [Contributing](#contributing)
- [License](#license)

## Features
- Predict survival based on passenger attributes such as age, gender, and ticket class.
- User-friendly input form to enter passenger data.
- Displays prediction results in real-time.

## Technologies Used
- **Python**: Programming language for backend development.
- **Flask**: Web framework for building the application.
- **Scikit-learn**: Machine learning library for model training and prediction.
- **Pandas**: Data manipulation and analysis.
- **HTML/CSS**: Frontend technologies for the user interface.

## Getting Started
To run the Titanic Survival Prediction App locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/titanic-survival-prediction.git
   cd titanic-survival-prediction
2. **Install Dependencies**
Make sure you have Python and pip installed. Then, install the required packages:

```bash
pip install -r requirements.txt

## Run the Application: Start the Flask server:## 

bash
Copy code
python app.py
The app will be running on http://127.0.0.1:5000.

##How to Use:##
Open your web browser and go to http://127.0.0.1:5000.
Fill in the passenger details in the input form.
Click the "Predict" button to get the survival prediction.
Model Training
The model is trained using the Titanic dataset from Kaggle. It uses various features such as:

## Model Training
The model is trained using the Titanic dataset from Kaggle. It uses various features such as:

- **Passenger class**
- **Gender**
- **Age**
- **Number of siblings/spouses aboard**
- **Number of parents/children aboard**
- **Ticket fare**
- **Port of embarkation**

### Important Notes:
- Ensure to handle missing values in the dataset before training the model.
- The trained model is serialized and loaded in the Flask app for making predictions.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you encounter any problems or have suggestions for improvements.
## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you encounter any problems or have suggestions for improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


