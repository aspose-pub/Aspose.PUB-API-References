---
title: "System::Reflection-Namespace"
linktitle: "System::Reflection"
second_title: "Aspose.PUB für C++"
description: "Wie man den System::Reflection-Namespace in C++ verwendet."
type: docs
weight: 3300
url: /de/cpp/system.reflection/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) Klasse, die eine Assembly beschreibt. Die Unterstützung ist eingeschränkt, da die Regeln zwischen C# und C++ stark unterschiedlich sind. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [AssemblyName](./assemblyname/) | Definiert den Namen der Assembly. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton zum Registrieren eines Typs in der ausführenden Assembly. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Basistyp für Singletons zum Registrieren eines Typs in der ausführenden Assembly. |
| [ConstructorInfo](./constructorinfo/) | Stellt Zugriff auf Konstruktormetadaten bereit. |
| [FieldInfo](./fieldinfo/) | Ermittelt die Attribute eines Feldes und stellt Zugriff auf Feldmetadaten bereit. |
| [MemberInfo](./memberinfo/) | Stellt Reflexionsinformationen zu Mitgliedern bereit. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [MethodBase](./methodbase/) | Grundlegende Informationen zu einer Methode. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [MethodInfo](./methodinfo/) | Stellt Informationen zu einer Klassenmethode dar. |
| [PropertyInfo](./propertyinfo/) | Stellt Informationen zu einer Eigenschaft dar. |
## Enums

| Aufzählung | Beschreibung |
| --- | --- |
| [BindingFlags](./bindingflags/) | Definiert Modi für das Nachschlagen von Mitgliedern und Typen sowie Bindungen. |
| [FieldAttributes](./fieldattributes/) | Reflektierte Feldattribute. |
| [MemberTypes](./membertypes/) | Markiert jeden Mitgliedstyp. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException wird von der Methode Module.GetTypes ausgelöst, wenn eine der Klassen in einem Modul nicht geladen werden kann. Wickeln Sie die Instanzen der Klasse ReflectionTypeLoadException niemals in einen [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException wird von Methoden ausgelöst, die über Reflexion aufgerufen werden. Wickeln Sie die Instanzen der Klasse TargetInvocationException niemals in einen [System::SmartPtr](../system/smartptr/). |
