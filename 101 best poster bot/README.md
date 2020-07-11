## `101`&nbsp;&nbsp;b`e`s`t` &nbsp;&nbsp;<br>`p`o`s`t`e`r &nbsp;&nbsp; `b`o`t`

### intro

![a](img/poster-archive-1.gif)

### Training an AI to be a poster-design-bot needed a dataset. The contest [100 best posters](https://100-beste-plakate.de/) provide an archive with all of their winner posters – a clean dataset of hot design with images of same size! perfect!
### To download the whole archive, I used an image crawler (see `crawler.py` in the directory)


### The AI i used to team up with is called `styleGAN`. It learns on its own ("unsupervised") without any classified data and tries to recognise patterns in the posters.   
<br><br><br>


### walk through the AI (after 3000 generations)
![a](img/poster-03.gif)    
<br><br><br>


### `image generation + selection + print`
### Because the AI does not give me 1 poster but a range of eXtrems of what it learned, the process stays a ping pong and I had to choose the poster. I also decided to screenprint it. Afterwards I participated again with the generated poster. 


![a](img/IMG_1021.jpg)
![a](img/IMG_1076-2.jpg)
<br><br><br>
### `conclusion`
### Sadly my poster did not make it in the 100 best. It seemed that lacked some parameters for judging a poster. <br>The `styleGAN` I used was:   
### 1. too random <br>2. the dataset is too small <br>3. posters are designed in layers like color, form, typography, humor, inspiration, personal style <br>4. my poster had no informational layer (announcement to an event)
### In the following I propose a draft of how different artificial intelligences could be used together to really replace the creative process of designing a poster:
<br><br><br><br><br>


### `resources`
runwayML download link (you can train a styleGAN there): [https://runwayml.com/](https://runwayml.com/)<br>
styleGAN on github:[https://github.com/NVlabs/stylegan2](https://github.com/NVlabs/stylegan2)
