## 测试OpenCV条形码检测
Reference:
- http://www.pyimagesearch.com/2014/11/24/detecting-barcodes-images-python-opencv/


## 使用OpenCV Docker镜像
镜像地址 https://github.com/janza/docker-python3-opencv

启动镜像
 `docker run -it docker-python3-opencv python`
或者
 `docker run -it docker-python3-opencv bash`

设置文件挂载 
`sudo docker run -it -v /home/peter/workspace/image-test:/tmp/image-test 8d7c146d2561 python`