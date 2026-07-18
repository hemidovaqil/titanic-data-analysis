# titanic-data-analysis
Titanic dataset analysis using Python (EDA)
## Data Cleaning
- Age → median
- Embarked → mode
- Fare → median
- Cabin → dropped
#3. Outlier Detection
    Conclusion
#4. Feature Engineering

In this step, new features were created to improve data representation:

- **FamilySize** = SibSp + Parch + 1  
  Represents the total number of family members aboard.

- **IsAlone**  
  Binary feature indicating whether a passenger was traveling alone (1 = alone, 0 = not alone).

These features help capture social structure and may improve model performance.