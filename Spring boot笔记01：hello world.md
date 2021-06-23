[官方文档](https://docs.spring.io/spring-boot/docs/2.2.13.RELEASE/reference/html/index.html)

### 1、快速创建

依赖的导入不需要一个个添加，spring准备好了一系列的使用场景所需要的依赖，比如：

```java
	<parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>2.3.4.RELEASE</version>
    </parent>

    <dependencies>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
        </dependency>
    </dependencies>
```

表示加载了2.3.4的spring boot版本中，web场景下所需要的依赖，包括json、tomcat、dispatcher Servlet等等。看名字都是叫spring-boot-stater-...的。

![1623984916852](C:\Users\Administrator.DESKTOP-J8UMSB2\AppData\Roaming\Typora\typora-user-images\1623984916852.png)

---



### 2、hello World

- 新建controller

![1623985289603](C:\Users\Administrator.DESKTOP-J8UMSB2\AppData\Roaming\Typora\typora-user-images\1623985289603.png)

![1623985328288](C:\Users\Administrator.DESKTOP-J8UMSB2\AppData\Roaming\Typora\typora-user-images\1623985328288.png)

**controller组件要在主程序同一个目录下，因为默认的组件扫描路径就跟主程序同一个包下面：**

![1623985532112](C:\Users\Administrator.DESKTOP-J8UMSB2\AppData\Roaming\Typora\typora-user-images\1623985532112.png)



### 3、配置文件

 maven工程的resource文件夹中创建application.properties文件。里面进行参数配置，比如服务端口：

![1623985649747](C:\Users\Administrator.DESKTOP-J8UMSB2\AppData\Roaming\Typora\typora-user-images\1623985649747.png)

[更多配置信息](https://docs.spring.io/spring-boot/docs/2.3.7.RELEASE/reference/html/appendix-application-properties.html#common-application-properties-server)



### 4、自定义banner

1. resource下的banner.txt文件，可以自动识别
2. 输入内容

![1623986694578](C:\Users\Administrator.DESKTOP-J8UMSB2\AppData\Roaming\Typora\typora-user-images\1623986694578.png)

[下载地址](https://www.bootschool.net/ascii-art/search)



