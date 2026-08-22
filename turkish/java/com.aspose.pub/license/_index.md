---
title: "Lisans"
second_title: "Aspose.PUB for Java API Referansı"
description: "Bileşeni lisanslamak için yöntemler sağlar."
type: docs
weight: 14
url: /tr/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Bileşeni lisanslamak için yöntemler sağlar.

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.

License license = new License();
license.setLicense("MyLicense.lic");
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License()](#License--) | Bu sınıfın yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | Varsayılan olarak varsayılan jdk güvenliğini kullanıyoruz. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | Varsayılan olarak varsayılan jre güvenliğini kullanıyoruz. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Bileşeni lisanslar. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Bileşeni lisanslar. |
### License() {#License--}
```
public License()
```


Bu sınıfın yeni bir örneğini başlatır.

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


Varsayılan olarak varsayılan jdk güvenliğini kullanıyoruz. Varsayılan değer == false. Bazı durumlarda özelleştirilmiş java ortamı gerekli algoritmaları destekleyemeyebilir, bu yüzden dahili yerleşik FIPS güvenliğini kullanmayı önerebiliriz.

**Returns:**
boolean - boolean değeri
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


Varsayılan olarak varsayılan jre güvenliğini kullanıyoruz. Varsayılan değer == false. Bazı durumlarda özelleştirilmiş java ortamı gerekli algoritmaları destekleyemeyebilir, bu yüzden dahili yerleşik FIPS güvenliğini kullanmayı önerebiliriz. Ayrıca şunu da unutmayın: JVM SecureRandom algoritmasına göre bazı işletim sistemlerinde /dev/random, sonuç döndürmeden önce ana makinede belirli bir miktarda \"gürültü\" üretilmesini bekler. Oracle’ın JVM’sinde rastgele sayı üretimi için kullanılan kütüphane, UNIX platformları için varsayılan olarak /dev/random’a dayanır. /dev/random daha güvenli olsa da, varsayılan JVM yapılandırması gecikmelere neden oluyorsa /dev/urandom kullanılması önerilir veya /dev/random için entropi üreten aygıtlar eklenir. Aşağıdaki java seçeneği gecikmeleri önlemeye ve securerandom.source ayarını geçersiz kılmaya yardımcı olabilir. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| internalFIPSSecurity | boolean | boolean değer |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Bileşeni lisanslar.

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. Bileşen jar dosyasının klasörü.

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseName | java.lang.String | Tam veya kısa bir dosya adı ya da gömülü kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Bileşeni lisanslar.

Lisansı içeren bir akış.

Bu yöntemi bir akıştan lisans yüklemek için kullanın.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | lisans Akışı |

