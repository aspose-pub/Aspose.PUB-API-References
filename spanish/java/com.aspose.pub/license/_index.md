---
title: "Licencia"
second_title: "Referencia de API de Aspose.PUB para Java"
description: "Proporciona métodos para licenciar el componente."
type: docs
weight: 14
url: /es/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Proporciona métodos para licenciar el componente.

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.

License license = new License();
license.setLicense("MyLicense.lic");
## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License--) | Inicializa una nueva instancia de esta clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | Por defecto usamos la seguridad predeterminada del jdk. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | Por defecto, estamos usando la seguridad predeterminada del jre. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licencia el componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencia el componente. |
### License() {#License--}
```
public License()
```


Inicializa una nueva instancia de esta clase.

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


Por defecto usamos la seguridad predeterminada del jdk. Valor predeterminado == false. En algunos casos, el entorno java personalizado no puede soportar los algoritmos requeridos, por lo que podemos sugerir usar la seguridad FIPS interna incorporada.

**Returns:**
boolean - valor boolean
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


Por defecto, estamos usando la seguridad predeterminada del jre. Valor predeterminado == false. En algunos casos, el entorno java personalizado no puede soportar los algoritmos requeridos, por lo que podemos sugerir usar la seguridad FIPS interna incorporada. Observe también: Según el algoritmo JVM SecureRandom en algunos sistemas operativos, /dev/random espera que se genere una cierta cantidad de \u201cnoise\u201d en la máquina host antes de devolver un resultado. La biblioteca utilizada para la generación de números aleatorios en la JVM de Oracle\u2019s depende de /dev/random por defecto en plataformas UNIX. Aunque /dev/random es más seguro, se recomienda usar /dev/urandom si la configuración predeterminada de la JVM tiene retrasos, o añadir dispositivos que generen entropía para /dev/random. La siguiente opción de java puede ayudar a evitar retrasos y sobrescribir la configuración securerandom.source setting. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| internalFIPSSecurity | boolean | valor booleano |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licencia el componente.

Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta del archivo jar del componente.

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | java.lang.String | Puede ser un nombre de archivo completo o corto o el nombre de un recurso incrustado. Use una cadena vacía para cambiar al modo de evaluación. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licencia el componente.

Un flujo que contiene la licencia.

Utilice este método para cargar una licencia desde un flujo.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de licencia |

