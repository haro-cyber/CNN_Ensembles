# CNN_Ensembles
Testing CNN ensembles with the CIFAR10 Datasets.

![image](https://user-images.githubusercontent.com/65751048/125156872-c7532a80-e1a2-11eb-9d3b-6882cf93aae3.png)
引用:https://qiita.com/koshian2/items/d569cd71b0e082111962

## Soft Ensemble
平均
average of the outputs of CNNs

## Hard Ensemble
多数決
taking the argmax of the outputs

## originals
### square
average of outputs**2
### root
average of root outputs
### N-square
average of outputs**N
### T-softmax
average of softmax(outputs/T)
