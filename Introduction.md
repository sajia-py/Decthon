# 🎯 Predicting Next Purchase with Random Forest

## 📌 Overview
This project leverages **machine learning** to predict whether a participant will make a future purchase. The dataset contains information about participants, and we apply a **Random Forest Classifier** to build an accurate predictive model.

## 🛠 Tech Stack
- **Python** (pandas, numpy, scikit-learn)
- **Machine Learning** (Random Forest Classifier)
- **Data Preprocessing** (Handling missing values, Label Encoding)
- **Model Evaluation** (Accuracy Score)

## 📂 Dataset
- `participants_training_dataset.csv` → Used to train the model.
- `participants_test_dataset.csv` → Used to generate final predictions.

## 📌 Steps to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/sajia-py/Decthon
   cd your-repo
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn
   ```
3. Place your dataset files in the project directory.
4. Run the script:
   ```bash
   python predict_next_purchase.py
   ```
5. The final predictions will be saved in `submission.csv`.

## 🔍 Key Features
✅ Handles missing values with **mean imputation**  
✅ Encodes categorical variables using **Label Encoding**  
✅ Uses **Random Forest Classifier** for prediction  
✅ Splits data into **training and validation** for better accuracy  
✅ Saves final predictions in `submission.csv`

## 📊 Model Performance
- The model is evaluated using **accuracy score** on the validation set.
- Further tuning can be done by experimenting with **hyperparameters**.

## 🚀 Future Improvements
🔹 Use feature engineering to improve prediction accuracy.  
🔹 Implement **hyperparameter tuning** using GridSearchCV.  
🔹 Try **alternative models** like XGBoost or Neural Networks.  

## 📝 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Feel free to fork the repository and submit a pull request! Suggestions and improvements are always welcome. 😊

