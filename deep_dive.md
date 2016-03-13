Deep Dive
=======

# Failure Factories
Adam, data editor at TBT  
* started with an outlier, showed that the black performance for reading and writing was going down and down
* looked at which schools had the worst schools
* heard from kids in those schools about awful things happening
  * saw a lot of kids start to fail their classes
* as they started to look, developed a theory that resegregation was causing the troubling performance
* Problem 1
  * conventional wisdom against their theory
  * school boards blamed the parents, saying that poor parents raised bad kids
* brought in a lot of resources to tackle the story
  * the start is: we want to answer the question
* required a different approach than other data projects
  * usually there are a contained number of tiny question
  * this project required testing conventional wisdom against the data
* Did a lot of tiny analyses, testing what is and isn't supposed to impact how students learn
  * went through a ton of things that we accept as normal, and set to see if its provable
* did a lot of things to get more than the normal data
  * surveyed other districts, cataloged school board promises, built database of kids talked to
  * Bodies: nowhere else in Florida had such a concentration of failing schools
* Convinced themselves that the situation was not normal, that what they were looking at was caused by decisions by people in power
  * built a case to rule out everything but the decisions of people in power
* They then had to convince other people
  * strong opinions
  * hard harm to understand, a different kind of harm, one that unfolds over decades
* Data as body-cams
  * use it as evidence that we can see
  * thousands of stories
    * want people to zoom from the individual to the whole
* used interactives that pulled from their database of kids, lots of stories generated from their individual story
* really powerful interactives and visual demonstrations helped to show the story, show the data and break down what the data means
  * used the power of web presentation to show the power of what we are exploring


## Working with big geodata without messign up
Dhrumil Mehta, Reuben Fischer-Baum - 538
* data: uber was expanding very quickly in NYC
  * received 4.4 million uber pickups, 89 million taxi pickups
* mistake 1
  * wrote a python script to try and geocode: would have taken 93 million
  * know which tool to use
* mistake 2
  * accidentally tried to reinvent GIS
* What worked
  * generated shapefiles in QGIS
  * put them into PostGIS and assigned each point a census tract
  * exported PostGIS data
* mistake 3
  * projection sloppiness
  * didnt code projections properly, lots of pickups in the ocean
* mistake 4
  * know how your tools work
* mapping in QGIS
  * by the time they finished, would have been way easier to do d3
* mistake 5bb
  * indexing makes queries faster
* mistake 6
  * cut corners
  * didn't normalize
  * didn't combine months into single table
  * didn't ignore messy datetime formatting
* making your data reusable! cutting corners hurts you later
* STRUCTURE YOUR DATA
* name things meaningfully, have fewer, more uniform files
* bad formatting caused some real bad misclassification
* BIG LESSONS
  * structure your data for any question you might have
  * take the time to normalize your DATA
  * know the right tool
  * dont invent something new
  * beware sunk costs!
  * visually validate

# Its All About Numbers
John Bones, from norway
* dont forget the stories at the heart of your numbers
* immigration
  * wanted to know what was happening with his data
  * got a ton of immigration data from EU
* Are the norwegian police solving more crimes
  * they got a huge budget increase and a lot more officers, but were they doing a better job?
  * got no better at doing their job
