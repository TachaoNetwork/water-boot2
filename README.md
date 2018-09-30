# water-boot2
踏潮spring-boot2基础架构

## 1，修改com.zjtachao.fish.water.common.base.boot.WaterBootApplication 类上的注解包名和类名
## 2，在自己的工程中饮用parent和common
```
<parent>
	<artifactId>water-boot-starter-parent</artifactId>
	<groupId>com.zjtachao.fish.water</groupId>
	<version>2.0.0</version>
</parent>
```
```
<dependency>
	<groupId>com.zjtachao.fish.water</groupId>
	<artifactId>water-boot-starter-common</artifactId>
	<version>2.0.0</version>
</dependency>
```
## 3，IDEA上添加启动主类com.zjtachao.fish.water.common.base.boot.WaterBootApplication
