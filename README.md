Deep Learning-Based Seasonal Disease Prediction System

Project Overview

The Deep Learning-Based Seasonal Disease Prediction System analyzes historical dengue data to understand disease trends and predict future dengue cases using deep learning techniques. The project uses time-series data containing climate and environmental features to train and evaluate LSTM and GRU models.

Objectives

* Analyze historical dengue case data.
* Study relationships between climate conditions and dengue cases.
* Prepare and preprocess data for time-series prediction.
* Train and evaluate LSTM and GRU deep learning models.
* Compare model performance for dengue case prediction.

Dataset

This project uses the DengAI: Predicting Disease Spread dataset, which contains historical dengue data for San Juan, Puerto Rico, and Iquitos, Peru.

The dataset includes climate-related features such as temperature, precipitation, humidity, and vegetation-related measurements, along with reported dengue case counts.

Dataset source: ⁠DengAI: Predicting Disease Spread — DrivenData

Technologies Used

* Python
* Jupyter Notebook
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn
* PyTorch
* LSTM (Long Short-Term Memory)
* GRU (Gated Recurrent Unit)

Methodology

1. Load and explore the dengue dataset.
2. Clean the data and handle missing values.
3. Merge climate features with reported dengue cases.
4. Scale numerical features and prepare time-series sequences.
5. Split the data chronologically into training and testing sets.
6. Train LSTM and GRU models.
7. Evaluate model performance and compare predictions.

Models Implemented

1. LSTM

An LSTM neural network is used to learn patterns in sequential climate data and predict dengue case counts.

2. GRU

A GRU neural network is trained for the same prediction task to compare its performance with the LSTM model.

Evaluation Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

Repository Contents

* seasonal_disease_prediction.ipynb — Main notebook containing data preprocessing, model training, evaluation, and visualizations.
* dengue_features_train.csv — Training climate features.
* dengue_labels_train.csv — Historical dengue case counts.
* dengue_features_test.csv — Test climate features.
* submission_format.csv — Required prediction submission format.

Note: Update the notebook filename above if your actual filename is different.

Results

The notebook contains the training results, evaluation metrics, and visualizations for both LSTM and GRU models. These results can be used to compare the models’ performance.

Conclusion

This project demonstrates the application of deep learning to time-series disease prediction. By implementing LSTM and GRU models, it explores how historical climate data can support dengue trend analysis and forecasting.

Future Enhancements

* Incorporate historical dengue case counts into the input sequences.
* Experiment with additional time-series forecasting models.
* Develop an interactive dashboard to visualize trends and predictions.
* Evaluate models using additional validation strategies.

Author

Divitha Reddy Gujja
Expected Outcome

The models aim to learn temporal patterns in historical disease case data and forecast future case counts. Prediction quality depends on the dataset and model performance.
