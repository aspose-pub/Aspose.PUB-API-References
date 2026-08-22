---
title: "PubException"
second_title: "Aspose.PUB for Java API 参考"
description: "表示在 PUB 应用程序执行期间发生的错误。"
type: docs
weight: 11
url: /zh/java/com.aspose.pub.exceptions/pubexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException
```
public class PubException extends System.ApplicationException
```

表示在 PUB 应用程序执行期间发生的错误。
## 构造函数

| Constructor | 描述 |
| --- | --- |
| [PubException(String message)](#PubException-java.lang.String-) | 初始化 [PubException](../../com.aspose.pub.exceptions/pubexception) 类的新实例。 |
| [PubException(String message, Throwable innerException)](#PubException-java.lang.String-java.lang.Throwable-) | 使用指定的错误消息和指向导致此异常的内部异常的引用，初始化 [PubException](../../com.aspose.pub.exceptions/pubexception) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMessage()](#getMessage--) | 获取描述当前异常的消息。 |
### PubException(String message) {#PubException-java.lang.String-}
```
public PubException(String message)
```


初始化 [PubException](../../com.aspose.pub.exceptions/pubexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 该消息。 |

### PubException(String message, Throwable innerException) {#PubException-java.lang.String-java.lang.Throwable-}
```
public PubException(String message, Throwable innerException)
```


使用指定的错误消息和指向导致此异常的内部异常的引用，初始化 [PubException](../../com.aspose.pub.exceptions/pubexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 解释异常原因的错误消息。 |
| innerException | java.lang.Throwable | 导致当前异常的异常，或者如果未指定内部异常，则为 null 引用（Visual Basic 中为 Nothing）。 |

### getMessage() {#getMessage--}
```
public String getMessage()
```


获取描述当前异常的消息。

**Returns:**
java.lang.String
