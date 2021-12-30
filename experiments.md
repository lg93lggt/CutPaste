# Experiment Results
To train self-supervised model we used same hyperparameters as was used in paper: 
| Hyperparameter  | Value |
| ------------- | ------------- |
| Number of epochs | 265 |
| Batch size | 32 |
| Learning rate | 0.03 |
| Input size | 256 |


## AUC comparison of our code and paper results

| Defect Name  | CutPaste binary (ours) | CutPaste binary (paper's)  | 
| ------------- | ------------- | ------------- | 
| tile  | 84.1 | 95.9 | 
| wood  | 89.5 | 94.9 | 
| pill | 88.7 | 93.4 | 
| leather | 98.7 | 99.7 | 
| hazelnut | 98.8 | 91.3 | 
| screw | 89.2 | 54.4 | 
| cable | 83.3 | 87.7 | 
| toothbrush | 94.7 | 99.2 | 
| capsule | 80.2 | 87.9 | 
| carpet | 57.9 | 67.9 | 
| zipper | 99.5 | 99.4 | 
| metal_nut | 91.5 | 96.8 | 
| bottle | 98.5 | 99.2 | 
| grid | 99.9 | 99.9 | 
| transistor | 84.4 | 96.4 | 


## ROC curves using embeddings from binary classification for self-supervised learning
<p float="left">
  <img src="/experiments/roc_binary/bottle.jpg" width="260" />
  <img src="experiments/roc_binary/cable.jpg" width="260" /> 
  <img src="experiments/roc_binary/capsule.jpg" width="260" />
</p>
<p float="left">
  <img src="/experiments/roc_binary/carpet.jpg" width="260" />
  <img src="experiments/roc_binary/grid.jpg" width="260" /> 
  <img src="experiments/roc_binary/hazelnut.jpg" width="260" />
</p>
<p float="left">
  <img src="/experiments/roc_binary/leather.jpg" width="260" />
  <img src="experiments/roc_binary/metal_nut.jpg" width="260" /> 
  <img src="experiments/roc_binary/pill.jpg" width="260" />
</p> 

<p float="left">
  <img src="experiments/roc_binary/toothbrush.jpg" width="260" />
  <img src="/experiments/roc_binary/screw.jpg" width="260" />
  <img src="experiments/roc_binary/tile.jpg" width="260" /> 
</p> 

<p float="left">
  <img src="experiments/roc_binary/zipper.jpg" width="260" />
  <img src="experiments/roc_binary/wood.jpg" width="260" /> 
  <img src="/experiments/roc_binary/transistor.jpg" width="260" />
</p>


## Self-supervised binary training results

**Training accuracy and loss for bottle**
<p float="left">
  <img src="experiments/self-supervised_binary/train_acc_bottle.png" width="300" />
  <img src="experiments/self-supervised_binary/train_loss_bottle.png" width="300" /> 
</p>


**Training accuracy and loss for pill**
<p float="left">
  <img src="experiments/self-supervised_binary/train_acc_pill.png" width="300" />
  <img src="experiments/self-supervised_binary/train_loss_pill.png" width="300" /> 
</p>


**Training accuracy and loss for cable**
<p float="left">
  <img src="experiments/self-supervised_binary/train_acc_cable.png" width="300" />
  <img src="experiments/self-supervised_binary/train_loss_cable.png" width="300" /> 
</p>


**Training accuracy and loss for capsule**
<p float="left">
  <img src="experiments/self-supervised_binary/train_acc_capsule.png" width="300" />
  <img src="experiments/self-supervised_binary/train_loss_capsule.png" width="300" /> 
</p>


**Training accuracy and loss for tile**
<p float="left">
  <img src="experiments/self-supervised_binary/train_acc_tile.png" width="300" />
  <img src="experiments/self-supervised_binary/train_loss_tile.png" width="300" /> 
</p>
 

## Results of Self-supervised with 3-way classification will be added soon 