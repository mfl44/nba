# NBA Advanced Player Stat Comparison Dashboard

## Overview

- The purpose of this project was to have a dashboard to show advanced NBA stats over time by player. All statistics were originally pulled from https://www.basketball-reference.com
- Data is from 1979-'80 season through 2016-'17 season and only includes players who played more than 500 minutes in a season

## Glossary of Statistics

1) PER: John Hollinger's measure of player's per minute statistical production; league average every year is 15.00

2) EFF: commonly used statistical benchmark for comparing the overall value of players; (Points + Rebounds + Assists + Steals + Blocks - Missed FG - Missed FT - TO)/Games Played [calculation done in Python]

3) eFG%: Effective Field Goal %; Field Goal % adjusted to account for 3-point shots are worth more than 2-point shots made

4) Adjusted Assist/Turnover Ratio: Assist to Turnover Ratio to adjust for the fact that turnovers do more harm than assists do good; [(2/3)* Assists]/Turnovers

5) Points by Season: Total points scored during season

6) Minutes Played by Season: Total number of minutes played during season

## Instructions for Use

- Players can be selected from the check filter on the bottom-right of the dashboard

- Once the box has been checked next to a player name, the color key and the charts will all automatically update to show the new selection

## Dashboard:

https://public.tableau.com/profile/mike.landron#!/vizhome/NBA_Advanced_Player_Stats/StatDashboard