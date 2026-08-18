---
title: "System::SmartPtr-Klasse"
linktitle: "SmartPtr"
second_title: "Aspose.PUB für C++"
description: "System::SmartPtr-Klasse. Zeigerklasse zum Umschließen von Typen, die im Heap alloziert werden. Verwenden Sie sie, um den Speicher für Klassen zu verwalten, die Object erben. Dieser Zeigertyp folgt den Semantiken von Intrusive‑Pointer. Der Referenzzähler wird entweder im Objekt selbst oder in einer Zählerstruktur gespeichert, die eng mit der Objektinstanz verknüpft ist. In jedem Fall bilden alle SmartPtr-Instanzen eine einzige Besitzgruppe, unabhängig davon, wie sie erstellt wurden, was sich vom Verhalten der std::shared_ptr‑Klasse unterscheidet. Das Konvertieren eines rohen Zeigers zu SmartPtr ist sicher, solange andere SmartPtr‑Instanzen gemeinsame Referenzen auf dasselbe Objekt halten. Eine SmartPtr‑Klasseninstanz kann sich in einem von zwei Zuständen befinden: Shared‑Pointer und Weak‑Pointer. Um das Objekt am Leben zu erhalten, sollte die Anzahl der Shared‑Referenzen positiv sein. Sowohl Weak‑ als auch Shared‑Pointer können verwendet werden, um auf das referenzierte Objekt zuzugreifen (Methoden aufzurufen, Felder zu lesen oder zu schreiben usw.), aber Weak‑Pointer nehmen nicht am Referenzzählen der Shared‑Pointer teil. Das Objekt wird gelöscht, wenn der letzte ''shared'' SmartPtr‑Pointer darauf zerstört wird. Stellen Sie also sicher, dass dies nicht geschieht, wenn keine anderen Shared‑SmartPtr‑Pointer auf das Objekt existieren, z. B. während der Objektkonstruktion oder -zerstörung. Verwenden Sie System::Object::ThisProtector‑Wächterobjekte (im C++‑Code) oder das CppCTORSelfReference‑ bzw. CppSelfReference‑Attribut (im zu übersetzenden C#‑Code), um dieses Problem zu beheben. Ähnlich sollten Sie Schleifenreferenzen durch die Verwendung der System::WeakPtr‑Zeigerklasse oder des System::SmartPtrMode::Weak‑Zeiger‑Modus (im C++‑Code) bzw. des CppWeakPtr‑Attributs (im zu übersetzenden C#‑Code) aufbrechen. Wenn zwei oder mehr Objekte sich gegenseitig mit ''shared''‑Pointern referenzieren, werden sie nie gelöscht. Sollte der Zeigertyp (weak oder shared) zur Laufzeit gewechselt werden müssen, verwenden Sie die Methode System::SmartPtr<T>::set_Mode() oder die Klasse System::DynamicWeakPtr. Die SmartPtr‑Klasse enthält keine virtuellen Methoden. Sie sollten sie nur erben, wenn Sie eine eigene Speicherverwaltungsstrategie erstellen. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const‑Referenz in C++ übergeben werden."
type: docs
weight: 5400
url: /de/cpp/system/smartptr/
---
## SmartPtr class


