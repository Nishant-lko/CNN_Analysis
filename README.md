# CNN_Analysis
Analysis on Different CNN Architecture on **Cifar-10 Dataset** 

## Architecture 1 : Modified LeNet 

#### For the first CNN Architecture I used a modified LeNet Architecture with few changes in kernel size,  number of convulational filters and used reLU instead tanh 



**First Test :  Accuracy Reached - 59.56%**
1. No Normalization , No resizing or Augementation 
2. 60 epochs , Batch size : 64 
3. Fixed Learning rate, lr = 0.01 
4. Optimizer : SGD , Loss : CrossEntropyLoss

### Graphical Analysis 

** Epoch vs Loss **

<img src="images/Architecture-1/epochvsloss.png" width="300">
<img src="images/Architecture-1/epochvsaccuracy.png" width="300">
<img src="images/Architecture-1/confusion_matrix.png" width="300">

**Accuracy for each label prediction**
    1.  Accuracy of airplane : 66.70 %
    2.  Accuracy of automobile : 52.30 %
    3.  Accuracy of bird : 51.10 %
    4.  Accuracy of cat : 56.40 %
    5.  Accuracy of deer : 62.40 %
    6.  Accuracy of dog : 32.80 %
    7.  Accuracy of frog : 70.50 %
    8.  Accuracy of horse : 58.00 %
    9.  Accuracy of ship : 76.60 %
    10. Accuracy of truck : 48.80 %



