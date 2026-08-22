---
title: "System::Xml::XmlWriterSettings sınıfı"
linktitle: "XmlWriterSettings"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlWriterSettings sınıfı. C++'da XmlWriter::Create yöntemiyle oluşturulan XmlWriter nesnesi üzerinde desteklenecek bir dizi özelliği belirtir."
type: docs
weight: 4500
url: /tr/cpp/system.xml/xmlwritersettings/
---
## XmlWriterSettings class


[XmlWriter](../xmlwriter/) nesnesi, [XmlWriter::Create](../xmlwriter/create/) yöntemiyle oluşturulduğunda desteklenecek bir dizi özelliği belirtir.

```cpp
class XmlWriterSettings : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() | [XmlWriterSettings](./) örneğinin bir kopyasını oluşturur. |
| [get_CheckCharacters](./get_checkcharacters/)() | XML yazarının, belgedeki tüm karakterlerin W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) belgesinin "2.2 Characters" bölümüne uygun olup olmadığını kontrol etmesi gerekip gerekmediğini gösteren bir değer döndürür. |
| [get_CloseOutput](./get_closeoutput/)() | [XmlWriter](../xmlwriter/), [XmlWriter::Close](../xmlwriter/close/) yöntemi çağrıldığında temel akışı veya TextWriter'ı da kapatmalı mı olduğunu gösteren bir değer döndürür. |
| [get_ConformanceLevel](./get_conformancelevel/)() | XML yazarının XML çıktısını kontrol ettiği uyumluluk seviyesini döndürür. |
| [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | [XmlWriter](../xmlwriter/), URI özniteliklerini kaçırmaması gerektiğini gösteren bir değer döndürür. |
| [get_Encoding](./get_encoding/)() | Kullanılacak metin kodlaması türünü döndürür. |
| [get_Indent](./get_indent/)() | Elemanları girintileme durumunu gösteren bir değeri döndürür. |
| [get_IndentChars](./get_indentchars/)() | Girintileme sırasında kullanılacak karakter dizisini döndürür. Bu ayar, [XmlWriterSettings::set_Indent](./set_indent/) değeri **true** olarak ayarlandığında kullanılır. |
| [get_NamespaceHandling](./get_namespacehandling/)() | XML içeriği yazılırken [XmlWriter](../xmlwriter/)'ın yinelenen ad alanı bildirimlerini kaldırıp kaldırmayacağını gösteren bir değeri döndürür. Varsayılan davranış, yazarın ad alanı çözücüsünde bulunan tüm ad alanı bildirimlerini çıkarmaktır. |
| [get_NewLineChars](./get_newlinechars/)() | Satır sonları için kullanılacak karakter dizisini döndürür. |
| [get_NewLineHandling](./get_newlinehandling/)() | Çıktıda satır sonlarını normalleştirip normalleştirmeyeceğini gösteren bir değeri döndürür. |
| [get_NewLineOnAttributes](./get_newlineonattributes/)() | Öznitelikleri yeni bir satıra yazıp yazmayacağını gösteren bir değeri döndürür. |
| [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Bir XML bildirimini atlayıp atlamayacağını gösteren bir değeri döndürür. |
| [get_OutputMethod](./get_outputmethod/)() | [XmlWriter](../xmlwriter/) çıktısını serileştirmek için kullanılan yöntemi döndürür. |
| [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | [XmlWriter](../xmlwriter/), [XmlWriter::Close](../xmlwriter/close/) yöntemi çağrıldığında kapatılmamış tüm eleman etiketlerine kapanış etiketleri ekleyip eklemeyeceğini gösteren bir değeri döndürür. |
| [Reset](./reset/)() | Ayarlar sınıfının üyelerini varsayılan değerlerine sıfırlar. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | XML yazarının, belgedeki tüm karakterlerin W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) "2.2 Characters" bölümüne uygun olup olmadığını kontrol edip kontrol etmeyeceğini gösteren bir değeri ayarlar. |
| [set_CloseOutput](./set_closeoutput/)(bool) | [XmlWriter](../xmlwriter/), [XmlWriter::Close](../xmlwriter/close/) yöntemi çağrıldığında temel akışı veya TextWriter'ı da kapatıp kapatmayacağını gösteren bir değeri ayarlar. |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | XML yazarının XML çıktısını kontrol ettiği uyumluluk seviyesini ayarlar. |
| [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(bool) | [XmlWriter](../xmlwriter/)'ın URI özniteliklerini kaçırmayacağını gösteren bir değeri ayarlar. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Kullanılacak metin kodlaması türünü ayarlar. |
| [set_Indent](./set_indent/)(bool) | Elemanları girintileme durumunu gösteren bir değeri ayarlar. |
| [set_IndentChars](./set_indentchars/)(const String\&) | Girintileme sırasında kullanılacak karakter dizisini ayarlar. Bu ayar, [XmlWriterSettings::set_Indent](./set_indent/) değeri **true** olarak ayarlandığında kullanılır. |
| [set_NamespaceHandling](./set_namespacehandling/)(System::Xml::NamespaceHandling) | XML içeriği yazılırken [XmlWriter](../xmlwriter/)'ın yinelenen ad alanı bildirimlerini kaldırıp kaldırmayacağını gösteren bir değeri ayarlar. Varsayılan davranış, yazarın ad alanı çözücüsünde bulunan tüm ad alanı bildirimlerini çıkarmaktır. |
| [set_NewLineChars](./set_newlinechars/)(const String\&) | Satır sonları için kullanılacak karakter dizisini ayarlar. |
| [set_NewLineHandling](./set_newlinehandling/)(System::Xml::NewLineHandling) | Çıktıda satır sonlarını normalleştirip normalleştirmeyeceğini gösteren bir değeri ayarlar. |
| [set_NewLineOnAttributes](./set_newlineonattributes/)(bool) | Öznitelikleri yeni bir satıra yazıp yazmayacağını gösteren bir değeri ayarlar. |
| [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(bool) | Bir XML bildirimini atlayıp atlamayacağını gösteren bir değeri ayarlar. |
| [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(bool) | [XmlWriter](../xmlwriter/), [XmlWriter::Close](../xmlwriter/close/) yöntemi çağrıldığında kapatılmamış tüm eleman etiketlerine kapanış etiketleri ekleyip eklemeyeceğini gösteren bir değeri ayarlar. |
| [XmlWriterSettings](./xmlwritersettings/)() | [XmlWriterSettings](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
