---
title: "System::Globalization::DateTimeFormatInfo class"
linktitle: "DateTimeFormatInfo"
second_title: "Aspose.PUB für C++"
description: "System::Globalization::DateTimeFormatInfo class. Menge von Datums- und Zeitformatierungsparametern. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 600
url: /de/cpp/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo class


Satz von Datums- und Zeitformatierungsparametern. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone](./clone/)() override | Klonen von Formatinformationen. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | Standardkonstruktor, erstellt invariante Formatinformationen. |
| [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Liefert abgekürzte Tagesnamen. |
| [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Liefert abgekürzte Monatsnamen im Genitiv. |
| [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Liefert abgekürzte Monatsnamen. |
| [get_AMDesignator](./get_amdesignator/)() const | Liefert AM-Bezeichner. |
| [get_Calendar](./get_calendar/)() const | Liefert den dem Formatierer zugehörigen Kalender. |
| [get_CalendarWeekRule](./get_calendarweekrule/)() const | Liefert die dem Formatierer zugehörige Kalenderwochenregel. |
| static [get_CurrentInfo](./get_currentinfo/)() | Liefert den Datums- und Zeitformatierer des aktuellen Threads. |
| [get_DateSeparator](./get_dateseparator/)() const | Liefert das Datums-Trennzeichen. |
| [get_DayNames](./get_daynames/)() const | Liefert Tagesnamen. |
| [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Liefert den ersten Wochentag. |
| [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Liefert das vollständige Datums- und Zeitmuster. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Liefert den invarianten Datums- und Zeitformatierer. |
| [get_IsReadOnly](./get_isreadonly/)() const | Überprüft, ob der Formatierer schreibgeschützt ist. |
| [get_LongDatePattern](./get_longdatepattern/)() const | Liefert das lange Datumsformat. |
| [get_LongTimePattern](./get_longtimepattern/)() const | Liefert das lange Zeitformat. |
| [get_MonthDayPattern](./get_monthdaypattern/)() const | Liefert das Monat‑Tag‑Muster. |
| [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Liefert Monatsnamen im Genitiv. |
| [get_MonthNames](./get_monthnames/)() const | Liefert Monatsnamen. |
| [get_NativeCalendarName](./get_nativecalendarname/)() const | Liefert den nativen Kalendernamen, falls verfügbar. |
| [get_PMDesignator](./get_pmdesignator/)() const | Liefert PM-Bezeichner. |
| [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Liefert das RFC1123-Muster. |
| [get_ShortDatePattern](./get_shortdatepattern/)() const | Liefert das kurze Datumsformat. |
| [get_ShortestDayNames](./get_shortestdaynames/)() const | Liefert die kürzest möglichen Tagesnamen. |
| [get_ShortTimePattern](./get_shorttimepattern/)() const | Ruft das Kurzzeitformat ab. |
| [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Ruft das sortierbare Datums- und Zeitformat ab. |
| [get_TimeSeparator](./get_timeseparator/)() const | Ruft das Zeittrennzeichen ab. |
| [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Ruft das universell sortierbare Datums- und Zeitformat ab. |
| [get_YearMonthPattern](./get_yearmonthpattern/)() const | Ruft das Jahr‑und‑Monat‑Format ab. |
| [GetAbbreviatedDayName](./getabbreviateddayname/)(DayOfWeek) const | Ruft den abgekürzten Wochentagsnamen ab. |
| [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Ruft den abgekürzten Ära-Namen ab. |
| [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Ruft den abgekürzten Monatsnamen ab. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Ruft alle Muster ab, in denen Datums‑ und Zeitwerte formatiert werden können. |
| [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Ruft alle Muster ab, in denen Datums‑ und Zeitwerte mit einer angegebenen Formatzeichenfolge formatiert werden können. |
| [GetDayName](./getdayname/)(DayOfWeek) const | Ruft den Wochentagsnamen ab. |
| [GetEra](./getera/)(const String\&) const | Ruft die Ära anhand des Namens ab. |
| [GetEraName](./geteraname/)(int) const | Ruft den Ära-Namen ab. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Ermittelt den Formatierer eines bestimmten Typs. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Ermittelt den mit dem Formatprovider verknüpften Formatierer. |
| [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Ruft den Schaltjahr‑Monatsnamen ab. |
| [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Ruft den Genitiv‑Monatsnamen ab. |
| [GetMonthName](./getmonthname/)(int) const | Ruft den Monatsnamen ab. |
| [GetShortestDayName](./getshortestdayname/)(DayOfWeek) const | Ruft den kürzesten Namen für den angegebenen Wochentag ab. |
| [operator=](./operator=/)(const DateTimeFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(const DateTimeFormatInfoPtr\&) | Ermittelt die schreibgeschützte Version des Formatierers. |
| [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const ArrayPtr\<String\>\&) | Legt die abgekürzten Tagesnamen fest. |
| [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const ArrayPtr\<String\>\&) | Legt die abgekürzten Monatsnamen im Genitiv fest. |
| [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const ArrayPtr\<String\>\&) | Legt die abgekürzten Monatsnamen fest. |
| [set_AMDesignator](./set_amdesignator/)(const String\&) | Legt das AM‑Bezeichner fest. |
| [set_Calendar](./set_calendar/)(const SharedPtr\<Calendar\>\&) | Legt den dem Formatierer zugeordneten Kalender fest. |
| [set_CalendarWeekRule](./set_calendarweekrule/)(CalendarWeekRule) | Legt die dem Formatierer zugeordnete Kalenderwochenregel fest. |
| [set_DateSeparator](./set_dateseparator/)(const String\&) | Legt das Datums­trennzeichen fest. |
| [set_DayNames](./set_daynames/)(const ArrayPtr\<String\>\&) | Legt die Tagesnamen fest. |
| [set_FirstDayOfWeek](./set_firstdayofweek/)(DayOfWeek) | Legt den ersten Tag der Woche fest. |
| [set_FullDateTimePattern](./set_fulldatetimepattern/)(const String\&) | Legt das vollständige Datum‑ und Zeitformat fest. |
| [set_LongDatePattern](./set_longdatepattern/)(const String\&) | Legt das lange Datumsformat fest. |
| [set_LongTimePattern](./set_longtimepattern/)(const String\&) | Legt das lange Zeitformat fest. |
| [set_MonthDayPattern](./set_monthdaypattern/)(const String\&) | Legt das Monats‑Tag‑Format fest. |
| [set_MonthGenitiveNames](./set_monthgenitivenames/)(const ArrayPtr\<String\>\&) | Legt die Monatsnamen im Genitiv fest. |
| [set_MonthNames](./set_monthnames/)(const ArrayPtr\<String\>\&) | Legt die Monatsnamen fest. |
| [set_PMDesignator](./set_pmdesignator/)(const String\&) | Legt das PM‑Kennzeichen fest. |
| [set_ShortDatePattern](./set_shortdatepattern/)(const String\&) | Legt das kurze Datumsformat fest. |
| [set_ShortestDayNames](./set_shortestdaynames/)(const ArrayPtr\<String\>\&) | Legt die kürzesten Tagesnamen fest, die möglich sind. |
| [set_ShortTimePattern](./set_shorttimepattern/)(const String\&) | Legt das kurze Zeitformat fest. |
| [set_TimeSeparator](./set_timeseparator/)(const String\&) | Legt das Zeittrennzeichen fest. |
| [set_YearMonthPattern](./set_yearmonthpattern/)(const String\&) | Legt das Jahres‑ und Monatsformat fest. |
| [SetAllDateTimePatterns](./setalldatetimepatterns/)(const ArrayPtr\<String\>\&, char16_t) | Legt Muster für das angegebene Format fest. |
## Siehe auch

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
