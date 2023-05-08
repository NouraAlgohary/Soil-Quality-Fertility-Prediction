# ML---Soil-Quality
**A machine learning model to predict soil fertility based on elemental soil analysis**

![The-5-Components-of-Healthy-Soil-1024x682](https://user-images.githubusercontent.com/103903785/235441777-7f0856c5-a7e6-4fc8-96f5-0f4d70594c04.jpg)

## Requirments
[Requirments](https://github.com/iurwpoietknckvjndfsm-gndvkd/ML---Soil-Quality/blob/main/Requirments.txt)

## Data
### Data Source
Raw Data is published on [kaggle](https://www.kaggle.com/datasets/rahuljaiswalonkaggle/soil-fertility-dataset)
- [Original Dataset](https://github.com/iurwpoietknckvjndfsm-gndvkd/ML---Soil-Quality/blob/main/Data/Raw%20Data.csv)
- [Modified Dataset](https://github.com/iurwpoietknckvjndfsm-gndvkd/ML---Soil-Quality/blob/main/Data/Soil%20Fertility%20Data%20(Modified%20Data).csv)

### Atrributes
- N - ratio of Nitrogen (NH4+) content in soil 
- P - ratio of Phosphorous (P) content in soil 
- K - ratio of Potassium (K) content in soil 
- ph - soil acidity (pH)
- ec - electrical conductivity
- oc - organic carbon
- S - sulfur (S)
- zn - Zinc (Zn)
- fe - Iron (Fe)
- cu - Copper (Cu)
- Mn - Manganese (Mn)
- B - Boron (B)
- fertility: categorical (0 "Less Fertile", 1 "Fertile", 2 "Highly Fertile")

## Resource/Situational Constraints
- Lack of Data about our region
- Lack of some classes
- Lack of experience in agriculutral science

## Process followed 
- Searched for a dataset from another country
- Creating additional instances for the least appearing class 
- monitored by an experienced specialist

## Code 
1. Import liberaries and modules
2. Naive approuch with RandomForestClassifier and raw data(accuracy = 88%)
3. Data Exploration for modified data
4. Choose a model 
    - SupportVectorClassifier 
    - RandomForestClassifier 
    - GaussianNB 
    - KNeighborsClassifier 
    - DecisionTreeClassifier
5. GridSearch
6. Train a RandomForestClassifier (accuracy = 97%)
7. Save the model
