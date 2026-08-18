---
title: "System::DynamicWeakPtr Klasse"
linktitle: "DynamicWeakPtr"
second_title: "Aspose.PUB für C++"
description: "System::DynamicWeakPtr Klasse. Smart-Pointer-Klasse, die die Zeigermodi von Template-Argumenten des gespeicherten Objekts verfolgt und nach jeder Zuweisung aktualisiert. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const-Referenz in C++ übergeben werden."
type: docs
weight: 2200
url: /de/cpp/system/dynamicweakptr/
---
## DynamicWeakPtr class


Smart‑Pointer‑Klasse, die die Zeigermodi von Template‑Argumenten des gespeicherten Objekts verfolgt und nach jeder Zuweisung aktualisiert. Dieser Typ ist ein Zeiger, der die Löschung anderer Objekte verwaltet. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const‑Referenz übergeben werden.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


| Parameter | Beschreibung |
| --- | --- |
| Pointee | Typ. |
| trunkMode | Modus des Smart Pointers selbst, shared oder weak. |
| weakLeafs | Indizes der Template-Argumente des gespeicherten Typs, die auf den weak-Pointer-Modus gesetzt werden sollen. |
## Nested classes

* Class [Reference](./reference/)
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Erstellt einen null Smart Pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(Pointee_ *) | Erstellt einen Smart Pointer, der auf das gegebene Objekt zeigt. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr_\&) | Kopierkonstruiert einen Smart Pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr\<Q\>\&) | Kopierkonstruiert einen Smart Pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(const DynamicWeakPtr_\&) | Kopierkonstruiert einen Smart Pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(SmartPtr_\&&) | Move-konstruiert einen Smart Pointer. |
| [operator=](./operator=/)(SmartPtr_\&&) | Move-zuweist einen Smart Pointer. |
| [operator=](./operator=/)(const SmartPtr_\&) | Kopierzuweist einen Smart Pointer. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Kopierzuweist einen Smart Pointer. |
| [operator=](./operator=/)(typename SmartPtr_::Pointee_ *) | Weist einen Smart Pointer zu. |
| [operator=](./operator=/)(std::nullptr_t) | Setzt den Smart-Pointer auf null. |
| [operator==](./operator==/)(std::nullptr_t) const | Prüft, ob der Smart-Pointer null ist. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Selbsttyp-Alias. |
| [Pointee_](./pointee_/) | Zieltyp. |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) Basisklassen-Alias. |

## Siehe auch

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
