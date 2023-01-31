# Predicting Lung Cancer
A healthcare company called Happy Health wants to determine someone's likelihood of Lung Cancer. I utilized this data set https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer to solve the issue.
The models used logistic regression and decision trees
![image](https://user-images.githubusercontent.com/110125695/214891810-e1cd01d9-f731-460b-a92b-7310533fc9f4.png)
# Business Understanding and Data Understanding
The industry was healthcare for this project. According to the CDC, age and smoking both increase the likelihood of having lung cancer.
I chose a data set that considered both features, in addition to age, yellow fingers, anxiety, peer pressure, chronic disease, fatigue, allergy, wheezing, alcohol, coughing, shortness of breath, swallowing difficulty, and chest pain.
# Modeling and Evaluation
I utilized logistic regression for the baseline model. I created another model with Decision Trees.
The Decision Tree model performed better. The baseline model had an accuracy of 88.46%. The decision tree model had an accuracy of 92.31%.
# Conclusion
I would recommend that the Decision Tree model would be used because it has a higher accuracy.
# Repository Navigation
The repository is split up into four sections: Business Understanding, Data preparation, Modeling, and Evaluation. In modeling, there are two sub-sections. 
One is for the baseline model. The other sub-section is for the decision tree model.

Links to the final notebook and presentation are here:
https://github.com/mayasandlin/CapstoneAI/blob/main/Predicting%20Lung%20Cancer.pptx
https://github.com/mayasandlin/CapstoneAI/blob/main/Predicting%20Lung%20Cancer.ipynb

To reproduce the data:
1. Find a data set
2. Transform any object datatypes to integers
3. Create x and y variables. X should be just the target variable. Y should be all other features.
4. Run the data through the code to test the accuracy.
