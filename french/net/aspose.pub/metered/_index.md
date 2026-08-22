---
title: "Classe Metered"
second_title: "Référence de l'API Aspose.PUB pour .NET"
description: "Classe Aspose.Pub.Metered. Fournit des méthodes pour définir la clé mesurée"
type: docs
weight: 190
url: /fr/net/aspose.pub/metered/
---
## Metered class

Fournit des méthodes pour définir la clé mesurée.

```csharp
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered/)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetMeteredKey](../../aspose.pub/metered/setmeteredkey/)(string, string) | Définit la clé publique et privée mesurée |
| static [GetConsumptionCredit](../../aspose.pub/metered/getconsumptioncredit/)() | Obtient le crédit de consommation |
| static [GetConsumptionQuantity](../../aspose.pub/metered/getconsumptionquantity/)() | Obtient la taille du fichier de consommation |

## Exemples

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée mesurée

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

le fichier jar du composant:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Voir aussi

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


