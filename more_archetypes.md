# 获取更多archetypes #
## rapid-flex-hibernate ##
```
mvn archetype:generate -B -DarchetypeGroupId=com.googlecode.rapid-framework  -DarchetypeArtifactId=rapid-flex-hibernate  -DarchetypeVersion=1.0 -DgroupId=com.company.project  -DartifactId=flex-hibernate-demo  -Dversion=1.0 -DarchetypeRepository=http://rapid-framework.googlecode.com/svn/trunk/repository
```
## rapid-flex-ibatis ##
```
mvn archetype:generate -B -DarchetypeGroupId=com.googlecode.rapid-framework -DarchetypeArtifactId=rapid-flex-ibatis  -DarchetypeVersion=1.0 -DgroupId=com.company.project  -DartifactId=flex-ibatis-demo  -Dversion=1.0 -DarchetypeRepository=http://rapid-framework.googlecode.com/svn/trunk/repository
```

flex插件新特性：
升级MVC框架至cairngorm3；增加依赖注入框架parsely2.4；解决Hibernate延迟加载问题；稍后将整理教程。

## rapid-springmvc-ibatis ##
```
mvn archetype:generate -B -DarchetypeGroupId=com.googlecode.rapid-framework  -DarchetypeArtifactId=rapid-springmvc-ibatis  -DarchetypeVersion=1.0 -DgroupId=com.company.project   -DartifactId=springmvc-ibatis-demo  -Dversion=1.0 -DarchetypeRepository=http://rapid-framework.googlecode.com/svn/trunk/repository
```

项目搭建过程参照
http://code.google.com/p/rapid-framework/wiki/rapid_achetype_springmvc_hibernate