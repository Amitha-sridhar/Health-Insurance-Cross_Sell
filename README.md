**ML-Capstone-Health-Insurance-Cross-sell-Prediction**
**Introduction:-**
Insurance is a means of protection from financial loss in which, in exchange for a fee, a party agrees to guarantee another party compensation in the event of a certain loss, damage, or injury. The amount of money charged by the insurer to the policyholder for the coverage set forth in the insurance policy is called the Premium.

Vehicle insurance (also known as car insurance, motor insurance, or auto insurance) is insurance for cars, trucks, motorcycles, and other road vehicles. Its primary use is to provide financial protection against physical damage or bodily injury resulting from traffic collisions and against liability that could also arise from incidents in a vehicle.
**Problem Statement:-**
Our client is an Insurance company that has provided Health Insurance to its customers. Now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company. Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimize its business model and revenue.
**DATASET:-**
Now, in order to predict, whether the customer would be interested in Vehicle insurance, we have information about following parameters

-> id : Unique ID for the customer
-> Gender : Gender of the customer
-> Age : Age of the customer
-> Driving License 0 : Customer does not have DL, 1 : Customer already has DL
-> Region Code : Unique code for the region of the customer
-> Previously Insured : 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance
-> Vehicle Age : Age of the Vehicle
-> Vehicle Damage :Yes : Customer got his/her vehicle damaged in the past. No : Customer didn't get his/her vehicle damaged in the past.
-> Annual Premium : The amount customer needs to pay as premium in the year
-> Policy Sales Channel : Anonymized Code for the channel of outreaching to the customer i.e. Different Agents, Over Mail, Over Phone, In Person, etc.
-> Vintage : Number of Days, Customer has been associated with the company
-> Response : 1 : Customer is interested, 0 : Customer is not interested
Our data set contains 381109 rows and 12 columns. We have 5 numeric and 6 categorical independent features.
**Workflow:-**
The workflow of this problem is divided into following sections-

I. Data Study - First, we will import python libraries such as NumPy and Pandas required to perform the study and then load the CSV file. Later we will perform some operations to understand and analyze the data.
II. Data Manipulation - Since Dataset contains int64, float64, object type of data and no Null Values in the Dataset, hence cleaning is not needed. We have handled outliers using the IQR method.
III. Correlation Graph
IV. EDA and Visualisation
V. Data Processing
**VI. Model Building**
-> Decision Tree Classifier- Decision tree is a flowchart-like tree structure, where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node (terminal node) holds a class label.
-> Random Forest Classifier- The random forest algorithm is made up of a collection of decision trees, and each tree in the ensemble consists of a data sample drawn from a training set with replacement, called the bootstrap sample.
-> XgBoost Classifier- XGBoost, which stands for Extreme Gradient Boosting, is a decision-tree-based ensemble Machine Learning algorithm that uses a gradient boosting framework and provides parallel tree boosting.
-> Naive bayes Classifier- A Naive Bayes classifier is a probabilistic machine learning model based on Bayes' Theorem that is used for classification task.
-> K Nearest neighbors(KNN)- The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.
-> Light Gradient Boosting(LGBM)- LightGBM is a gradient boosting framework based on decision trees to increases the efficiency of the model and reduces memory usage.
**VI. Comparison Metrics**
**VII. Conclusion:-**

-> Males prefer to take Vehicle Insurance as compared to Females.
-> Middle Age Population(30-50 yrs) are more likely to take Vehicle Insurance.
-> Majority of people are interested in paying an annual premium in the range of 30k-40k(High Premium).
-> Sales Channels 140-160 is the most contacted channel among all the channels and it has provided highest no. of conversion.
