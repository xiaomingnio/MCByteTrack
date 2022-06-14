# MCByteTrack
The c++ implement of Multi class ByteTrack

#### 安装
安装eigen-3.3.9和opencv4.6(包括contrib)

#### 相关下载
```
模型下载 yolox onnx 模型
https://github.com/Megvii-BaseDetection/YOLOX/tree/main/demo/ONNXRuntime 

示例视频下载
https://pan.baidu.com/s/1RhT7UVtYK_3qiCg36GTb8Q?pwd=test
```
#### 编译运行
修改cmakelists的opencv路径

```
mkdir build 
cd build && rm -rf * 
cmake .. && make 
```

#### Acknowledgement
https://github.com/Megvii-BaseDetection/YOLOX
https://github.com/hpc203/bytetrack-opencv-onnxruntime
https://github.com/CaptainEven/MCMOT-ByteTrack
https://github.com/huangwgang/MCFairMot


