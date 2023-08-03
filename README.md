# Home Credit Default Risk Analysis : Project Overview
![OIP (1)](https://github.com/vinayvascuri/Capstone6812/assets/121827398/b39e0c16-5d2e-45d5-a14f-4f1076daee62)

# Introduction:

Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.

# Business Problem:
The Business problem for the Home Loan Credit Risk analysis project is to build a predictive model that can assess the credit risk of individuals applying for home loans. Home Credit wants to minimize its risk exposure by identifying potential borrowers who are likely to default on its home loans. By analyzing historical loan data and borrower information, the goal is to create a model that accurately predicts whether a loan applicant is likely to default or not.

In a concise way we can say that the Business Problem is to:
#### Identify underserved individuals
#### Assess repayment ability
#### Predict high-risk clients


# Project Objective:
The project's objective is to develop a machine learning model that can effectively predict the creditworthiness of loan applicants for home mortgages. The model will be trained on historical loan data containing various attributes such as income, marital status,employment history, loan amount, and other relevant features. By using this historical data, the model will learn to recognize patterns and correlations that are indicative of a high or low credit risk.

To put it simply project's objective is to:

## Build a model to:
#### Effectively extend loans to creditworthy individuals and decline those with insufficient repayment ability.
#### Accurately assess and suggest the Home credit group regarding the applicant’s loan repayment capability


# Your group's solution to the business problem.

Our group's solution to the Home Credit Risk Analysis involved building a predictive model using machine learning techniques. Out of all the models employed, the Light Gradient Boosting (LGB) model followed by Random forest model turned out to be best models in assessing the creditworthiness of potential borrowers, particularly those with limited credit histories. The above two models received the best Kaggle score of .671 and .662 respectively.In this case, to address class imbalance in the dataset, we have used Upsampling and downsampling techniques.

The Top 3 features that helped in attaining the solution for the LGB model are 
DAYS_ID_PUBLISH, 
DAYS_REGISTRATION, 
DAYS_LAST_PHONE_CHANGE. 

We suggest HOME CREDIT group to disburse loans to the type of person

1) who is MARRIED, 
2) who has HIGHER EDUCATION, 
3) who is a BUSINESSMAN,
4) who OWNS A CAR and
5) who OWNS A APARTMENT OR HOUSE.
  
Persons who meet the above conditions are less likely to default.

Ultimately, our solution will contribute to Home Credit's mission of broadening financial inclusion and providing a positive borrowing experience for the unbanked population.

# Your contribution to the project

In the Home Credit Risk Analysis project, my primary contribution was to lead the data preprocessing and feature engineering stages. I collaborated with the team where we had brainstorming sessions on weekly basis in understanding of the dataset. I took the initiative of conducting the weekly meetings, assigning tasks to the team members which helped all the members to be on the same page throughout the project.  Further, I actively participated in EDA, Data cleaning, Model selection, evaluation, and interpretation, providing valuable insights and recommendations to enhance the model's transparency and fairness.

During the Modeling phase of the Home Credit Kaggle project, I made significant contributions by developing and implementing various models to predict loan repayment probabilities. Firstly, I worked on logistic regression model and contributed in combining all the machine learning models derived by the team members. Throughout the modeling phase, I conducted thorough evaluations using metrics such as Accuracy, ROC AUC score to assess model performance. These evaluations helped in selecting the most suitable models for deployment.Through careful analysis and transformation of the data, I engineered meaningful features that captured crucial insights into borrower's repayment abilities. 

Additionally, I played a key role in addressing class imbalance by applying a combination of upsampling and downsampling techniques to ensure a balanced training dataset for the predictive models. My efforts in optimizing the data representation and handling class imbalance significantly improved the model's performance in accurately predicting credit risk for the unbanked population.  Ultimately, my contributions contributed to Home Credit's mission of expanding financial inclusion and empowering clients with a positive and safe borrowing experience.

# The business value of the solution.

The business value of the Home Credit Risk Analysis project lies in its ability to significantly enhance Home Credit's lending operations and contribute to the company's mission of financial inclusion.

In numeric terms, the business value can be evaluated as follows:

1. *Default Prevention: Assuming the average mortgage in the portfolio is $200,000 and HomeCredit group grants 1000 loans per year. If historically 2% of loans defaulted and this model could prevent 50% of these, it would save the company 0.02*0.5*1000$200,000 = $2,000,000 per year.
   
2. *Improved Customer Satisfaction: Generally faster loan processing might increase the customer base. If Homecredit could attract even 1% more customers due to improved satisfaction, for a company processing 10,000 loans annually, this could equate to 100 additional loans. If the company earns a 1% origination fee on each loan of $200,000, this equates to 100$200,000*0.01 = $200,000 per year.

The actual savings will depend on the specifics of loan portfolio, the accuracy of the model, the cost of false negatives and positives, etc. Also, a 67% accuracy rate means that 33 out of every 100 predictions could be incorrect, which could lead to significant costs in terms of false negatives and positives. The company needs to take this into consideration when implementing the model. 


# Difficulties that your group encountered along the way.

Throughout the Home Credit Risk Analysis project, our group encountered several challenges that required careful consideration and problem-solving. The significant difference in the number of loan defaulters and non-defaulters made it challenging to build a model that could accurately predict both classes. One of the main difficulties was dealing with the class imbalance in the dataset. We had to experiment with various upsampling and downsampling techniques to strike the right balance between the classes without introducing bias or overfitting.

Moreover, interpreting and explaining the model's predictions was a significant challenge. As we used machine learning algorithms, understanding the decision-making process and providing transparent explanations for model predictions were not straightforward tasks. We dedicated considerable effort to employ model interpretability techniques and feature importance analysis to gain insights into the factors influencing credit risk predictions.

Additionally, the project had strict timelines and limited resources, which added pressure to meet deadlines and efficiently allocate tasks among team members. All the team members are either in Full-time job roles or in Internships at various organizations. Regular communication and collaboration were essential to overcome these time constraints and ensure the project's progress remained on track.

Overall, the difficulties we encountered in dealing with class imbalance, handling complex alternative data, interpreting model predictions, and managing project constraints were valuable learning experiences. By working collaboratively, seeking innovative solutions, and adapting our approaches, we successfully navigated these challenges and delivered a robust credit risk prediction model for Home Credit.

# What you learned in the project.

The Home Credit Risk Analysis project provided me with invaluable learning experiences across various aspects of data science and machine learning. Firstly, it is my first project deploying various machine learning models into a dataset which resulted in a good idea of how various machine learning models work. Also, I gained a deeper understanding of the challenges associated with imbalanced datasets and the importance of handling class imbalance effectively. 

The project also taught me the value of effective collaboration and communication within a team setting. Regular meetings, clear task allocation, and leveraging each team member's expertise were crucial for project success, particularly given the project's strict timelines and limited resources.

Overall, the Home Credit Risk Analysis project deepened my understanding of data science methodologies and their application in real-world scenarios. It enriched my skill set in handling imbalanced data, integrating diverse data sources, and interpreting complex machine learning models. The project's challenges and learning experiences have further motivated me to continue honing my data science expertise and contributing to impactful solutions in the field.


