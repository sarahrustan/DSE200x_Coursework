# Exploring attitudes towards opioids using k-modes clustering algorithm

_Objective:_ To inform jury selection strategy by identifying clusters of demographic and experiential variables that are associated with attitudes towards opioids.

_Data:_ 2018 proprietary national survey (_n_ = 1,200); 2015 ZIP Code Tabulation Areas Gazetteer File (_N_ = 33,144); B25001 HOUSING UNITS by ZCTA, 2012-2016 American Community Survey 5-Year Estimates (_n_ = 33,120) 

_Methods:_ Combine data from mutiple sources to create a variable identifying each survey response geography as urban, suburban, or rural. Conduct cluster analysis using k-modes clustering algorithm (an unsupervised machine learning algorithm for categorical variables) to determine whether there are clusters of demographic and experiential variables associated with attitudes towards opioids, including urban, suburban or rural geography.

_Results:_ Three distinct groups of survey respondents were identified. The first two groups embody attitudes typical of plaintiff- and defense-oriented jurors in similar cases, while the third group appears to have demonstrated a significant acquiescence bias, which is a tendency to either answer 'Yes' or choose the first response option given. 

As shown in the attached notebook, the graph representing the costs associated with different number of clusters indicates that the 'elbow' occurs at three clusters; in other words, the amount that model fit improves with the addition of each additional cluster decreases after three clusters. This suggests that three clusters is the ideal number for this analysis. However, since identifying differences in attitudes between sub-groups of plaintiff- or defense-oriented jurors could prove useful in framing the case, future research could include using the k-modes clustering algorithm for 4 (and possibly more) clusters.
