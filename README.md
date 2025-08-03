# Supervised learning and Unsupervised learning
## Part 1: Predicting Building Energy Efficiency (Supervised Learning)
Scenario - You are working for an architecture firm, and your task is to build a model that predicts the energy efficiency rating of buildings based on features like wall area, roof area, overall height, etc.  
### code: Energy efficiency prediction.py  
In this exercise, you trained a RandomForestRegressor model to predict the energy efficiency of buildings based on features such as wall area, roof area, overall height, and glazing area.

## Expected Results
1.**Data Visualizations** - Scatter plots will show the relationship between each feature and the target variable (energy efficiency). Students should observe how changes in features may relate to energy efficiency, although with synthetic data, these relationships might not show clear trends.  
2.**Model Performance** - After training the model and making predictions, students will evaluate the model using Mean Squared Error (MSE). With synthetic data, the MSE value may vary, but it gives an idea of the average error in the model's predictions. The closer this value is to zero, the better the model's performance.  
3.**Prediction vs. True Value Plot** - The scatter plot comparing true values and model predictions should ideally show points along the diagonal line (y=x), indicating accurate predictions. Deviations from this line suggest prediction errors.  
4. Remember to delete the notebook instance.  
**True Values vs Predicted Values** of supervised model<img width="917" height="584" alt="image" src="https://github.com/user-attachments/assets/11c20f3c-85d7-4cb4-91aa-d4e5d38e50a6" />
## Part 2: Vehicle Clustering (Unsupervised Learning)
Scenario - You are working for an automotive company, and your task is to cluster vehicles into groups based on their features such as weight, engine size, and horsepower.  
### code: Vehicle Clustering.py  
In this exercise, you used KMeans clustering to group vehicles based on their features like weight, engine size, and horsepower.

## Expected Results  
1. **Cluster Visualization** - The scatter plot will visually depict how vehicles are grouped based on weight and horsepower. Each cluster will be represented by a different color. With synthetic data, the distinctness of clusters may vary, but students should be able to see groupings based on the chosen features.
2. **Interpreting Clusters** - There are no 'correct' labels in unsupervised learning, but students should observe how vehicles are grouped based on similarities in their features. They might see, for example, that heavier vehicles with higher horsepower are grouped together.
3.
4.   In both tasks, the exact numerical results can vary based on the randomness in the synthetic data generation and the inherent variability in machine learning models. The key learning outcome is understanding the process of applying machine learning techniques and interpreting the results, rather than achieving specific numerical accuracy or clustering results.
   <img width="628" height="457" alt="image" src="https://github.com/user-attachments/assets/1bcd0abd-7da4-4bfd-9db1-92fe8b108b84" />

