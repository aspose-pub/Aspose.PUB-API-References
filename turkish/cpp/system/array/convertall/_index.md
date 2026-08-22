---
title: "System::Array::ConvertAll yöntemi"
linktitle: "ConvertAll"
second_title: "Aspose.PUB için C++"
description: "System::Array::ConvertAll yöntemi. Belirtilen dizi elemanlarını OutputType türüne dönüştüren belirtilen dönüştürücü temsilcisi kullanılarak yeni bir Array nesnesi oluşturur ve doldurur C++'ta."
type: docs
weight: 4800
url: /tr/cpp/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method


Belirtilen dizi elemanlarını **OutputType** türüne dönüştüren belirtilen dönüştürücü temsilcisi kullanılarak yeni bir [Array](../) nesnesi oluşturur ve doldurur.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```


| Parametre | Açıklama |
| --- | --- |
| InputType | Girdi dizisinin elemanlarının türü |
| OutputType | Sonuç dizisinin elemanlarının türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input_array | ArrayPtr\<InputType\> | Bir [Array](../) nesnesi |
| dönüştürücü | Converter\<InputType, OutputType\> | **OutputType** türündeki eşdeğer değerlere dönüştürmek için girdi dizisinin her bir elemanını dönüştüren bir Converter nesnesi |

### ReturnValue

Yeni bir dizi, **OutputType** türündeki değerlerin **input_array** değerlerine eşdeğer olduğu

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method


Belirtilen dizi elemanlarını **OutputType** türüne dönüştüren belirtilen dönüştürücü fonksiyon nesnesi kullanılarak yeni bir [Array](../) nesnesi oluşturur ve doldurur.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```


| Parametre | Açıklama |
| --- | --- |
| InputType | Girdi dizisinin elemanlarının türü |
| OutputType | Sonuç dizisinin elemanlarının türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input_array | ArrayPtr\<InputType\> | Bir [Array](../) nesnesi |
| dönüştürücü | std::function\<OutputType(InputType)> | Girdi dizisinin her bir elemanını **OutputType** türündeki eşdeğer değerlere dönüştürmek için kullanılan bir fonksiyon nesnesi |

### ReturnValue

Yeni bir dizi, **OutputType** türündeki değerlerin **input_array** değerlerine eşdeğer olduğu

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
