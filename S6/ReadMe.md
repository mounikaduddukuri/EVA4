# EVA4-Session6
## Team Members
1. B Sridevi  - sridevi.b@vishnu.edu.in
2. Abhinav Dayal - abhinav.dayal@vishnu.edu.in
3. A. Lakshmana Rao - 18pa1a0511@vishnu.edu.in
4. Sanjay Varma G - 18pa1a1211@vishnu.edu.in

### Points about my code
[main jupyter notebook link](https://github.com/Lakshman511/EVA4/blob/master/S6/EVA4_S6_final.ipynb)
1. StatsManager is a class that I have used to maintain accuracy values,loss values,misclassified images.It also has some methods to plot test accuracy vs validation accuracy and test loss vs valdation loss.A method called plot_misclassified_25() is used to plot 25 misclassified images.
2. In misclassified images I put some text in which "pred" means prediction value and "target" means actual value
3. ModelTrainTester class is used for taining and testing the model...
4. I have used 4 ModelTrainTester objects.


## m1 - Model1(Without L1 and L2 Regularizations)
1. In this model I haven't used any L1 or L2 regularizations.
2. In this model the 25 misclassified Images are..
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m1_misclassified_images.png)

3.The test loss vs validation loss graph is...
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m1_loss.png)
4.The test accuracy vs validation accuracy is...
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m1_accuracy.png)


## m2-Model2(With L1 Regularization)
1.Lambda value=1e-5

2. In this model the 25 misclassified Images are..
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m2_misclassified_images.png)

3.The test loss vs validation loss graph is...
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m2_loss.png)
4.The test accuracy vs validation accuracy is...
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m2_accuracy.png)

## m3-Model3(With L2 Regularization)
1.Lambda value used is 1e-4
2. In this model the 25 misclassified Images are..
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m3_misclassified_images.png)
3.The test loss vs validation loss graph is...
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m3_loss.png)
4.The test accuracy vs validation accuracy is...
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m3_accuracy.png)
## m4 - Model4(With L1 and L2 Regularization)
1.L1lambda=1e-5 L2lambda=1e-4
2. In this model the 25 misclassified Images are..
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m4_misclassified_images.png)
3.The test loss vs validation loss graph is...
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m4_loss.png)

4.The test accuracy vs validation accuracy is...
![](https://github.com/Lakshman511/EVA4/blob/master/S6/m4_accuracy.png)


## Comparison among all
### validation loss of all 4 models
![](https://github.com/Lakshman511/EVA4/blob/master/S6/All_loss.png)

### valdation accuracies of all 4 models
![](https://github.com/Lakshman511/EVA4/blob/master/S6/All_accuracy.png)
## Observations
1. From above graphs we can say that highest accuracy is achieved when L2 regularization is used
2. when we used L1 regularization our model is not stable accuracy is changing randomly
3. Although the models in which we used regularizations achieve higher accuracy than the model without any regularization we can see that this model is stable.
4. Here stable in the sense it's accuracy is not dropping or raising rapidly and randomly.Instead it's accuracy is growing gradually.
5. We must handle L1 regularization with care as it seems highly instable in our case.
