---
title: "Klasse Metered"
second_title: "Aspose.PUB für .NET API-Referenz"
description: "Aspose.Pub.Metered Klasse. Stellt Methoden zum Festlegen des Metered-Schlüssels bereit"
type: docs
weight: 190
url: /de/net/aspose.pub/metered/
---
## Metered class

Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../aspose.pub/metered/setmeteredkey/)(string, string) | Setzt öffentlichen und privaten Metered-Schlüssel |
| static [GetConsumptionCredit](../../aspose.pub/metered/getconsumptioncredit/)() | Liefert Verbrauchsguthaben |
| static [GetConsumptionQuantity](../../aspose.pub/metered/getconsumptionquantity/)() | Liefert Verbrauchsdateigröße |

## Beispiele

In diesem Beispiel wird versucht, den öffentlichen und privaten Metered-Schlüssel festzulegen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

die Komponenten‑JAR‑Datei:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Siehe auch

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


