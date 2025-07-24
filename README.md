# Docker
```
    "registry-mirrors": [
        "https://do.nark.eu.org",
        "https://dc.j8.work",
        "https://docker.m.daocloud.io",
        "https://dockerproxy.com",
        "https://docker.mirrors.ustc.edu.cn",
        "https://docker.nju.edu.cn"
    ]
```

---

# Springboot
## 镜像设置
写在`pom.xml`中
```
 <repositories>
    <repository>
        <id>alimaven</id>
        <name>aliyun maven</name>
        <url>http://maven.aliyun.com/nexus/content/groups/public/</url>
    </repository>
</repositories>
```

## Spring Initializr URL
1.官网默认地址```(17/21/24)```
```
https://start.spring.io/
```
2.阿里云代理地址```(8/11/17/19)```
```
http://start.aliyun.com
```
3.国内第三方代理地址```(17/21/24)```
```
https://start.springboot.io
```

---

# Maven
## 镜像设置
写在`setting`中
```
  <mirrors>
    <mirror>  
     <id>alimaven</id>  
     <name>aliyun maven</name>  
     <url>http://maven.aliyun.com/nexus/content/groups/public/</url>  
     <mirrorOf>central</mirrorOf>          
   	</mirror> 
  </mirrors>
```

## Maven 包手动安装
```bash
mvn install:install-file -Dfile="E:\FirefoxDownload\langchain4j-open-ai-1.1.0.jar" -DgroupId="dev.langchain4j" -DartifactId="langchain4j-open-ai" -Dversion="1.1.0" -Dpackaging=jar
```

## 中央仓库地址
- https://mvnrepository.com/

---

# Git 代理设置
```bash
git config --global http.proxy http://127.0.0.1:7890
```
