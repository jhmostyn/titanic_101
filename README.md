# titanic_101

Uploaded as a reminder of where my Data Science studies started, here is my first crack at Titanic: Machine Learning from Disaster <https://www.kaggle.com/c/titanic>

# Positives

1. It scores in the low eighties, along with most of the regular kaggle submissions, however it isn't Kaggle-compliant because of my favourite feature..

2. Impution of missing ages, by web scraping a titanic website (<http://www.titanicfacts.net/>), and using the Levenshtein distance to match inconsistences in the names across the data sources, removing a manual step. The results aren't perfect, but it's a cute proof of concept of how Data Science concepts, and a little creativity, can be used to solve the wrangling steps.

# Negatives

1. Re-running the code, the biggest newbie mistake is up for debate, but I'd give it to using brute force to calculate the results of every combination of features. Running tens of thousands of logistic regression models is far, far less elegant than the variety of computational, or even manual, feature selection methods, however this was a learning exercise!

2. A consistent cross validation method really should have been used throughout, instead of, in some cases, a test train split and cross validation (!?)

3. I see a distinct lack of random state seeding, reducing the repeatability of results.

4. I could go on :)
