---
title: "System::Nullable class"
linktitle: "Nullable"
second_title: "Aspose.PUB für C++"
description: "System::Nullable class. Vorwärtsdeklaration in C++."
type: docs
weight: 4600
url: /de/cpp/system/nullable/
---
## Nullable class


Vorwärtsdeklaration.

```cpp
template<typename T>class Nullable
```


| Parameter | Beschreibung |
| --- | --- |
| T | Der zugrunde liegende Werttyp, der von der [Nullable](./)-Klasse erweitert wird |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Equals](./equals/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem vom angegebenen [Nullable](./)-Objekt dargestellten Wert entspricht. |
| [get_HasValue](./get_hasvalue/)() const | Bestimmt, ob das aktuelle Objekt irgendeinen Wert darstellt. |
| [get_Value](./get_value/)() const | Gibt eine Kopie des vom aktuellen Objekt dargestellten Wertes zurück. |
| [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| [GetValueOrDefault](./getvalueordefault/)(T) | Gibt den vom aktuellen Objekt dargestellten Wert zurück oder den angegebenen Wert, wenn der vom aktuellen Objekt dargestellte Wert null ist. |
| [GetValueOrDefault](./getvalueordefault/)() |  |
| [IsNull](./isnull/)() const | Bestimmt, ob das aktuelle Objekt einen Nullwert darstellt. |
| [Nullable](./nullable/)() | Konstruiert eine Instanz, die einen Nullwert darstellt. |
| [Nullable](./nullable/)(std::nullptr_t) | Konstruiert eine Instanz, die null darstellt. |
| [Nullable](./nullable/)(const T1\&) | Konstruiert eine Instanz der Klasse [Nullable](./), die den angegebenen Wert darstellt, der (falls erforderlich) in den Wert des zugrunde liegenden Typs T konvertiert wird. |
| [Nullable](./nullable/)(const Nullable\<T1\>\&) | Konstruiert eine Instanz, die einen Wert darstellt, der vom angegebenen [Nullable](./)-Objekt repräsentiert wird. Das angegebene nullable‑Objekt kann einen Wert eines anderen Typs als den zugrunde liegenden Typ der konstruierten Instanz repräsentieren; in diesem Fall wird der dargestellte Wert in einen Wert des Typs T konvertiert. |
| [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<bool()>\&, bool) const | Hilfsfunktion, um zu prüfen, ob sowohl dieses als auch **other** nicht null sind und in diesem Fall ein Lambda aufzurufen. Wird in Implementierungen verwendet. |
| [operator const T &](./operatorconstt&/)() const | Gibt eine konstante Referenz auf den vom aktuellen Objekt dargestellten Wert zurück. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht null ist. |
| [operator!=](./operator!=/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht dem angegebenen Wert entspricht. |
| [operator!=](./operator!=/)(const Nullable\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert nicht dem Wert entspricht, der vom angegebenen [Nullable](./)-Objekt dargestellt wird. |
| [operator&=](./operator&=/)(bool) | Wendet [operator&=()](./operator&=/) auf den vom aktuellen Objekt dargestellten Wert an und verwendet den angegebenen Wert als rechtes Argument. |
| [operator+](./operator+/)(std::nullptr_t) const | Gibt eine standardmäßig konstruierte Instanz der Klasse Nullable<T> zurück. |
| [operator+](./operator+/)(const T1\&) const | Addiert nullable und nicht‑nullable Werte. |
| [operator+](./operator+/)(const Nullable\<T1\>\&) const | Addiert nullable Werte. |
| [operator+=](./operator+=/)(std::nullptr_t) | Setzt das aktuelle Objekt zurück, sodass es einen Nullwert darstellt. |
| [operator+=](./operator+=/)(const T1\&) | Wendet [operator+=()](./operator+=/) auf den vom aktuellen Objekt dargestellten Wert an und verwendet den angegebenen Wert als rechtes Argument. |
| [operator+=](./operator+=/)(const Nullable\<T1\>\&) | Wendet [operator+=()](./operator+=/) auf den vom aktuellen Objekt dargestellten Wert an und verwendet den Wert, der vom angegebenen [Nullable](./)-Objekt dargestellt wird, als rechtes Argument. |
| [operator-](./operator-/)(T1) const | Subtrahiert nullable und null‑gezeigte Werte. |
| [operator-](./operator-/)(const T1\&) const | Subtrahiert nullable und nicht‑nullable Werte. |
| [operator-](./operator-/)(const Nullable\<T1\>\&) const | Subtrahiert nullable Werte. |
| [operator-=](./operator-=/)(T1) | Gibt eine Instanz der Klasse [Nullable](./) zurück, die einen Nullwert darstellt. |
| [operator-=](./operator-=/)(const T1\&) | Wendet [operator-=()](./operator-=/) auf den vom aktuellen Objekt dargestellten Wert an und verwendet den angegebenen Wert als rechtes Argument. |
| [operator-=](./operator-=/)(const Nullable\<T1\>\&) | Wendet [operator-=()](./operator-=/) auf den vom aktuellen Objekt dargestellten Wert an und verwendet dabei den vom angegebenen [Nullable](./) Objekt dargestellten Wert als Rechtsargument. |
| [operator<](./operator_/)(std::nullptr_t) const | Gibt immer false zurück. |
| [operator<](./operator_/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner ist als der angegebene Wert, indem [operator<()](./operator_/) auf diese Werte angewendet wird. |
| [operator<](./operator_/)(const Nullable\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner ist als der vom angegebenen [Nullable](./) Objekt dargestellte Wert, indem [operator<()](./operator_/) auf diese Werte angewendet wird. |
| [operator<=](./operator_=/)(std::nullptr_t) const | Gibt immer false zurück. |
| [operator<=](./operator_=/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem angegebenen Wert ist, indem [operator<=()](./operator_=/) auf diese Werte angewendet wird. |
| [operator<=](./operator_=/)(const Nullable\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem vom angegebenen [Nullable](./) Objekt dargestellten Wert ist, indem [operator<=()](./operator_=/) auf diese Werte angewendet wird. |
| [operator=](./operator=/)(std::nullptr_t) | Weist dem aktuellen Objekt einen Nullwert zu. |
| [operator=](./operator=/)(const T1\&) | Ersetzt den derzeit vom Objekt dargestellten Wert durch den angegebenen. |
| [operator=](./operator=/)(const Nullable\<T1\>\&) | Ersetzt den derzeit vom Objekt dargestellten Wert durch den angegebenen. |
| [operator==](./operator==/)(std::nullptr_t) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert Null ist. |
| [operator==](./operator==/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem angegebenen Wert entspricht. |
| [operator==](./operator==/)(const Nullable\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert dem vom angegebenen [Nullable](./)-Objekt dargestellten Wert entspricht. |
| [operator>](./operator_/)(std::nullptr_t) const | Gibt immer false zurück. |
| [operator>](./operator_/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer ist als der angegebene Wert, indem [operator>()](./operator_/) auf diese Werte angewendet wird. |
| [operator>](./operator_/)(const Nullable\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer ist als der vom angegebenen [Nullable](./) Objekt dargestellte Wert, indem [operator>()](./operator_/) auf diese Werte angewendet wird. |
| [operator>=](./operator_=/)(std::nullptr_t) const | Gibt immer false zurück. |
| [operator>=](./operator_=/)(const T1\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer oder gleich dem vom angegebenen Objekt dargestellten Wert ist, indem [operator>=()](./operator_=/) auf diese Werte angewendet wird. |
| [operator>=](./operator_=/)(const Nullable\<T1\>\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer oder gleich dem vom angegebenen [Nullable](./) Objekt dargestellten Wert ist, indem [operator>=()](./operator_=/) auf diese Werte angewendet wird. |
| [operator | =](./operator_=/)(bool) | Wendet [operator | =()](./operator_=/) auf den vom aktuellen Objekt dargestellten Wert, wobei der angegebene Wert als Rechtsargument verwendet wird. |
| [reset](./reset/)() | Setzt den derzeit dargestellten Wert auf Null. |
| [ToString](./tostring/)() const | Konvertiert den vom aktuellen Objekt dargestellten Wert in einen String. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ValueType](./valuetype/) | Ein Alias für einen Typ des von dieser Klasse dargestellten Werts. |
## Hinweise


Stellt einen Wert des angegebenen Typs dar, dem Null zugewiesen werden kann. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../smartptr/), um Objekte dieses Typs zu verwalten.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
