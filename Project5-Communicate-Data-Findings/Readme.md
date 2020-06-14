
## Titanic Survival Data Exploration

### Dataset

RMS Titanic was a British passenger liner operated by the White Star Line that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after striking an iceberg during her maiden voyage from Southampton to New York City. Of the estimated 2,224 passengers and crew aboard, more than 1,500 died, making the sinking one of modern history's deadliest peacetime commercial marine disasters.

The dataset used for this project consists of various information on 891 passengers that were aboard the ship. The information include: Passenger id, Name, survival (Yes or No), Ticket class, Sex, Age, relatives/siblings, Cabin and Embarkment. The data can be found at [Titanic Train Data](https://www.kaggle.com/c/titanic/data?select=train.csv)

#### Key Notes:
- Survival - 0 (No), 1 (Yes)
- Pclass - Ticket Class (1,2,3) - (1st class, 2nd class, 3rd class)
- Embarked - Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

### Summary of Findigs from exploration:
- Majority of the passengers on board were youths between the age 20 to 30 years, most of which were boarding third class.
- There were more males on board then females
- Majority of the passengers embarked from Southampton
- Distribution of the Fare is unimodal and rightly skewed, with majority of the passengers paying between 5 to 25 pounds
- Correlation between Age and Fair is positive, but very weak.
- When Survival is compared with Age, Majority of the passengers that survived are between the ages 20 and 40 years. Same with those that did not survived. This is quite expected as that is the age range that forms majority of the passengers on the ship
- A higher proportion of passengers in 1st class survived, compared to that of 2nd and 3rd class
- A higher proportion of females survived, compared to males
- Having siblings/spouse seems not to affect survival rate, because even passengers with siblings/spouses did not have a higher proportion of survival.
- Passengers with parent/child have a slighly higher proprtion of survival.
- A higher proportion of passengers within the age bracket 15 and 50 years, and who paid fare higher than 70 pounds survived.

### Key insights for Explanatory visualisation / Presentation
- My focus is majorly on how several features of the passangers relate to survival. Features like (Age, having relatives, Fare paid, ticket class and sex)
- Other insights from the data are distribution of the passengers in terms of age, fare and sex.
- Histogram and bar charts were used for univariate visualizations
- Scatter plot, Violin plot and Clustered Bar Charts were used for bivariate visualizations
- FacetGrid was used for multivariate visualizations.


```python

```
