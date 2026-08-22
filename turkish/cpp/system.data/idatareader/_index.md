---
title: "System::Data::IDataReader sınıfı"
linktitle: "IDataReader"
second_title: "Aspose.PUB için C++"
description: "System::Data::IDataReader sınıfı. Ardışık verileri okumak için bir arayüz. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığına (stack) ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1200
url: /tr/cpp/system.data/idatareader/
---
## IDataReader class


Ardışık verileri okumak için bir arayüz. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığına (stack) ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class IDataReader : public System::Data::IDataRecord
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Read](./read/)() | RTTI bilgisi. |
## Ayrıca Bakınız

* Class [IDataRecord](../idatarecord/)
* Namespace [System::Data](../)
* Library [Aspose.PUB for C++](../../)
