---
title: "Clase Metered"
second_title: "Referencia de API de Aspose.PUB para .NET"
description: "Clase Aspose.Pub.Metered. Proporciona métodos para establecer la clave metered"
type: docs
weight: 190
url: /es/net/aspose.pub/metered/
---
## Metered class

Proporciona métodos para establecer la clave medida.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered/)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetMeteredKey](../../aspose.pub/metered/setmeteredkey/)(string, string) | Establece la clave pública y privada metered |
| static [GetConsumptionCredit](../../aspose.pub/metered/getconsumptioncredit/)() | Obtiene el crédito de consumo |
| static [GetConsumptionQuantity](../../aspose.pub/metered/getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo |

## Ejemplos

En este ejemplo, se intentará establecer la clave pública y privada metered

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

el archivo jar del componente:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ver también

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


