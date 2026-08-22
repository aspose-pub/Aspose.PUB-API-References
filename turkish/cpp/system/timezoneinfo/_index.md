---
title: "System::TimeZoneInfo sınıfı"
linktitle: "TimeZoneInfo"
second_title: "Aspose.PUB için C++"
description: "System::TimeZoneInfo sınıfı. Belirli bir saat dilimini tanımlayan bir bilgiyi temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 6100
url: /tr/cpp/system/timezoneinfo/
---
## TimeZoneInfo class


Belirli bir saat dilimini tanımlayan bir bilgiyi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## Nested classes

* Class [AdjustmentRule](./adjustmentrule/)
* Class [TransitionTime](./transitiontime/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [ClearCachedData](./clearcacheddata/)() | Önbelleğe alınmış saat dilimi verilerini temizle. |
| static [ConvertTime](./converttime/)(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) | [Convert](../convert/) zamanı bir saat diliminden diğerine dönüştür. |
| static [ConvertTime](./converttime/)(const DateTimeOffset\&, const TimeZoneInfoPtr\&) | [Convert](../convert/) zamanı belirtilen bir saat dilimindeki zamana dönüştür. |
| static [ConvertTime](./converttime/)(DateTime, const TimeZoneInfoPtr\&) | [Convert](../convert/) zamanı belirtilen bir saat dilimindeki zamana dönüştür. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(DateTime, const String\&) | [Convert](../convert/) zamanı belirtilen bir saat dilimindeki zamana dönüştür. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const DateTimeOffset\&, const String\&) | [Convert](../convert/) zamanı belirtilen bir saat dilimindeki zamana dönüştür. |
| static [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(DateTime, const String\&, const String\&) | [Convert](../convert/) zamanı belirtilen bir saat dilimindeki zamana dönüştür. |
| static [ConvertTimeFromUtc](./converttimefromutc/)(DateTime, const TimeZoneInfoPtr\&) | UTC zamanını belirtilen bir saat dilimindeki zamana dönüştürür. |
| static [ConvertTimeToUtc](./converttimetoutc/)(DateTime, const TimeZoneInfoPtr\&) | Zamanı UTC zamanına dönüştürür. |
| static [ConvertTimeToUtc](./converttimetoutc/)(DateTime) | Zamanı UTC zamanına dönüştürür. |
| static [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)(DateTime) | Zamanı UTC zamanına dönüştürür. DAHİLİ KULLANIM İÇİN. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) | Özel bir saat dilimi oluşturur. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) | Özel bir saat dilimi oluşturur. |
| static [CreateCustomTimeZone](./createcustomtimezone/)(const String\&, TimeSpan, const String\&, const String\&) | Özel bir saat dilimi oluşturur. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(TimeZoneInfoPtr) override | Geçerli ve belirtilen nesnelerin eşit olup olmadığını belirler. |
| static [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const String\&) | Belirtilen tanımlayıcıya sahip saat dilimini alır. |
| [get_BaseUtcOffset](./get_baseutcoffset/)() const | Geçerli saat diliminin standart zamanı ile UTC zamanı arasındaki zaman aralığını temsil eden bir [TimeSpan](../timespan/) örneği döndürür. |
| [get_DaylightName](./get_daylightname/)() const | Geçerli saat diliminin yaz saati uygulaması için adını alır. |
| [get_DisplayName](./get_displayname/)() const | Geçerli saat diliminin adını alır. |
| [get_Id](./get_id/)() const | Geçerli nesne tarafından temsil edilen saat diliminin tanımlayıcısını döndürür. |
| static [get_Local](./get_local/)() | Yerel bir saat dilimini temsil eden bir [TimeZoneInfo](./) örneği döndürür. |
| [get_StandardName](./get_standardname/)() const | Geçerli saat diliminin standart zamanı için adı alır. |
| [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | Saat diliminin yaz saati kurallarına sahip olup olmadığını gösteren bayrağı alır. |
| static [get_Utc](./get_utc/)() | UTC saat dilimini temsil eden bir [TimeZoneInfo](./) örneği döndürür. |
| [GetAdjustmentRules](./getadjustmentrules/)() const | Geçerli [TimeZoneInfo](./) nesnesine uygulanan ayarlama kurallarını temsil eden [AdjustmentRule](./adjustmentrule/) nesnelerinden oluşan bir dizi döndürür. |
| [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(DateTime) const | Belirtilen bir tarih ve zamanın eşlenebileceği UTC tarih ve zamanlarını alır. |
| [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const DateTimeOffset\&) const | Belirtilen bir tarih ve zamanın eşlenebileceği UTC tarih ve zamanlarını alır. |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../object/gethashcode/) yönteminin bir benzeridir. Özel nesnelerin hashlenmesini sağlar. |
| static [GetSystemTimeZones](./getsystemtimezones/)() | Yerel sistemde mevcut olan tüm saat dilimlerinin sıralı koleksiyonunu alır. |
| [GetUtcOffset](./getutcoffset/)(DateTime) const | Belirtilen tarih ve saat için bu saat dilimindeki zaman ile UTC saat dilimi arasındaki farkı hesaplar. |
| [GetUtcOffset](./getutcoffset/)(const DateTimeOffset\&) const | Belirtilen tarih ve saat için bu saat dilimindeki zaman ile UTC saat dilimi arasındaki farkı hesaplar. |
| static [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)(DateTime, const TimeZoneInfoPtr\&) | Belirtilen bir saat dilimindeki UTC tarih‑zamanı için UTC ofsetini döndüren dahili yardımcı işlev. YALNIZCA DAHİLİ KULLANIM İÇİN. |
| static [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)(DateTime, const TimeZoneInfoPtr\&, bool\&, bool\&) | Belirtilen bir saat dilimindeki UTC tarih‑zamanı için UTC ofsetini döndüren dahili yardımcı işlev. YALNIZCA DAHİLİ KULLANIM İÇİN. |
| [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)(DateTime) const | Belirtilen tarih ve saat için bu saat dilimindeki zaman ile UTC saat dilimi arasındaki farkı hesaplar. YALNIZCA DAHİLİ KULLANIM İÇİN. |
| [HasSameRules](./hassamerules/)(const TimeZoneInfoPtr\&) const | Geçerli ve başka bir saat diliminin aynı ayarlama kurallarına sahip olup olmadığını denetler. |
| [IsAmbiguousTime](./isambiguoustime/)(DateTime) const | Belirtilen tarih ve saatin belirsiz olup olmadığını ve birden çok UTC zamanına eşlenebileceğini denetler. |
| [IsAmbiguousTime](./isambiguoustime/)(const DateTimeOffset\&) const | Belirtilen tarih ve saatin belirsiz olup olmadığını ve birden çok UTC zamanına eşlenebileceğini denetler. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)(DateTime) const | Belirtilen tarih ve saatin yaz saati uygulama aralığı içinde olup olmadığını denetler. |
| [IsDaylightSavingTime](./isdaylightsavingtime/)(const DateTimeOffset\&) const | Belirtilen tarih ve saatin yaz saati uygulama aralığı içinde olup olmadığını denetler. |
| [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)(DateTime) const | Belirtilen tarih ve saatin yaz saati uygulama aralığı içinde olup olmadığını denetler. |
| [IsInvalidTime](./isinvalidtime/)(DateTime) const | Belirtilen tarih ve saatin geçersiz olup olmadığını denetler. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../object/tostring/) metodunun bir benzeri. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static [TransitionTimeToDateTime](./transitiontimetodatetime/)(int32_t, const TransitionTime\&) | Bir yılı ve [TransitionTime](./transitiontime/) öğesini bir [DateTime](../datetime/) nesnesine dönüştüren yardımcı işlev. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | [AdjustmentRule](./adjustmentrule/) sınıfının bir örneğine ortak gösterici için bir takma ad. |
## Ayrıca Bakınız

* Class [IEquatable](../iequatable/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
