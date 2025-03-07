# Climate Change Modeling Project

## Overview
This project focuses on analyzing historical climate data to predict future trends in **temperature anomalies, sea level rise, and extreme weather events**. Using machine learning techniques, the project aims to identify patterns and provide insights that can help with climate change mitigation and adaptation strategies.

## Dataset
The dataset contains historical climate-related variables such as:
- **Year, Country**
- **Temperature anomalies**
- **CO2 levels**
- **Sea level rise**
- **Rainfall patterns**
- **Population**
- **Renewable energy usage**
- **Weather events**
- **Forest cover**

## Project Workflow
1. **Data Preprocessing**  
   - Cleaning missing values and handling outliers.
   - Feature engineering and selection.
   - Splitting data into **training (70%), validation (15%), and test (15%)** sets.

2. **Model Training & Tuning**
   - A **Pipeline** is created using **StandardScaler** and **RandomForestRegressor**.
   - Hyperparameter tuning is done using **GridSearchCV**.
   - Separate models are trained for:
     - **Temperature anomaly prediction**
     - **Sea level rise prediction**
     - **Extreme weather event forecasting**

3. **Model Evaluation**
   - Models are evaluated using metrics like **R² score, RMSE, and MAE**.
   - Best-performing models are saved for future predictions.

## Code Structure
- `data_preprocessing.py` → Handles **data cleaning, feature engineering, and dataset splitting**.
- `model_training.py` → Implements **machine learning models with hyperparameter tuning**.
- `evaluation.py` → **Evaluates** model performance on test data.
- `app.py` (Optional) → Can be added for **deployment as an API using Flask or Streamlit**.

## How to Run the Project
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/yourusername/climate-change-modeling.git
   cd climate-change-modeling
   ```

2. **Install Dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Data Preprocessing:**  
   ```bash
   python data_preprocessing.py
   ```

4. **Train the Models:**  
   ```bash
   python model_training.py
   ```

5. **Evaluate the Models:**  
   ```bash
   python evaluation.py
   ```

## Results & Insights
- The trained models provide **accurate predictions** for temperature anomalies and sea level rise.
- Extreme weather event forecasting is challenging due to data variability, but improvements can be made with **more features and advanced models (LSTMs, CNNs, etc.)**.

## Future Improvements
- **Incorporating deep learning models (LSTMs, CNNs) for time-series forecasting**.
- **Integration of real-time climate data APIs** for continuous learning.
- **Deployment of an interactive dashboard** using Flask/Streamlit.

## Author
**Aniket Surwade**  
**Email:** mailbox.as.aniketsurwade@gmail.com  
**LinkedIn:** [[Your LinkedIn Profile](https://www.linkedin.com/in/aniket-surwade/)]

---
Feel free to contribute or suggest improvements! 🚀

