---
title: "Licence"
second_title: "Référence API d'Aspose.PUB pour Java"
description: "Fournit des méthodes pour licencier le composant."
type: docs
weight: 14
url: /fr/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fournit des méthodes pour licencier le composant.

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

License license = new License();
license.setLicense("MyLicense.lic");
## Constructeurs

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initialise une nouvelle instance de cette classe. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | Par défaut, nous utilisons la sécurité JDK par défaut. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | Par défaut, nous utilisons la sécurité JRE par défaut. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licencie le composant. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencie le composant. |
### License() {#License--}
```
public License()
```


Initialise une nouvelle instance de cette classe.

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


Par défaut, nous utilisons la sécurité JDK par défaut. Valeur par défaut == false. Dans certains cas, un environnement Java personnalisé ne peut pas prendre en charge les algorithmes requis, nous pouvons donc suggérer d'utiliser la sécurité FIPS interne intégrée.

**Returns:**
boolean - valeur boolean
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


Par défaut, nous utilisons la sécurité JRE par défaut. Valeur par défaut == false. Dans certains cas, un environnement Java personnalisé ne peut pas prendre en charge les algorithmes requis, nous pouvons donc suggérer d'utiliser la sécurité FIPS interne intégrée. Notez également : Selon l'algorithme JVM SecureRandom sur certains systèmes d'exploitation, /dev/random attend qu'une certaine quantité de \u201cnoise\u201d soit générée sur la machine hôte avant de renvoyer un résultat. La bibliothèque utilisée pour la génération de nombres aléatoires dans la JVM d'Oracle\u2019s repose sur /dev/random par défaut pour les plateformes UNIX. Bien que /dev/random soit plus sécurisé, il\u2019s recommandé d'utiliser /dev/urandom si la configuration JVM par défaut entraîne des délais, ou d'ajouter des dispositifs qui génèrent de l'entropie pour /dev/random. L'option java suivante peut aider à éviter les délais et à remplacer le paramètre securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| internalFIPSSecurity | booléen | valeur booléenne |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licencie le composant.

Essaye de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier du fichier jar du composant.

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Peut être un nom de fichier complet ou court ou le nom d'une ressource intégrée Utilisez une chaîne vide pour passer en mode d'évaluation |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licencie le composant.

Un flux contenant la licence.

Utilisez cette méthode pour charger une licence à partir d'un flux.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | license Flux |

