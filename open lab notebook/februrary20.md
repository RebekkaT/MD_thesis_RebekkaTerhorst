# Analysis of physiological data
-20201202
- I finished analysing the samples of Cortisol, Alpha-Amylase and Heartrate and added the notebooks containig the statistic analysis into the 'Code'- Folder.
- A few questions arised looking at the results.
I conducted a mixed ANOVA (split-plot ANOVA) for all three datatypes after testing for normal distribution, homoscedacity and sphericity.
In none of the three analysis a significant interaction between the groups showed up.
Nevertheless, looking at the descriptive statistics, it seems as if for both (cortisol and amylase) already between timepoint 2 and 3 (time where the first stress test was conducted and where the paradigm for both conditions(water and music) were the same) the groups start to go apart only for then having a paralell continuity. This indicates, that independent from the project paradigm, an influence on the data took place. (instruction during stress test differs, Versuchsleiter changes etc)
- Next I will try to find this interaction as well as finish analysing the analysis of respiration-data.

-20201402
- I found, that until now I only analysed the period of acoustic intervention for the heartrate analysis. The new script in the 'Code' Folder shows the procedure for a Analysis with the whole experiment setting (stressI - acoustic - stressII)
- Even though there is no significant interaction between the two conditions (music and water) when conductin a repeated measures ANOVA with each group for itself, the heartrate differs significantly during the different project settings (stress and acoustic intervention). The heartrate is significantly lower during acoustic intervention than during stress. 
- This indicates, that the used stresstest works as planned.
