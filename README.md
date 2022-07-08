# Mechanical Properties Prediction
<h3> Motive </h3>
To predict the mechanical properties of steel like Tensile Strength, Yield Strength, (%) Elogation & Reduction in Area (%) by its doping elements percentage.
<h3> Process </h3>
1. Used MatNavi Dataset of Mechanical Properties of Low alloyed Steels. <br>
2. Data preprocessing like checking null values & renaming columns with appropriate names. <br>
3. EDA by checking correlation and skewness of features. Some features are highly skewed and Correlated. <br>
<h6> Linear Regression </h6>
4. Performing Linear Regression after removing some correlated features. <br>
5. R<sup>2</sup> score by Linear Reg. for four dependent features are 0.82, 0.50, 0.46, 0.38. 
<h6> Lasso Regression </h6>
6. As R<sup>2</sup> score is not satisfactory in this, so performed Lasso Regression considering all features becauce Lasso auto penalise the features. <br>
7. R<sup>2</sup> score by Lasso for four features are 0.82, 0.59, 0.22, 0.19. <br>
<h6> Random Forest Regression </h6>
8. As Lasso R<sup>2</sup> score is also unsatisfactory, hence approached for Random Forest Regression as it uses multiple Decision Trees. <br>
9. R<sup>2</sup> score by RFG for four features are 0.92, 0.95, 0.86, 0.83.
<h3> Conclusion </h3>
The random forest regressor performs better in each category and overall as compared to Linear and Lasso Regression. Being computationally advance and highly versatile to fit itself on a complex data, this model makes for an ideal choice for prediction of mechanical properties of low-alloy steels with mean R<sup>2</sup> score of 0.89 which is significant. All the four properties of steel like Tensile Strength, Yield Strength, (%) Elogation & Reduction in Area (%) can be predicted with high accuracy.
