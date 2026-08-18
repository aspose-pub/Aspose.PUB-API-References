---
title: "System::TypeInfo Klasse"
linktitle: "TypeInfo"
second_title: "Aspose.PUB für C++"
description: "System::TypeInfo Klasse. Stellt einen bestimmten Typ dar und liefert Informationen darüber in C++."
type: docs
weight: 6400
url: /de/cpp/system/typeinfo/
---
## TypeInfo class


Stellt einen bestimmten Typ dar und liefert Informationen darüber.

```cpp
class TypeInfo
```

## Nested classes

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Fügt das angegebene Attribut zur Liste der Attribute des Typs hinzu. |
| [AddDefaultConstructor](./adddefaultconstructor/)() | Setzt den Standardkonstruktor für den Typ T. |
| [AddDefaultConstructor](./adddefaultconstructor/)(DefaultConstructor) | Setzt den Standardkonstruktor über den Funktor, der die Klasseninstanz erstellt. |
| [AddMember](./addmember/)(const SharedPtr\<System::Reflection::MemberInfo\>\&) | Fügt das angegebene Mitglied zur Liste der Mitglieder des Typs hinzu. |
| static [BoxedValueType](./boxedvaluetype/)() | Stellt eine eindeutige [TypeInfo](./)-Struktur für den [BoxedValue](./boxedvalue/)-Typ bereit, die von mehreren Boxed*-Klassen gemeinsam genutzt wird. |
| [Equals](./equals/)(const TypeInfo\&) const |  |
| [get_Assembly](./get_assembly/)() const | NICHT IMPLEMENTIERT. Gibt einen Zeiger auf die Assembly zurück, in der der vom aktuellen Objekt repräsentierte Typ deklariert ist. |
| [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NICHT IMPLEMENTIERT. Gibt den vollqualifizierten Namen einschließlich des Assembly-Namens des vom aktuellen Objekt repräsentierten Typs zurück. |
| [get_BaseType](./get_basetype/)() const | Gibt den Basis‑Typ‑Deskriptor zurück. |
| [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Ermittelt einen Wert, der angibt, ob das aktuelle Type‑Objekt Typ‑Parameter hat, die nicht durch konkrete Typen ersetzt wurden. |
| [get_DeclaredMember](./get_declaredmember/)(const String\&) const | Ermittelt die Liste der Mitglieder mit dem angegebenen Namen. |
| [get_FullName](./get_fullname/)() const | Gibt den vollqualifizierten Namen (ohne den Assembly‑Namen) des vom aktuellen Objekt repräsentierten Typs zurück. |
| [get_GenericTypeArguments](./get_generictypearguments/)() const | Ermittelt ein Array der generischen Typ‑Argumente für diesen Typ. |
| [get_IsAbstract](./get_isabstract/)() const | Ermittelt einen Wert, der angibt, ob der Typ abstrakt ist und überschrieben werden muss. |
| [get_IsArray](./get_isarray/)() const | Ermittelt einen Wert, der angibt, ob der Typ ein Array ist. |
| [get_IsClass](./get_isclass/)() const | Ermittelt einen Wert, der angibt, ob der Typ eine Klasse oder ein Delegat ist; das heißt, kein Werttyp oder Interface. |
| [get_IsEnum](./get_isenum/)() const | Ermittelt einen Wert, der angibt, ob der aktuelle Typ eine Aufzählung darstellt. |
| [get_IsGenericType](./get_isgenerictype/)() const |  |
| [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Ermittelt einen Wert, der angibt, ob der aktuelle Typ eine generische Typdefinition darstellt, aus der andere generische Typen erstellt werden können. |
| [get_IsInterface](./get_isinterface/)() const | Ermittelt einen Wert, der angibt, ob der Typ ein Interface ist; das heißt, keine Klasse oder ein Werttyp. |
| [get_IsSealed](./get_issealed/)() const | Ermittelt einen Wert, der angibt, ob der Typ als sealed deklariert ist. |
| [get_IsValueType](./get_isvaluetype/)() const | Ermittelt einen Wert, der angibt, ob der Typ ein Werttyp ist. |
| [get_IsVisible](./get_isvisible/)() const | Ermittelt einen Wert, der angibt, ob auf den Typ von Code außerhalb der Assembly zugegriffen werden kann. |
| [get_Name](./get_name/)() const | Gibt den Namen des vom aktuellen Objekt repräsentierten Typs zurück. |
| [get_Namespace](./get_namespace/)() const | Ermittelt den Namespace des Typs. |
| [GetConstructor](./getconstructor/)(const ArrayPtr\<TypeInfo\>\&) const | Sucht nach einem öffentlichen Instanz‑Konstruktor, dessen Parameter mit den Typen im angegebenen Array übereinstimmen. |
| [GetConstructors](./getconstructors/)(System::Reflection::BindingFlags) const | Sucht nach den für den aktuellen Typ definierten Konstruktoren unter Verwendung der angegebenen BindingFlags. |
| [GetConstructors](./getconstructors/)() const | Gibt alle für den aktuellen Typ definierten öffentlichen Konstruktoren zurück. |
| [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&) const | Sucht nach dem benutzerdefinierten Attribut mit dem angegebenen Typ, das auf den vom aktuellen Objekt repräsentierten Typ angewendet wurde. |
| [GetCustomAttributes](./getcustomattributes/)() const | Gibt ein Array zurück, das Objekte enthält, die alle auf den Typ angewendeten benutzerdefinierten Attribute repräsentieren. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Gibt ein Array zurück, das Objekte enthält, die spezifische auf den Typ angewendete Attribute repräsentieren. |
| [GetElementType](./getelementtype/)() const | NICHT IMPLEMENTIERT. |
| [GetField](./getfield/)(const System::String\&, System::Reflection::BindingFlags) const | Sucht nach dem angegebenen Feld unter Verwendung der angegebenen Bindungsbeschränkungen. |
| [GetFields](./getfields/)(System::Reflection::BindingFlags) const | Sucht nach den für den aktuellen Typ definierten Feldern unter Verwendung der angegebenen Bindungsbeschränkungen. |
| [GetGenericArguments](./getgenericarguments/)() const | Ermittelt ein Array der generischen Typ‑Argumente für diesen Typ. |
| [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode zurück, der mit dieser Instanz verknüpft ist. |
| [GetInterfaces](./getinterfaces/)() const | Ruft alle vom aktuellen Typ implementierten oder geerbten Schnittstellen ab. |
| [GetMember](./getmember/)(const String\&) const | Ermittelt die Liste der Mitglieder mit dem angegebenen Namen. |
| [GetMethod](./getmethod/)(const String\&) const | Ruft die Methode mit dem angegebenen Namen ab. |
| [GetProperties](./getproperties/)() const | Gibt alle öffentlichen Eigenschaften des aktuellen Typs zurück. |
| [GetProperties](./getproperties/)(System::Reflection::BindingFlags) const | Sucht nach den Eigenschaften des aktuellen Typs unter Verwendung der angegebenen Bindungsbeschränkungen. |
| [GetTemplParamType](./gettemplparamtype/)() const | Ruft den Deskriptor des Typparameters der Vorlage ab. |
| [Hash](./hash/)() const | Gibt einen Hashwert zurück, der mit dem vom aktuellen Objekt dargestellten Typ verknüpft ist. |
| [IsAssignableFrom](./isassignablefrom/)(const TypeInfo\&) const | Bestimmt, ob eine Instanz eines angegebenen Typs einer Variablen des aktuellen Typs zugewiesen werden kann. |
| [IsDefined](./isdefined/)(const TypeInfo\&, bool) const | NICHT IMPLEMENTIERT. Gibt an, ob ein oder mehrere Attribute des angegebenen Typs oder seiner abgeleiteten Typen auf dieses Mitglied angewendet werden. |
| [IsInstanceOfType](./isinstanceoftype/)(const SharedPtr\<Object\>\&) const | Bestimmt, ob das angegebene Objekt eine Instanz des aktuellen Typs ist. |
| [IsSubclassOf](./issubclassof/)(const TypeInfo\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Typ eine Unterklasse der angegebenen Klasse ist. |
| [operator!=](./operator!=/)(const TypeInfo\&) const | Bestimmt, ob das aktuelle und das angegebene [TypeInfo](./)-Objekt nicht gleich sind. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Bestimmt, ob das aktuelle [TypeInfo](./)-Objekt kein Null-Objekt ist, d. h. es einen Typ darstellt. |
| [operator==](./operator==/)(const TypeInfo\&) const | Bestimmt, ob das aktuelle und das angegebene [TypeInfo](./)-Objekt gleich sind. |
| [operator==](./operator==/)(std::nullptr_t) const | Bestimmt, ob das aktuelle [TypeInfo](./)-Objekt ein Null-Objekt ist, d. h. keinen Typ darstellt. |
| [reset](./reset/)() | Setzt [TypeInfo](./) auf null. |
| [set_IsValueType](./set_isvaluetype/)(bool) | Setzt einen Wert, der angibt, ob der Typ ein Werttyp ist. |
| [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Setzt den Deskriptor des Basistyps. |
| [SetTemplParamType](./settemplparamtype/)(const TypeInfo\&) | Setzt den Deskriptor des Typparameters der Vorlage. |
| static [StringHash](./stringhash/)(const char_t *) | Berechnet den Hash für die angegebene Zeichenkette. |
| [ToString](./tostring/)() const | Gibt eine Zeichenkette zurück, die den Namen des vom aktuellen Objekt dargestellten Typs enthält. |
| static [Type](./type/)() | Gibt ein [TypeInfo](./)-Objekt zurück, das die [TypeInfo](./)-Klasse repräsentiert. |
| [TypeInfo](./typeinfo/)() | Standardkonstruktor (kein Typ ist gesetzt). |
| [TypeInfo](./typeinfo/)(std::nullptr_t) | Null-Objekt-Konstruktor (kein Typ ist festgelegt). |
| [TypeInfo](./typeinfo/)(const char_t *) | Konstruktor. |
| [TypeInfo](./typeinfo/)(const char_t *, uint32_t) | Konstruktor. |
| [TypeInfo](./typeinfo/)(const std::type_info\&) | Konstruktor. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [EmptyType](./emptytype/) | Konstante, die eine leere Liste von [TypeInfo](./) darstellt. |
| static [EmptyTypes](./emptytypes/) | Konstante, die eine leere Liste von [TypeInfo](./) darstellt. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Funktionszeiger zum Erzeugen des Typs. |
## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
