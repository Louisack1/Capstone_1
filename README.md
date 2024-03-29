## Capstone Project on Home Credit Default Risk Prediction.

Home Credit, with a mission to extend credit services to unbanked and underbanked groups traditionally deemed high-risk due to a lack of conventional credit history, employs predictive analytics to enhance risk assessment and ensure equitable credit access. This aligns with their goal of reducing loan defaults and fostering financial inclusion. 

This collaborative capstone project, undertaken by a team of four students from the University of Utah (David Eccles Business School), focuses on forecasting loan applicants' creditworthiness and repayment capacity. Leveraging a dataset from Home Credit containing telco and transactional data, the team utilizes exploratory data analysis, feature engineering, and machine learning techniques to construct predictive models, contributing to Home Credit's mission of responsible lending.
## Business Problem:

Since many prospective borrowers lack established credit histories, loans are unfairly withheld from them. By offering loans to these people, Home Credit hopes to address this issue, but it is difficult to determine with any degree of certainty how well they can be expected to return the loans. The business problem can be summarized as: How can Home Credit make sure that deserving customers with weak or no credit histories are not denied loans and that loans are designed to provide customers the best chance of successfully repaying them?

## Basic Methodology:

 - Cleaning and preprocessing.
 - Carrying out visual EDA for getting a general sense of data and understanding the relationships between various attributes.
 - Ascertaining critical attributes and their effect on target.
 - Applying ML models to predict default probability.

## Models Developed:

  - Random Forest
  - XGBoost
  - Logistic Regression
  - Naive Bayes

## Feature Selection and Model Building

![Models](https://github.com/Louisack1/Capstone_1/assets/144054790/5dd7e28a-0eab-424a-8fe9-6119ac02752b)


The logistic regression algorithm was our team's choice, given its exceptional accuracy in predicting outcomes, resulting in an impressive accuracy score exceeding 0.732 and a Kaggle score above 0.724. This success initiated a thoughtful discussion about the equilibrium between approving loans and minimizing defaults. 
However, our model initially displayed an underprediction of ruins compared to the actual outcomes in our training data, emphasizing the need to enhance the representation of default cases and navigate the trade-off between precision and minority class representation. Our comprehensive analysis pinpointed key variables crucial for forecasting loan repayment, guiding us to concentrate on gathering the most predictive data for future loan processing.

The precision of our predictive model is transforming the assessment of loan applicants, categorizing them with precision based on an extensive dataset of over 356,000 client records. This approach is instrumental in reducing default risk and facilitating credit access for individuals lacking traditional financial histories. 
It forms a vital strategy for consistently lowering default rates and promoting economic resilience in emerging markets. Moreover, it plays a crucial role in maintaining Home Credit's financial equilibrium as it expands financial inclusion while prudently managing default risk.

## Important Predictors:
EXT_SOURCE_1
EXT_SOURCE_2
EXT_SOURCE_3
CODE_GENDERM
FLAG_OWN_CARY
DAYS_EMPLOYED
DAYS_ID_PUBLISH
REGION_RATING_CLIENT_W_CITY 
NAME_CONTRACT_TYPERevolving loans 
FLAG_DOCUMENT_3
log_AMT_CREDIT 

![Important_Predictors](https://github.com/Louisack1/Capstone_1/assets/144054790/00da8441-54d0-4530-9ae4-eadfa466b3a9)


## Role:

My involvement in the project encompassed the creation of the Gradient Boost model, drafting the report, and assisting in developing the PowerPoint presentation.

## Challenges:

Our path was marked by various challenges, encompassing extensive data handling and addressing prolonged processing times. Additionally, we contended with issues related to feature imputation, resulting in an altered distribution of our features. 

## Experience from the project:

In this project, we gained valuable insights into the practical application of data analytics in real-time business scenarios. The experience was a challenging yet enlightening journey, grappling with the complexities of handling extensive datasets marked by significant missing data—tasks involved identifying key features and selecting the optimal model to devise a comprehensive business solution. 
The continuous commitment to a business-centric approach was a critical and enduring test of focus and strategy. Summing it up, this project was both enjoyable and immensely challenging.

## Conclusion:

This capstone project, focused on Home Credit Default Risk Prediction, was executed by a team of students from the University of Utah, David Eccles Business School. Utilizing exploratory data analysis, feature engineering, and machine learning techniques, the team successfully formulated predictive models for assessing the creditworthiness of loan applicants. The project is designed to improve decision-making within the lending industry and effectively address credit risks.

## Application in Lending Practices

The project's findings have direct applications in the lending industry, enabling the assessment of loan applicants' creditworthiness and forecasting their repayment abilities. Through the utilization of machine learning techniques, financial institutions can optimize decision-making processes, leading to more informed selections and a mitigation of default risks.

