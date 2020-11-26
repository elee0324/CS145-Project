# CS145-Project: Studying the Impacts of Health and Well-Being on Education Level Worldwide
Fall 2020

# Introduction 

Having a population with access to education is known to be one of the main factors that predict well-being and happiness on a nationwide level, so we wanted to see
what factors may affect a population's ability to attend school. We aimed to analyze the World Bank's Health Population Dataset by studying the various factors that impact the level of education attainable in different countries. Some of these factors include access to healthcare, measured by expenditure on healthcare per capita, and the prevalence of certain diseases or health conditions. We found that our model accurately predicted whether a country had a high vs low enrollment rate for children under 18 (defined as above or below the average) with an accuracy of 0.964.

Our project consisted of four steps (all found in the ipynb notebook):
1. Explore the Health Population dataset through queries using MySQL and create visualizations
2. Split the data into train, eval, and test sets and extract appropriate features (engineered and raw)
3. Train logistic regression model, iterate to improve, and make predictions
4. Draw conclusions based on our queries and model results
