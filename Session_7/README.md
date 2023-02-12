## Problem Definition&#x1F537;

Task is to train resnet model for 20 epochs on CIFAR10 dataset and observe and plot loss curves, both for test and train datasets. Next task would be to identify 10 misclassified images. And we would have to show the GradCAM output on those 10 misclassified images.



## Repo;

https://github.com/visionenthusiast/source_code



## Model;

https://github.com/visionenthusiast/source_code/blob/main/models/resnet.py


## main.py;

https://github.com/visionenthusiast/source_code/blob/main/main.py



## utils.py;

https://github.com/visionenthusiast/source_code/blob/main/utils/utils.py



## Training Log (model :resnet , epoch 20, best validation accuracy : 76%);

Epoch:  0 Learning Rate:  0.1

Train set: Average loss: 2.2244, Accuracy: 13494.0/50000 (26.99%)


Test set: Average loss: 0.0531, Accuracy: 3690/10000 (36.90%)

Epoch:  1 Learning Rate:  0.1

Train set: Average loss: 1.5835, Accuracy: 18479.0/50000 (36.96%)


Test set: Average loss: 0.0479, Accuracy: 4284/10000 (42.84%)

Epoch:  2 Learning Rate:  0.1

Train set: Average loss: 0.9087, Accuracy: 21132.0/50000 (42.26%)


Test set: Average loss: 0.0459, Accuracy: 4631/10000 (46.31%)

Epoch:  3 Learning Rate:  0.1

Train set: Average loss: 1.0675, Accuracy: 22910.0/50000 (45.82%)


Test set: Average loss: 0.0420, Accuracy: 5145/10000 (51.45%)

Epoch:  4 Learning Rate:  0.1

Train set: Average loss: 1.1206, Accuracy: 24883.0/50000 (49.77%)


Test set: Average loss: 0.0400, Accuracy: 5409/10000 (54.09%)

Epoch:  5 Learning Rate:  0.1

Train set: Average loss: 1.2766, Accuracy: 26289.0/50000 (52.58%)


Test set: Average loss: 0.0365, Accuracy: 5821/10000 (58.21%)

Epoch:  6 Learning Rate:  0.1

Train set: Average loss: 1.3898, Accuracy: 27658.0/50000 (55.32%)


Test set: Average loss: 0.0363, Accuracy: 5838/10000 (58.38%)

Epoch:  7 Learning Rate:  0.1

Train set: Average loss: 1.0912, Accuracy: 28596.0/50000 (57.19%)


Test set: Average loss: 0.0347, Accuracy: 6098/10000 (60.98%)

Epoch:  8 Learning Rate:  0.1

Train set: Average loss: 1.4294, Accuracy: 29927.0/50000 (59.85%)


Test set: Average loss: 0.0322, Accuracy: 6385/10000 (63.85%)

Epoch:  9 Learning Rate:  0.1

Train set: Average loss: 0.9875, Accuracy: 30808.0/50000 (61.62%)


Test set: Average loss: 0.0300, Accuracy: 6657/10000 (66.57%)

Epoch:  10 Learning Rate:  0.010000000000000002

Train set: Average loss: 1.1666, Accuracy: 32166.0/50000 (64.33%)


Test set: Average loss: 0.0253, Accuracy: 7139/10000 (71.39%)

Epoch:  11 Learning Rate:  0.010000000000000002

Train set: Average loss: 1.2298, Accuracy: 33001.0/50000 (66.00%)


Test set: Average loss: 0.0252, Accuracy: 7201/10000 (72.01%)

Epoch:  12 Learning Rate:  0.010000000000000002

Train set: Average loss: 1.2600, Accuracy: 33363.0/50000 (66.73%)


Test set: Average loss: 0.0246, Accuracy: 7270/10000 (72.70%)

Epoch:  13 Learning Rate:  0.010000000000000002

Train set: Average loss: 0.9400, Accuracy: 33701.0/50000 (67.40%)


Test set: Average loss: 0.0239, Accuracy: 7333/10000 (73.33%)

Epoch:  14 Learning Rate:  0.010000000000000002

Train set: Average loss: 1.3010, Accuracy: 34003.0/50000 (68.01%)


Test set: Average loss: 0.0236, Accuracy: 7380/10000 (73.80%)

Epoch:  15 Learning Rate:  0.010000000000000002

Train set: Average loss: 0.7269, Accuracy: 34401.0/50000 (68.80%)


Test set: Average loss: 0.0233, Accuracy: 7426/10000 (74.26%)

Epoch:  16 Learning Rate:  0.010000000000000002

Train set: Average loss: 1.2617, Accuracy: 34461.0/50000 (68.92%)


Test set: Average loss: 0.0229, Accuracy: 7489/10000 (74.89%)

Epoch:  17 Learning Rate:  0.010000000000000002

Train set: Average loss: 0.8123, Accuracy: 34758.0/50000 (69.52%)


Test set: Average loss: 0.0229, Accuracy: 7480/10000 (74.80%)

Epoch:  18 Learning Rate:  0.010000000000000002

Train set: Average loss: 1.2333, Accuracy: 35013.0/50000 (70.03%)


Test set: Average loss: 0.0223, Accuracy: 7499/10000 (74.99%)

Epoch:  19 Learning Rate:  0.010000000000000002

Train set: Average loss: 0.5476, Accuracy: 35251.0/50000 (70.50%)


Test set: Average loss: 0.0219, Accuracy: 7600/10000 (76.00%)

Finished Training



## Validation Loss and Accuracy Progression;

![image](https://github.com/visionenthusiast/EVA8/blob/main/Session_7/images/training:test%20accuracy.png)

## Misclassified Images Gallery;

![image](https://github.com/visionenthusiast/EVA8/blob/main/Session_7/images/misclassified.png)

## GradCAM Outputs Gallery;

![image](https://github.com/visionenthusiast/EVA8/blob/main/Session_7/images/Gradcam.png)



                                            |
## Methods used in main.py;

| Method                             | Purpose                                                            |
| ---------------------------------- |:------------------------------------------------------------------:|
| train                              | trains the model                                                   |
| test                               | tests the model                                                    |
| print_model_summary                | returns model summary                                              |                                                 |

## External Reference Used&#x1F537;

https://github.com/kazuto1011/grad-cam-pytorch/blob/fd10ff7fc85ae064938531235a5dd3889ca46fed/grad_cam.py
