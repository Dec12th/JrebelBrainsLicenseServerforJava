# JrebelBrainsLicenseServerforJava
## 自建JRebel License Server
自建JRebel License Server 用到的源码

编译打包：mvn clean package

启动命令：
java -jar JrebelBrainsLicenseServerforJava-1.0-SNAPSHOT-jar-with-dependencies.jar -p 8081

linux后台启动：nohup java -jar JrebelBrainsLicenseServerforJava-1.0-SNAPSHOT-jar-with-dependencies.jar -p 8081 >/dev/null 2>&1 &


访问地址:http://localhost:8081/{GUID}
guid可以使用UUID直接生成，或者使用https://www.uuidgenerator.net

## 破解补丁破解IDEA

### 补丁地址
https://raw.githubusercontent.com/Dec12th/JrebelBrainsLicenseServerforJava/master/JetbrainsIdesCrack-4.2-release.jar

### 使用方法
1. 将补丁放在安装包的/bin路径下;
2. 分别 对本文件夹(bin)下的idea.exe.vmoptions和idea64.exe.vmoptions这两个文件进行修改，打开文件在末尾添加如下配置指令：
<pre><code>
Windows版：-javaagent:D:/idea/bin/JetbrainsIdesCrack-4.2-release.jar

Mac版：-javaagent:../bin/JetbrainsIdesCrack-4.2-release.jar

Linux版：-javaagent:../bin/JetbrainsIdesCrack-4.2-release.jar
</code></pre>
保存编辑后的文件;


3. 拷贝如下注册码：
<pre><code>
ThisCrackLicenseId-{
"licenseId":"ThisCrackLicenseId",
"licenseeName":"Rover12421",
"assigneeName":"",
"assigneeEmail":"rover12421@163.com",
"licenseRestriction":"For Rover12421 Crack, Only Test! Please support genuine!!!",
"checkConcurrentUse":false,
"products":[
{"code":"II","paidUpTo":"9998-12-31"},
{"code":"DM","paidUpTo":"9998-12-31"},
{"code":"AC","paidUpTo":"9998-12-31"},
{"code":"RS0","paidUpTo":"9998-12-31"},
{"code":"WS","paidUpTo":"9998-12-31"},
{"code":"DPN","paidUpTo":"9998-12-31"},
{"code":"RC","paidUpTo":"9998-12-31"},
{"code":"PS","paidUpTo":"9998-12-31"},
{"code":"DC","paidUpTo":"9998-12-31"},
{"code":"RM","paidUpTo":"9998-12-31"},
{"code":"CL","paidUpTo":"9998-12-31"},
{"code":"PC","paidUpTo":"9998-12-31"}
],
"hash":"2911276/0",
"gracePeriodDays":7,
"autoProlongated":false}
  </code></pre>
4. 打开IDEA，进入激活窗口此时需要选择 激活码(Activation code) 的激活方式，并输入刚刚拷贝激活码进行激活
5. 激活完成
