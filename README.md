# Sales Rate Prediction with Flask

## Project Overview

This project demonstrates a machine learning model for predicting sales rates. It includes components for model training and deployment with Flask. The project is structured as follows:

- **`Sales_rate_prediction.ipynb`**: Contains the code for training the machine learning model to predict sales rates.
- **`app.py`**: Flask application that receives employee details through a GUI or API calls, computes the predicted sales rate based on the model, and returns the result.
- **`templates/`**: Contains HTML templates for user input and displaying the predicted sales rate.
- **`static/`**: Contains CSS files for styling the webpage.

## Running the Project

### Local Deployment

1. **Navigate to the Project Directory**: Ensure you are in the project home directory where the `model.pkl` file is also located.

2. **Start the Flask Application**: Run the following command to start the Flask server:
   ```bash
   python app.py
   ```
3. **Access the Application**: By default, the Flask server runs on port 5000. Open your web browser and navigate to:
   - [http://localhost:5000](http://localhost:5000)

### Public Deployment

1. **Access the Model API**: Once deployed publicly, you can access the application at:
   - [http://sales-rate-prediction.herokuapp.com](http://sales-rate-prediction.herokuapp.com)

## Conclusion

The **`Sales_Rate_Prediction_Flask`** project showcases the application of machine learning for predicting sales rates and demonstrates deployment using Flask. This project provides a complete example of integrating a machine learning model with a web application for real-time predictions.

---
