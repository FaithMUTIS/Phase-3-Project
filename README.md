# Phase-3-Project
## **Background**

Terry v. Ohio, a landmark U.S. Supreme Court case decided in 1968, established the principle of **"reasonable suspicion,"** which allows police officers to temporarily detain individuals based on suspicious behavior, even in the absence of probable cause required for arrest. These stops, known as **Terry Stops**, have become a standard police practice, particularly in situations involving suspicious drivers. While Terry Stops are intended to prevent crime and ensure public safety, they have also raised significant concerns about potential bias in law enforcement, particularly regarding **race and gender**.

In recent years, the role of race and other demographic factors in policing has come under intense scrutiny. Research has suggested that certain demographic groups may be disproportionately affected by police practices, leading to questions about the fairness and objectivity of these interactions. This project aims to explore these issues by building a machine learning classifier to predict whether an arrest was made during a Terry Stop are affected by presence of weapons, time of day, gender, and race.

## **Problem Statement**

While Terry Stops are legally justified under the principle of "reasonable suspicion," there is ongoing debate about whether these stops are conducted in a manner that is free from bias. The core problem this project seeks to address is whether certain factors, particularly race and gender, disproportionately influence the likelihood of arrest during a Terry Stop. Understanding these dynamics is crucial for law enforcement agencies, policymakers, and the public as they work to ensure that policing practices are fair, transparent, and just.

This project will focus on developing a classification model to predict arrest outcomes during Terry Stops. The model will analyze various factors, including demographic information, to determine which variables most strongly influence the likelihood of an arrest. By doing so, the project aims to shed light on potential biases in policing practices and offer insights that could guide more equitable law enforcement strategies.

## **Objectives**

1. **Data Exploration and Understanding**:
   - This will involve analyzing the distribution of key variables, particularly those related to demographics such as race and gender, as well as other critical factors like the presence of weapons and the time of day. Additionally, any data quality issues, such as missing values or outliers, will be identified and appropriately addressed to ensure the reliability of the analysis and subsequent modeling.

2. **Model Development**:
   - Build a baseline classification model using logistic regression to predict whether an arrest was made during a Terry Stop.
   - Develop a decision tree model as an alternative approach, comparing its performance with the logistic regression model.

3. **Feature Importance Analysis**:
   - This will involve identifying the most influential features in predicting arrest outcomes, with particular attention given to demographic factors such as race and gender. Sensitivity analyses will be performed to assess how changes in these key features impact the model’s predictions, providing deeper insights into the factors driving arrest decisions during Terry Stops.

4. **Evaluation of Model Performance**:

   - This will be done using appropriate classification metrics, including accuracy, precision, recall, and the F1 score.  By comparing the performance of the logistic regression and decision tree models, the project will determine the most effective approach for predicting arrest outcomes in the context of Terry Stops.

5. **Ethical Considerations and Recommendations**:
   - Discuss the ethical implications of using demographic data in predictive policing models, with a focus on the potential for bias and discrimination.
   - Provide recommendations for law enforcement agencies based on the findings, aimed at promoting fairer and more transparent policing practices.