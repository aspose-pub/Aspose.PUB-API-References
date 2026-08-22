---
title: "License.SetLicense"
second_title: "Aspose.PUB für .NET API-Referenz"
description: "License-Methode. Lizenziert die Komponente"
type: docs
weight: 20
url: /de/net/aspose.pub/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | String | Kann ein voller oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie eine leere Zeichenfolge, um in den Evaluierungsmodus zu wechseln. |

## Hinweise

Versucht, die Lizenz an den folgenden Speicherorten zu finden:

1. Expliziter Pfad.

2. Der Ordner, der die Aspose‑Komponenten‑Assembly enthält.

3. Der Ordner, der die Aufruf‑Assembly des Clients enthält.

4. Der Ordner, der die Entry‑(Startup‑)Assembly enthält.

5. Eine eingebettete Ressource in der Aufruf‑Assembly des Clients.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der Aufruf‑Assembly des Clients.

2. Der Ordner, der die Aspose‑Komponenten‑JAR‑Datei enthält.

3. Der Ordner, der die Aufruf‑JAR‑Datei des Clients enthält.

### Siehe auch

* class [License](../)
* namespace [Aspose.Pub](../../license/)
* assembly [Aspose.PUB](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datenstrom | Stream | Ein Datenstrom, der die Lizenz enthält. |

## Hinweise

Verwenden Sie diese Methode, um eine Lizenz aus einem Datenstrom zu laden.

### Siehe auch

* class [License](../)
* namespace [Aspose.Pub](../../license/)
* assembly [Aspose.PUB](../../../)


