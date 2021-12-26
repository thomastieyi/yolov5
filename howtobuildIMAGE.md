1. 
```
cd yolov5

docker build -f DockerCPU  -t  xxxxx/yolov5cpu ./

注意把DockerCPU文件中115.25.41.49:2340的代理地址换成你自己的
```
2.
 ```
 sudo docker run --ipc=host -it  xxxxx/yolov5cpu

 python3 detect.py
 ```