# Ambari-service-custom
Ambari集成flume1.7，es7.2，kibana7.2

以flume1.7为例

1. 下载flume1.7压缩包
2. 上传至Ambari集群的主节点
3. 解压缩
4. 将解压缩后的文件夹复制到Ambari service文件夹下
    
    ```shell
    [root@vm01 apps]# cp -r ./FLUME-1.7 /var/lib/ambari-server/resources/stacks/HDP/2.6/services
    ```
5. 重启ambari server
6. 在ambari的web页面进行安装

注：flume1.7安装时和自带的flume不同，需要提前将conf参数设置好

具体自定义服务步骤请查看：[小柚麯]()
