---
title: "System::Globalization::CultureInfo Klasse"
linktitle: "CultureInfo"
second_title: "Aspose.PUB für C++"
description: "System::Globalization::CultureInfo Klasse. Sammlung kultur­spezifischer Werte und Algorithmen. Setter‑Operationen sind nur bei nicht schreibgeschützten Objekten aktiviert. Objekte dieser Klasse sollten ausschließlich mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 500
url: /de/cpp/system.globalization/cultureinfo/
---
## CultureInfo class


Sammlung kultur­spezifischer Werte und Algorithmen. Setter‑Operationen sind nur bei nicht schreibgeschützten Objekten aktiviert. Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [ClearCachedData](./clearcacheddata/)() | Aktualisiert zwischengespeicherte Kulturinformationen. |
| [Clone](./clone/)() override | Klont Kulturinformationen. |
| static [CreateSpecificCulture](./createspecificculture/)(const String\&) | Erstellt eine Kultur anhand des Namens. |
| explicit [CultureInfo](./cultureinfo/)(int) | RTTI-Informationen. |
| [CultureInfo](./cultureinfo/)(int, bool) | Konstruktor. |
| explicit [CultureInfo](./cultureinfo/)(const String\&) | Konstruktor. |
| [CultureInfo](./cultureinfo/)(const String\&, bool) | Konstruktor. |
| [CultureInfo](./cultureinfo/)(std::nullptr_t) | Wirft immer ArgumentNullException. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Vergleicht Objekte. |
| virtual [get_Calendar](./get_calendar/)() const | Liefert den vom Kulturobjekt verwendeten Kalender. |
| virtual [get_CompareInfo](./get_compareinfo/)() const | Liefert einen String-Vergleicher, der den Kulturregeln entspricht. |
| [get_CultureTypes](./get_culturetypes/)() const | Liefert die bitweise Kombination von Kulturtypen, die die aktuelle Kultur beschreiben. |
| static [get_CurrentCulture](./get_currentculture/)() | Liefert die für den aktuellen Thread eingestellte Kultur. |
| static [get_CurrentUICulture](./get_currentuiculture/)() | Liefert die UI‑Kultur des aktuellen Threads. |
| virtual [get_DateTimeFormat](./get_datetimeformat/)() const | Liefert Datumsformatinformationen. |
| static [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Liefert die Standardkultur in der aktuellen Anwendungsdomäne. |
| static [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Liefert die Standard‑UI‑Kultur in der aktuellen Anwendungsdomäne. |
| virtual [get_DisplayName](./get_displayname/)() const | Liefert den Anzeigenamen der Kultur. |
| virtual [get_EnglishName](./get_englishname/)() const | Liefert den englischen Namen der Kultur zurück. |
| [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Liefert den RFC‑4646‑Namen für eine Sprache. |
| static [get_InstalledUICulture](./get_installeduiculture/)() | Liefert die mit dem Betriebssystem installierte Kultur. |
| static [get_InvariantCulture](./get_invariantculture/)() | Liefert die invariant Kultur. |
| virtual [get_IsNeutralCulture](./get_isneutralculture/)() const | Prüft, ob die Kultur neutral ist. |
| [get_IsReadOnly](./get_isreadonly/)() const | Prüft, ob das Kulturobjekt schreibgeschützt ist. |
| virtual [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Liefert die aktive Eingabe‑Locale‑Kennung. |
| virtual [get_LCID](./get_lcid/)() const | Liefert die Kultur‑Kennung. |
| virtual [get_Name](./get_name/)() const | Liefert den Namen der Kultur. |
| virtual [get_NativeName](./get_nativename/)() const | Liefert den nativen Namen der Kultur. |
| virtual [get_NumberFormat](./get_numberformat/)() const | Liefert Informationen zum Zahlenformat. |
| virtual [get_OptionalCalendars](./get_optionalcalendars/)() const | Liste der Kalender, die mit der Kultur verwendet werden können. |
| virtual [get_Parent](./get_parent/)() const | Liefert die übergeordnete Kultur. |
| virtual [get_TextInfo](./get_textinfo/)() const | Liefert die von der Kultur verwendeten Textparameter. |
| virtual [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Liefert den dreibuchstabigen ISO‑639‑2‑Sprachcode. |
| virtual [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Liefert den dreibuchstabigen Code für die Sprache, wie in der [Windows](../../system.windows/)‑API definiert. |
| virtual [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Liefert den zweibuchstabigen ISO‑Sprachnamen, der mit der Kultur verknüpft ist. |
| [get_UseUserOverride](./get_useuseroverride/)() const | Liefert ein Flag, das angibt, ob die [CultureInfo](./) benutzerdefinierte Kultureinstellungen verwendet. |
| [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Liefert eine alternative Kultur, die für Konsolenanwendungen geeignet ist. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&) | Liefert die Kultur anhand ihres Namens. Entspricht CreateSpecificCulture. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&, const String\&) | Liefert die Kultur anhand ihres Namens. |
| static [GetCultureInfo](./getcultureinfo/)(int32_t) | Liefert die Kultur anhand ihrer ID. |
| static [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const String\&) | Veraltet. Liefert ein schreibgeschütztes [CultureInfo](./)-Objekt anhand des angegebenen RFC‑4646‑Sprach-Tags. |
| static [GetCultures](./getcultures/)(CultureTypes) | Liefert Kulturen, die in die angegebenen Typen fallen. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Liefert das Formatobjekt für einen bestimmten Typ. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode des Objekts zurück. |
| [IsInherited](./isinherited/)() const | Liest das is-inherited-Flag. NUR ZUR INTERNEN VERWENDUNG. |
| [operator=](./operator=/)(const CultureInfo\&) |  |
| [operator==](./operator==/)(const CultureInfo\&) const | Vergleicht Kulturparameter. |
| static [ReadOnly](./readonly/)(const CultureInfoPtr\&) | Liefert eine schreibgeschützte Version der Kultur. |
| static [set_CurrentCulture](./set_currentculture/)(const CultureInfoPtr\&) | Setzt die Kultur für den aktuellen Thread. |
| static [set_CurrentUICulture](./set_currentuiculture/)(const CultureInfoPtr\&) | Setzt die UI-Kultur des aktuellen Threads. |
| virtual [set_DateTimeFormat](./set_datetimeformat/)(DateTimeFormatInfoPtr) | Setzt Datumsformatinformationen. |
| static [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const CultureInfoPtr\&) | Setzt die Standardkultur in der aktuellen Anwendungsdomäne. |
| static [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const CultureInfoPtr\&) | Setzt die Standard-UI-Kultur in der aktuellen Anwendungsdomäne. |
| virtual [set_NumberFormat](./set_numberformat/)(NumberFormatInfoPtr) | Liefert Informationen zum Zahlenformat. |
| [ToString](./tostring/)() const override | Konvertiert die Kultur in einen String. |
## Siehe auch

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
