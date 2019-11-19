# basic-train-on-cifar10
basic training on CIFAR10 dataset with ResNet 



|   Model  |  n   | 200-epoch ResNet v1, % Accuracy | Orig. Paper ResNet v1, % Accuracy | 200-epoch ResNet v2, % Accuracy | Orig. Paper ResNet v2, % Accuracy | sec/epoch, GTX1080Ti, v1 (v2)|
|:-------- |:----:|:---------:|:---------: |:---------: |:---------: |:--------: |
 ResNet20  | 3 (2)| 92.16     | 91.25      |            |            | 35 (   )  |
 ResNet32  | 5(NA)| 92.46     | 92.49      | NA         | NA         | 50 ( NA)  |
 ResNet44  | 7(NA)| 92.50     | 92.83      | NA         | NA         | 70 ( NA)  |
 ResNet56  | 9 (6)| 92.71     | 93.03      | 93.01      | NA         | 90 (100)  |
 ResNet110 |18(12)| 92.65     | 93.39+-.16 | 93.15      | 93.63      | 165(180)  |
 ResNet164 |27(18)|           | 94.07      |            | 94.54      |    (   )  |
 ResNet1001| (111)|           | 92.39      |            | 95.08+-.14 |    (   )  |
