 # Service prediction applying logistic regression
###Project objective
 - **Primary Objective:**: 
 The main goal of this project is to predict whether a client will hire the service based on data from the last marketing campaign. We aim to determine this by analyzing client descriptions that are similar to those of previous campaign participants.
 - **Secondary Objective**: 
 A secondary objective is to identify the characteristics of the predictive model that have the most significant influence on decision-making. This will provide a clearer understanding of the client profile.
#### Dataset Overview: 
I utilized the "Bank" dataset obtained from Kaggle. This dataset contains detailed information regarding a previous marketing campaign for a bank service, encompassing various client characteristics and campaign specifics. The variable "deposit" indicates the client's decision regarding service hiring.
####Project Development: 
I am currently developing my first project in data analysis and data science, making this a valuable challenge where I can consolidate the knowledge I've gained since I began my studies in January 2024. The project process includes the following steps:
Data Preparation:
After downloading the dataset, I performed an initial data cleaning process to ensure quality and consistency.

- **Exploratory Data Analysis (EDA):
**I conducted EDA to identify significant variables for analysis. This involved examining how different characteristics interact with the "deposit" decision and understanding the underlying story behind the data. This step allowed me to pinpoint the categories I wanted to analyze further and incorporate into the model.

- **Model Development:
**I proceeded to build the first predictive model using logistic regression. I applied one-hot encoding and eliminated irrelevant characteristics that did not contribute meaningfully to the model's predictive power.

- ** Model Evaluation:
**Achieving a 66.68% success rate with the model was a significant milestone, especially compared to previous attempts. Encouraged by this result, I conducted A/B testing and analyzed the coefficients to refine my understanding of the model's performance.

- **Refinement**:
I developed a second predictive model, incorporating more accurate information regarding causality and correlation. However, the results did not significantly differ from the first model.

- **Results Visualization:**
Finally, I visualized my results using the ROC curve method, providing a comprehensive view of the model's performance.
