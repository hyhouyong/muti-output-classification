## muti-output-classification
## Train:
        python train.py --dataset dataset --model output/fashion.model --categorybin output/category_lb.pickle --colorbin output/color_lb.pickle
        
## Test:
        python classify.py --model output/fashion.model --categorybin output/category_lb.pickle --colorbin output/color_lb.pickle --image examples/black_dress.jpg

