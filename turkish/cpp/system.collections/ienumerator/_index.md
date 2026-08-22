---
title: "System::Collections::IEnumerator class"
linktitle: "IEnumerator"
second_title: "Aspose.PUB için C++"
description: "System::Collections::IEnumerator sınıfı. Bazı öğeler üzerinde yineleme yapmak için kullanılabilecek bir enumerator arayüzü. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 600
url: /tr/cpp/system.collections/ienumerator/
---
## IEnumerator class


Bazı öğeler üzerinde yineleme yapmak için kullanılabilecek bir enumerator arayüzü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class IEnumerator : public virtual System::IDisposable,
                    public virtual System::Object
```


| Parametre | Açıklama |
| --- | --- |
| T | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Current](./current/)() const | Geçerli öğeyi alır. |
| virtual [get_Current](./get_current/)() const | Geçerli öğeyi alır. |
| virtual [MoveNext](./movenext/)() | Enumerator'ı bir sonraki öğeye taşır. Daha önce bir öğe referans alınmamışsa, referansı mevcut ilk öğeye ayarlar. Eğer konteyner sonuna gelinmişse, hiçbir şey yapmaz. |
| virtual [Reset](./reset/)() | Enumerator'ı ilk öğeden önceki konuma sıfırlar. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ValueType](./valuetype/) | RTTI bilgisi. |

## Ayrıca Bakınız

* Class [IDisposable](../../system/idisposable/)
* Class [Object](../../system/object/)
* Namespace [System::Collections](../)
* Library [Aspose.PUB for C++](../../)
