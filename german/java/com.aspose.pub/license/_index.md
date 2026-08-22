---
title: "Lizenz"
second_title: "Aspose.PUB for Java API-Referenz"
description: "Stellt Methoden bereit, um die Komponente zu lizenzieren."
type: docs
weight: 14
url: /de/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Stellt Methoden bereit, um die Komponente zu lizenzieren.

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

License license = new License();
license.setLicense("MyLicense.lic");
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) | Initialisiert eine neue Instanz dieser Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | Standardmäßig verwenden wir die standardmäßige JDK-Sicherheit. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | Standardmäßig verwenden wir die standardmäßige JRE-Sicherheit. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. |
### License() {#License--}
```
public License()
```


Initialisiert eine neue Instanz dieser Klasse.

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


Standardmäßig verwenden wir die standardmäßige JDK-Sicherheit. Standardwert == false. In einigen Fällen kann die angepasste Java-Umgebung die erforderlichen Algorithmen nicht unterstützen, daher können wir vorschlagen, die interne eingebaute FIPS-Sicherheit zu verwenden.

**Returns:**
boolean - boolean-Wert
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


Standardmäßig verwenden wir die standardmäßige JRE-Sicherheit. Standardwert == false. In einigen Fällen kann die angepasste Java-Umgebung die erforderlichen Algorithmen nicht unterstützen, daher können wir vorschlagen, die interne eingebaute FIPS-Sicherheit zu verwenden. Hinweis: Laut dem JVM SecureRandom-Algorithmus wartet /dev/random auf manchen Betriebssystemen, bis eine bestimmte Menge an \u201cnoise\u201d auf dem Host‑Computer erzeugt wurde, bevor ein Ergebnis zurückgegeben wird. Die Bibliothek, die für die Zufallszahlengenerierung in Oracles JVM verwendet wird, greift standardmäßig auf /dev/random für UNIX‑Plattformen zurück. Obwohl /dev/random sicherer ist, wird empfohlen, /dev/urandom zu verwenden, wenn die Standard‑JVM‑Konfiguration Verzögerungen verursacht, oder Geräte hinzuzufügen, die Entropie für /dev/random erzeugen. Die folgende Java‑Option kann helfen, Verzögerungen zu vermeiden und die Einstellung securerandom.source zu überschreiben. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| internalFIPSSecurity | boolean | boolescher Wert |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Lizenziert die Komponente.

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner der Komponenten‑Jar‑Datei.

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | java.lang.String | Kann ein voller oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie einen leeren String, um in den Evaluierungsmodus zu wechseln. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Lizenziert die Komponente.

Ein Stream, der die Lizenz enthält.

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Lizenz‑Stream |

