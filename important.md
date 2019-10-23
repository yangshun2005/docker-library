# azure提供了下载gcr的镜像方法
### GCR Proxy Cache服务器相当于一台GCR镜像服务器，国内用户可以经由该服务器从gcr.io下载镜像。
http://mirror.azure.cn/help/gcr-proxy-cache.html


```
使用GCR Proxy Cache从gcr.io下载镜像
docker pull gcr.azk8s.cn/google_containers/<imagename>:<version>
例子
docker pull gcr.azk8s.cn/google_containers/pause-amd64:3.0
docker pull gcr.azk8s.cn/google_containers/kubedns-amd64:1.7
```

# 在科学上网的情况下，在gcr查看img方法

打开 https://console.cloud.google.com/gcr/images/google-containers/GLOBAL ，在右边的“过滤条件“中输入关键词来搜索。

然后再选择正确的镜像。

通常，gcr.io官方镜像的命名规则为：
gcr.io/google_containers/IMAGE_NAME:IMAGE_TAG

比如：
gcr.io/google_containers/kube-apiserver-amd64:v1.10.3
————————————————
版权声明：本文为CSDN博主「nklinsirui」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/nklinsirui/article/details/80581286

# Kubernetes国内镜像、下载安装包和拉取gcr.io镜像
https://blog.csdn.net/nklinsirui/article/details/80581286
