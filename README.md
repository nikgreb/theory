# Theory
Statistical Theory Final Project Write-Up

We are examining is a Historic Wildlife Observations database categorizing animals in the Yellowstone National Park area. Each row in the dataset is an animal sighting There are 37 variables, most of which contain non-numeric information, such as observer, type of animal, evidence comments, and more. We will be using the bison sightings data, so we filtered by animal, and then made a function to get the number of sightings of bison. 

During the 1800s, there was a large prevalence of bison hunting in the west. This caused bison populations to decline rapidly, and by the year 1883, it was estimated that only 25177 bison remained in North America. Yellowstone National Park in Wyoming is the only place in the United States where wild bison have lived continuously since prehistoric times. However due to the large herds of bison still in Yellowstone today, the park has become a hit spot to view Bison. From this, our research question was looking into the historical data, and asking: What is the total population of bison in Yellowstone and the surrounding area during the years 1796 to 1881?


Based on the properties of the distribution, I would suppose that a poisson distribution would be best used, as our data is count data, which is integer based, and depends on some rate of bison sightings. The poisson distribution, however, has the same parameter for mean and variance, which makes it fairly unflexible. Our data has different mean and variance, which means that the poisson distribution cannot be used. 




  Sighting - seeing one bison i.e (seen a bison)
  observation - one recorded number of sightings i.e. (count that day)

We are getting at the parent population size, or the toal number of bison.
This is intersting to someone as it can talk about the health of the bison populations, point indicators to hunting or poaching, or look at envriomental concerns for bison. 

4. Our two estimators:
mean : from our data, the distribution of means would be distribution the average number of bison sightings in Yellowstone. 
maximum from our data the maximum distribution would show some dist for the maximum bison spotted overall. 
