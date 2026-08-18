---
title: "System::Drawing::Imaging::EncoderParameter Klasse"
linktitle: "EncoderParameter"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Imaging::EncoderParameter Klasse. Dient als Container, der verwendet wird, um Werte an einen Bild‑Encoder zu übergeben. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 600
url: /de/cpp/system.drawing.imaging/encoderparameter/
---
## EncoderParameter class


Dient als Container, der verwendet wird, um Werte an einen Bild‑Encoder zu übergeben. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)‑Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class EncoderParameter : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [EncoderParameter](./encoderparameter/)() | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, uint8_t, bool) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int16_t) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die einen Bruch darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t, int64_t) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die einen Bereich von Ganzzahlwerten darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t, int32_t, int32_t) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die einen Bereich von Brüchen darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const String\&) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<uint8_t\>\&, bool) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die ein Array von Werten darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int16_t\>\&) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die ein Array von Werten darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die ein Array von Werten darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die ein Array von Brüchen darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&, const ArrayPtr\<int64_t\>\&) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die ein Array von Bereichen von Ganzzahlen darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die ein Array von Bereichen von Brüchen darstellt. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int, EncoderParameterValueType, void *) | Erstellt eine neue Instanz der [EncoderParameter](./)‑Klasse, die die angegebene Anzahl von Werten des angegebenen Typs darstellt, die aus dem angegebenen Puffer gelesen werden. |
| [get_Encoder](./get_encoder/)() const | Gibt das [Encoder](../encoder/)‑Objekt zurück, das mit dem aktuellen [EncoderParameter](./)‑Objekt verknüpft ist. |
| [get_NumberOfValues](./get_numberofvalues/)() const | Gibt die Anzahl der vom aktuellen Objekt dargestellten Werte zurück. |
| [get_Type](./get_type/)() const | Gibt den Typ der vom aktuellen Objekt dargestellten Werte zurück. |
| [set_Encoder](./set_encoder/)(const EncoderPtr\&) | Verknüpft das angegebene [Encoder](../encoder/)‑Objekt mit dem aktuellen [EncoderParameter](./)‑Objekt. |
| [~EncoderParameter](./~encoderparameter/)() | Destruktor. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PUB for C++](../../)
