- 20200302
- I continued analysing respirational and GSC data. As assumed from the results uo to now, one can see easily that the stress induction and relaxation worked very well during the experiment. A difference between the two conditions (water and music) can not be seen.
- For the saliva samples I tried to do an outlier detection. After excluding the quantile above 90 and lower 10, the difference in both (alpha amylas and cortisol) during the beginning and instruction period and the first stress test (which differed between the groups even though the setting at the beginning should be absolute the same) this difference disappeared.
Since I have a mixed setting with within and between variables, I dind't find a possibility to conduct an ANCOVA until now.
- I'm looking for a way to analyse covariates 
- Concerning the GCS Analysis: seems to be very artifact sensible. some subjects had little peaks but many (wich were detected) and counted as well as the big peaks (which indicate a much bigger stress). With the module 'peak_finder' I am currently using, it is not possible to better differenciate the peaks. Nevertheless it detects very well the stress and relax-phases.
