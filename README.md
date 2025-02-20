Here’s a short summary about our Project:

### **1. Data:**
- Raw air quality data with columns: Date, Location, PM2.5, PM10, NO2, O3, CO, SO2, Temperature, Humidity, AirQualityIndex.

### **2. Model:**
- Use **Random Forest Regressor** for predicting the **Air Quality Index (AQI)**.
- Input features: PM2.5, PM10, NO2, O3, CO, SO2, Temperature, Humidity.
- Evaluate model using **Mean Squared Error (MSE)**.

### **3. Data Preprocessing:**
- Handle missing values by filling with the column mean.
- Normalize features using **StandardScaler** for consistent scale.
- Save cleaned data for model input.

### **4. Evaluation:**
- Model performance measured by **MSE**, **RMSE**, and **R-Squared (R2)**.
- Feature importance: PM2.5 and NO2 are the most impactful.

### **5. Documentation:**
- **Project Objective**: Predict AQI based on environmental factors.
- **Methodology**: Collect data, preprocess, train model, and evaluate accuracy.
