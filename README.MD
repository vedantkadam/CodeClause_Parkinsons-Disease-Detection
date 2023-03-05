# Parkinson's Detection using Machine Learning

- Parkinson's disease is a progressive disorder that affects the nervous system and the parts of the body controlled by the nerves. Symptoms start slowly. The first symptom may be a barely noticeable tremor in just one hand. Tremors are common, but the disorder may also cause stiffness or slowing of movement.

- To diagnose Parkinson's, a doctor will take a neurological history and perform an in-office exam. Although there are no standard diagnostic tests, some doctors may order imaging testing to help confirm a PD diagnosis in the early stages of the disease.


- DataSet Link - [Dataset](https://www.kaggle.com/datasets/dipayanbiswas/parkinsons-disease-speech-signal-features) 

## Library Used
- Numpy
- Pandas
- sklearn

## Models Used
```
models = {
    '           Linear SVM': LinearSVC(),
    '    Gradient Boosting': GradientBoostingClassifier(),
    '        Decision Tree': DecisionTreeClassifier(),
    '        Random Forest': RandomForestClassifier(),
    ' KNeighborsClassifier': KNeighborsClassifier(),
    '   Bagging Classifier': BaggingClassifier(),
    '                  svc':       SVC()
}
```
## Model Accuracy
```
Linear SVM: 85.53%
    Gradient Boosting: 82.24%
        Decision Tree: 78.29%
        Random Forest: 82.89%
 KNeighborsClassifier: 82.24%
   Bagging Classifier: 82.89%
                  svc: 83.55%
```

