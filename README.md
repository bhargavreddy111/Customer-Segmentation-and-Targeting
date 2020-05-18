# Customer-Segmentation-and-Targeting
As a service industry, banking sector has seen success in using machine learning to target their customers with appropriate marketing strategies. By analyzing customers’ transactional data and needs, banks can understand their current customers better and also expect their future ones. In detail, machine learning techniques help banks to improve their business by reaching out to different customer segments with customized loan scheme offerings. In this project, I have initially done exploratory data analysis to understand what factors could possibly influence a potential customer and then moved to use clustering techniques to split the customer data into 3 segments. Finally, I tried to predict whether an existing customer will be accepting personal loan offer using Decision Tree and Random forest models. I have managed to achieve an accuracy of 98.4% with the best performing model.

Data Description

ID: Customer ID (unique)
Age: Customer's age
Experience: Number of years of professional experience
Income: Annual income of the customer in $1, 000
ZIP Code: Customer's home address ZIP code
Family: Number of customer's family member 
CCAvg: Customer's average spending on credit cards per month in $1,000
Education: Customer's education Level (1: Undergrad; 2: Graduate; 3: Advanced/Professional)
Mortgage: The value of house mortgage in $1,000
Personal Loan: If this customer accept the personal loan offered in the last campaign? (1 - Yes, 0 - No)
Securities Account: Does the customer have a securities account with the bank? (1 - Yes, 0 - No)
CD Account: Does the customer have a certificate of deposit (CD) account with the bank? (1 - Yes, 0 - No)
Online: Does the customer use internet banking facilities? (1 - Yes, 0 - No)
CreditCard: Does the customer use a credit card issued by this Bank? (1 - Yes, 0 - No)
