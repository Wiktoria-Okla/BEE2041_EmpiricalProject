# <center><span style="color: #E22420;">:checkered_flag:**Release the Speed**</span>:checkered_flag:


## <center>Data-led Performance Analysis Across the 2023 Formula 1 Season
The 2023 Formula 1 racing season was one to remember, with  heart-stopping crashes and battles for victory. With 22 races all around the globe, and impressive performance of 22 drivers spanning over 10 teams. This blog unpacks the performance of teams and individual drivers to uncover the strongest performance, and possible contenders fighting for the 2024 championship. 
    
    
This blog dives into across-season performance of teams and drivers, as well as their consistency. It analyses key components driving race performance, such as pit stop times and qualifier rounds. Buckle up to uncover the data behind the fastest sport on the planet.
    
## <center><span style="color: #E22420;">**Race Analysis**</span>

    
### <center>Team Performance

    
| Team                         | Points |
| ---------------------------- | ------ |
| Red Bull Racing Honda RBPT   | 790    |
| Mercedes                     | 374    |
| Ferrari                      | 363    |
| Aston Martin Aramco Mercedes | 266    |
| McLaren Mercedes             | 266    |
| Alpine Renault               | 110    |
| Williams Mercedes            | 26     |
| AlphaTauri Honda RBPT        | 22     |
| Alfa Romeo Ferrari           | 16     |
| Haas Ferrari                 | 9      |
    
Figure 1: Table showing the cumulative points per team for the entire 2023 season 
    
The end-of-season team rankings, presented in Figure 1, show an incredible lead from Red Bull who scored more than double the points of any other contender. The strength of this performance is something other teams should perhaps fear.On the contrast, Haas stands out as the weakest team of the season, with a sole 9 points scored over 22 races.   

