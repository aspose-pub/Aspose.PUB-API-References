---
title: "System::Globalization::NumberFormatInfo Klasse"
linktitle: "NumberFormatInfo"
second_title: "Aspose.PUB für C++"
description: "System::Globalization::NumberFormatInfo Klasse. Enthält Informationen darüber, wie Zahlen formatiert werden. Setter‑Operationen sind nur bei nicht schreibgeschützten Objekten aktiviert. Objekte dieser Klasse sollten ausschließlich mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1900
url: /de/cpp/system.globalization/numberformatinfo/
---
## NumberFormatInfo class


Enthält Informationen darüber, wie Zahlen formatiert werden. Setter‑Operationen sind nur bei nicht schreibgeschützten Objekten aktiviert. Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone](./clone/)() override | Klonen von Formatinformationen. |
| [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Liefert die Anzahl der Dezimalstellen der Währung. |
| [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Liefert das Dezimaltrennzeichen der Währung. |
| [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Liefert das Tausendertrennzeichen der Währung. |
| [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Liefert die Anzahl der Dezimalstellen der Währung pro Gruppe. |
| [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Liefert das negative Währungsmuster. |
| [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Liefert das positive Währungsmuster. |
| [get_CurrencySymbol](./get_currencysymbol/)() const | Liefert das Währungssymbol. |
| static [get_CurrentInfo](./get_currentinfo/)() | Liefert die vom aktuellen Thread‑Kultur definierten Zahlenformatinformationen. |
| [get_DigitSubstitution](./get_digitsubstitution/)() const | Liefert einen Wert, der angibt, wie die Form einer Ziffer angezeigt wird. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Liefert die vom Invarianten‑Kultur definierten Zahlenformatinformationen. |
| [get_IsReadOnly](./get_isreadonly/)() const | Prüft, ob das Format schreibgeschützt ist. |
| [get_NaNSymbol](./get_nansymbol/)() const | Liefert das Not-a-Number‑Symbol. |
| [get_NativeDigits](./get_nativedigits/)() const | Liefert die Ziffernsymbole (0 bis 9). |
| [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Liefert das Symbol für negative Unendlichkeit. |
| [get_NegativeSign](./get_negativesign/)() const | Liefert das negative Vorzeichen. |
| [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Liefert die Anzahl der Dezimalstellen. |
| [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Liefert das Dezimaltrennzeichen. |
| [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Liefert das Tausendertrennzeichen. |
| [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Liefert die Anzahl der Ziffern pro Gruppe. |
| [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Liefert das negative Zahlenmuster. |
| [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Liefert die Anzahl der Dezimalstellen in Prozentwerten. |
| [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Ermittelt das Dezimaltrennzeichen in Prozentwerten. |
| [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Ermittelt das Gruppentrennzeichen in Prozentwerten. |
| [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Ermittelt die Anzahl der Ziffern pro Prozentwertgruppe. |
| [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Ermittelt das negative Prozentmuster. |
| [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Ermittelt das positive Prozentmuster. |
| [get_PercentSymbol](./get_percentsymbol/)() const | Ermittelt das Prozentzeichen. |
| [get_PerMilleSymbol](./get_permillesymbol/)() const | Ermittelt das Promillezeichen. |
| [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Ermittelt das Symbol für positive Unendlichkeit. |
| [get_PositiveSign](./get_positivesign/)() const | Ermittelt das positive Vorzeichen. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Ermittelt den Formatierer eines bestimmten Typs. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Ermittelt den mit dem Formatprovider verknüpften Formatierer. |
| [NumberFormatInfo](./numberformatinfo/)() | Standardkonstruktor (invariant [NumberFormatInfo](./)). |
| [operator=](./operator=/)(const NumberFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(NumberFormatInfoPtr) | Ermittelt die schreibgeschützte Version des Formatierers. |
| [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Legt die Anzahl der Dezimalstellen der Währung fest. |
| [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const String\&) | Legt das Dezimaltrennzeichen der Währung fest. |
| [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const String\&) | Legt das Gruppentrennzeichen der Währung fest. |
| [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const ArrayPtr\<int\>\&) | Legt die Anzahl der Dezimalstellen der Währung pro Gruppe fest. |
| [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Legt das negative Währungsformat fest. |
| [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Legt das positive Währungsformat fest. |
| [set_CurrencySymbol](./set_currencysymbol/)(const String\&) | Legt das Währungssymbol fest. |
| [set_DigitSubstitution](./set_digitsubstitution/)(DigitShapes) | Legt einen Wert fest, der bestimmt, wie die Form einer Ziffer angezeigt wird. |
| [set_NaNSymbol](./set_nansymbol/)(const String\&) | Legt das Symbol für 'Not-a-Number' fest. |
| [set_NativeDigits](./set_nativedigits/)(const ArrayPtr\<String\>\&) | Legt die Ziffernsymbole (0 bis 9) fest. |
| [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const String\&) | Legt das Symbol für negative Unendlichkeit fest. |
| [set_NegativeSign](./set_negativesign/)(const String\&) | Legt das negative Vorzeichen fest. |
| [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Legt die Anzahl der Dezimalstellen fest. |
| [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const String\&) | Legt das Dezimaltrennzeichen fest. |
| [set_NumberGroupSeparator](./set_numbergroupseparator/)(const String\&) | Legt das Tausendertrennzeichen fest. |
| [set_NumberGroupSizes](./set_numbergroupsizes/)(const ArrayPtr\<int\>\&) | Legt die Anzahl der Ziffern pro Gruppe fest. |
| [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Legt das negative Zahlenformat fest. |
| [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Legt die Anzahl der Dezimalstellen in Prozentwerten fest. |
| [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const String\&) | Legt das Dezimaltrennzeichen in Prozentwerten fest. |
| [set_PercentGroupSeparator](./set_percentgroupseparator/)(const String\&) | Legt das Gruppentrennzeichen in Prozentwerten fest. |
| [set_PercentGroupSizes](./set_percentgroupsizes/)(const ArrayPtr\<int\>\&) | Legt die Anzahl der Ziffern pro Prozentwertgruppe fest. |
| [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Legt das negative Prozentformat fest. |
| [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Legt das positive Prozentformat fest. |
| [set_PercentSymbol](./set_percentsymbol/)(const String\&) | Legt das Prozentzeichen fest. |
| [set_PerMilleSymbol](./set_permillesymbol/)(const String\&) | Legt das Promillezeichen fest. |
| [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const String\&) | Legt das Symbol für positive Unendlichkeit fest. |
| [set_PositiveSign](./set_positivesign/)(const String\&) | Legt das positive Vorzeichen fest. |
## Siehe auch

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
