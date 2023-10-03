

# The Paper
<a href='https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf'>ImageNet Classification with Deep Convolutional
Neural Networks</a>

# Architecture 
### Important Features of the Architecture: 
1. ReLu Activation Functions
2. Distributed Training 
3. Local Response Normalisation
4. Overlapping Pooling

### Methods to Reduce Overfitting
- Data Augmentation
- Dropout

### Network Architecture 

![AlexNet](https://github.com/stephenCarmody/pytorch-playground/blob/main/1-AlexNet/images/AlexNet.png)


# Notes
- I aimed not to recreate their distributed training schema due to time constraints. Instead I plan to use something more modern from <code>torch.dsitributed</code>.