# MiningProcessProject
The main goal is to use this data to predict how much impurity is in the ore concentrate. 

**Mining Process Flotation Plant Database**

As this impurity is measured every hour, if we can predict how much silica (impurity) is in the ore concentrate, we can help the engineers, giving them early information to take actions (empowering!). Hence, they will be able to take corrective actions in advance (reduce impurity, if it is the case) and also help the environment (reducing the amount of ore that goes to tailings as you reduce silica in the ore concentrate).

More Information on the dataset: 

The first column shows time and date range (from march of 2017 until september of 2017). Some columns were sampled every 20 second. Others were sampled on a hourly base.

The second and third columns are quality measures of the iron ore pulp right before it is fed into the flotation plant. Column 4 until column 8 are the most important variables that impact in the ore quality in the end of the process. From column 9 until column 22, we can see process data (level and air flow inside the flotation columns, which also impact in ore quality. The last two columns are the final iron ore pulp quality measurement from the lab.
Target is to predict the last column, which is the % of silica in the iron ore concentrate.

**Objectives**

- Is it possible to predict % Silica Concentrate every minute?

- How many steps (hours) ahead can we predict % Silica in Concentrate? This would help engineers to act in predictive and optimized way, mitigatin the % of iron that could have gone to tailings.

- Is it possible to predict % Silica in Concentrate whitout using % Iron Concentrate column (as they are highly correlated)?

 Source of data: **Kaggle**

 **Project plan**

1. Data Exploration and Preprocessing 
     - Python: clustering and anomaly detection 
    
2. Correlation Analysis

3. Normalization

4. Variable 
    - Linear Regression
    - Random Forest
    
5. Partition of the data 

6. Evaluation metrics

7. Naive Benchmark 

8. Machine Learning 
    -selected methods: ,,.......
        
9. Sensitivity Analysis 
