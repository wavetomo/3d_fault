# 3d_fault
offical code for the paper “3D seismic fault detection using recurrent convolutional neural networks with compound loss”
## (0) environment requirement  
pytorch1.9.0 || pytorch-lightning 1.5.5

## (1)the data used in the notebook
链接：https://drive.google.com/file/d/1j637LrLEjqmmWkWxKdWVJ2IDj3a6ZTdO/view?usp=sharing
## (2)Usage
### import the field seismic data in this line: gx = np.load("/data/max/3d-nets/f3.npy")# load the data in this line  
### load the weight in this line: model=model.load_from_checkpoint("")# load the weight in this line
### Then, run the notebook from start.
