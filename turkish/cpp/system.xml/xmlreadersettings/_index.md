---
title: "System::Xml::XmlReaderSettings sınıfı"
linktitle: "XmlReaderSettings"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlReaderSettings sınıfı. C++'da XmlReader::Create yöntemiyle oluşturulan XmlReader nesnesi üzerinde desteklenecek bir dizi özelliği belirtir."
type: docs
weight: 3400
url: /tr/cpp/system.xml/xmlreadersettings/
---
## XmlReaderSettings class


[XmlReader](../xmlreader/) nesnesi, [XmlReader::Create](../xmlreader/create/) yöntemiyle oluşturulduğunda desteklenecek bir dizi özelliği belirtir.

```cpp
class XmlReaderSettings : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CheckReadOnly](./checkreadonly/)(const String\&) |  |
| [Clone](./clone/)() | [XmlReaderSettings](./) örneğinin bir kopyasını oluşturur. |
| [get_CheckCharacters](./get_checkcharacters/)() | Karakter denetimi yapılıp yapılmayacağını gösteren bir değer döndürür. |
| [get_CloseInput](./get_closeinput/)() | Okuyucu kapatıldığında temel akışın veya TextReader'ın kapatılıp kapatılmayacağını gösteren bir değer döndürür. |
| [get_ConformanceLevel](./get_conformancelevel/)() | [XmlReader](../xmlreader/) nesnesinin uyacağı uyumluluk seviyesini döndürür. |
| [get_DtdProcessing](./get_dtdprocessing/)() | DTD işleme şeklini belirleyen bir değer döndürür. |
| [get_IgnoreComments](./get_ignorecomments/)() | Yorumların göz ardı edilip edilmeyeceğini gösteren bir değer döndürür. |
| [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | İşlem talimatlarının göz ardı edilip edilmeyeceğini gösteren bir değer döndürür. |
| [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Önemsiz boşlukların göz ardı edilip edilmeyeceğini gösteren bir değer döndürür. |
| [get_LineNumberOffset](./get_linenumberoffset/)() | [XmlReader](../xmlreader/) nesnesinin satır numarası ofsetini döndürür. |
| [get_LinePositionOffset](./get_linepositionoffset/)() | [XmlReader](../xmlreader/) nesnesinin satır konumu ofsetini döndürür. |
| [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Varlıkların genişletilmesi sonucunda bir belgede izin verilen azami karakter sayısını gösteren bir değer döndürür. |
| [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Bir XML belgesinde izin verilen azami karakter sayısını gösteren bir değer döndürür. Sıfır (0) değeri, XML belgesinin boyutu için sınırlama olmadığını ifade eder. Sıfır olmayan bir değer, azami boyutu karakter cinsinden belirtir. |
| [get_NameTable](./get_nametable/)() | Atomize edilmiş dize karşılaştırmaları için kullanılan [XmlNameTable](../xmlnametable/) nesnesini döndürür. |
| [get_ProhibitDtd](./get_prohibitdtd/)() | Belge türü tanımının (DTD) işlenmesini yasaklayıp yasaklamayacağını gösteren bir değer döndürür. |
| [get_Schemas](./get_schemas/)() | Şema doğrulaması yapılırken kullanılacak XmlSchemaSet nesnesini döndürür. |
| [get_ValidationFlags](./get_validationflags/)() | Şema doğrulama ayarlarını gösteren bir değer döndürür. Bu ayar, şemaları doğrulayan [XmlReader](../xmlreader/) nesnelerine uygulanır ([XmlReaderSettings::get_ValidationType](./get_validationtype/) değeri [ValidationType::Schema](../validationtype/) olduğunda). |
| [get_ValidationType](./get_validationtype/)() | Okuma sırasında [XmlReader](../xmlreader/) nesnesinin doğrulama yapıp yapmayacağını veya tip ataması yapıp yapmayacağını gösteren bir değer döndürür. |
| [Reset](./reset/)() | Ayarlar sınıfının üyelerini varsayılan değerlerine sıfırlar. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Karakter denetimi yapılıp yapılmayacağını gösteren bir değeri ayarlar. |
| [set_CloseInput](./set_closeinput/)(bool) | Okuyucu kapatıldığında temel akışın veya TextReader'ın kapatılıp kapatılmayacağını belirten bir değer ayarlar. |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | [XmlReader](../xmlreader/) uyacağı uyumluluk seviyesini ayarlar. |
| [set_DtdProcessing](./set_dtdprocessing/)(System::Xml::DtdProcessing) | DTD'lerin işlenmesini belirleyen bir değer ayarlar. |
| [set_IgnoreComments](./set_ignorecomments/)(bool) | Yorumları görmezden gelip gelmeyeceğini belirten bir değer ayarlar. |
| [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(bool) | İşlem talimatlarını görmezden gelip gelmeyeceğini belirten bir değer ayarlar. |
| [set_IgnoreWhitespace](./set_ignorewhitespace/)(bool) | Önemli olmayan boşlukları görmezden gelip gelmeyeceğini belirten bir değer ayarlar. |
| [set_LineNumberOffset](./set_linenumberoffset/)(int32_t) | [XmlReader](../xmlreader/) nesnesinin satır numarası ofsetini ayarlar. |
| [set_LinePositionOffset](./set_linepositionoffset/)(int32_t) | [XmlReader](../xmlreader/) nesnesinin satır konumu ofsetini ayarlar. |
| [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(int64_t) | Varlıkların genişletilmesinden kaynaklanan bir belgede izin verilen azami karakter sayısını belirten bir değer ayarlar. |
| [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(int64_t) | Bir XML belgesinde izin verilen azami karakter sayısını belirten bir değer ayarlar. Sıfır (0) değeri, XML belgesinin boyutu için sınırlama olmadığını ifade eder. Sıfır olmayan bir değer, azami boyutu karakter cinsinden belirtir. |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Atomize edilmiş dize karşılaştırmaları için kullanılan [XmlNameTable](../xmlnametable/) ayarlar. |
| [set_ProhibitDtd](./set_prohibitdtd/)(bool) | Belge türü tanımının (DTD) işlenmesini yasaklayıp yasaklamayacağını belirten bir değer ayarlar. |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Şema doğrulaması yapılırken kullanılacak XmlSchemaSet'i ayarlar. |
| [set_ValidationFlags](./set_validationflags/)(Schema::XmlSchemaValidationFlags) | Şema doğrulama ayarlarını belirten bir değer ayarlar. Bu ayar, şemaları doğrulayan [XmlReader](../xmlreader/) nesnelerine uygulanır ([XmlReaderSettings::get_ValidationType](./get_validationtype/) değeri [ValidationType::Schema](../validationtype/) olduğunda). |
| [set_ValidationType](./set_validationtype/)(System::Xml::ValidationType) | [XmlReader](../xmlreader/) okuma sırasında doğrulama veya tip ataması yapıp yapmayacağını belirten bir değer ayarlar. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Harici belgelere erişmek için kullanılan [XmlResolver](../xmlresolver/) ayarlar. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Okuyucu doğrulama hatalarıyla karşılaştığında gerçekleşen bir olay işleyicisi ekler. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Okuyucu doğrulama hatalarıyla karşılaştığında gerçekleşen bir olay işleyicisini kaldırır. |
| [XmlReaderSettings](./xmlreadersettings/)() | [XmlReaderSettings](./) sınıfının yeni bir örneğini başlatır. |
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
