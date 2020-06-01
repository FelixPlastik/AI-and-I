# detected objects

Object detection (or object/image recognition) is a quite popular AI usage. It takes input images, analyses them and recognizes things, or faces or whatever you want. The more images you give it to learn from, the better it recognizes things later.  
The use cases reach from surveillance cameras to monitor people to selfdriving cars that recognize cats on the street.  
Sometimes this works incredibely good, but often it doesn't. My experiment started with the search for the faults, in betweens and blind spots.

Here some pics of image recognition to bring you in the mood:
![](https://pyimagesearch.com/wp-content/uploads/2018/11/yolo_dl4cv.jpg)  
![](img/table-1.jpg)


### 1. YOLO table (YOLO = you look only once)
All things are split into categories, classes and sub-classes.  
I recognized that tables are a well trained class since a lot of things lay on tables and its basically in a lot of indoor sceneries.
So how much does it take to be a table?

The YOLO table is a cover in the shape of a table to cover objects to appear like a table for example the Mercedes table.
![a](img/table-1.jpg)  

![b](img/table-2.jpg)  
quick sketch of the cover

![c](img/table-3.jpg)
first tests (failing horribly but also funny)
it seems that color aswell as context of an object are an important factors.

See here the final YOLO table with some proof-of-design pictures:
