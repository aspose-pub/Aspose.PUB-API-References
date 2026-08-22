---
title: "System::Runtime::Serialization::IFormatterConverter sınıfı"
linktitle: "IFormatterConverter"
second_title: "Aspose.PUB için C++"
description: "System::Runtime::Serialization::IFormatterConverter sınıfı. System::Runtime::Serialization::SerializationInfo bir örneği ile System::Runtime::Serialization::SerializationInfo içindeki verileri ayrıştırmak için biçimlendirici tarafından sağlanan en uygun sınıf arasında bağlantı sağlar (C++ içinde)."
type: docs
weight: 200
url: /tr/cpp/system.runtime.serialization/iformatterconverter/
---
## IFormatterConverter class


Bir [System::Runtime::Serialization::SerializationInfo](../serializationinfo/) örneği ile [System::Runtime::Serialization::SerializationInfo](../serializationinfo/) içindeki verileri ayrıştırmak için biçimlendirici tarafından sağlanan en uygun sınıf arasında bağlantı sağlar.

```cpp
class IFormatterConverter : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, const TypeInfo\&) | RTTI bilgisi. |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, TypeCode) | Bir değeri verilen [System::TypeCode](../../system/typecode/) değerine dönüştürür. |
| virtual [ToBoolean](./toboolean/)(System::SharedPtr\<Object\>) | Bir değeri bool tipine dönüştürür. |
| virtual [ToByte](./tobyte/)(System::SharedPtr\<Object\>) | Bir değeri uint8_t tipine dönüştürür. |
| virtual [ToChar](./tochar/)(System::SharedPtr\<Object\>) | Bir değeri char16_t tipine dönüştürür. |
| virtual [ToDateTime](./todatetime/)(System::SharedPtr\<Object\>) | Bir değeri [DateTime](../../system/datetime/) tipine dönüştürür. |
| virtual [ToDecimal](./todecimal/)(System::SharedPtr\<Object\>) | Bir değeri [Decimal](../../system/decimal/) tipine dönüştürür. |
| virtual [ToDouble](./todouble/)(System::SharedPtr\<Object\>) | Bir değeri double tipine dönüştürür. |
| virtual [ToInt16](./toint16/)(System::SharedPtr\<Object\>) | Bir değeri int16_t'ye dönüştürür. |
| virtual [ToInt32](./toint32/)(System::SharedPtr\<Object\>) | Bir değeri int32_t'ye dönüştürür. |
| virtual [ToInt64](./toint64/)(System::SharedPtr\<Object\>) | Bir değeri int64_t'ye dönüştürür. |
| virtual [ToSByte](./tosbyte/)(System::SharedPtr\<Object\>) | Bir değeri int8_t'ye dönüştürür. |
| virtual [ToSingle](./tosingle/)(System::SharedPtr\<Object\>) | Bir değeri float'a dönüştürür. |
| virtual [ToString](./tostring/)(System::SharedPtr\<Object\>) | Bir değeri [String](../../system/string/) tipine dönüştürür. |
| virtual [ToUInt16](./touint16/)(System::SharedPtr\<Object\>) | Bir değeri uint16_t'ye dönüştürür. |
| virtual [ToUInt32](./touint32/)(System::SharedPtr\<Object\>) | Bir değeri uint32_t'ye dönüştürür. |
| virtual [ToUInt64](./touint64/)(System::SharedPtr\<Object\>) | Bir değeri uint64_t'ye dönüştürür. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PUB for C++](../../)
