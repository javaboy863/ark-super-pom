# 1.什么是ark-super-pom？
&emsp;&emsp;ark-super-pom是ark系列框架里面，负责统一管理jar的组件，它的作用是统一管理jar的版本号和jar的依赖关系。

# 2.ark-super-pom解决了什么问题？
&emsp;&emsp;当公司里的服务只是单体服务时，并不需要此组件管理jar。当服务数量到一定规模时（>5），需要统一管控各服务的依赖及版本号，因此有了ark-super-pom组件。

# 3.使用场景
- 微服务较多的公司；
- 中大型互联网公司；
- 其他需要统一管理jar的版本号和jar依赖关系的场景。

# 4.ark-super-pom如何使用？
```xml
<parent>
    <groupId>com.ark</groupId>
    <artifactId>ark-super-pom</artifactId>
    <version>1.0</version>
</parent>
```