# Theory
Statistical Theory Final Project Write-Up

1. Dataset: The we are examining is a Historic Wildlife Observations database categorizing animals in the Yellowstone National Park area. Each row in the dataset is an animal sighting There are 37 variables, most of which contain non-numeric information, such as observer, type of animal, evidence comments, and more. We will be using the bison sightings data, so we filtered by animal, and then made a function to get the number of sightings of bison. 

2. Based on the properties of the distribution, I would suppose that a poisson distribution would be best used, as our data is count data, which is integer based, and depends on some rate of bison sightings. That being said it is not reasonable to assume that the rate for the poisson distribution stays the same over the 70 years that the data collection took place. (In 1883, almost no bison remained in America as they had been hunted almost to extinction).

3. What is the total population of bison in Yellowstone?

  Sighting - seeing one bison i.e (seen a bison)
  observation - one recorded number of sightings i.e. (count that day)

We are getting at the parent population size, or the toal number of bison.
This is intersting to someone as it can talk about the health of the bison populations, point indicators to hunting or poaching, or look at envriomental concerns for bison. 

4. Our two estimators:
mean : from our data, the distribution of means would be distribution the average number of bison sightings in Yellowstone. 
maximum from our data the maximum distribution would show some dist for the maximum bison spotted overall. 
