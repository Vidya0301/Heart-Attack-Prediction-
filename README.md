🧠 Problem Statement

Heart disease is one of the leading causes of death globally. Predicting the possibility of a heart attack at an early stage can assist healthcare providers in taking timely action.
This project uses machine learning to classify patients as at risk or not at risk based on medical parameters.

📊 Dataset

We use the Heart Disease Dataset from Kaggle
.
It contains 14 attributes, including:

age – Age of the patient

sex – Gender (1 = male, 0 = female)

cp – Chest pain type (4 types)

trestbps – Resting blood pressure (mm Hg)

chol – Serum cholesterol (mg/dl)

fbs – Fasting blood sugar (>120 mg/dl)

restecg – Resting ECG results

thalach – Maximum heart rate achieved

exang – Exercise induced angina

oldpeak – ST depression induced by exercise

slope – Slope of peak exercise ST segment

ca – Number of major vessels (0–3) colored by fluoroscopy

thal – Thalassemia status

target – (0 = No heart disease, 1 = Heart disease present)

🛠️ Technologies Used

Python 3

Libraries:

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – visualization

Scikit-learn – model building

Logistic Regression, Random Forest, Decision Tree, SVM

⚙️ Project Workflow

Import Dataset

Data Preprocessing

Handling missing values

Encoding categorical data

Normalizing numerical data

Exploratory Data Analysis (EDA)

Correlation heatmap

Distribution of target variable

Model Building

Train/test split

Apply multiple ML algorithms

Evaluate using accuracy, precision, recall, F1-score

Model Comparison

Choose best-performing model

📈 Results

The best performing model achieved XX% accuracy on the test set.

Logistic Regression performed well, but Random Forest gave the highest precision and recall for predicting heart disease.

🚀 Future Work

Deploy the model using Streamlit or Flask for real-time predictions.

Tune hyperparameters further for better accuracy.

Collect and test on real-world data to improve generalization.

📂 How to Run

Clone this repository:

git clone https://github.com/yourusername/heart-attack-prediction.git
cd heart-attack-prediction


Install dependencies:

pip install -r requirements.txt


Run the notebook or script:

jupyter notebook heart_attack_prediction.ipynb

👩‍💻 Author

Your Name – Your GitHub Profile
