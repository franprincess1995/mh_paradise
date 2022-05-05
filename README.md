This notebook explores how the town of Paradise's number of MHP lots compares with other similarly populated cities in 2018. This analysis will help me show that MHP living was a major part of Paradise, which was previously known as a place where senior citizens could find a place to live out their retirement. 

Main questions for Serdar (May 5):

1. There are a lot of values in the city column for mobile home parks. How do I ensure that there are no close matches, like ‘Los Angeles’ and ‘Los Angles,’ or something like that. I suppose I could use open refine? But wondering if there’s anything in Pandas that would function similarly. 

2. Should I redo the analysis with 5-year estimates of 2018 population? The Census dataset I use has the one-year estimates of population.

3. There are only 372 matches between the two datasets. Is that ok? I ended up analyzing with the left join but I did the right join also to see which values in the city column of MH dataset didn’t have a corresponding value in the census dataset. 