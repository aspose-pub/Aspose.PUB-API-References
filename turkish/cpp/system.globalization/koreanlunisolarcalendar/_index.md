---
title: "System::Globalization::KoreanLunisolarCalendar sınıfı"
linktitle: "KoreanLunisolarCalendar"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::KoreanLunisolarCalendar sınıfı. Kore lunisolar takvimi. Henüz uygulanmadı. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1800
url: /tr/cpp/system.globalization/koreanlunisolarcalendar/
---
## KoreanLunisolarCalendar class


Kore lunisolar takvimi. Henüz uygulanmadı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class KoreanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() override | RTTI bilgisi. |
| [get_Eras](./get_eras/)() const override | Takvimde mevcut olan dönemlerin listesini alır. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Takvim tarafından desteklenen maksimum zaman noktası. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Takvim tarafından desteklenen minimum zaman noktası. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Belirtilen yıl için artık ayı alır. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | RTTI bilgisi. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Günün artık olup olmadığını kontrol eder. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Günün artık olup olmadığını kontrol eder. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Yılın artık olup olmadığını kontrol eder. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Yılın artık olup olmadığını kontrol eder. |
| [KoreanLunisolarCalendar](./koreanlunisolarcalendar/)() | Yapıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [GregorianEra](./gregorianera/) | Mevcut Gregoryen dönemi. |
## Ayrıca Bakınız

* Class [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
