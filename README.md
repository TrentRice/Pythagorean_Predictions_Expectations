# Pythagorean Expectation for Prediction in Python

##Background

The Pythagorean expectation is a sports analytics formula (originally devised by Bill James) that uses a team’s scoring data (runs, goals, or points scored and allowed) to estimate its expected winning percentage. 

In its simplest form the formula: (score for)^2 / ((score for)^2 + (score against)^2) 

Although it was developed originally for baseball, the same concept can be adapted to many leagues. In each case, a Pythagorean formula predicts how a team’s scoring differential should translate into wins. This approach is highly relevant in modern sports analytics because it provides a clear, data-driven baseline for team performance. By comparing a team’s actual record to its Pythagorean expectation, analysts can identify teams that have over-performed or under-performed relative to their scoring. Such discrepancies often signal luck, efficiency, or misfortune and can help forecast regression or improvement in subsequent blocks of games or seasons. 

##Data Analysis
The Pythagorean_Predictions_Expectations repository brings these ideas into Python across multiple sports. It contains code and example analyses for major leagues including NHL hockey, IPL cricket, MLB baseball, NBA basketball, and English soccer, computing each team’s Pythagorean win rate and comparing it to the actual results. 

This enabled rich exploratory data analysis to be conducted such as regression techniques and data visualization. The project shows how the Pythagorean formula performs in different scoring contexts proving to be better for prediction in certain sports than others, however more often then not showing strong results. 

In short, this repository is a hands-on example of applied analytics, bridging raw sports data with predictive modeling in a way that is useful, and directly relevant to the sports data community.
