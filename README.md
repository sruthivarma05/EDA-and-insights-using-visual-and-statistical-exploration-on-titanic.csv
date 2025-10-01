# EDA-and-insights-using-visual-and-statistical-exploration-on-titanic.csv
This project analyzes the Titanic dataset to understand patterns of survival based on socio-economic status, gender, age, and family composition. It identifies key factors like class, fare, and gender that strongly influenced who survived.
The objective of this project was to extract insights from the Titanic dataset using visual and statistical exploration. I began by examining the basic structure and statistics of the dataset, including the number of rows, columns, data types, and summary statistics for all features. I also looked at value counts for key categorical columns like Survived, Pclass, Sex, and Embarked to understand their distributions.

Next, I assessed missing data using a heatmap, which highlighted gaps in columns like Age and Cabin. I then explored numeric features by creating histograms and boxplots to understand their distributions and detect outliers. Correlation analysis and a heatmap helped identify relationships between numeric features, especially with Survived.

To visualize interactions, I created a pairplot of numeric features colored by survival and a scatterplot of Age versus Fare. These visualizations helped reveal patterns such as how survival varied with socio-economic status and age.

Key Findings

Females had a much higher survival rate than males.

Passengers in higher classes (lower Pclass numbers) and those paying higher fares were more likely to survive.

Family size had a mixed effect; larger families sometimes had lower survival chances.

Age and Fare distributions were skewed, with children and high-paying passengers showing slightly better survival.

Correlation analysis confirmed that Pclass, Fare, and Sex were the strongest predictors of survival.

Overall, this exploratory analysis provided a clear understanding of the factors influencing survival on the Titanic and laid the groundwork for predictive modeling.
