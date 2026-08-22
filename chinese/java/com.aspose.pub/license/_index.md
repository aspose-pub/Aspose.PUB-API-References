---
title: "许可证"
second_title: "Aspose.PUB for Java API 参考"
description: "提供对组件授权的方法。"
type: docs
weight: 14
url: /zh/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

提供对组件授权的方法。

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹中查找名为 MyLicense.lic 的许可证文件，随后在调用程序集的嵌入资源中查找。

License license = new License();
license.setLicense("MyLicense.lic");
## 构造函数

| Constructor | 描述 |
| --- | --- |
| [License()](#License--) | 初始化此类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | 默认情况下我们使用默认的 JDK 安全。 |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | 默认情况下，我们使用默认的 JRE 安全。 |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 授权组件。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 授权组件。 |
### License() {#License--}
```
public License()
```


初始化此类的新实例。

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹中查找名为 MyLicense.lic 的许可证文件，随后在调用程序集的嵌入资源中查找。

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


默认情况下我们使用默认的 JDK 安全。默认值 == false。在某些情况下，定制的 Java 环境可能不支持所需的算法，因此我们建议使用内部内置的 FIPS 安全。

**Returns:**
boolean - boolean 值
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


默认情况下，我们使用默认的 JRE 安全。默认值 == false。在某些情况下，定制的 Java 环境可能不支持所需的算法，因此我们建议使用内部内置的 FIPS 安全。另请注意：根据 JVM SecureRandom 算法，在某些操作系统上 /dev/random 在返回结果之前会等待主机生成一定量的 \\u201cnoise\\u201d。Oracle\\u2019s JVM 用于随机数生成的库在 UNIX 平台上默认依赖 /dev/random。虽然 /dev/random 更安全，但如果默认 JVM 配置导致延迟，建议使用 /dev/urandom，或添加产生熵的设备供 /dev/random 使用。以下 java 选项可帮助避免延迟并覆盖 securerandom.source 设置。-Djava.security.egd=file:/dev/./urandom

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| internalFIPSSecurity | 布尔 | 布尔值 |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


授权组件。

尝试在以下位置查找许可证：

1. 明确的路径。

2. 组件 jar 文件的文件夹。

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹中查找名为 MyLicense.lic 的许可证文件，随后在调用程序集的嵌入资源中查找。

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | java.lang.String | 可以是完整或简短的文件名，或嵌入资源的名称。使用空字符串切换到评估模式。 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


授权组件。

包含许可证的流。

使用此方法从流中加载许可证。

License license = new License();
license.setLicense(myStream);

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | license 流 |

