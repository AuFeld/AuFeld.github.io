---
layout: post
title: Transfermarket
subtitle: Football Player Procurement Analysis 
cover-img: /assets/img/path.jpg
gh-repo: AuFeld
tags: [football, english premier league]
---

An analysis of how well football clubs in the English Premier League procure players in the Transfermarket.

## Introduction

Thanks to lucrative TV Broadcasting deals for the rights to televise English Premier League (EPL) matches, club expenditures 
to acquire new players since 2010 has skyrocketed. The market to procure a player who is currently under contract by another
club is known as the Transfermarket.

In the 2010/2011 Season, football clubs in the EPL spent a total of $796m, an average of $39.84m per club, to acquire new
players. Fast forward to the 2017/2018 Season, when EPL clubs spent a record of $2.481b, an average of $124m per club, to
acquire new players from other clubs.

## Hypothesis Objectives

- Are football clubs in the English Premier League better at procuring players then others? 
- Identify club investment strategies for player acquisitions to achieve success in the EPL.

## Methodology

Implement quantitative data collected from the web to measure key metrics:

### 1. Correlation Values relating to:
#### - Club Expenditures per Season
#### - Points Earned per Season
### 2. Feature Weights relating to:
#### - Goals Scored
#### - Goals Conceded

## Results

Southampton, Tottenham, and West Hampton have the best positive correlation values of 0.25 and higher. This indicates that those clubs have a positive relationship between the money they spent to acquire new clubs and the immeadiate points returned in the same season. Fulham, Crystal Palace, and Aston Villa have recorded a strong negative relationship of -0.75 or greater between the money they spent to acquire new clubs and the immeadiate points returned in the same season. 

![EPL Expenditure Correlation Values](https://miro.medium.com/max/950/1*SxdtbtJL6qd54DWd94xgIw.png)

Since the 1995/1996 season, every EPL Club was identified as a 'Champion' or 'Relegated' (3 max) each season. In doing so, I was able to identify the features that corresponded to each label of 'Champion' or 'Relegated'. Excluding Goal Difference, Goals Scored had the highest feature importance when identifying key features relating to a 'Champion'. Again, excluding Goal Difference, Goals Conceded had the highest feature importance when identifying key features relating to clubs who were 'Relegated'. By identifying these key features we are able to determine that if a club wanted to focus purely on being 'Champions', then they should focus on acquiring players from the Transfermarket who will score goals. Since scoring goals costs money, teams with financial constraints should focus on acquiring defensive players to reduce the amount of goals conceded and decrease their chances of being 'Relegated'.

![Cost of Goals in the EPL](https://miro.medium.com/max/1400/1*S660ehGKfSyTzGjdQBy3xA.png)

## Link to My Work

![My Work](https://github.com/AuFeld/Transfermarket)
 
