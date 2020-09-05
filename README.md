# Contraceptives-Data-Analysis
This project analyses a dataset to determine a correlation between women’s age and their use of contraceptives. It also predicts the use of contraceptives based on some attributes.

# Introduction

To measure the effectiveness of Indonesia’s National Family Planning Program and subsequently improve the program, the National Indonesia Contraceptive Prevalence Survey (NICPS) collected data on fertility and family planning in 1987. The survey was designed to simultaneously measure contraceptive prevalence and fertility, and the factors that influence these outcomes, such as education and availability of contraceptives. We used the data from this survey, retrieved from the UCI Machine Learning Repository, for our final project.

The participants in the survey were married women between the ages of 15-49, that were either not pregnant or didn’t know they were at the time of the interview. Although 11,884 women were interviewed, the dataset we explored is a random subset of 999 of these participants. Each row in our dataset represents one of these women through a unique ID.

Our dataset is divided into two tables: participant and family_background. The participant table provides information on a participant’s demographics, like education level, religion, etc. and contraceptive method choice. The key variable here is Wife age, which gives us the ages of all the participants in the survey. Data on the number of children (Num children) ever born to each participant is also of interest to us. Both of these variables are quantitative.

The family background table provides information on a woman’s husband’s characteristics along with other demographics like media exposure and standard of living. The variables we explore further are Husband education and Husband occupation. Husband education gives us the level of each participant’s husband’s education from 1 to 4, 1 being low and 4 being high. Husband occupation describes the occupation the husband is involved in based on predefined categories, 1 being professional, technical or clerical work; 2 being sales/services; 3 being manual labor and 4 being agriculture. Both of these variables are categorical.

# Hypothesis Testing and Prediction Questions

By combining both of the tables in this dataset, we can study the relationships between a participants' demographics, husband's lifestyle, and her contraception usage. We are particularly interested in exploring how a wife's age may be associated with her use of a contraceptive.

In particular, we are interested in determining whether there is an association between a wife's age and her use of contraceptives. Our null hypothesis is that there is no relationship between these two variables. Our alternative hypothesis is that there is a association between these variables, and, in particular, younger women are more likely to be using contraceptives compared to older women.

Relatedly, we wish to determine whether family characteristics like woman's age, number of children, and other attributes like husband education and occupation can be used to predict whether or not a woman uses a contraceptive. We employ the K- Nearest Neighbors classifier method to accomplish this task.
