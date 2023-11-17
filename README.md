# Identify-key-factors-for-anemia-level-in-child
# Problem statement: 
Anemia levels in children has been a public health concern in most developing countries, due to the high level of prevalence and its importance in affecting future growth and development. This objective of this project was to identify determined factors that affects the anemia level in children in Nigeria using the dataset provided by Adeola Adesina. 
Data resource: https://www.kaggle.com/datasets/adeolaadesina/factors-affecting-children-anemia-level/discussion/453573

# Methodology: 
•	Data preprocessing: missing value and duplicated value checking;
•	Variables visualization: create seaborn barplot for categorical variables and histogram for continuous numerical variables;
•	Label encoding of categorical variables;
•	Feature selection: variance threshold and correlation matrix
•	Chi square test for target variable-anemia level in children
# Explanatory notes:
For the dataset, there are two columns with the same name – anemia level. After initial knowledge search, it was found that Blood hemoglobin level is most common diagnostic test for anemia. However, no clear descriptive information was provided from the data provider. Then I performed the classification model to find out the matching columns for mom’s and children. The results showed that the ‘anemia level_2’ are perfectly predicted from the ‘Hemoglobin level adjusted for altitude (g/dl - 1 decimal)’. Then for the ‘anemia level’ is from mother’s sample, and strongly predicted from the ‘Hemoglobin level adjusted for altitude and smoking (g/dl - 1 decimal)’. 
After clarifying these dataset questions, A chi square test was performed to identify the relationship between mothers' age, education level, wealth index, birth in the previous five years, use of mosquito net and the target variable: anemia levels in children. 
# Conclusion: 
It was found that ‘iron pills’ was significantly associated with the anemia level in children. 

