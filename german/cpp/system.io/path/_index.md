---
title: "System::IO::Path Klasse"
linktitle: "Pfad"
second_title: "Aspose.PUB für C++"
description: "System::IO::Path Klasse. Stellt Methoden zum Manipulieren von Pfaden bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon in C++ erstellen."
type: docs
weight: 1900
url: /de/cpp/system.io/path/
---
## Path class


Bietet Methoden zur Pfadmanipulation. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon erstellen.

```cpp
class Path
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [ChangeExtension](./changeextension/)(const String\&, const String\&) | Ändert die Erweiterung im angegebenen Dateipfad. |
| static [CheckPath](./checkpath/)(const String\&, const String\&, bool) | Ermittelt, ob der angegebene Pfad gültig ist, indem geprüft wird, ob er ungültige Zeichen enthält. Es wird eine Ausnahme ausgelöst, wenn der Pfad ungültige Zeichen enthält. |
| static [Combine](./combine/)(const ArrayPtr\<String\>\&) | Kombiniert die angegebenen Pfadsegmente zu einem einzigen Pfad und fügt bei Bedarf Verzeichnistrennzeichen zwischen den Segmenten ein. |
| static [Combine](./combine/)(const String\&, const String\&) | Kombiniert zwei angegebene Pfadsegmente zu einem einzigen Pfad und fügt bei Bedarf ein Verzeichnistrennzeichen zwischen den Segmenten ein. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&) | Kombiniert drei angegebene Pfadsegmente zu einem einzigen Pfad und fügt bei Bedarf Verzeichnistrennzeichen zwischen den Segmenten ein. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&, const String\&) | Kombiniert vier angegebene Pfadsegmente zu einem einzigen Pfad und fügt bei Bedarf Trennzeichen für Verzeichnisse zwischen den Segmenten ein. |
| static [GetDirectoryName](./getdirectoryname/)(const String\&) | Gibt den Namen des Verzeichnisses zurück, auf das der angegebene Pfad verweist. |
| static [GetExtension](./getextension/)(const String\&) | Gibt die Erweiterung der Datei zurück, auf die der angegebene Pfad verweist. |
| static [GetFileName](./getfilename/)(const String\&) | Gibt den Namen der Datei zurück, auf die der angegebene Pfad verweist. |
| static [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const String\&) | Gibt den Namen der Datei ohne Erweiterung zurück, auf die der angegebene Pfad verweist. |
| static [GetFullPath](./getfullpath/)(const String\&) | Konvertiert den angegebenen Pfad in einen absoluten Pfad. |
| static [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Gibt ein Array zurück, das Zeichen enthält, die in Dateinamen nicht erlaubt sind. |
| static [GetInvalidPathChars](./getinvalidpathchars/)() | Gibt ein Array zurück, das Zeichen enthält, die in Pfadnamen nicht erlaubt sind. |
| static [GetPathRoot](./getpathroot/)(const String\&) | Gibt das Stammverzeichnis des angegebenen Pfads zurück. |
| static [GetRandomFileName](./getrandomfilename/)() | Gibt einen zufällig generierten Dateinamen zurück. |
| static [GetTempFileName_](./gettempfilename_/)() | Erstellt eine neue Datei mit einem eindeutigen Namen und gibt den vollständigen Pfad dazu zurück. |
| static [GetTempFileNameSafe](./gettempfilenamesafe/)() | Erstellt eine neue Datei mit einem eindeutigen Namen und gibt den vollständigen Pfad dazu zurück. Ist ein Synonym der Methode [GetTempFileName_()](./gettempfilename_/). |
| static [GetTempPath](./gettemppath/)() | Gibt den Pfad des temporären Verzeichnisses des aktuellen Benutzers zurück. |
| static [HasExtension](./hasextension/)(const String\&) | Bestimmt, ob der angegebene Pfad auf eine Datei mit Erweiterung verweist. |
| static [IsPathRooted](./ispathrooted/)(const String\&) | Bestimmt, ob der angegebene Pfad eine Wurzel enthält. |
| static [NormalizePath](./normalizepath/)(const String\&) | Normalisiert den angegebenen Pfad. |
| static [ToBoost](./toboost/)(const String\&) | Gibt eine Instanz der Klasse boost::filesystem::path zurück, die den angegebenen Pfad darstellt. |
| static [ToString](./tostring/)(const boost::filesystem::path\&) | Gibt eine String-Darstellung des angegebenen Boost-Pfadobjekts zurück. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Ein alternatives Zeichen, das verwendet wird, um Verzeichnisebenen in einem Pfad zu trennen. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Ein Zeichen, das verwendet wird, um Verzeichnisebenen in einem Pfad zu trennen. |
| static [PathSeparator](./pathseparator/) | Ein Trennzeichen, das verwendet wird, um Pfadzeichenfolgen in Umgebungsvariablen zu trennen. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Ein Laufwerks‑Trennzeichen. |
## Hinweise



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Erstelle einen zufälligen Dateinamen.
  auto filename = Path::GetRandomFileName();

  // Gib Informationen über den Dateinamen aus.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## Siehe auch

* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
