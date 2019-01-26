# muti-output-classification
### Show
![](https://github.com/hyhouyong/muti-output-classification/blob/master/output/keras_multi_label_animation.gif)<br>
### DataSet
![](https://github.com/hyhouyong/muti-output-classification/blob/master/output/3.jpg)
### Model:
![](https://github.com/hyhouyong/muti-output-classification/blob/master/output/2.png)
### Train:
        python train.py --dataset dataset --model output/fashion.model --categorybin output/category_lb.pickle --colorbin output/color_lb.pickle        
### Test:
        python classify.py --model output/fashion.model --categorybin output/category_lb.pickle --colorbin output/color_lb.pickle --image examples/black_dress.jpg
### Result:
![](https://github.com/hyhouyong/muti-output-classification/blob/master/output/output_accs.png)<br>
![](https://github.com/hyhouyong/muti-output-classification/blob/master/output/output_losses.png)       
#### Reference
        https://www.pyimagesearch.com/2018/05/07/multi-label-classification-with-keras/

