---
title: "System::OperatingSystem Klasse"
linktitle: "OperatingSystem"
second_title: "Aspose.PUB für C++"
description: "System::OperatingSystem Klasse. Stellt ein bestimmtes Betriebssystem dar und liefert Informationen darüber. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 5100
url: /de/cpp/system/operatingsystem/
---
## OperatingSystem class


Stellt ein bestimmtes Betriebssystem dar und liefert Informationen darüber. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class OperatingSystem
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Platform](./get_platform/)() const | Gibt die Plattformkennung des vom aktuellen Objekt dargestellten Betriebssystems zurück. |
| [get_ServicePack](./get_servicepack/)() const | Gibt den Namen des Service Packs des vom aktuellen Objekt dargestellten Betriebssystems zurück. |
| [get_Version](./get_version/)() const | Gibt eine konstante Referenz auf ein [Version](../version/)‑Objekt zurück, das die Version des vom aktuellen Objekt dargestellten Betriebssystems repräsentiert. |
| [get_VersionString](./get_versionstring/)() const | Gibt die Zeichenkettenrepräsentation der Version des vom aktuellen Objekt dargestellten Betriebssystems zurück. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&) | Konstruiert eine Instanz, die ein Betriebssystem darstellt, das durch eine bestimmte Plattform‑ID und Version angegeben ist. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&, const String\&) | Konstruiert eine Instanz, die ein Betriebssystem darstellt, das durch eine bestimmte Plattform‑ID, Version und Service Pack angegeben ist. |
| [ToString](./tostring/)() const | Gibt die Zeichenkettenrepräsentation der Version des vom aktuellen Objekt dargestellten Betriebssystems zurück. |
## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
