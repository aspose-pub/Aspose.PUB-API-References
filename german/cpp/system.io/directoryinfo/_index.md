---
title: "System::IO::DirectoryInfo Klasse"
linktitle: "DirectoryInfo"
second_title: "Aspose.PUB für C++"
description: "System::IO::DirectoryInfo Klasse. Stellt einen Dateisystempfad dar, ein Verzeichnis, das durch diesen Pfad referenziert wird, und bietet Instanzmethoden zum Manipulieren von Verzeichnissen. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1200
url: /de/cpp/system.io/directoryinfo/
---
## DirectoryInfo class


Stellt einen Dateisystempfad dar, ein Verzeichnis, das durch diesen Pfad referenziert wird, und bietet Instanzmethoden zum Manipulieren von Verzeichnissen. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Create](./create/)() | Erstellt ein Verzeichnis am Pfad, der vom aktuellen Objekt repräsentiert wird. |
| [CreateSubdirectory](./createsubdirectory/)(const String\&) | Erstellt Unterverzeichnisse am angegebenen Pfad. |
| [Delete](./delete/)() override | Entfernt das Verzeichnis, das durch den vom aktuellen Objekt repräsentierten Pfad referenziert wird, wenn das Verzeichnis leer ist. |
| [Delete](./delete/)(bool) | Entfernt das Verzeichnis, das durch den vom aktuellen Objekt repräsentierten Pfad referenziert wird. Ein Parameter gibt an, ob der Inhalt des Verzeichnisses rekursiv entfernt werden soll, wenn das Verzeichnis nicht leer ist. |
| [DirectoryInfo](./directoryinfo/)(const String\&) | Konstruiert eine Instanz der Klasse [DirectoryInfo](./) auf dem angegebenen Pfad. |
| [EnumerateDirectories](./enumeratedirectories/)() | Gibt eine aufzählbare Sammlung zurück, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Unterverzeichnisse enthält. |
| [EnumerateDirectories](./enumeratedirectories/)(const String\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [EnumerateDirectories](./enumeratedirectories/)(const String\&, SearchOption) | Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [EnumerateFiles](./enumeratefiles/)() | Gibt eine aufzählbare Sammlung zurück, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Dateien enthält. |
| [EnumerateFiles](./enumeratefiles/)(const String\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien, die die angegebenen Suchkriterien erfüllen. |
| [EnumerateFiles](./enumeratefiles/)(const String\&, SearchOption) | Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Dateien, die die angegebenen Suchkriterien erfüllen. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Gibt eine aufzählbare Sammlung zurück, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Dateien und Verzeichnisse enthält. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const String\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const String\&, SearchOption) | Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [get_Exists](./get_exists/)() override | Bestimmt, ob der vom aktuellen Objekt dargestellte Pfad auf ein vorhandenes Verzeichnis verweist. |
| [get_Name](./get_name/)() override | Gibt den Namen der Entität zurück, auf die der vom aktuellen Objekt dargestellte Pfad verweist. |
| [get_Parent](./get_parent/)() | Gibt einen Shared Pointer auf ein [DirectoryInfo](./)-Objekt zurück, das einen Pfad darstellt, der auf das übergeordnete Verzeichnis des vom aktuellen Objekt dargestellten Verzeichnisses verweist. |
| [get_Root](./get_root/)() | Gibt einen Shared Pointer auf ein [DirectoryInfo](./)-Objekt zurück, das einen Pfad darstellt, der auf das Stammverzeichnis des vom aktuellen Objekt dargestellten Verzeichnisses verweist. |
| [GetDirectories](./getdirectories/)() | Gibt ein Array zurück, das Shared Pointer auf [DirectoryInfo](./)-Objekte enthält, die alle im vom aktuellen Objekt dargestellten Verzeichnis befindlichen Unterverzeichnisse repräsentieren. |
| [GetDirectories](./getdirectories/)(const String\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [GetDirectories](./getdirectories/)(const String\&, SearchOption) | Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [GetFiles](./getfiles/)() | Gibt ein Array zurück, das Shared Pointer auf [FileInfo](../fileinfo/)-Objekte enthält, die alle im vom aktuellen Objekt dargestellten Verzeichnis befindlichen Verzeichnisse repräsentieren. |
| [GetFiles](./getfiles/)(const String\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien, die die angegebenen Suchkriterien erfüllen. |
| [GetFiles](./getfiles/)(const String\&, SearchOption) | Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Dateien, die die angegebenen Suchkriterien erfüllen. |
| [GetFileSystemInfos](./getfilesysteminfos/)() | Gibt ein Array zurück, das Shared Pointer auf [FileSystemInfo](../filesysteminfo/)-Objekte enthält, die alle im vom aktuellen Objekt dargestellten Verzeichnis befindlichen Dateien und Verzeichnisse repräsentieren. |
| [GetFileSystemInfos](./getfilesysteminfos/)(const String\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [GetFileSystemInfos](./getfilesysteminfos/)(const String\&, SearchOption) | Durchsucht entweder das vom aktuellen Objekt repräsentierte Verzeichnis oder den gesamten Verzeichnisbaum, der im vom aktuellen Objekt repräsentierten Verzeichnis verwurzelt ist, nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [MoveTo](./moveto/)(const String\&) | Verschiebt das vom aktuellen Objekt dargestellte Verzeichnis und dessen gesamten Inhalt an den angegebenen Ort. |
| [ToString](./tostring/)() const override | Gibt einen String zurück, der den vom aktuellen Objekt dargestellten Pfad enthält. |
## Siehe auch

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
