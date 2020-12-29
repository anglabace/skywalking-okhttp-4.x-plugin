# skywalking-okhttp-4.x-plugin
skywalking 兼容okhttp 4.x版本的自动注入

# 编译`jar`包
克隆`master`分支代码到本地，使用`maven`命令进行构建，拷贝`target`目录下的`okhttp-4.x.jar`包到`agent/plugin`目录，再重启`skywalking agent`
```
cd skywalking-okhttp-4.x-plugin
mvn clean install
```
