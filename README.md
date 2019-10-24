# Final_Project

Using machine learning to predict the outcome of NFL games in an attempt to beat Vegas odds.

<b>Project Overview:</b>
<li> Use historical NFL scoring and spread data to predict outcome of future games.
<br></br>

<b>File Structure:</b>
<li> data: Historical NFL scoring and spread data as well as output CSV's from data cleaning.
<li> python: Scripts for data cleaning, aggregation, and machine learning.

<b>Steps for working model:</b>
<li> data_aggregation.ipynb (Takes data and changes format from a home team vs away team to favorite vs underdog. Flags created to mark winner and yearly total poihts for and against each team aggreageted on a weekly basis.)
<li> Final_Project_Football_Prediction_ML.ipynb (Takes aggreagated data and strips it to only the data relevant for training and testing, and then runs data through each ML model.)
