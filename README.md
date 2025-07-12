❤️ Heart Disease Prediction Using Machine Learning
📝 Description:
This project is focused on predicting the presence of heart disease in patients using machine learning classification algorithms. By analyzing health-related parameters such as age, cholesterol level, blood pressure, and chest pain type, the system predicts whether a patient is likely to have heart disease. A user-friendly GUI built with Tkinter allows non-technical users to input values and get predictions in real time.

📁 Dataset Description:
The dataset (heart.csv) includes 14 features related to cardiovascular health:

age – Age of the patient

sex – Gender (1 = male; 0 = female)

cp – Chest pain type (0–3)

trestbps – Resting blood pressure

chol – Serum cholesterol

fbs – Fasting blood sugar (>120 mg/dl)

restecg – Resting electrocardiographic results

thalach – Maximum heart rate achieved

exang – Exercise-induced angina

oldpeak – ST depression induced by exercise

slope – Slope of peak exercise ST segment

ca – Major vessels colored by fluoroscopy

thal – Thalassemia

target – Heart disease presence (1 = yes, 0 = no)

📚 Required Libraries:

pandas – For data handling

numpy – For numerical calculations

matplotlib / seaborn – For visualizations

scikit-learn – For machine learning modeling

Tkinter – For creating the graphical user interface

joblib – For model serialization (saving/loading ML model)

🔍 Data Preprocessing:

No missing values in the dataset

Categorical data encoded numerically

Correlation analysis for feature selection

Dataset split into training (80%) and testing (20%)

🤖 Algorithms Used:

Various ML classifiers were trained and compared:

Logistic Regression

Support Vector Machine (SVM)

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

Naive Bayes

📊 Results:

Best Model: Random Forest Classifier

Accuracy: ~85%

Evaluation Metrics: Confusion matrix, precision, recall, F1-score

Feature Importance: Visualized to show key influencing features

🖥️ Graphical User Interface (GUI):

Built using Python’s Tkinter module

Provides form fields for user input: age, sex, cholesterol, chest pain type, etc.

On clicking “Predict,” it loads the trained model and displays prediction (Heart Disease: Yes/No)

Enhances usability for users without coding knowledge
