# PLAICRAFT: Minecraft Player Behavior Modeling
This project analyzes player activity on a specialized Minecraft server used for research at the University of British Columbia (UBC). By modeling behavioral patterns—such as play frequency, gender, and experience levels—we developed a predictive framework to identify players most likely to subscribe to newsletters and contribute data to the study.

**Project Scope**
Managing player retention and data contribution is a key challenge for research-based game servers. This analysis identifies the "signature" behaviors of high-engagement players to help researchers optimize recruitment and communication strategies.

**Technical Workflow** 

Directed a team of four to implement a full-stack data analysis pipeline in R:
- Data Cleaning & EDA: Processed raw player logs using the Tidyverse to handle missing values and engineer features related to player experience.
- Feature Selection: Applied Best Subset Selection to isolate the most statistically significant behavioral predictors, ensuring a lean and interpretable model.
- Machine Learning: Implemented K-Nearest Neighbors (KNN) classification to predict subscription intent.
- Optimization: Utilized the tidymodels framework for cross-validation and hyperparameter tuning of $k$ to maximize predictive accuracy.

**Key Findings** 
- Predictive Accuracy: Successfully identified key correlations between player "experience levels" and their likelihood of subscribing to community newsletters.
- Strategic Insights: Discovered that specific early-game milestones are stronger predictors of long-term engagement than total playtime alone.

**Tech StackLanguage:**
- RLibraries: tidyverse, tidymodels, repr, ggplot2
- Environment: Jupyter (IRkernel)
