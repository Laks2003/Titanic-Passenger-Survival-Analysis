The goal of this task is to extract meaningful insights, detect patterns, anomalies, and correlations from the Titanic dataset using statistical and visual exploration methods with Python (Pandas, Matplotlib, Seaborn).  

**Tools & TechnologiesLanguage:** Python   

**Libraries:**
Pandas & NumPy (Data manipulation & numerical calculations)   
Matplotlib & Seaborn (Data visualization & plotting)   

**Environment:** Google Colab

**Data Inspection & Structure:** 
The dataset contains 891 passengers with 12 features.
Inspected data types, non-null counts, and summary statistics using .info(), .describe(), and .value_counts().   

**Univariate Analysis:**
Age Distribution: Passenger ages are roughly bell-shaped and right-skewed, centered around a mean of 29.70 years and a median of 28.00 years, with a notable cluster of infants and young children.
Fare Distribution: Ticket prices are severely right-skewed. While the median fare was $14.45, the mean fare was $32.20, driven by extreme high-value outliers paying up to $512.33.

**Bivariate & Multivariate Analysis:**
The correlation heatmap revealed that Pclass and Fare had a strong negative correlation, Pclass and Survived had a negative relationship, and Fare and Survived had a positive relationship
The multivariate pairplot showed clear separation by sex across most variables, with females surviving at much higher rates regardless of class or fare, while males in third class with low fares had the worst outcomes.

In summary, sex and passenger class were the two most powerful predictors of survival, fare served as a useful proxy for socioeconomic status.
