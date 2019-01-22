# Tracking by Detection Using YOLOv3 for Test

## Requirements
- python 2.7
- tensorflow_gpu
- keras
- opencv-python

## How to use
- 1 Install python 2.7 (we recommend you use [Anaconda](https://www.anaconda.com/download))
- 2 Install `cuda` and `cudnn` following this [website](https://developer.nvidia.com/cuda-90-download-archive)
- 3 Install python requirements using `pip`    
- 3 Download the yolov3 model from [here](https://pan.baidu.com/s/1FZjFZoukOfqfMMCUX48kng), and put the model file `yolov3.h5` into `./models` folder.
- 4 Change the `video_path`  or `img_series_path` in `main.py` to the videos or image series you want to  detect.
- 5 run `python main.py ` in the terminal, and you will see the tracking result. 

## References
- 1 [yolo](https://pjreddie.com/darknet/yolo/)
- 2 [kalman filter]()
