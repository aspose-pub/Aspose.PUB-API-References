---
title: "System::Globalization::DateTimeFormatInfo sınıfı"
linktitle: "DateTimeFormatInfo"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::DateTimeFormatInfo sınıfı. Tarih ve saat biçimlendirme parametrelerinin kümesi. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 600
url: /tr/cpp/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo class


Date ve saat biçimlendirme parametrelerinin kümesi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() override | Biçim bilgilerini kopyalar. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | Varsayılan yapıcı, değişmez biçim bilgisi oluşturur. |
| [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Kısaltılmış gün adlarını alır. |
| [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | İyelik hâlindeki kısaltılmış ay adlarını alır. |
| [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Kısaltılmış ay adlarını alır. |
| [get_AMDesignator](./get_amdesignator/)() const | ÖÖ göstergesini alır. |
| [get_Calendar](./get_calendar/)() const | Biçimlendiriciyle ilişkili takvimi alır. |
| [get_CalendarWeekRule](./get_calendarweekrule/)() const | Biçimlendiriciyle ilişkili takvim hafta kuralını alır. |
| static [get_CurrentInfo](./get_currentinfo/)() | Geçerli iş parçacığının tarih ve saat biçimlendiricisini alır. |
| [get_DateSeparator](./get_dateseparator/)() const | Tarih ayıracını alır. |
| [get_DayNames](./get_daynames/)() const | Gün adlarını alır. |
| [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Haftanın ilk gününü alır. |
| [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Tam tarih ve saat desenini alır. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Değişmez tarih ve saat biçimlendiricisini alır. |
| [get_IsReadOnly](./get_isreadonly/)() const | Biçimlendiricinin yalnızca okunur olup olmadığını denetler. |
| [get_LongDatePattern](./get_longdatepattern/)() const | Uzun tarih desenini alır. |
| [get_LongTimePattern](./get_longtimepattern/)() const | Uzun saat desenini alır. |
| [get_MonthDayPattern](./get_monthdaypattern/)() const | Ay gün desenini alır. |
| [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | İyelik hâlindeki ay adlarını alır. |
| [get_MonthNames](./get_monthnames/)() const | Ay adlarını alır. |
| [get_NativeCalendarName](./get_nativecalendarname/)() const | Mevcutsa yerel takvim adını alır. |
| [get_PMDesignator](./get_pmdesignator/)() const | ÖS göstergesini alır. |
| [get_RFC1123Pattern](./get_rfc1123pattern/)() const | RFC1123 desenini alır. |
| [get_ShortDatePattern](./get_shortdatepattern/)() const | Kısa tarih desenini alır. |
| [get_ShortestDayNames](./get_shortestdaynames/)() const | Mümkün olan en kısa gün adlarını alır. |
| [get_ShortTimePattern](./get_shorttimepattern/)() const | Kısa zaman desenini alır. |
| [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Sıralanabilir tarih ve zaman desenini alır. |
| [get_TimeSeparator](./get_timeseparator/)() const | Zaman ayıracını alır. |
| [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Evrensel sıralanabilir tarih ve zaman desenini alır. |
| [get_YearMonthPattern](./get_yearmonthpattern/)() const | Yıl ve ay desenini alır. |
| [GetAbbreviatedDayName](./getabbreviateddayname/)(DayOfWeek) const | Kısaltılmış hafta günü adını alır. |
| [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Kısaltılmış dönem adını alır. |
| [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Kısaltılmış ay adını alır. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Tarih ve zaman değerlerinin biçimlendirilebileceği tüm desenleri alır. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Belirtilen biçim dizesi kullanılarak tarih ve zaman değerlerinin biçimlendirilebileceği tüm desenleri alır. |
| [GetDayName](./getdayname/)(DayOfWeek) const | Hafta günü adını alır. |
| [GetEra](./getera/)(const String\&) const | Dönemi adına göre alır. |
| [GetEraName](./geteraname/)(int) const | Dönem adını alır. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Belirli tipte biçimleyiciyi alır. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Biçim sağlayıcıyla ilişkili biçimleyiciyi alır. |
| [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Artık yıl ayı adını alır. |
| [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | İyelik ay adını alır. |
| [GetMonthName](./getmonthname/)(int) const | Ay adını alır. |
| [GetShortestDayName](./getshortestdayname/)(DayOfWeek) const | Belirtilen hafta günü için en kısa adı alır. |
| [operator=](./operator=/)(const DateTimeFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(const DateTimeFormatInfoPtr\&) | Biçimleyicinin yalnızca okunabilir sürümünü alır. |
| [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const ArrayPtr\<String\>\&) | Kısaltılmış gün adlarını ayarlar. |
| [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const ArrayPtr\<String\>\&) | İyelik biçimde kısaltılmış ay adlarını ayarlar. |
| [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const ArrayPtr\<String\>\&) | Kısaltılmış ay adlarını ayarlar. |
| [set_AMDesignator](./set_amdesignator/)(const String\&) | ÖÖ işaretleyicisini ayarlar. |
| [set_Calendar](./set_calendar/)(const SharedPtr\<Calendar\>\&) | Biçimlendiriciyle ilişkili takvimi ayarlar. |
| [set_CalendarWeekRule](./set_calendarweekrule/)(CalendarWeekRule) | Biçimlendiriciyle ilişkili takvim hafta kuralını ayarlar. |
| [set_DateSeparator](./set_dateseparator/)(const String\&) | Tarih ayırıcıyı ayarlar. |
| [set_DayNames](./set_daynames/)(const ArrayPtr\<String\>\&) | Gün adlarını ayarlar. |
| [set_FirstDayOfWeek](./set_firstdayofweek/)(DayOfWeek) | Haftanın ilk gününü ayarlar. |
| [set_FullDateTimePattern](./set_fulldatetimepattern/)(const String\&) | Tam tarih ve saat desenini ayarlar. |
| [set_LongDatePattern](./set_longdatepattern/)(const String\&) | Uzun tarih desenini ayarlar. |
| [set_LongTimePattern](./set_longtimepattern/)(const String\&) | Uzun saat desenini ayarlar. |
| [set_MonthDayPattern](./set_monthdaypattern/)(const String\&) | Ay günü desenini ayarlar. |
| [set_MonthGenitiveNames](./set_monthgenitivenames/)(const ArrayPtr\<String\>\&) | Ay adlarını tamlayan hâlde ayarlar. |
| [set_MonthNames](./set_monthnames/)(const ArrayPtr\<String\>\&) | Ay adlarını ayarlar. |
| [set_PMDesignator](./set_pmdesignator/)(const String\&) | PM belirtecini ayarlar. |
| [set_ShortDatePattern](./set_shortdatepattern/)(const String\&) | Kısa tarih desenini ayarlar. |
| [set_ShortestDayNames](./set_shortestdaynames/)(const ArrayPtr\<String\>\&) | Mümkün olan en kısa gün adlarını ayarlar. |
| [set_ShortTimePattern](./set_shorttimepattern/)(const String\&) | Kısa saat desenini ayarlar. |
| [set_TimeSeparator](./set_timeseparator/)(const String\&) | Saat ayırıcıyı ayarlar. |
| [set_YearMonthPattern](./set_yearmonthpattern/)(const String\&) | Yıl ve ay desenini ayarlar. |
| [SetAllDateTimePatterns](./setalldatetimepatterns/)(const ArrayPtr\<String\>\&, char16_t) | Belirtilen format için desenleri ayarlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
