---
title: "Licens"
second_title: "Aspose.PUB för Java API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten."
type: docs
weight: 14
url: /sv/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Tillhandahåller metoder för att licensiera komponenten.

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för startsammanställningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

License license = new License();
license.setLicense("MyLicense.lic");
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [License()](#License--) | Initierar en ny instans av denna klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | Som standard använder vi standard jdk-säkerhet. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | Som standard använder vi standard jre-säkerhet. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licensierar komponenten. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licensierar komponenten. |
### License() {#License--}
```
public License()
```


Initierar en ny instans av denna klass.

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för startsammanställningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


Som standard använder vi standard jdk-säkerhet. Standardvärde == false. I vissa fall kan en anpassad java-miljö inte stödja erforderliga algoritmer, så vi kan föreslå att använda intern inbyggd FIPS-säkerhet.

**Returns:**
boolean - boolean‑värde
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


Som standard använder vi standard jre-säkerhet. Standardvärde == false. I vissa fall kan en anpassad java-miljö inte stödja erforderliga algoritmer, så vi kan föreslå att använda intern inbyggd FIPS-säkerhet. Observera också: Enligt JVM SecureRandom-algoritmen väntar /dev/random på en viss mängd \u201cnoise\u201d som genereras på värddatorn innan ett resultat returneras på vissa operativsystem. Biblioteket som används för slumpmässig talgenerering i Oracle\u2019s JVM förlitar sig som standard på /dev/random för UNIX-plattformar. Även om /dev/random är säkrare, rekommenderas det att använda /dev/urandom om standard JVM‑konfigurationen har fördröjningar, eller lägga till enheter som genererar entropi för /dev/random. Följande java‑alternativ kan hjälpa till att undvika fördröjningar och åsidosätta inställningen securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| internalFIPSSecurity | boolean | booleskt värde |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licensierar komponenten.

Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen för komponent-jar-filen.

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för startsammanställningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | java.lang.String | Kan vara ett fullständigt eller kort filnamn eller namnet på en inbäddad resurs. Använd en tom sträng för att växla till utvärderingsläge. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licensierar komponenten.

En ström som innehåller licensen.

Använd den här metoden för att läsa in en licens från en ström.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | license Ström |

