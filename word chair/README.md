# `Wo`r`d` &nbsp; c`ha`i`r`

In `word chair` I used a technique called [Activation Atlas](https://distill.pub/2019/activation-atlas/). The problem with neuronal networks is that most of the time they are black boxes. For instance, if you take the image of a dog and put it in the network, it says: `100% dog`. We would agree with that, but we don't know what actually happened inside the black box that it says "this is a dog".


The project `Activation Atlas` by Google Brain and OpenAI tries to reverse engineer this black box to better understand what neuronal networks "thinks" in certain parts of an image – so they ask: What do you think of the first upper 10px? ...what do you think of the second 10px?... and so on. 
This creates a kind of cloud of assumptions which are images again. With the assumptions there come text predictions which looks like this:  

!img
  
So I took the "Activation Atlas" to make assumptions about a video of a chair. I used these predictions of the parts of the image for each videoframe (1 image = 71 rows á 15 = 1065 cells * 247 frames = 263055 predictions) and turned them in words. 


here are some if the tests i made with different objects:

   
resources:
- activation atlas 

