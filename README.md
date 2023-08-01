# Fish Weight Prediction Web App

This web application is built using Flask and allows users to predict the weight of a fish based on its various measurements. The predictive model used in this app was trained using the "Diabetes dataset."

## Getting Started

To use this web application locally, follow the steps below:

1. Clone this repository to your local machine.

2. Install the required dependencies by running the following command in your terminal or command prompt:

3. Run the Flask app by executing the following command in the project directory:

4. Once the app is running, open your web browser and go to `http://localhost:5000/`.

## Usage

1. On the home page, enter the fish measurements in the provided input fields.

2. Select the species of the fish from the dropdown menu.

3. Click on the "Predict the Weight" button to see the predicted weight of the fish.

## Web App Structure

- `app.py`: This is the main Flask application file containing the app's routing and prediction logic.

- `new_model.pkl`: The serialized machine learning model used for making predictions.

- `templates/home.html`: The HTML template file for the web application's user interface.

## Credits

- The machine learning model used in this app is built with scikit-learn.

- The web application is powered by Flask.

- The Bootstrap CSS framework is used for basic styling.

## License

This project is licensed under the MIT License.
