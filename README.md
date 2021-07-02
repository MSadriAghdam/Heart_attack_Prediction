# Heart_attack_Prediction
The dataset consists of a group of patients with their medical information and the output (target) describes cases that had/not a heart attack.

## About this dataset
Age: Age of the patient

Sex: Sex of the patient

exang: exercise induced angina (1 = yes; 0 = no)

ca: number of major vessels (0-3)

cp : Chest Pain type chest pain type

Value 1: typical angina
Value 2: atypical angina
Value 3: non-anginal pain
Value 4: asymptomatic
trtbps : resting blood pressure (in mm Hg)

chol : cholestoral in mg/dl fetched via BMI sensor

fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

rest_ecg : resting electrocardiographic results

Value 0: normal
Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
thalach : maximum heart rate achieved

target: 0= less chance of heart attack 1= more chance of heart attack

## Preprocessing
First, I split data into categorical and numerical variables. Then for Categorical variables, I got dummies and for numerical variables I scaled them. #As there is no specific correlation between them and also there are no missing values in the dataset, there is no need for more cleaning and preprocessing here.

## Visualization
Using a pair plot, I plotted all variables' relations against each other. Moreover, I plotted a heatmap to find the correlation between variables with do not indicate a specific correlation.

## Model
As we want to classify the outputs, I used Logistic Regression as an ML model. Also, in the end, I plotted a Confusion matrix to check the final result.

## Result
Accuracy: 0.8852459016393442
Precision: 0.9032258064516129
Recall: 0.875
