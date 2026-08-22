---
title: "System::Collections::Generic::LinkedListNode sınıfı"
linktitle: "LinkedListNode"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::LinkedListNode sınıfı. Bağlı listedeki düğüm. Bağlı listede sarılmış std::list yineleyicisi üzerine bir sarmalayıcı uygular. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığıt üzerinde ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 3200
url: /tr/cpp/system.collections.generic/linkedlistnode/
---
## LinkedListNode class


Bağlı listedeki düğüm. Bağlı listede sarılmış std::list yineleyicisi üzerine bir sarmalayıcı uygular. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığıt üzerinde ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T>class LinkedListNode : public System::Object
```


| Parametre | Açıklama |
| --- | --- |
| T | Depolanan değer tipi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_List](./get_list/)() const | İçeren listeyi alır. |
| [get_Next](./get_next/)() const | Sonraki düğümü alır. |
| [get_Previous](./get_previous/)() const | Önceki düğümü alır. |
| [get_Value](./get_value/)() const | Depolanan değeri alır. |
| [LinkedListNode](./linkedlistnode/)(const T\&) | Yapıcı. |
| [set_Value](./set_value/)(const T\&) | Depolanan değeri ayarlar. |

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
