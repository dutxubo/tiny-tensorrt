<!--
 * @Description: In User Settings Edit
 * @Author: zerollzeng
 * @Date: 2019-08-23 09:16:35
 * @LastEditTime: 2019-12-16 19:38:35
 * @LastEditors: zerollzeng
 -->

English | [中文简体](https://github.com/zerollzeng/tiny-tensorrt/blob/master/docs/README-CN.md)

![image](https://user-images.githubusercontent.com/38289304/70904144-96992680-203b-11ea-9d41-221af2fe3d5b.png)

# tiny-tensorrt
a simple, efficient, easy-to-use nvidia TensorRT wrapper for cnn with c++ and python api,support caffe, uff and onnx format models.

# Features
- [x] Custom plugin tutorial and well_commented sample! ---2019-12-11 :fire::fire::fire:
- [x] Custom onnx model output node  ---2019.10.18
- [x] Upgrade with TensorRT 6.0.1.5 --- 2019.9.29
- [x] Support onnx,caffe and tensorflow model
- [ ] Support more model and layer --working on
- [x] PReLU and up-sample plugin
- [x] Engine serialization and deserialization
- [x] INT8 support for caffe model
- [x] Python api support
- [x] Set device

# System Requirements
cuda 10.0+

TensorRT 6.x

for python api, python 2.x/3.x and numpy in needed

this project is fully test in ubuntu 16.04. I tested it with 1060ti, 1050ti, 1080ti, 1660ti, 2080, 2080ti and p4.

# Docs

[User Guide](https://github.com/zerollzeng/tiny-tensorrt/blob/master/docs/UserGuide.md)

[Custom Plugin Tutorial](https://github.com/zerollzeng/tiny-tensorrt/blob/master/docs/CustomPlugin.md)

# Extra Support layer
- upsample with custom scale, under test with yolov3.
- yolo-det, last layer of yolov3 which sum three scales output and generate final result for nms. under test with yolov3.
- PRELU, under test with openpose and mtcnn.

# About License
For the 3rd-party module and TensorRT, maybe you need to follow their license

For the part I wrote, you can do anything you want

