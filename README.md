# SIH
## Road Damage detection
1. clone this repo
2. change the directory to the folder cloned
3. To test

This code below return list of images with boxes drawn on it
```
import detection as run
image_np,*_ = run.detect(test_image)
```
To get other params
```
image_np,boxes_collect,scores_collect,classes_collect,num_collect = detect(test_image, plot_show = True)
```

To plot 
```
import detection as run
image_np,*_ = run.detect(test_image, plot_show=True)
```
