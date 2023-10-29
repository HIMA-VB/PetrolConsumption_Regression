# PetrolConsumption_Regression



```markdown
# Decision Tree Regressor for Petrol Consumption Prediction

This repository contains Python code for training a Decision Tree Regressor to predict petrol consumption based on various attributes. The dataset used is the "petrol_consumption.csv."

## Contents

1. **Data Loading and Preprocessing:**
    - The code loads the dataset from the `petrol_consumption.csv` file.
    - The dataset is split into features (independent variables) and the target variable (petrol consumption).
    - A training and testing split is performed using scikit-learn's `train_test_split`.

2. **Model Training:**
    - A Decision Tree Regressor is trained using the training data to predict petrol consumption.

3. **Model Evaluation:**
    - The code makes predictions on the test data using the trained model.
    - Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) are computed to evaluate the model's performance.
    - The actual and predicted petrol consumption values are displayed.

4. **Results:**
    - The results are printed to the console, including the MAE, MSE, and RMSE.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/petrol-consumption-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd petrol-consumption-prediction
   ```

3. Run the Python script to train the Decision Tree Regressor and evaluate its performance:
   ```bash
   python decision_tree_petrol.py
   ```

4. View the results in the script's output, including the MAE, MSE, and RMSE.

## Dependencies

Ensure you have the required Python libraries installed. You can install them using the following commands:

```bash
pip install numpy
pip install matplotlib
pip install pandas
pip install scikit-learn
```

## Data

The dataset is loaded from the `petrol_consumption.csv` file. Make sure you have the dataset available in the project directory or specify the correct file path in the code.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

This code demonstrates the use of a Decision Tree Regressor for predicting petrol consumption based on various attributes. You can adapt and modify it for similar regression tasks or experiment with different machine learning algorithms.

If you have any questions or encounter any issues, please feel free to open an issue or contact the project maintainers.

Happy predicting petrol consumption!
```
