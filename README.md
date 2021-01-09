#### 写在前面：
​	视频教程：https://www.bilibili.com/video/BV1mK4y1V7cd/ 

​	项目原地址：https://github.com/testerSunshine/12306   

​	因作为没有维护，本人进行二次开发，现在可以用【2020-12-24】。
- 目前在维护版本地址：https://github.com/gzldc/12306



   - 

启动命令：
   1.安装依赖包:  pip3 install -r requirements.txt -i https://mirrors.aliyun.com/pypi/simple
   2.加入cdn:    python3 run.py c
   3.启动脚本:    python3 run.py r  

## IP 代理池
推荐一个ip代理池的项目：https://github.com/Python3WebSpider/ProxyPool
简单使用方法：`docker-compose up`

## 本地云打码平台搭建（基于docker)
在安装好docker环境下，运行如下命令：
```angular2html
docker run -d -p 8080:80 --name 12306 yinaoxiong/12306_code_server
```
