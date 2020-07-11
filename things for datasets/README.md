### `T`h`i`n`g`s &nbsp;`f`o`r`&nbsp; d`a`t`a`s`e`t`s` 

![](https://pjreddie.com/media/image/Screen_Shot_2016-09-07_at_10.56.09_PM.png)

### `Object detection` is a type of AI that is able to recognise objects in images and videos. The use cases reach from surveillance cameras for monitoring people, machines for sorting out cucumbers to selfdriving cars that recognize cats on the street. 
### An interesting behaviour of `object detections` is that they recognise some things inccredibly good and some things they ignore completely. This comes from the fact that the training data still gets labeled by hand which causes faults and blind spots. For example, when the person who labels the data does not know cucumbers, the object detection will never recognise a cucumber as a cucumber (but perhaps as a tree). 

### I chose the 3 classes `person`, `cup` & `table` which are very well recognised and started playling around with them. <br> I was looking for the limits of recognizability, the in-betweens and the blind spots. The object recognition herefor served as a second perspective to prove or reject my designs.   

<br><br><br>

### `tests`
![a](img/tasse.gif)   
<br><br>   
![a](img/kanne-gif-4.gif)   
<br><br>   
![a](img/venti.gif)   
> bilder tisch   

Based on the tests, I designed a series of furnishing objects. All of them are created in a ping pong with `object detection AI` but they differ in their relation to the AI.

### `1. YOLO table` 
### YOLO table (= *Y*ou *L*ook *O*nly *O*nce) is a table cover in the shape of a table. The cover can make any object a table. 
<br>   
![a](img/table.gif)   

<br><br><br>  



### `2. 2D-3D cup`
### For object detections a 2D representation of a cup is enough to be a cup. For humans a cup just makes sense when you can drink out of it. The 2D-3D cup is compromise for both realities.
![c](img/capri-gif.gif)

<br><br><br>  



### `3. hair curtain` 
### Hairs seem to be a strong feature for the recognition of humans. The hair curtain is the ultimate humanizer.
![c](img/prediction-yolo-hair-1.jpg)


<br><br><br>  


### `resources` 
Darknet YOLO (official website): [https://pjreddie.com/darknet/yolo/](https://pjreddie.com/darknet/yolo/)   
code for yolo github: [https://pjreddie.com/darknet/yolo/](https://pjreddie.com/darknet/yolo/)   