Pointer‑Klasse, um Typen, die auf dem Heap alloziert werden, zu kapseln. Verwenden Sie sie, um den Speicher für Klassen, die von [Object](../object/) erben, zu verwalten. Dieser Pointer‑Typ folgt den Intrusive‑Pointer‑Semantiken. Der Referenzzähler wird entweder im [Object](../object/) selbst oder in einer Zählerstruktur gespeichert, die eng mit der [Object](../object/)-Instanz verknüpft ist. In jedem Fall bilden alle [SmartPtr](./)-Instanzen eine Single‑Ownership‑Gruppe, unabhängig davon, wie sie erstellt wurden, was sich vom Verhalten der Klasse std::shared_ptr unterscheidet. Das Konvertieren eines rohen Zeigers zu [SmartPtr](./) ist sicher, solange andere [SmartPtr](./)-Instanzen geteilte Referenzen auf dasselbe Objekt halten. Eine [SmartPtr](./)-Klasseninstanz kann sich in einem von zwei Zuständen befinden: Shared‑Pointer und Weak‑Pointer. Um das Objekt am Leben zu erhalten, sollte die Anzahl der geteilten Referenzen darauf positiv sein. Sowohl Weak‑ als auch Shared‑Pointer können verwendet werden, um auf das referenzierte Objekt zuzugreifen (Methoden aufzurufen, Felder zu lesen oder zu schreiben usw.), aber Weak‑Pointer nehmen nicht am Referenzzählen der Shared‑Pointer teil. [Object](../object/) wird gelöscht, wenn der letzte „shared“ [SmartPtr](./)-Pointer darauf zerstört wird. Stellen Sie also sicher, dass dies nicht geschieht, wenn keine anderen geteilten [SmartPtr](./)-Pointer auf das Objekt existieren, z. B. während der Objektkonstruktion oder -zerstörung. Verwenden Sie System::Object::ThisProtector‑Sentry‑Objekte (im C++‑Code) oder das Attribut CppCTORSelfReference bzw. CppSelfReference (im zu übersetzenden C#‑Code), um dieses Problem zu beheben. Stellen Sie außerdem sicher, Schleifenreferenzen zu brechen, indem Sie die Pointer‑Klasse [System::WeakPtr](../weakptr/) oder den Pointer‑Modus [System::SmartPtrMode::Weak](../smartptrmode/) (im C++‑Code) bzw. das Attribut CppWeakPtr (im zu übersetzenden C#‑Code) verwenden. Wenn zwei oder mehr Objekte sich gegenseitig mit „shared“-Pointern referenzieren, werden sie niemals gelöscht. Sollte der Pointer‑Typ (weak oder shared) zur Laufzeit gewechselt werden müssen, verwenden Sie die Methode [System::SmartPtr<T>::set_Mode()](./set_mode/) oder die Klasse [System::DynamicWeakPtr](../dynamicweakptr/). Die [SmartPtr](./)-Klasse enthält keine virtuellen Methoden. Sie sollten sie nur erben, wenn Sie eine eigene Speicherverwaltungsstrategie erstellen. Dieser Typ ist ein Pointer, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const‑Referenz übergeben werden.

```cpp
template<class T>class SmartPtr
```


| Parameter | Beschreibung |
| --- | --- |
| T | Typ des referenzierten Objekts. Muss entweder [System::Object](../object/) oder eine Unterklasse davon sein. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [begin](./begin/)() | Zugriff auf die Methode [begin()](./begin/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [begin()](./begin/) ist. |
| [begin](./begin/)() const | Zugriff auf die Methode [begin()](./begin/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [begin()](./begin/) ist. |
| [Cast](./cast/)() const | Wandelt den Pointer in seinen eigenen Typ um. |
| [Cast](./cast/)() const | Wandelt den Pointer mittels static_cast in den Basistyp um. |
| [Cast](./cast/)() const | Wandelt den Pointer mittels dynamic_cast in den abgeleiteten Typ um. |
| [Cast](./cast/)() const | Wandelt den Pointer mittels dynamic_cast in den abgeleiteten Typ um. |
| [cbegin](./cbegin/)() const | Zugriff auf die Methode [cbegin()](./cbegin/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [cbegin()](./cbegin/) ist. |
| [cend](./cend/)() const | Zugriff auf die Methode [cend()](./cend/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [cend()](./cend/) ist. |
| [const_pointer_cast](./const_pointer_cast/)() const | Wandelt den Pointer mittels const_cast in einen anderen Typ um, wobei das referenzierte Objekt verwendet wird. |
| [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Wandelt den Zeiger mit dynamic_cast in einen anderen Typ um, basierend auf dem referenzierten Objekt. |
| [end](./end/)() | Zugriffsmethode für die [end()](./end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein spezialisierter Typ mit einer [end()](./end/)-Methode ist. |
| [end](./end/)() const | Zugriffsmethode für die [end()](./end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein spezialisierter Typ mit einer [end()](./end/)-Methode ist. |
| [get](./get/)() const | Liefert das referenzierte Objekt. |
| [get_Mode](./get_mode/)() const | Liefert den Zeigermodus. |
| [get_shared](./get_shared/)() const | Liefert das referenzierte Objekt, prüft jedoch, dass der Zeiger im Shared‑Modus ist. |
| [get_shared_count](./get_shared_count/)() const | Liefert die Anzahl der vorhandenen Shared‑Pointer auf das referenzierte Objekt, einschließlich des aktuellen. Prüft, dass der aktuelle Zeiger im Shared‑Modus ist. |
| [GetHashCode](./gethashcode/)() const | Ruft [GetHashCode()](./gethashcode/) für das referenzierte Objekt auf. |
| [GetObjectNotNull](./getobjectnotnull/)() const | Liefert das aktuell referenzierte Objekt (falls vorhanden) oder wirft eine Ausnahme. |
| [GetObjectOrNull](./getobjectornull/)() const | Liefert das referenzierte Objekt (falls vorhanden) oder nullptr. Entspricht [get()](./get/). |
| [GetObjectOwner](./getobjectowner/)() const | Liefert das referenzierte Objekt. |
| [GetPointer](./getpointer/)() const | Liefert das referenzierte Objekt (falls vorhanden) oder nullptr. Entspricht [get()](./get/). |
| [Is](./is/)(const System::TypeInfo\&) const | Prüft, ob das referenzierte Objekt vom angegebenen Typ oder einem abgeleiteten Typ ist. Entspricht der C#‑'is'-Semantik. |
| [IsAliasingPtr](./isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das eigene zeigt (erstellt durch einen Alias‑Konstruktor). |
| [IsShared](./isshared/)() const | Prüft, ob der Zeiger im Shared‑Modus ist. |
| [IsWeak](./isweak/)() const | Prüft, ob der Zeiger im Weak‑Modus ist. |
| explicit [operator bool](./operatorbool/)() const | Prüft, ob der Zeiger nicht null ist. |
| [operator!](./operator!/)() const | Prüft, ob der Zeiger null ist. |
| [operator*](./operator_/)() const | Liefert eine Referenz auf das referenzierte Objekt. Prüft, dass der Zeiger nicht null ist. |
| [operator->](./operator-_/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| [operator<](./operator_/)(Y *) const | Bietet weniger‑Vergleichssemantik für die Klasse [SmartPtr](./). |
| [operator<](./operator_/)(SmartPtr\<Y\> const\&) const | Bietet weniger‑Vergleichssemantik für die Klasse [SmartPtr](./). |
| [operator=](./operator=/)(SmartPtr_\&&) | Verschiebt die Zuweisung eines [SmartPtr](./)-Objekts. x wird unbrauchbar. |
| [operator=](./operator=/)(const SmartPtr_\&) | Kopiert die Zuweisung eines [SmartPtr](./)-Objekts. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Kopiert die Zuweisung eines [SmartPtr](./)-Objekts. Führt erforderliche Typkonvertierungen durch. |
| [operator=](./operator=/)(Pointee_ *) | Weist einen rohen Zeiger einem [SmartPtr](./)-Objekt zu. |
| [operator=](./operator=/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| [operator==](./operator==/)(std::nullptr_t) const | Prüft, ob der Zeiger auf nullptr zeigt. |
| [operator[]](./operator[]/)(IdxType) const | Zugriff auf Array-Elemente. Kompiliert nur, wenn SmartPtr_ eine Spezialisierung von [System::Array](../array/) ist. |
| [RemoveAliasing](./removealiasing/)() const | Entfernt Aliasing (erstellt durch einen Alias-Konstruktor) vom Zeiger, stellt sicher, dass er (bei geteilten Zeigern) verwaltet oder (bei schwachen Zeigern) verfolgt, dasselbe Objekt, auf das er zeigt. |
| [reset](./reset/)(Pointee_ *) | Setzt das referenzierte Objekt. |
| [reset](./reset/)() | Setzt den Zeiger auf nullptr. |
| [set_Mode](./set_mode/)(SmartPtrMode) | Setzt den Zeigermodus. Kann die Referenzzähler des referenzierten Objekts ändern. |
| [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(uint32_t) const | Ruft die Methode SetTemplateWeakPtr() am referenzierten Objekt auf (falls vorhanden). |
| [SmartPtr](./smartptr/)(SmartPtrMode) | Erstellt ein [SmartPtr](./)-Objekt im erforderlichen Modus. |
| [SmartPtr](./smartptr/)(std::nullptr_t, SmartPtrMode) | Erstellt ein Nullzeiger-[SmartPtr](./)-Objekt im erforderlichen Modus. |
| [SmartPtr](./smartptr/)(Pointee_ *, SmartPtrMode) | Erstellt ein [SmartPtr](./), das auf das angegebene Objekt zeigt, oder konvertiert einen rohen Zeiger zu einem [SmartPtr](./). |
| [SmartPtr](./smartptr/)(const SmartPtr_\&, SmartPtrMode) | Kopiert ein [SmartPtr](./)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
| [SmartPtr](./smartptr/)(const SmartPtr\<Q\>\&, SmartPtrMode) | Kopiert ein [SmartPtr](./)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt, falls erlaubt, eine Typkonvertierung durch. |
| [SmartPtr](./smartptr/)(SmartPtr_\&&, SmartPtrMode) | Verschiebt ein [SmartPtr](./)-Objekt. Tauscht im Wesentlichen zwei Zeiger, wenn beide im selben Modus sind. x kann nach dem Aufruf unbrauchbar sein. |
| explicit [SmartPtr](./smartptr/)(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typumwandlung gibt, die in C++ nicht unterstützt wird. |
| explicit [SmartPtr](./smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Codekonstrukte zu übersetzen. |
| [SmartPtr](./smartptr/)(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) | Erstellt ein [SmartPtr](./), das Eigentumsinformationen mit dem Anfangswert von ptr teilt, aber einen nicht verwandten und nicht verwalteten Zeiger p enthält. |
| [static_pointer_cast](./static_pointer_cast/)() const | Wandelt den Zeiger mittels static_cast auf das referenzierte Objekt in einen anderen Typ um. |
| [ToObjectPtr](./toobjectptr/)() const | Konvertiert jeden Zeigertyp zu einem Zeiger auf [Object](../object/). Erfordert nicht, dass der Pointee_-Typ vollständig ist. |
| static [Type](./type/)() | Abkürzung, um das [System::TypeInfo](../typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
| [~SmartPtr](./~smartptr/)() | Zerstört das [SmartPtr](./)-Objekt. Falls nötig, verringert es den Referenzzähler des referenzierten Objekts und löscht das Objekt. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ArrayType](./arraytype/) | Dasselbe wie Pointee_, falls es eine Spezialisierung von [System::Array](../array/) ist, sonst void. |
| [Pointee_](./pointee_/) | Zieltyp. |
| [SmartPtr_](./smartptr_/) | Spezialisierter Smart-Pointer-Typ. |
| [ValueType](./valuetype/) | Speichertyp des referenzierten Arrays. Nur sinnvoll, wenn T eine Spezialisierung von [System::Array](../array/) ist. |

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
