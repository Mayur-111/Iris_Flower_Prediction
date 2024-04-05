# Iris Flower Prediction Web Application

This is a simple web application built using Flask that predicts the species of an iris flower based on its sepal length, sepal width, petal length, and petal width. 
The prediction is made using a logistic regression model trained on the Iris dataset from Scikit-learn.

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository to your local machine:
2. Navigate to the project directory:
3. Install the required dependencies using pip:
4. Run the Flask application:
5. Open your web browser and go to http://localhost:5000 to access the application.

## Usage

1. Once you access the application in your web browser, you will see a form where you can enter the sepal length, sepal width, petal length, and petal width of an iris flower.
2. Enter the values in the respective input fields and click the "Predict" button.
3. The application will then display the predicted species of the iris flower based on the input values.

## File Structure

## File Structure

- `app.py`: Flask application containing the routes and logic for the web application.
- `frontend_page.html`: HTML template for the user interface of the web application.
- `iris.py`: Python script containing the code for model training and pickling.
- `logistic_model.pkl`: Pickle file containing the trained logistic regression model.
- `requirements.txt`: List of Python dependencies required to run the application.

## Technologies Used

- Python
- Flask
- HTML/CSS
- Scikit-learn

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


