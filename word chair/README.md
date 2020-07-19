## `Wo`r`d` &nbsp; c`ha`i`r`

### The problem with neuronal networks is that they are "black boxes" and we don't know what's going on inside. <br> For instance, if we take the image of a dog and put it in the network, it says: <br>`100% dog`.<br>We would agree with that. But we don't know what actually happened inside the black box that leads to the AI's conclusion that `this is a dog`.   
<br><br>
![a](img/out-1-3.jpg)
<br><br> 

### [Activation Atlas](https://distill.pub/2019/activation-atlas/) is an open source project to reverse engineer the black box of AI, to better understand what neuronal networks "think" in certain parts of an image. So they ask:   
### `What do you see in the first 10x10 Pixels?` <br>`What do you see in the second 10x10 Pixels?`<br>`...and so on`.       
![a](img/predictions-2.gif)    
<br><br> 

### I used `Activation Atlas` to make assumptions about a video of a chair.<br>Each videoframe is split up into parts and gets analysed. Afterwards I took the highest predictions and turned them into a word map. <br><br>`1 frame = 71 x 15 rows` <br>`= 1065 cells` <br> `1065 cells x 247 frames` <br>`= 263055 predictions`  
![a](img/gif-stuhl-2.gif)   
![a](img/arrow-down-1.jpg)   
![a](img/word-2.gif)   


<br>
<br>
<br>
<br>
<br>
<br>


### resources   
Full overview of Activation Atlas: [https://distill.pub/2019/activation-atlas/](https://distill.pub/2019/activation-atlas/)     
Activation atlas on github: [https://github.com/tensorflow/lucid](https://github.com/tensorflow/lucid)   
Overview of all ImageNet classes: [https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a](https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a) ; [http://image-net.org/explore.php](http://image-net.org/explore.php)   
GoogleColabs I used: [https://colab.research.google.com/github/tensorflow/lucid/blob/master/notebooks/activation-atlas/activation-atlas-adversarial.ipynb](https://colab.research.google.com/github/tensorflow/lucid/blob/master/notebooks/activation-atlas/activation-atlas-adversarial.ipynb) ; [https://colab.research.google.com/github/tensorflow/lucid/blob/master/notebooks/building-blocks/ActivationGrid.ipynb](https://colab.research.google.com/github/tensorflow/lucid/blob/master/notebooks/building-blocks/ActivationGrid.ipynb)




