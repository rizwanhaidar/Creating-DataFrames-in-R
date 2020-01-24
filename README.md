# Creating-DataFrames-in-R
Put your jet pack on because it is time for some space exploration!  As a first goal, you want to construct a data frame that describes the main characteristics of eight planets in our solar system.

Since using built-in data sets is not even half the fun of creating your own data sets, the rest of this chapter is based on your personally developed data set. Put your jet pack on because it is time for some space exploration! 

As a first goal, you want to construct a data frame that describes the main characteristics of eight planets in our solar system. 

According to your good friend Buzz, the main features of a planet are:
## The type of planet (Terrestrial or Gas Giant).
## The planet's diameter relative to the diameter of the Earth.
## The planet's rotation across the sun relative to that of the Earth.
## If the planet has rings or not (TRUE or FALSE).

After doing some high-quality research on Wikipedia, you feel confident enough to create the necessary vectors: name, type, diameter, rotation and rings; these vectors have already been coded up on the right. The first element in each of these vectors correspond to the first observation.

You construct a data frame with the *data.frame()* function. As arguments, you pass the vectors from before: they will become the different columns of your data frame. Because every column has the same length, the vectors you pass should also have the same length. But don't forget that it is possible (and likely) that they contain different types of data
