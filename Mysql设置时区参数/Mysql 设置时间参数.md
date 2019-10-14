# JDBC ——MySQL 设置时区参数

问题：Exception in thread "main" java.sql.SQLException: The server time zone value '�й���׼ʱ��' is unrecognized or represents

![](img\01.png)



解决方法：给 url 设置时区参数

```java
String url = "jdbc:mysql://localhost:3306/taobao?serverTimezone=Asia/Shanghai" ;
```



![](img\02.png)