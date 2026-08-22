---
title: "System::Text::EncoderReplacementFallback sınıfı"
linktitle: "EncoderReplacementFallback"
second_title: "Aspose.PUB için C++"
description: "System::Text::EncoderReplacementFallback sınıfı. Hatalı sembolü bir stub (yer tutucu) ile değiştirme geri dönüş stratejisi sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1400
url: /tr/cpp/system.text/encoderreplacementfallback/
---
## EncoderReplacementFallback class


Hatalı sembolü bir geçici değerle değiştirme geri dönüş stratejisi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class EncoderReplacementFallback : public System::Text::EncoderFallback
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Geri dönüş tamponu oluşturur. |
| [EncoderReplacementFallback](./encoderreplacementfallback/)() | Varsayılan "?" değiştirme dizesini kullanan yapıcı. |
| [EncoderReplacementFallback](./encoderreplacementfallback/)(const String\&) | Yapıcı. |
| [get_DefaultString](./get_defaultstring/)() const | Değiştirme dizesini alır. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Örneğin döndürebileceği azami karakter sayısını al. |
## Ayrıca Bakınız

* Class [EncoderFallback](../encoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
