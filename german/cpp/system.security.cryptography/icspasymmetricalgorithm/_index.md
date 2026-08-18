---
title: "System::Security::Cryptography::ICspAsymmetricAlgorithm Klasse"
linktitle: "ICspAsymmetricAlgorithm"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::ICspAsymmetricAlgorithm Klasse. Basisklasse für asymmetrische Algorithmen. Objekte dieser Klasse dürfen nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2100
url: /de/cpp/system.security.cryptography/icspasymmetricalgorithm/
---
## ICspAsymmetricAlgorithm class


Basisklasse für asymmetrische Algorithmen. Objekte dieser Klasse dürfen nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ICspAsymmetricAlgorithm : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [ExportCspBlob](./exportcspblob/)(bool) | Exportiert ein Blob mit Schlüsselinformationen. |
| virtual [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() | RTTI-Informationen. |
| virtual [ImportCspBlob](./importcspblob/)(ByteArrayPtr) | Importiert Schlüsselinformationen aus einem Daten-Blob. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PUB for C++](../../)
