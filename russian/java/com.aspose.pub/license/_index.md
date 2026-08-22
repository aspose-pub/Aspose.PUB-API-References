---
title: "Лицензия"
second_title: "Aspose.PUB для Java справочник API"
description: "Предоставляет методы лицензирования компонента."
type: docs
weight: 14
url: /ru/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Предоставляет методы лицензирования компонента.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

License license = new License();
license.setLicense(\"MyLicense.lic\");
## Конструкторы

| Constructor | Описание |
| --- | --- |
| [License()](#License--) | Инициализирует новый экземпляр этого класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | По умолчанию мы используем стандартную безопасность jdk. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | По умолчанию мы используем стандартную безопасность jre. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
### License() {#License--}
```
public License()
```


Инициализирует новый экземпляр этого класса.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

License license = new License();
license.setLicense(\"MyLicense.lic\");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


По умолчанию мы используем стандартную безопасность jdk. Значение по умолчанию == false. В некоторых случаях настроенная среда Java не поддерживает требуемые алгоритмы, поэтому мы можем предложить использовать внутреннюю встроенную безопасность FIPS.

**Returns:**
boolean - значение boolean
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


По умолчанию мы используем стандартную безопасность jre. Значение по умолчанию == false. В некоторых случаях настроенная среда Java не поддерживает требуемые алгоритмы, поэтому мы можем предложить использовать внутреннюю встроенную безопасность FIPS. Также обратите внимание: согласно алгоритму JVM SecureRandom в некоторых операционных системах /dev/random ожидает генерацию определённого количества \\\\\\u201cnoise\\\\\\\u201d на хост‑машине перед возвратом результата. Библиотека, используемая для генерации случайных чисел в JVM Oracle, по умолчанию полагается на /dev/random для UNIX‑платформ. Хотя /dev/random более безопасен, рекомендуется использовать /dev/urandom, если конфигурация JVM по умолчанию вызывает задержки, или добавить устройства, генерирующие энтропию для /dev/random. Следующая опция java может помочь избежать задержек и переопределить настройку securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| internalFIPSSecurity | boolean | логическое значение |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Лицензирует компонент.

Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка файла jar компонента.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

License license = new License();
license.setLicense(\"MyLicense.lic\");

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | java.lang.String | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку, чтобы переключиться в режим оценки. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Лицензирует компонент.

Поток, содержащий лицензию.

Используйте этот метод для загрузки лицензии из потока.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | java.io.InputStream | license Поток |

