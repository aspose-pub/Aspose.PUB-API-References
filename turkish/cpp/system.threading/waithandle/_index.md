---
title: "System::Threading::WaitHandle class"
linktitle: "WaitHandle"
second_title: "Aspose.PUB için C++"
description: "System::Threading::WaitHandle sınıfı. Bekleme ilkel temel sınıfı. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1300
url: /tr/cpp/system.threading/waithandle/
---
## WaitHandle class


Bekleme ilkel temel sınıfı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class WaitHandle : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Close](./close/)() | İşaretçiyle ilişkili tüm kaynakları serbest bırakır. |
| [get_Handle](./get_handle/)() | İşaretçiyi alır. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | RTTI bilgisi. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Tüm işaretçilerin tetiklenmesini bekler. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Tüm işaretçilerin tetiklenmesini bekler. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | İşaretçilerden herhangi birinin tetiklenmesini bekler. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | İşaretçilerden herhangi birinin tetiklenmesini bekler. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | İşaretçilerden herhangi birinin tetiklenmesini bekler. |
| virtual [WaitOne](./waitone/)() | İşaretçinin sınırsız bir süre boyunca tetiklenmesini bekler. |
| virtual [WaitOne](./waitone/)(int) | İşaretçinin tetiklenmesini bekler. |
| virtual [WaitOne](./waitone/)(TimeSpan) | İşaretçinin tetiklenmesini bekler. |
| virtual [WaitOne](./waitone/)(int, bool) | İşaretçinin tetiklenmesini bekler. |
| virtual [~WaitHandle](./~waithandle/)() | Yıkıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [WaitTimeout](./waittimeout/) | Fonksiyon tarafından döndürülecek özel değer, aksi takdirde zaman aşımı geçerse ve hiçbir şey sinyal göndermezse dizi içindeki sinyal verilen nesnenin indeksini döndürür. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