![image](https://hackmd.io/_uploads/SkT_G_rWA.png)
Figure 2: Time series line chart showing the cumulative points per race over the 2023 season
    
The time series in Figure 2 demonstrates the journeys the teams took us on across the season. One team stands out from the rest due to its outstanding performance: Red Bull. The Red Bull team started off the 2023 season in a powerful stance, securing points  from the first race and asserting dominance over the leaderboard from the first takeoff. The team's position only strenghtens from this point, steeply accumulating points across every race. Despite small dips in a few races, such as the one in June 2023, the overall trajectory is positive right up until the last race of the season: Abu Dhabi on November the 26th.

In the first half of the season Red Bull's closest contendors have been Mercedes and Aston Martin. However after this point, Aston Martin's strong
trajectory quickly diminished across the second-half of the season.We cannot pin-point an exact reason for this trends, but we can speculate possible causes to have been: faulty changes in strategy, quicker car development pace of other cars, or simply weaker skillset of the drivers on the second-half circuits. This turnout of events positioned Ferrari as a key contendor, battling Mercedes for the second place.
    
In the end Mercedes won a firm second place, with Ferrari positioned third, Although this is not the anticipated outcome for the team, the small margin between the cumulative points of both teams should be a thrilling outcome for Ferrari who lagged behind Mercedes for the entirety of the competition. cumulative points of both teams. Despite strong performances from both teams, the Red Bulls finished miles ahead.
    
When we take a closer look, the trajectories of two teams stand out from the rest: Ferrari and McLaren. Since the checkered flag, Ferrari has had a moderate upward trajectory but has demonstrated significant improvement since the race in September 2023. McLaren's journey is a similar story, however with a far more dramatic result. McLaren had started incredibly flat, lacking points until July 2023. However, since this race the team’s trajectory sharply ascending, accumulating an impressive 285 across 14 races in the latter half of the season. The shifts observed in both teams' trajectories signal a strategic change or upgrade in car components.This signals an important message that Ferrari and McLaren are positioning themselves competitively, making these the teams to watch out for in the 2024 season.

![image](https://hackmd.io/_uploads/Hyxr3OGWC.png)
Figure 3: Box plot showing the distribution of points earned per team across races 
    
When we consider the distribution of points scored by each teams' drivers seen in Figure 3, Red Bull clearly outshines the others. Red Bull's points distribution is negatively skewed with the majority of points being positioned above the 12 points mark. Contrastingly, the distributions of all other teams lie in the 0 to 12 points territory, with strong to moderate skews. Red Bull distringuishes itself with a consistent track record of high podium finishes, scoring points on every occassion wheras many teams have shown consistent struggle to secure singular points.
    
In spite of this, it is essential to note that Red Bull exhibits the widest range and interquartile range, indicating a considerable variability in the performance of its drivers. Conversely, Mercedes stands out here with a distribution which aligns closer with a normal distribution, suggesting that its drivers tend to perform around the median of the rankings.
    
When considering the median performances, Red Bull median is striking with approximately 18 points scored per driver per race on average, which is substantially higher than other teams who have a median of 8 and below. A notable fiding is that Mercedes and Ferrari share the same median and upper quartile points per driver. This reinstates the observation from Figure 1 previously, that this is the closest battle on the racing grid. However, a closer analysis at the at the data dispersion reveals that Ferrari holds a greater range and interquartile range than Mercedes.

This shows that although Ferrari and Mercedes on average perform similarily, Mercedes maintains a considerably more consistent performance throughout the season. This observation indicates that Mercedes does indeed hold a stronger position on the racing grid, while Ferrari needs to vastly improve to stand a chance of winning the second place in the 2024 championship. 
    
When examining outliers, Alpine Renault stands out from the rest. Alpine singificantly struggled throughout the season, scoring an average of 1 point per driver per race. However, what also distniguishes Aline from the rest is its unique presence of two outliers, at 12 and 15 points. These observations represent real spikes in performance, which far surprass Alipne's typical output. Alipne should take advantage of these two perfromances, to conduct robust analysis of the strategic decisions made throughout these instances to uncover key strengths which can be leveraged to race performance for seasons to come.

For Alphatauri, Williams, Haas, and Alfa Romeo we can only see the individual instances of points scored as these teams do not have sufficient spread of points to even make up a distribution. Instead we must look at individual points to assess performance, which reveal that these are four wekaest team on the grid due to their scores being situated in the range of 6 and below. Particularly noteworthy are Alfa Romeo and Haas who stand out as the weakest two teams of the season, with only three and four instances, respectively, of points-worthy performances across a 22-race season.


### <center>Driver Performance
![image](https://hackmd.io/_uploads/r1gundfZC.png)

Figure 4: Box plot showing distribution of points earned by driver
    
Diving in, let's break this down further by examining individual drivers' distributions in Figure 4. The first highlight is the large variance in perfromance across nearly all drivers. Lando Norris notably stands out with the largest interquartile range across all drivers, signalling notably inconsistent performance across the season. This disparity stems from Norris experiencing both poor finishes, where he failes to secure any points, and remarkable podium finishes. The strongest performance by Norris was 19 points scored per race. Similarly, Charles Leclerc also exhibited large inconsistencies in performance, holighted by the second-highest interquartile range on the racing grid. 
    
This breakdown is interesting when we consider Red Bull’s performance in Figure 3, especially the extensive dispersion of data. This per-driver breakdown allows us to see how Sergio Perez has signficantly contributed to the wide distribution of scores observed previously in Figure 3, wheras Max Verstappen stands confidently as the strongest and most consistent driver on the grid, consistently scoring 25+ points per race. 

This chart also identifies the weakest driver Nyck De Vries from Alphatauri who has failed to secure any points across the season. This is partly due to the swift performance of Alphatauri's team principle who removed the driver from the grid half way through the season, with Daniel Ricciardo placed as the replacement for the second half of the season. Ricciardo proved his ability by securing 6 points 7 races and reinstating that Nyck De Vries is not of sufficient standard for Formula 1 and therefore is not a contender for a seat in the 2024 season. Behind Nyck sit Kevin Magnussen and Logan Sargeant who only managed to score points on one occasion across the season, and sit in a futile position of being potentially eliminated from Formula 1 racing in the upcoming seasons.

![image](https://hackmd.io/_uploads/rJYmxdU-A.png)
Figure 5: Heatmap showing the most common race finish positions by each driver
    
Considering the distribution of finishing positions for each driver seen in Figure 5, Max Verstappen's stands out from the rest. Verstappen's finishing positions are strongly concentrated in the podoium territory, holding 19 first place finishes, and 2 instances of second place. This is an incredible result for a 22-race season. Once more, the spotlight falls on Max Verstappen as a considerable outlier on the Formula 1 racing grid, with no competitors in sight. This observation prompts an interesting consideration regarding Sergio Perez , who despite driving in the same car, does not come anywhere close to Max's perfromances. This underscores the overbearing impact of driver's skills over the car specifications, in racing success.
    
Lando Norris also stands out with a  fairly large spread of finishing positions, between 2 and 17. Howevever, notablly most of Norris's finishes have been in the second place which hilights the high potential of this driver. This makes Norris a likely target for other team principals, potentially opening up Lando Norris to more opportunities to move around the grid. Does Norris have the potential to become Verstappen's next contender? Only the future will tell. 
    
### <center><span style="color:lightcoral ;">**Now we know which drivers are the strongest perfromers on the grid, but what is the determinant of race result?** </span>



### <center>Pit Stop Performance
![image](https://hackmd.io/_uploads/BJG1TdGZR.png)
Figure 6: Boxplots showing the distribution of pit stop times per team

Figure 6 illustrates a striking consistency in pit stop times across the Formula 1 teams. Most of the teams tend to have pit stops in the range of 16 and 33 seconds for the whole race, as the sum for both cars. Red Bull and Mercedes stand out with the most efficient pit stop crews, with a median time of approximately 24 for both cars, indicating an impressively quick 12 second pit stop per car. Considering, that these are also the two teams battling for first and second place, this indicates pit stop times as a potential key indicator of final race performance. Considering this correlation, it is advisable for teams to prioritise pit stop efficiency as a key objective for the 2024 season.

The chart also uncovers outliers, showcases stances of exceptionally efficient pit stops as well as technical difficulties sabotaging pit stop efficiency. A key outlier is the 57-second overall race pit stop time for Alfa Romeo, which is an exceptionally poor performance, compared to their usual average of 23 seconds.
    
### <center>The Impact of Different Factors on Race Performance 
    
![image](https://hackmd.io/_uploads/HJCoCKf-R.png)
Figure 7: Results of an OLS regression with qualifying position, and pit stop times as independent variables and points scored in a race as the dependent variable

Now we know how different teams and drivers performed, let's look at how pit stop performance impacts race results, alongside other variables. Figure 7 demonstrates the impact of qualifying position and pit stop performance on the number of points scored per driver in a race. Firstly the R-squared value measures what proportion of the dependent variable (points scored per race) can be explained by qualifying position and and pit stop times. In this regression these two variables explain about 48.1% of variance in points scored per race which shows that these 2 variables explain a moderate variance in race performance but there's still many factors that impact this, such as ability of the driver, and weather conditions amongst others. 
    
Moving onto the coefficients of the 2 independent variables tested, the variable 'PosQ', which measures the impact of qualifying position, is -0.8956. This indicates that for every place increase in qualifying position, the number of points increased by approximately 0.8956 points. This is a statistically significant result with a p-value below 0.05.

The variable 'Pit_time', measuring the time spent in the pit stop has a coefficient of -0.0894 but its p value is greater than 0.05 meaning that this result is not significantly significant. This result indicates that we cannot confidently conclude that pit stop times have a significant impact on points scored in a race. This result however is likely due to the fact that pit stop times across the teams tend to be very similar, limiting the model's ability to adequately capture the impact of pit stop times on points scored per race. Despite of these results, we cannot undermine the impact of pit stop efficiency plays in the end race outcome, and cannot be overlooked by teams in preparation stages.
    
## <center>**Summary**
* <span style="color: lightcoral;">Red Bulls in Lead</span> - Across all analysis Red Bull’s dominance on the Formula 1 racing grid is real. This team achieved a strong 1st place at the end of the season and showed superb performance across finishing positions, qualifiers, and pit stops. This result has been made possible due to the outstanding performance of Max Verstappen who achieved podium finishes on 21 out of 22 occasions, standing out as gold dust on the grid.
    
* <span style="color: lightcoral;">Tense Battles </span>- Mercedes and Ferrari showcased the most tense battle of the season battling for the second place. Mercedes came out on top by a mere 11 points. These teams are the ones to watch out for in the upcoming Formula 1 season. 
    
* <span style="color: lightcoral;">Determinants of Race Performance  </span> - The qualifying position has been highlighted as a key indicator of race performance, hilighting the teams' need to focus on qualifying rounds to boost overall race outcomes. Wheras, the impact of pit stop times has been arguably undermined by throughout this analysis, likely due to lack of variation across teams. Nevertheless, there's no denying the pit stop efficiency of the 2 leading teams: Red Bull and Mercedes. Furthermore, we cannot  undermine the catastrophic consequences of a poor pit stop, hindering the driver's progress for the raminder of the race. These results just about capture the complexities of the sport, bringing attention to the multitude of factors that must seamlessly align to attain strong race performance. 
    
* <span style="color: lightcoral;">Unique Driver Peformances </span>Lando Norris from McLaren demonstrated fantastic potential across the season. Achieving podium finishes 7 times, he has been the driving force behind McLaren’s mid-season improvement in performance. Conversely, some drivers struggled significantly, such as Nyck de Vries who was removed from the grid mid-season. Kevin Magnussen and Logan Sargeant, also demonstrated performances who fell short of competitive standard, placing themselves at risk of being replaced in the upcoming seasons. 

Word Count: 2499
    