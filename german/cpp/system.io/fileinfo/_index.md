---
title: "System::IO::FileInfo Klasse"
linktitle: "FileInfo"
second_title: "Aspose.PUB für C++"
description: "System::IO::FileInfo Klasse. Stellt einen Pfad zu einer Datei und die von diesem Pfad referenzierte Datei dar und bietet Methoden zu deren Manipulation. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1400
url: /de/cpp/system.io/fileinfo/
---
## FileInfo class


Stellt einen Pfad zu einer Datei und die von diesem Pfad referenzierte Datei dar und bietet Methoden zu deren Manipulation. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AppendText](./appendtext/)() | Öffnet eine Datei, die durch das aktuelle Objekt repräsentiert wird, zum Schreiben von Text mit UTF-8-Kodierung, im 'Append'-Modus ohne Freigabe. |
| [CopyTo](./copyto/)(const String\&) | Kopiert die durch das aktuelle Objekt repräsentierte Datei an den angegebenen Ort. Wenn die Zieldatei bereits existiert, schlägt das Kopieren fehl. |
| [CopyTo](./copyto/)(const String\&, bool) | Kopiert die durch das aktuelle Objekt repräsentierte Datei an den angegebenen Ort. Ein Parameter gibt an, ob die vorhandene Zieldatei überschrieben werden soll. |
| [Create](./create/)() | Erstellt eine Datei am durch den Pfad des aktuellen Objekts angegebenen Ort und öffnet sie zum Lesen und Schreiben, im Truncate-Modus und ohne Freigabe. |
| [CreateText](./createtext/)() | Erstellt eine Datei am durch den Pfad des aktuellen Objekts angegebenen Ort und öffnet sie zum Schreiben von Text mit UTF-8-Kodierung ohne Freigabe. |
| [Decrypt](./decrypt/)() | NICHT IMPLEMENTIERT. |
| [Delete](./delete/)() override | Entfernt die durch das aktuelle Objekt repräsentierte Datei. |
| [Encrypt](./encrypt/)() | NICHT IMPLEMENTIERT. |
| [FileInfo](./fileinfo/)(const String\&) | Konstruiert eine neue Instanz der Klasse [FileInfo](./), die die angegebene Datei repräsentiert. |
| [get_Directory](./get_directory/)() | Gibt ein [DirectoryInfo](../directoryinfo/)-Objekt zurück, das ein Verzeichnis repräsentiert, in dem die durch das aktuelle Objekt dargestellte Datei gespeichert ist. |
| [get_DirectoryName](./get_directoryname/)() | Gibt den vollständigen Namen des Verzeichnisses zurück, in dem die durch das aktuelle Objekt dargestellte Datei gespeichert ist. |
| [get_Exists](./get_exists/)() override | Gibt einen Wert zurück, der angibt, ob die Datei existiert. |
| [get_IsReadOnly](./get_isreadonly/)() | Gibt einen Wert zurück, der angibt, ob das ReadOnly-Attribut gesetzt ist. |
| [get_Length](./get_length/)() | Gibt die Größe der Datei in Bytes zurück. |
| [get_Name](./get_name/)() override | Gibt den Namen der Datei zurück. |
| [MoveTo](./moveto/)(const String\&) | Verschiebt die durch das aktuelle Objekt dargestellte Datei an den angegebenen Ort. |
| [Open](./open/)(FileMode) | Öffnet die durch das aktuelle Objekt dargestellte Datei im angegebenen Modus zum Lesen und Schreiben und ohne Freigabe. |
| [Open](./open/)(FileMode, FileAccess) | Öffnet die durch das aktuelle Objekt dargestellte Datei im angegebenen Modus, mit dem angegebenen Zugriffstyp und ohne Freigabe. |
| [Open](./open/)(FileMode, FileAccess, FileShare) | Öffnet die durch das aktuelle Objekt dargestellte Datei im angegebenen Modus, mit dem angegebenen Zugriffstyp und der Freigabeoption. |
| [OpenRead](./openread/)() | Öffnet eine durch das aktuelle Objekt dargestellte Datei nur zum Lesen, im 'Open'-Modus mit gemeinsamem Lesezugriff. |
| [OpenText](./opentext/)() | Öffnet die vorhandene Datei am durch den Pfad des aktuellen Objekts angegebenen Ort zum Lesen von Text mit UTF-8-Kodierung ohne Freigabe. |
| [OpenWrite](./openwrite/)() | Öffnet eine durch das aktuelle Objekt dargestellte Datei nur zum Schreiben, im 'OpenOrCreate'-Modus ohne Freigabe. |
| [Replace](./replace/)(const String\&, const String\&) | Ersetzt den Inhalt einer angegebenen Zieldatei durch die durch das aktuelle [FileInfo](./)-Objekt dargestellte Datei und erstellt ein Backup der ersetzten Datei. |
| [Replace](./replace/)(const String\&, const String\&, bool) | Ersetzt den Inhalt einer angegebenen Zieldatei durch die durch das aktuelle [FileInfo](./)-Objekt dargestellte Datei und erstellt ein Backup der ersetzten Datei. |
| [set_IsReadOnly](./set_isreadonly/)(bool) | Setzt oder entfernt das ReadOnly-Attribut der Datei. |
| [ToString](./tostring/)() const override | Gibt einen Pfad zurück, der durch das aktuelle Objekt repräsentiert wird. |
## Siehe auch

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
