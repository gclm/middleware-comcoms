<<<<<<< Updated upstream
# oss-nexus-parent
nexus/Maven 中央仓库上传父类

# 功能点

- 证书
- 开发者
- 上传配置文件

# 使用方法

# oss-nexus-parent
nexus/Maven 中央仓库上传父类

# 功能点

- 证书
- 开发者
- 上传配置文件

# 使用方法

1. 添加 POM 依赖

```xml
<parent>
     <groupId>club.gclmit</groupId>
     <artifactId>oss-nexus-parent</artifactId>
     <version>2.0.0</version>
</parent>
```
__
2. 执行下面的指令

```shell script
mvn clean deploy -P nexus-oss-release
=======
# oss-nexus-parent
nexus/Maven 中央仓库上传父类

# 功能点

- 证书
- 开发者
- 上传配置文件

# 使用方法

## 中央仓库

1. 添加 POM 依赖

```xml
<parent>
     <groupId>club.gclmit</groupId>
     <artifactId>oss-nexus-parent</artifactId>
     <version>1.0.0</version>
</parent>
```

2. 执行下面的指令

```shell script
mvn clean deploy -P sonatype-oss-release
>>>>>>> Stashed changes
```