# Heart-disease-machine-learning-model
# Heart Disease Prediction with Decision Tree

This project predicts the presence of heart disease using a **Decision Tree Classifier** and the **Heart Disease Dataset** from Kaggle.  

## How It Works
- Load `heart.csv` using **pandas**  
- Split into features (`X`) and target (`Y`)  
- Use an **80/20 train-test split**  
- Train a **DecisionTreeClassifier**  
- Evaluate using **accuracy_score**

- ## Specifics of the CSV
- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholestoral in mg/dl
- fasting blood sugar > 120 mg/dl
- resting electrocardiographic results (values 0,1,2)
- maximum heart rate achieved
- exercise induced angina
- oldpeak = ST depression induced by exercise relative to rest
- the slope of the peak exercise ST segment
- number of major vessels (0-3) colored by flourosopy
- thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
- The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.
- **this is real data just without the names and social security numbers of the real patients**


## Requirements
- Python 3.x  
- pandas  
- scikit-learn
