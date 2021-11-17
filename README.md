# Nba_Analyzer

## Brief:
When you are picking a fantasy basketball lineup, or any portfolio for that matter, there are a plethora of tells and signs to aid (or hinder) you in making good decisions. We are hoping to answer if there is any hope in our fantasy leagues by following what the experts do- that is selecting basketball players that are paid more than their peers, picking the players for our lineups that the real life General Managers pay for there players? What does a players salary tell us about their fantasy performance? 
    
Maybe this will help us think following the experts into high expense funds, when there is often a low cost option readily available.. or maybe GM's in the NBA should look at our application when deciding how much they should pay their own Free Agents?

## User Needs:
    1) Help the user select players for their fantasy lineups
    2) Show volatility of a players gamescore
    3) Know what a basketball earns in salary for 2021

## Business Needs:
    1) Pull a JSON request from the API
    2) Compile multiple player's boxscores in the same DataFrame
    3) Calculate game scores
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
    2) Deal with missing games
    3) Organize game scores by players in the same DataFrame
Part 4)
    1) Plot the values by Date
    2) Each player has their own Y-value

## API's
Ball Don't Lie
NBA Stats

## Instalation, Required Libraries, and Programs:
JSON
Pandas

## ScreenShots

