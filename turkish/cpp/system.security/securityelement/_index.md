---
title: "System::Security::SecurityElement sınıfı"
linktitle: "SecurityElement"
second_title: "Aspose.PUB için C++"
description: "System::Security::SecurityElement sınıfı. XML nesne modeli, güvenlik nesnesini kodlamak için kullanılır. Uygulanmamıştır. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak C++'de geçirin."
type: docs
weight: 300
url: /tr/cpp/system.security/securityelement/
---
## SecurityElement class


XML nesne modeli, güvenlik nesnesini kodlamak için kullanılır. Uygulanmamıştır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class SecurityElement : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddAttribute](./addattribute/)(const String\&, const String\&) | Etikete bir öznitelik ekler. |
| [AddChild](./addchild/)(SecurityElement) | Alt etiket ekler. |
| [Attribute](./attribute/)(const String\&) | Öznitelik değerini alır. |
| [Copy](./copy/)() | Etiketi kopyalar. |
| [Equal](./equal/)(SecurityElement) | Parametrelerin eşitliğini kontrol eder. |
| static [Escape](./escape/)(const String\&) | XML dizesindeki karakterleri kaçırır. |
| static [FromString](./fromstring/)(const String\&) | XML kodundan bir öğe oluşturur. |
| [get_Attributes](./get_attributes/)() | Etiket özniteliklerini alır. |
| [get_Children](./get_children/)() | Etiketin alt nesnelerini alır. |
| [get_Tag](./get_tag/)() | Etiketin adını alır. |
| [get_Text](./get_text/)() | Etiketin iç metnini alır. |
| static [IsValidAttributeName](./isvalidattributename/)(const String\&) | Özellik adının geçerli olup olmadığını denetler. |
| static [IsValidAttributeValue](./isvalidattributevalue/)(const String\&) | Özellik değerinin geçerli olup olmadığını denetler. |
| static [IsValidTag](./isvalidtag/)(const String\&) | Etiketin geçerli olup olmadığını denetler. |
| static [IsValidText](./isvalidtext/)(const String\&) | Metnin geçerli olup olmadığını denetler. |
| [SearchForChildByTag](./searchforchildbytag/)(const String\&) | İsme göre alt etiketi alır. |
| [SearchForTextOfTag](./searchfortextoftag/)(const String\&) | Etiket adına göre alt etiketin iç metnini alır. |
| [SecurityElement](./securityelement/)(const String\&) | Yapıcı. |
| [SecurityElement](./securityelement/)(const String\&, const String\&) | Yapıcı. |
| [set_Attributes](./set_attributes/)(System::Collections::Generic::Dictionary\<String, String\>) | Etiket özelliklerini ayarlar. |
| [set_Children](./set_children/)(System::Collections::Generic::List\<SecurityElement\>) | Etiketin alt nesnelerini ayarlar. |
| [set_Tag](./set_tag/)(const String\&) | Etiketin adını ayarlar. |
| [set_Text](./set_text/)(const String\&) | Etiketin iç metnini ayarlar. |
| [ToString](./tostring/)() const override | Etiketi dizeye dönüştürür. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Security](../)
* Library [Aspose.PUB for C++](../../)
