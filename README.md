# 3d_fault
offical code for the paper “3D seismic fault detection using recurrent convolutional neural networks with compound loss”
## (0) environment requirement  
pytorch1.9.0 || pytorch-lightning 1.5.5

## (1)the data used in the notebook
link：https://drive.google.com/file/d/1j637LrLEjqmmWkWxKdWVJ2IDj3a6ZTdO/view?usp=sharing
## (2)the onnx file used in the notebook
link：https://drive.google.com/file/d/1yXmXEpjaDEQyMrio9xNpKgJsvmMxFvPk/view?usp=share_link
## (3)Usage
### import the field seismic data in this line: gx = np.load("/home1/max/3d-net/data_for_seminal/f3.npy")# load the data in this line  
### load the weight in this line: filepath="model.onnx"# load the weight and model in this line
### Then, run the notebook from start.
