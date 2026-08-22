---
title: "Classe Metered"
second_title: "Riferimento API di Aspose.PUB per .NET"
description: "Classe Aspose.Pub.Metered. Fornisce metodi per impostare la chiave a consumo"
type: docs
weight: 190
url: /it/net/aspose.pub/metered/
---
## Metered class

Fornisce metodi per impostare la chiave a consumo.

```csharp
public class Metered
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Metered](metered/)() | Inizializza una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetMeteredKey](../../aspose.pub/metered/setmeteredkey/)(string, string) | Imposta la chiave pubblica e privata a consumo |
| static [GetConsumptionCredit](../../aspose.pub/metered/getconsumptioncredit/)() | Ottiene il credito di consumo |
| static [GetConsumptionQuantity](../../aspose.pub/metered/getconsumptionquantity/)() | Ottiene la dimensione del file di consumo |

## Esempi

In questo esempio, verrà tentato di impostare la chiave pubblica e privata a consumo

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

il file JAR del componente:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Vedi anche

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


