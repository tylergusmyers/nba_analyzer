# Nba_Analyzer

## Brief:
We are hoping to answer if there is any hope in our fantasy leagues by following what the experts do- that is selecting basketball players that are paid more than their peers, picking the players for our lineups that the real life General Managers pay for there players? What does a players salary tell us about their fantasy performance? 
    
Maybe this will help us think following the experts into high expense funds, when there is often a low cost option readily available.. or maybe GM's in the NBA should look at our application when deciding how much they should pay their own Free Agents?


## Summary of Analysis - Results:
The player hit the highest Game_Score_Ratio was Kyrie Irving. He has the best Game Score for the salary he was paid. 


## User Needs:
    1) Help the user select players for their fantasy lineups
    2) Show volatility and standard deviation of a players gamescore
    3) Know what a basketball earns in salary for 2021

## Business Needs:
    1) Pull a JSON request from the API
    2) Compile multiple player's boxscores in the same DataFrame
    3) Update the gamescores on an ongoing basis
    4) Plot performance data insightfully against a players current salary

## How to Use // Code Structure
Part 1:    
    1) Download the CSV of top paid NBA players
    2) Run Players through an API call to add ID's
    3) Structure a DataFrame to include Player information in one DataFrame
Part 2:
    1) Run player IDs through an API to gather game data
    2) Calculate a 'game score ratio' for each row in the DataFrame
Part 3:
    1) Clean the data to coordinate games across dates
    2) Eliminate data with missing games
    3) Organize game scores by players in the same DataFrame
Part 4)
    1) Plot the gamescores over time

## API's
Player Salaries to CSV - https://hoopshype.com/salaries/players/
API request - https://www.balldontlie.io/#stats
Game Score Calculation - https://captaincalculator.com/sports/basketball/game-score-calculator/

## Instalation, Required Libraries, and Programs:
import requests
import matplotlib.pyplot as plt
import json
import pprint
import pandas as pd
import pycurl
from itertools import chain
import numpy as np
import streamlit as st
