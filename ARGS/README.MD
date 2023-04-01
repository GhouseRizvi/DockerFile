### ARGS 
ARG is used to supply few variables at the time of image creation.
ARG is used for only image creation where ENV used during image and container creation as well.
We can use as our first instruction in the docker file its a Execption 
ARG is the only instruction we can use befrom from
the arg variable declared before from cannot be accessed after from.

# How to find the arg values in the container
 # using ENV and ARG for the Best Results
* Create an ENV Variable and assign the Arg value to that
* So we can access the vaues in both image and container.
