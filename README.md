**This notebook explores how the town of Paradise's number of MHP lots compares with other similarly populated cities in 2018. This analysis will help me show that MHP living was a major part of Paradise, which was previously known as a place where senior citizens could find a place to live out their retirement.**

--

UPDATE May 5 evening:

I ended up going ahead and doing the same analysis using the ACS 5-year estimates as opposed to the vintage population estimates table I was initially using. I spoke with someone from the Census bureau, who upon hearing the nature of my analysis, said that the ACS 5-year estimates would be better because it encompasses a larger number of places with smaller populations. 

In doing so, my merge was more successful. When I initially did the merge with the population estimates, I only ended up with 372 matches between the two datasets (the MH dataset had more than 800 unique city names). However, when I did the merge with the ACS 5-year estimates, I ended up with more than 600 matches. Not perfect, but better. 

--

Main questions for Serdar (May 5):

1. There are a lot of values in the city column for mobile home parks. How do I ensure that there are no close matches, like ‘Los Angeles’ and ‘Los Angles,’ or something like that. I suppose I could use open refine? But wondering if there’s anything in Pandas that would function similarly. 

~~2. Should I redo the analysis with 5-year estimates of 2018 population? The Census dataset I use has the one-year estimates of population.~~

~~3. There are only 372 matches between the two datasets. Is that ok? I ended up analyzing with the left join but I did the right join also to see which values in the city column of MH dataset didn’t have a corresponding value in the census dataset.~~ 