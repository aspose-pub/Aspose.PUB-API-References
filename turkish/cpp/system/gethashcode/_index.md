---
title: "System::GetHashCode yöntemi"
linktitle: "GetHashCode"
second_title: "Aspose.PUB için C++"
description: "System::GetHashCode yöntemi. std::thread::id için özelleştirme; C++'da belirtilen thread nesnesi için hash kodunu döndürür."
type: docs
weight: 19300
url: /tr/cpp/system/gethashcode/
---
## System::GetHashCode(const std::thread::id\&) method


std::thread::id için özelleştirme; belirtilen thread nesnesi için hash kodunu döndürür.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::GetHashCode(const T\&) method


Belirtilen skaler değer için bir hash kodu döndürür.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun hash kodu ürettiği değerin tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | Hash kodu üretilecek değer |

### ReturnValue

Belirtilen değer için üretilen hash kodu

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::GetHashCode(const T\&) method


Belirtilen nesne için bir hash kodu döndürür.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun hash kodu ürettiği nesnenin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | Hash kodu üretilecek nesneyi işaret eden [SmartPtr](../smartptr/) |

### ReturnValue

Belirtilen nesne için üretilen hash kodu

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::GetHashCode(const T\&) method


Belirtilen nesne (exception) için bir hash kodu döndürür.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun hash kodu ürettiği nesnenin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | Hash kodu üretilecek nesneyi içeren Exception Wrapper |

### ReturnValue

Belirtilen nesne için üretilen hash kodu

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::GetHashCode(const T\&) method


Belirtilen nesne (akıllı gösterici ya da exception değil) için bir hash kodu döndürür.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun hash kodu ürettiği nesnenin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | Hash kodu üretilecek nesneye const referans |

### ReturnValue

Belirtilen nesne için üretilen hash kodu

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
