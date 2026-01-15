# When Should a Team Use the Power Play?
Our analysis over when and how to use the power play in mixed doubles curling.  Submitted for the CSAS 2026 Data Challenge.

Our names and contacts will be excluded until juding is finalized, per instruction request, but you can see and contact us through our github accounts.

## About the Project
Link to Project Website: https://statds.org/events/csas2026/challenge.html

Description from CSAS:

> Curling is a sport where two teams take turns sliding stones down a sheet of ice towards a target. The most common form of the game features teams with four players, with each player getting two shots per round, known in curling as an “end”. When one player shoots, two of their teammates follow the stone down the ice, sweeping its path with brooms to direct it to the desired position. Teams score by having the stone closest to the center of the target at the completion of the end, one point for each stone inside of the opponent’s closest stone. After a set number of ends (usually 8 or 10), the team with more points is the winner.

> This Data Challenge focuses on power play optimization - when to use it, how to execute it, and how to defend against it - using data from international competition results that show final stone positions.

## Using these files
To run these files, ensure that the following libraries are installed:
- Numpy
- Pandas
- Seaborn
- Matplotlib
- Random

These come preinstalled when using services such as Google Colab (where these files were created).

Data also comes from this github repository: https://github.com/CSAS-Data-Challenge/2026. We link directly to these files in our notebooks.  If these files are no longer in existence, these files will not execute.

## What each files does
All files are cleaned up versions of our work which were included in our final report.

### PowerPlayDescriptive.ipynb
This file produces descriptive visualizations about the power play such as its frequency and expected points gained from the play.

### RuleOfThumb1.ipynb
This file explores the idea of sacrificing a point to retain the hammer and prevent the opponent from using a power play (it probably isn’t a good idea).

### RuleOfThumb2.ipynb
This file explores when teams elect to use the power play and gives evidence to suggest that teams are using it too late in the game, at least when they are losing.

### RuleOfThumb3.ipynb
This file explores what teams should do to score big on a powerplay, giving evidence that powerplay teams should draw more and leave more stones in play in the house for larger gains.
