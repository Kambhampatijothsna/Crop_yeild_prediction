🌾 Crop Yield Prediction using Machine Learning

This project focuses on predicting crop yield (hg/ha) based on various agricultural and environmental factors such as rainfall, temperature, pesticide usage, crop type, and country/region. The prediction is performed using Machine Learning regression models.

📌 Project Overview

Crop yield prediction helps farmers, researchers, and policymakers make better agricultural decisions.
This project uses historical agricultural data to train regression models and predict crop yield for a given crop, country, and year.

📂 Dataset Information

The dataset contains the following columns:

Area → Country/Region name

Item → Crop name (e.g., Wheat, Rice, Sorghum)

Year → Year of record

hg/ha_yield → Crop yield (Target column)

average_rain_fall_mm_per_year → Rainfall per year

pesticides_tonnes → Pesticide usage in tonnes

avg_temp → Average temperature

⚙️ Technologies Used

Python

Google Colab / Jupyter Notebook

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Machine Learning Regression Models

🧠 Machine Learning Models Used

The following regression models were trained and compared:

Random Forest Regressor

K-Nearest Neighbors (KNN)

DecisionTreeRegressor

BaggingRegressor(
(and other regression models if applicable)

Model performance was evaluated using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

R² Score

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repo-name.git

2️⃣ Navigate to Project Folder
cd your-repo-name

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Notebook / Script

Open the notebook in Jupyter/Colab and execute all cells.

📌 Example Prediction Output

Example input:

Crop: Wheat

Country: India

Year: 2023

Example output:

Predicted Crop Yield: 22067.54 hg/ha

📊 Results

The best-performing model was selected based on the highest R² Score and lowest error metrics.

Example comparison:

Model	MAE	RMSE	R² Score
Random Forest	3713.40	9384.34	0.9877
Bayesian Ridge	3990.92	10136.62	0.9857
KNN	4611.26	10396.80	0.9849
📁 Project Structure
📦 Crop-Yield-Prediction
 ┣ 📜 crop_yield_prediction.ipynb
 ┣ 📜 dataset.csv
 ┣ 📜 README.md
 ┣ 📜 requirements.txt

🌟 Future Enhancements

Add more advanced models (XGBoost, CatBoost, LightGBM)

Deploy as a web app using Flask/Streamlit

Add interactive UI for crop and area selection

Improve feature engineering and preprocessing

🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

📜 License

This project is for educational purposes and is open-source.
