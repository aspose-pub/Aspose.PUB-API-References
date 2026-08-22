---
title: "System::Text::DecoderReplacementFallback sınıfı"
linktitle: "DecoderReplacementFallback"
second_title: "Aspose.PUB için C++"
description: "System::Text::DecoderReplacementFallback sınıfı. Hatalı sembolü bir geçici değerle değiştirme geri dönüş stratejisi sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığıt (stack) üzerinde veya new operatörüyle oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 700
url: /tr/cpp/system.text/decoderreplacementfallback/
---
## DecoderReplacementFallback class


Hatalı sembolü bir geçici değerle değiştirme geri dönüş stratejisi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class DecoderReplacementFallback : public System::Text::DecoderFallback
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Geri dönüş tamponu oluşturur. |
| [DecoderReplacementFallback](./decoderreplacementfallback/)() | Varsayılan "?" değiştirme dizesini kullanan yapıcı. |
| [DecoderReplacementFallback](./decoderreplacementfallback/)(const String\&) | Yapıcı. |
| [get_DefaultString](./get_defaultstring/)() const | Değiştirme dizesini alır. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Örneğin döndürebileceği azami karakter sayısını al. |
## Ayrıca Bakınız

* Class [DecoderFallback](../decoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
