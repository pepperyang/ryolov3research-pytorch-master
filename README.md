An oriented bounding boxes implement of YOLOv3 with SEnet , Deformable Convolution and rotated NMS written in CUDA. 

enviroment： 
ubuntu16.04 pytorch1.1

requirement：
numpy
opencv
matplotlib
tensorboardX
shapely

install:

cd ./yolo/nms

python setup.py build_ext --inplace

usage:

1.make your own dataset by labeImage https://github.com/woshiwwwppp/ryolov3research-pytorch-master/blob/master/labelImg.exe

2.use generate_data.py to get label file

3.set the parameter in object_classes_all.txt and config.py

3.use train.py to train

![image](https://github.com/woshiwwwppp/ryolov3research-pytorch-master/blob/master/picture.jpg)
