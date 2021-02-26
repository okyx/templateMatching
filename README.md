# templateMatching
Template matching is an algorithm that can find piece of image in another image to classify it
all we need to do is find the correlation between 2 pic

you can see my file SourceImg.png , 
and the template file templateIMG.png

There are many correlation formula , in this example i use the formula below<br>
![equation](https://latex.codecogs.com/gif.latex?\frac{\sum&space;xy}{\sqrt{x^{2}}\sqrt{y^2}})

after move all the pixel , set threshold = 0.8<br>
and all correlation above the threshold will be drawn rectangle <br>

you can see the result at result.png
