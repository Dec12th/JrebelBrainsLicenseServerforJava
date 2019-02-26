# JrebelBrainsLicenseServerforJava
自建JRebel License Server 用到的源码

编译打包：mvn clean package

启动命令：
java -jar JrebelBrainsLicenseServerforJava-1.0-SNAPSHOT-jar-with-dependencies.jar -p 8081

linux后台启动：nohup java -jar JrebelBrainsLicenseServerforJava-1.0-SNAPSHOT-jar-with-dependencies.jar -p 8081 >/dev/null 2>&1 &


访问地址:http://localhost:8081/{GUID}
guid可以使用UUID直接生成，或者使用https://www.uuidgenerator.net
