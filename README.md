# Data Visulization:

## Notes:
* we can do it using seaborn ```import seaborn as sns ```
* Seaborn is a tool used on top of Matplotlib, it can pretty iy up
* useful methods:
 1. ```sns.set()``` to give a them
 2. `sns.load_dataset` : seaborn has some handy data sets we can use
 3. to load one of them:
 `sns.get_dataset_names()` `mpg = sns.load_dataset("mpg")`
 4. `sns.barplot(x="origin",y="mpg",data=mpg_by_origin)`
 5. `sns.countplot(data=mpg, x="cylinders")`
 6. `sns.relplot(x="model_year",y="mpg",data=avg_mpg)`
 7. `sns.lmplot(x="year",y="passengers",data=year_sums)`  to make some prediction 
 8. ` g.set_xticklabels(labels=list(month_abbr)[1:]) `
`