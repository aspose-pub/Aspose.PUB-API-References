---
title: "System::Globalization::JulianCalendar class"
linktitle: "JulianCalendar"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::JulianCalendar sınıfı. Julian takvim. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığına (stack) veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'de fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1600
url: /tr/cpp/system.globalization/juliancalendar/
---
## JulianCalendar class


Julian takvim. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığına (stack) veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class JulianCalendar : public System::Globalization::Calendar
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() override | RTTI bilgisi. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Algoritma türünü alır. |
| [get_Eras](./get_eras/)() const override | Takvimde mevcut olan dönemlerin listesini alır. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Takvim tarafından desteklenen maksimum zaman noktası. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Takvim tarafından desteklenen minimum zaman noktası. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Belirli ay içindeki gün sayısını alır. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Belirli ay içindeki gün sayısını alır. |
| [GetDaysInYear](./getdaysinyear/)(int, int) const override | Belirli yıl içindeki gün sayısını alır. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Belirli yıl içindeki gün sayısını alır. |
| [GetEra](./getera/)(DateTime) const override | Belirtilen zaman noktası için dönemi alır. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Belirtilen yıl için artık ayı alır. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Belirtilen yıl için artık ayı alır. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Belirtilen yıldaki ay sayısını alır. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI bilgisi. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Günün artık olup olmadığını kontrol eder. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Günün artık olup olmadığını kontrol eder. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ayın artık olup olmadığını kontrol eder. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Ayın artık olup olmadığını kontrol eder. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Yılın artık olup olmadığını kontrol eder. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Yılın artık olup olmadığını kontrol eder. |
| [JulianCalendar](./juliancalendar/)() | Yapıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [JulianEra](./julianera/) | Mevcut julian dönemi. |
## Ayrıca Bakınız

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
