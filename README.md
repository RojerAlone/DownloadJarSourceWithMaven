# 用maven下载jar包以及源码
　　修改`pom.xml`文件中的依赖，保存后双击`installsource.bat`即可。
## maven 阿里云仓库
```xml
<mirror>
    <id>alimaven</id>
    <name>aliyun maven</name>
    <url>http://maven.aliyun.com/nexus/content/groups/public/</url>
    <mirrorOf>central</mirrorOf>        
</mirror>
```