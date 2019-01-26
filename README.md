## muti-output-classification
![](https://github.com/hyhouyong/muti-output-classification/blob/master/output/output_accs.png)
## Train:
        python train.py --dataset dataset --model output/fashion.model --categorybin output/category_lb.pickle --colorbin output/color_lb.pickle
        
## Test:
        python classify.py --model output/fashion.model --categorybin output/category_lb.pickle --colorbin output/color_lb.pickle --image examples/black_dress.jpg

