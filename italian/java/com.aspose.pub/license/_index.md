---
title: "Licenza"
second_title: "Riferimento API di Aspose.PUB per Java"
description: "Fornisce metodi per licenziare il componente."
type: docs
weight: 14
url: /it/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fornisce metodi per licenziare il componente.

In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.

License license = new License();
license.setLicense("MyLicense.lic");
## Costruttori

| Constructor | Descrizione |
| --- | --- |
| [License()](#License--) | Inizializza una nuova istanza di questa classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | Per impostazione predefinita, utilizziamo la sicurezza jdk predefinita. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | Per impostazione predefinita, utilizziamo la sicurezza jre predefinita. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenzia il componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenzia il componente. |
### License() {#License--}
```
public License()
```


Inizializza una nuova istanza di questa classe.

In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


Per impostazione predefinita utilizziamo la sicurezza jdk predefinita. Valore predefinito == false. In alcuni casi l'ambiente java personalizzato non può supportare gli algoritmi richiesti, quindi possiamo suggerire di utilizzare la sicurezza FIPS integrata interna.

**Returns:**
boolean - valore boolean
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


Per impostazione predefinita, utilizziamo la sicurezza jre predefinita. Valore predefinito == false. In alcuni casi l'ambiente java personalizzato non può supportare gli algoritmi richiesti, quindi possiamo suggerire di utilizzare la sicurezza FIPS integrata interna. Nota anche: secondo l'algoritmo JVM SecureRandom, su alcuni sistemi operativi /dev/random attende che venga generata una certa quantità di \u201cnoise\u201d sulla macchina host prima di restituire un risultato. La libreria usata per la generazione di numeri casuali nella JVM di Oracle\u2019s si basa su /dev/random per impostazione predefinita sulle piattaforme UNIX. Sebbene /dev/random sia più sicuro, è consigliato utilizzare /dev/urandom se la configurazione predefinita della JVM presenta ritardi, oppure aggiungere dispositivi che generano entropia per /dev/random. La seguente opzione java può aiutare a evitare ritardi e sovrascrivere l'impostazione securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| internalFIPSSecurity | boolean | valore booleano |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licenzia il componente.

Cerca di trovare la licenza nei seguenti percorsi:

1. Percorso esplicito.

2. La cartella del file jar del componente.

In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | java.lang.String | Può essere un nome file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licenzia il componente.

Uno stream che contiene la licenza.

Utilizza questo metodo per caricare una licenza da uno stream.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Flusso di licenza |

