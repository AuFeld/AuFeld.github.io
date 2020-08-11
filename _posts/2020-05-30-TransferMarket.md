---
layout: post
title: Transfermarket
subtitle: Football Player Procurement Analysis 
cover-img: /assets/img/path.jpg
gh-repo: AuFeld
tags: [football, english premier league]
---


# Introduction

The market to procure a player who is currently under contract by another club is known as the Transfermarket. Thanks to lucrative TV Broadcasting deals for the rights to televise English Premier League (EPL) matches, club expenditures to acquire new players since 2010 has skyrocketed.  In the 2010/2011 Season, football clubs in the EPL spent a total of $796m, an average of $39.84m per club, to acquire new players. Fast forward to the 2017/2018 Season, when EPL clubs spent a record of $2.481b, an average of $124m per club, to acquire new players from other clubs.

![EPL Transfermarket Expenditures per Season](https://miro.medium.com/max/790/1*Eljiu83E74Zd7ZTpBLiUKA.png)

# Hypothesis

Football club's expenditures in the Transfermarket has no immediate impact of points earned in the English Premier League. 

--- 

# Methodology

Implement quantitative data collected from the web to measure key metrics:

### 1. Correlation Values relating to:
- Club Expenditures per Season
- Points Earned per Season

### 2. Corrlation Values:
+1.0 = a perfect positive relationship between two variables  <br>
+0.7 = a strong positive relationship  <br>
+0.5 = a moderate positive relationship  <br>
+0.3 = a weak positive relationship  <br   >
   0 = no relationship between two variables  <br>
-0.3 = a weak negative relationship  <br>
-0.5 = a moderate negative relationship  <br>
-0.7 = a strong negative relationship  <br>
-1.0 = a perfect negative relationship between two variables  <br>


# Results

Southampton, Tottenham, and West Hampton have correlation values of 0.25 and higher. This indicates that those clubs have a weak positive relationship between the money they spent 
to acquire new players in the Transfermarket and the immeadiate points returned in the same season. Fulham, Crystal Palace, and Aston Villa have recorded a strong negative
relationship of -0.75 or greater between the money they spent to acquire new clubs and the immeadiate points returned in the same season. 

![EPL Expenditure Correlation Values](https://miro.medium.com/max/950/1*SxdtbtJL6qd54DWd94xgIw.png)


# Conclusion

For every club in the EPL that has appeared in five seasons or more since the 2010/2011 season, there are only strong negative correlation values between money spent in the Transfermarket and the immeadiate points earned in the same season. It is evident that the null hypothesis is incorrect and should be rejected.  


***


## Further Application of Study: 
<br>

#### Expenditure Strategy in the Transfermarket

Since the 1995/1996 season, every EPL Club was identified as a 'Champion' or 'Relegated' (three clubs are relegate) each season. In doing so, I was able to identify features that
correspond to each title of a club being a 'Champion' or 'Relegated'. Excluding Goal Difference, Goals Scored had the highest feature importance when identifying key features
relating to a 'Champion'. Again, excluding Goal Difference, Goals Conceded had the highest feature importance when identifying key features relating to clubs who were 'Relegated'. 
By identifying these key features we are able to determine that if a club wanted to focus purely on being 'Champions', then they should focus on acquiring players from the
Transfermarket who will score goals. Since scoring goals costs money, teams with financial constraints should focus on acquiring defensive players to reduce the amount of goals
conceded and decrease their chances of being 'Relegated'.

![Cost of Goals in the EPL](https://miro.medium.com/max/1400/1*S660ehGKfSyTzGjdQBy3xA.png)

--- 

# Tech Stack

#### Jupyter Notebook | Scikit-learn | Matplotlib | Seaborn | Eli5

# Link to My Code

[My Code](https://github.com/AuFeld/Transfermarket)
 
