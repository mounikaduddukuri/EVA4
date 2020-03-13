# EVA4-Session7
## Team Members
1. B Sridevi  - sridevi.b@vishnu.edu.in
2. Abhinav Dayal - abhinav.dayal@vishnu.edu.in
3. A. Lakshmana Rao - 18pa1a0511@vishnu.edu.in
4. Sanjay Varma G - 18pa1a1211@vishnu.edu.in

### Observations
1. In this assignment we move on to Cifar10 dataset.
2. On observing the images it may be safe to say that we can add maxpooling after 2 or 3 convolutions.
3. We can also add data agmentation techniques like random erasing and randomflipping and rotations.

### Goals of this assignment
1. To achieve 80% accuracy within 1M parameters and any number of epochs.
2. To use dialation layer and depth wise seperable layer

### Results
1. [This is the model](https://github.com/Lakshman511/EVA4/blob/master/S7/EVA_4_S7.ipynb) with 157952 parameters 
2. It achieves 81% accuracy in 10 epochs.
3. We used dialation with dialation value=2.
4. Also used depth wise seperable layer, gap layer followed by fully connected layer are used.
5. This model is the object of Cfar10Net class of [this file](https://github.com/Lakshman511/EVA4/blob/master/S7/myLibrary/eva4models.py)

### Model2
1. [This](https://github.com/Lakshman511/EVA4/blob/master/S7/EVA_4_S7_2.ipynb) is the Lighter version of above model
2. Number of parameters is:87,152
3. It achieved 80% accuracy at 9th epoch
4. This model is the object of Cfar10Net2 class of [this file](https://github.com/Lakshman511/EVA4/blob/master/S7/myLibrary/eva4models.py)

#### Note:
1. In this model we implemented our own library by mounting google drive.
2. [This](https://github.com/Lakshman511/EVA4/tree/master/S7/myLibrary) is the link for our library.
