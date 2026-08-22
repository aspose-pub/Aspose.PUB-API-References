---
title: "System::TimeZone sınıfı"
linktitle: "TimeZone"
second_title: "Aspose.PUB için C++"
description: "System::TimeZone sınıfı. Bir saat dilimini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 6000
url: /tr/cpp/system/timezone/
---
## TimeZone class


Bir saat dilimini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class TimeZone : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [get_CurrentTimeZone](./get_currenttimezone/)() | Geçerli saat dilimini temsil eden yeni bir [TimeZone](./) sınıf örneği döndürür. |
| virtual [get_DaylightName](./get_daylightname/)() const | Geçerli nesne tarafından temsil edilen saat diliminin yaz saati uygulaması için bir ad döndürür. |
| virtual [get_StandardName](./get_standardname/)() const | Geçerli nesne tarafından temsil edilen saat diliminin standart zamanı için bir ad döndürür. |
| virtual [GetDaylightChanges](./getdaylightchanges/)(int32_t) | Belirli bir yıl için yaz saati dönemini döndürür. |
| virtual [GetUtcOffset](./getutcoffset/)(DateTime) | Belirtilen yerel zaman için UTC ofsetini döndürür. |
| virtual [IsDaylightSavingTime](./isdaylightsavingtime/)(DateTime) | Belirtilen [DateTime](../datetime/) nesnesi tarafından temsil edilen tarih ve saat değerinin, geçerli [TimeZone](./) nesnesi tarafından temsil edilen saat diliminin yaz saati aralığına düşüp düşmediğini belirler. |
## Ayrıca Bakınız

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
