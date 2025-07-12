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

# Springboot
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

# Maven
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
