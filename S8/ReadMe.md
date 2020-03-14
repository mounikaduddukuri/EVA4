
# EVA4-Session8
## Team Members
1. B Sridevi  - sridevi.b@vishnu.edu.in
2. Abhinav Dayal - abhinav.dayal@vishnu.edu.in
3. A. Lakshmana Rao - 18pa1a0511@vishnu.edu.in
4. Sanjay Varma G - 18pa1a1211@vishnu.edu.in

## Goals of the assignment...
1. To use ResNet18 architecture
2. To achieve 85% accuracy in any number of epochs

## Result
1. Achieved 91.22% accuracy in 15 epochs.
2. Used our own library.
3. WE used our previous library.Only models "eva4models" file is updated.ResNet model is copied to our "eva4models" file from [this link](https://github.com/kuangliu/pytorch-cifar).

## Epoch logs
Epochs 100% 15/15 [07:53<00:00, 31.52s/it]
. Batch=391 Loss=1.0038 Acc=47.29%
100% 391/391 [00:29<00:00, 14.68it/s]
Validation loss decreased (100000.000000 --> 1.510893).  Saving model ...
Epoch: 1, Train set: Average loss: 0.0113, Accuracy: 47.29%; Test set: Average loss: 1.5109, Accuracy: 49.06%
Learning Rate = 0.045726


. Batch=782 Loss=0.8485 Acc=61.83%
100% 391/391 [00:29<00:00, 14.66it/s]
Validation loss decreased (1.510893 --> 1.322811).  Saving model ...
Epoch: 2, Train set: Average loss: 0.0085, Accuracy: 61.83%; Test set: Average loss: 1.3228, Accuracy: 58.85%
Learning Rate = 0.131107


. Batch=1173 Loss=0.6951 Acc=69.77%
100% 391/391 [00:28<00:00, 13.51it/s]
Validation loss decreased (1.322811 --> 0.754300).  Saving model ...
Epoch: 3, Train set: Average loss: 0.0068, Accuracy: 69.77%; Test set: Average loss: 0.7543, Accuracy: 74.68%
Learning Rate = 0.228148


. Batch=1564 Loss=0.9100 Acc=74.09%
100% 391/391 [00:28<00:00, 14.80it/s]
Validation loss decreased (0.754300 --> 0.651653).  Saving model ...
Epoch: 4, Train set: Average loss: 0.0058, Accuracy: 74.09%; Test set: Average loss: 0.6517, Accuracy: 77.39%
Learning Rate = 0.291394


. Batch=1955 Loss=0.6504 Acc=77.03%
100% 391/391 [00:28<00:00, 14.64it/s]
Validation loss decreased (0.651653 --> 0.637261).  Saving model ...
Epoch: 5, Train set: Average loss: 0.0051, Accuracy: 77.03%; Test set: Average loss: 0.6373, Accuracy: 78.94%
Learning Rate = 0.298307


. Batch=2346 Loss=0.5646 Acc=79.56%
100% 391/391 [00:29<00:00, 13.45it/s]
Validation loss decreased (0.637261 --> 0.513277).  Saving model ...
Epoch: 6, Train set: Average loss: 0.0045, Accuracy: 79.56%; Test set: Average loss: 0.5133, Accuracy: 83.03%
Learning Rate = 0.285096


. Batch=2737 Loss=0.6576 Acc=81.64%
100% 391/391 [00:28<00:00, 14.81it/s]
Validation loss decreased (0.513277 --> 0.489063).  Saving model ...
Epoch: 7, Train set: Average loss: 0.0041, Accuracy: 81.64%; Test set: Average loss: 0.4891, Accuracy: 84.07%
Learning Rate = 0.259880


. Batch=3128 Loss=0.6176 Acc=83.41%
100% 391/391 [00:28<00:00, 14.57it/s]
Validation loss decreased (0.489063 --> 0.429212).  Saving model ...
Epoch: 8, Train set: Average loss: 0.0037, Accuracy: 83.41%; Test set: Average loss: 0.4292, Accuracy: 85.58%
Learning Rate = 0.224901


. Batch=3519 Loss=0.4249 Acc=84.72%
100% 391/391 [00:28<00:00, 14.76it/s]
Validation loss decreased (0.429212 --> 0.402917).  Saving model ...
Epoch: 9, Train set: Average loss: 0.0034, Accuracy: 84.72%; Test set: Average loss: 0.4029, Accuracy: 86.92%
Learning Rate = 0.183267


. Batch=3910 Loss=0.2587 Acc=86.38%
100% 391/391 [00:29<00:00, 14.82it/s]
Validation loss decreased (0.402917 --> 0.359327).  Saving model ...
Epoch: 10, Train set: Average loss: 0.0031, Accuracy: 86.38%; Test set: Average loss: 0.3593, Accuracy: 87.82%
Learning Rate = 0.138677


. Batch=4301 Loss=0.3455 Acc=87.55%
100% 391/391 [00:28<00:00, 14.69it/s]
Validation loss decreased (0.359327 --> 0.353305).  Saving model ...
Epoch: 11, Train set: Average loss: 0.0028, Accuracy: 87.55%; Test set: Average loss: 0.3533, Accuracy: 88.04%
Learning Rate = 0.095093


. Batch=4692 Loss=0.3563 Acc=88.93%
100% 391/391 [00:29<00:00, 13.48it/s]
Validation loss decreased (0.353305 --> 0.350839).  Saving model ...
Epoch: 12, Train set: Average loss: 0.0025, Accuracy: 88.93%; Test set: Average loss: 0.3508, Accuracy: 88.31%
Learning Rate = 0.056388


. Batch=5083 Loss=0.3655 Acc=90.58%
100% 391/391 [00:28<00:00, 13.53it/s]
Validation loss decreased (0.350839 --> 0.304058).  Saving model ...
Epoch: 13, Train set: Average loss: 0.0021, Accuracy: 90.58%; Test set: Average loss: 0.3041, Accuracy: 90.03%
Learning Rate = 0.026001


. Batch=5474 Loss=0.4202 Acc=92.00%
100% 391/391 [00:28<00:00, 13.61it/s]
Validation loss decreased (0.304058 --> 0.284838).  Saving model ...
Epoch: 14, Train set: Average loss: 0.0018, Accuracy: 92.00%; Test set: Average loss: 0.2848, Accuracy: 91.22%
Learning Rate = 0.006631


. Batch=5865 Loss=0.2214 Acc=92.88%
100% 391/391 [00:29<00:00, 13.41it/s]
Validation loss decreased (0.284838 --> 0.283242).  Saving model ...
Epoch: 15, Train set: Average loss: 0.0016, Accuracy: 92.88%; Test set: Average loss: 0.2832, Accuracy: 91.21%
Learning Rate = 0.000001
