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

<div class='tableauPlaceholder' id='viz1511199646292' style='position: relative'><noscript><a href='https://public.tableau.com/profile/mike.landron#!/vizhome/NBA_Advanced_Player_Stats/StatDashboard'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NB&#47;NBA_Advanced_Player_Stats&#47;StatDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NBA_Advanced_Player_Stats&#47;StatDashboard' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NB&#47;NBA_Advanced_Player_Stats&#47;StatDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1511199646292');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.minWidth='420px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='610px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>