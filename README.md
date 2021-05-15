# Admission_Predictor
### A ML Regression project to predict chance of an admit

This projects helps predicting the chance of an admit (in %) provided the following features:
1. GRE Scores: (Out of 340)
2. TOEFL Scores: (Out of 120)
3. University Rating: (Out of 5)
4. SOP Rating (Statement of Purpose): (Out of 5)
5. LOR Rating (Letter of Recommendation): (Out of 5)
6. CGPA: (Out of 10)
7. Research Opportunity:  (1 or 0)


Admission_Predict.ipynb file gives the walkthrough over the complete project. 
Model.pkl file is the saved pickle file of final model.
CaseStudy.csv is the csv file of Case Study considered for prediction

app.py file gives the walkthrough over the deployment of project in flask. 
LinearRegression.sav is the saved file of model used in flask.

plots folder contains the saved images of all plots of EDA and model performances


To run the prject, follow below steps:
1.  Create anaconda environment
2.  Activate environment
3.  >pip install -r requirement.txt
4.  >python app.py
5.  Navigate to URL http://localhost:5000


Please feel free to connect for any suggestions or doubts!!!


The credit for dataset used for training goes to https://www.kaggle.com/mohansacharya/graduate-admissions
The credit for image used in html file for background goes to https://blog.unpakt.com/wp-content/uploads/2017/06/63064200_l-education-graduation-and-people-concept-silhouettes-of-many-happy-students-in-gowns-throwing-mortarboards-in-air-1024x651.jpg
