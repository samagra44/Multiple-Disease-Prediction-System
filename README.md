# Multiple Disease Prediction Web App

This web application allows users to predict the likelihood of several diseases including Diabetes, Heart Disease, and Parkinson's Disease. It provides a simple and user-friendly interface for predicting these diseases using machine learning models.

## Table of Contents
- [Features](#features)
- [About Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- Predict Diabetes, Heart Disease, and Parkinson's Disease.
- Easy-to-use web interface.
- Provides prediction results and explanations.

## About Dataset

### 1. Heart Disease Dataset
  This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

#### Attribute Information:
* age    
* sex    
* chest pain type (4 values)     
* resting blood pressure    
* serum cholestoral in mg/dl    
* fasting blood sugar > 120 mg/dl    
* resting electrocardiographic results (values 0,1,2)    
* maximum heart rate achieved    
* exercise induced angina    
* oldpeak = ST depression induced by exercise relative to rest    
* the slope of the peak exercise ST segment    
* number of major vessels (0-3) colored by flourosopy     
thal: 0 = normal; 1 = fixed defect; 2 = reversable defect     
* The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.    

### 2. Parkinson’s Disease Data Set
This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds to one of 195 voice recordings from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for PD.

The data is in ASCII CSV format. The rows of the CSV file contain an instance corresponding to one voice recording. There are around six recordings per patient, the name of the patient is identified in the first column.For further information or to pass on comments, please contact Max Little (little '@' robots.ox.ac.uk).

Further details are contained in the following reference -- if you use this dataset, please cite:
Max A. Little, Patrick E. McSharry, Eric J. Hunter, Lorraine O. Ramig (2008), 'Suitability of dysphonia measurements for telemonitoring of Parkinson's disease', IEEE Transactions on Biomedical Engineering (to appear).     

* Matrix column entries (attributes):
* name - ASCII subject name and recording number
* MDVP:Fo(Hz) - Average vocal fundamental frequency
* MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
* MDVP:Flo(Hz) - Minimum vocal fundamental frequency
* MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several measures of variation in fundamental frequency
* MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
* NHR, HNR - Two measures of the ratio of noise to tonal components in the voice
* status - The health status of the subject (one) - Parkinson's, (zero) - healthy
* RPDE, D2 - Two nonlinear dynamical complexity measures
* DFA - Signal fractal scaling exponent
* spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation

### 3. Diabetes Dataset
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.    

Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

* Pregnancies: Number of times pregnant
* Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* BloodPressure: Diastolic blood pressure (mm Hg)
* SkinThickness: Triceps skin fold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml)
* BMI: Body mass index (weight in kg/(height in m)^2)
* DiabetesPedigreeFunction: Diabetes pedigree function
* Age: Age (years)
* Outcome: Class variable (0 or 1)

## Prerequisites
- Python 3.7 or higher
- Git (optional)

## Installation

1. Clone the repository to your local machine (or download and extract the ZIP file).
    ```
    git clone https://github.com/samagra44/Multiple_Prediction_app.git
    ```

2. Navigate to the project directory.
    ```
    cd multiple-disease-prediction
    ```

3. Create a virtual environment (optional but recommended).
    ```
    python -m venv venv
    ```

4. Activate the virtual environment (Windows).
    ```
    venv\Scripts\activate
    ```

   Activate the virtual environment (macOS and Linux).
    ```
    source venv/bin/activate
    ```

5. Install the required Python packages.
    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app.
    ```
    streamlit run app.py
    ```

2. Open your web browser and navigate to `http://localhost:8501`.

3. Use the web interface to make disease predictions.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.

2. Clone your forked repository to your local machine.

3. Create a new branch for your feature or bug fix.
    ```
    git checkout -b feature/your-feature-name
    ```

4. Make your changes and commit them.
    ```
    git commit -m "Add your commit message here"
    ```

5. Push your changes to your forked repository.
    ```
    git push origin feature/your-feature-name
    ```

6. Open a pull request on the original repository.

![Streamlit](https://github.com/samagra44/Multiple_Prediction_app/assets/77968722/2077ef79-5748-4bd6-aaa8-3b197457d884)


