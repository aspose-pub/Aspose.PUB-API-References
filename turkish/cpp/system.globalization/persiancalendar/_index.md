---
title: "System::Globalization::PersianCalendar class"
linktitle: "PersianCalendar"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::PersianCalendar sınıfı. Pers takvimi. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2000
url: /tr/cpp/system.globalization/persiancalendar/
---
## PersianCalendar class


Pers takvimi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class PersianCalendar : public System::Globalization::Calendar
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() override | RTTI bilgisi. |
| [get_AlgorithmType](./get_algorithmtype/)() const override | Algoritma türünü alır. |
| [get_Eras](./get_eras/)() const override | Takvimde mevcut olan dönemlerin listesini alır. |
| [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Takvim tarafından desteklenen maksimum zaman noktası. |
| [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Takvim tarafından desteklenen minimum zaman noktası. |
| [GetDayOfWeek](./getdayofweek/)(DateTime) const override | Belirtilen zaman noktası için haftanın gününü alır. |
| [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Belirli ay içindeki gün sayısını alır. |
| virtual [GetDaysInMonth](./getdaysinmonth/)(int, int) const | RTTI bilgisi. |
| [GetDaysInYear](./getdaysinyear/)(int, int) const override | Belirli yıl içindeki gün sayısını alır. |
| virtual [GetDaysInYear](./getdaysinyear/)(int) const | Belirli yıl içindeki gün sayısını alır. |
| [GetLeapMonth](./getleapmonth/)(int, int) const override | Belirtilen yıl için artık ayı alır. |
| virtual [GetLeapMonth](./getleapmonth/)(int) const | Belirtilen yıl için artık ayı alır. |
| [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Belirtilen yıldaki ay sayısını alır. |
| virtual [GetMonthsInYear](./getmonthsinyear/)(int) const | Belirtilen yıldaki ay sayısını alır. |
| [IsLeapDay](./isleapday/)(int, int, int, int) const override | Günün artık olup olmadığını kontrol eder. |
| virtual [IsLeapDay](./isleapday/)(int, int, int) const | Günün artık olup olmadığını kontrol eder. |
| [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ayın artık olup olmadığını kontrol eder. |
| virtual [IsLeapMonth](./isleapmonth/)(int, int) const | Ayın artık olup olmadığını kontrol eder. |
| [IsLeapYear](./isleapyear/)(int, int) const override | Yılın artık olup olmadığını kontrol eder. |
| virtual [IsLeapYear](./isleapyear/)(int) const | Yılın artık olup olmadığını kontrol eder. |
| [PersianCalendar](./persiancalendar/)() | Yapıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [PersianEra](./persianera/) | Mevcut Pers dönemi. |
## Ayrıca Bakınız

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
