# SpringBoot版本升级问题

**SpringBoot 2.0.8** 升级到 **SpringBoot 2.3.9** 。

修改**enbank**工程下的**athena-dependencies**的**pom.xml**文件配置。

```xml
<spring.version>5.0.12.RELEASE </spring.version>
<spring-boot.version>2.0.8.RELEASE </spring-boot.version>
```

修改为：

```xml
<spring.version>5.2.13.RELEASE </spring.version>
<spring-boot.version>2.3.9.RELEASE </spring-boot.version>
```



# 1、snakeyaml 错误

错误：

```shell
java.lang.NoSuchMethodError: org.yaml.snakeyaml.LoaderOptions.setMaxAliasesForCollections(I)V
```

解决：

修改 **snakeyaml**版本号，保持版本号一致。

```xml
<snakeyaml.version>1.19</snakeyaml.version>
```

修改为升级后的**SrpingBoot**中的**snakeyaml**版本：

```xml
<snakeyaml.version>1.26</snakeyaml.version>
```

修改后重新加载maven，再次运行程序。



# 2、flywaydb错误

错误：

```shell
java.lang.NoClassDefFoundError: org/flywaydb/core/api/configuration/FluentConfiguration
```

解决：

修改 **flywaydb**版本号，**SpringBoot2.x**需要**flywaydb5.1**以上的。

```xml
<flywaydb.version>4.2.0</flywaydb.version>
```

修改为：

```xml
<flywaydb.version>5.2.4</flywaydb.version>
```

修改后重新加载maven，再次运行程序。



# 3、palceholder问题

**db-config.xml**文件无法读取**yml**文件的配置。

错误：

```shell
java.lang.IllegalArgumentException：Could not resolve palceholder 'datasource.driver' in value "${datasource.driver}"
```

原因：**SpringBoot**版本与**SpringClould**版本冲突。

解决：升级**SpringCloud**版本。

```xml
<spring-clould.version>Finchley.SR4</spring-clould.version>
```

修改为

```xml
<spring-clould.version>Hoxton.SR10</spring-clould.version>
```



修改后重新加载maven，再次运行程序，无报错，程序可以正常运行，除参数中心外，各中心启动成功。



# 4、参数中心启动失败

参数中心启动失败，**redis**配置出错。

报错：

```xml
java.lang.NoSuchMethodError:org.springframework.data.redis.repository.configureation.RedisRepositoryConfigrationExtension.
```

解决措施：

注释掉pom.xml文件中的redis配置，重构项目。

```xml
<!-- redis -->
<dependency>
............
</dependency>
<!-- redis end -->
```

注：项目未使用**redis**，故无需进行**redis**配置。

重构完成，启动成功。