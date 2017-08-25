![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# Added features
YOLO is now able to export image annotations into JSON files (see `annotations/annotation_example.json`). Moreover, it can now deal with an images list given in parameter to annotate images in a row. For instance :
```
$ ./darknet detector test cfg/coco.data cfg/yolo.cfg weights/yolo.weights data/dog.jpg data/horses.jpg
```
# YOLO versions
| YOLO version | Configuration file | Data file | Weights file |
|--------------|-------------|-----------|--------------|
|  YOLO v1 coco| yolo.cfg    | coco.data | yolo.weights |
|  YOLO v2 coco| yolo.2.0.cfg| coco.data | yolo.2.0.weights |
|  YOLO v2 voc | yolo-voc.2.0.cfg| voc.data | yolo-voc.2.0.weights|

# Darknet
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).
