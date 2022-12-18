## Medical Cost Analysis
This is a guided project aiming to estimate the approximate cost of health insurance of individuals based on the given personal information. The dataset link: https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv
### Content of the Dataset
Columns:
- age: Age of primary beneficiary
- sex: Insurance contractor gender: female, male
- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg/m $^2$ ) using the ratio of height to weight, ideally 18.5 to 24.9.
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking habit: yes, no
- region: The beneficiary's residential area in the US: northeast, southeast, southwest, northwest
- charges: Individual medical costs billed by health insurance
### Tasks
1. Perform an exploratory data analysis.
    - Examine the distribution of BMI(body mass index).
    - Examine the relationship between "smoker" and "charges".
    - Examine the relationship between "smoker" and "region".
    - Examine the relationship between "bmi" and "sex".
    - Find the "region" with the most "children".
    - Examine the relationship between "age" and "bmi".
    - Examine the relationship between "bmi" and "children".
    - Is there an outlier in the "bmi" variable?
    - Examine the relationship between "bmi" and "charges".
    - Examine the relationship between "region", "smoker" and "bmi" using bar plot.
2. Data Pre-processing
    - Use label encoding and one-hot encoding techniques to deal with categorical data.
    - Split the dataset into train and test data.
    - Scale the dataset by normalizing(min-max or standard scaling).
3. Model selection
    - Select several regression models and train them.
    - Examine the performances of the selected models using cross validation.
    - Optimize the hyper-parameters of the model selected in the previous step.
    - Optimize parameters with grid search or randomized search.
4. Evaluate the optimized model using regression model evaluation metrics. (Ex. MSE, MAE)
