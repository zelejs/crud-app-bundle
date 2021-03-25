# crud-app-bundle
Dependens all required dependencies for CRUD app

### 增加授权模块依赖
```
<dependency>
   <groupId>com.jfeat</groupId>
   <artifactId>uaas</artifactId>
   <version>3.0.2</version>
</dependency>
```

### 第一次运行进行数据初始化
`cat src/main/resources/application.yml`

```yml
# spring.profiles.active由dev改为standlone
spring:
  profiles:
    active: standalone
```

### 成功初始化后`spring.profiles.active`改回`dev`
