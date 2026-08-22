---
title: "License.SetLicense"
second_title: "Riferimento API di Aspose.PUB per .NET"
description: "License metodo. Concede la licenza al componente"
type: docs
weight: 20
url: /it/net/aspose.pub/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licenzia il componente.

```csharp
public void SetLicense(string licenseName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | String | Può essere un nome file completo o abbreviato o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

## Osservazioni

Cerca di trovare la licenza nelle seguenti posizioni:

1. Percorso esplicito.

2. La cartella che contiene l'assembly del componente Aspose.

3. La cartella che contiene l'assembly chiamante del cliente.

4. La cartella che contiene l'assembly di ingresso (avvio).

5. Una risorsa incorporata nell'assembly chiamante del cliente.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Percorso esplicito.

2. Una risorsa incorporata nell'assembly chiamante del cliente.

2. La cartella che contiene il file JAR del componente Aspose.

3. La cartella che contiene il file JAR chiamante del cliente.

### Vedi anche

* class [License](../)
* namespace [Aspose.Pub](../../license/)
* assembly [Aspose.PUB](../../../)

---

## SetLicense(Stream) {#setlicense}

Licenzia il componente.

```csharp
public void SetLicense(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Un flusso che contiene la licenza. |

## Osservazioni

Usa questo metodo per caricare una licenza da un flusso.

### Vedi anche

* class [License](../)
* namespace [Aspose.Pub](../../license/)
* assembly [Aspose.PUB](../../../)


