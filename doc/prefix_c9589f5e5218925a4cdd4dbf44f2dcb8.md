##功能描述
* 可以通过自定义Dockerfile，build完之后，导出docker镜像。命令如下：
1、docker build ：`docker build -t 镜像名 .`
2、导出docker镜像 ：`docker save -o /xxx/镜像名.tar 镜像名`
3、将镜像包同步给 opensource@tsign.cn
4、欺骗防御开发团队对镜像包进行安全扫描，如果无安全风险，团队会将该镜像包上传到公用Harbor上。

##开发说明

##使用说明

##注意事项