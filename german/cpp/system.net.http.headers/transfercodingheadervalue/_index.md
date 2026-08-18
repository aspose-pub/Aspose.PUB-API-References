---
title: "System::Net::Http::Headers::TransferCodingHeaderValue Klasse"
linktitle: "TransferCodingHeaderValue"
second_title: "Aspose.PUB für C++"
description: "System::Net::Http::Headers::TransferCodingHeaderValue Klasse. Stellt einen Wert des ''Accept-Encoding''-Headers dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2400
url: /de/cpp/system.net.http.headers/transfercodingheadervalue/
---
## TransferCodingHeaderValue class


Stellt einen Wert des 'Accept-Encoding'-Headers dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class TransferCodingHeaderValue : public virtual System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Vergleicht Objekte anhand der C#-Semantik von [Object.Equals](../../system/object/equals/). |
| [get_Parameters](./get_parameters/)() | Gibt die Parameter zurück. |
| [get_Value](./get_value/)() | RTTI-Informationen. |
| [GetHashCode](./gethashcode/)() const override | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| static [GetTransferCodingLength](./gettransfercodinglength/)(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) | Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der [TransferCodingHeaderValue](./)-Klasse. |
| static [Parse](./parse/)(String) | Konvertiert einen übergebenen String in eine Instanz der [TransferCodingHeaderValue](./)-Klasse. |
| [ToString](./tostring/)() const override | Analog zur C#‑Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| [TransferCodingHeaderValue](./transfercodingheadervalue/)() | Konstruiert eine neue Instanz. |
| [TransferCodingHeaderValue](./transfercodingheadervalue/)(String) | Konstruiert eine neue Instanz. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<TransferCodingHeaderValue\>\&) | Versucht, einen übergebenen String in eine Instanz der [TransferCodingHeaderValue](./)-Klasse zu konvertieren. |
## Siehe auch

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
