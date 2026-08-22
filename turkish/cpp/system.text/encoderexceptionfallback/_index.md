---
title: "System::Text::EncoderExceptionFallback sınıfı"
linktitle: "EncoderExceptionFallback"
second_title: "Aspose.PUB için C++"
description: "System::Text::EncoderExceptionFallback sınıfı. İstisna fırlatan bir geri dönüş stratejisi sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1000
url: /tr/cpp/system.text/encoderexceptionfallback/
---
## EncoderExceptionFallback class


İstisna fırlatan bir geri dönüş stratejisi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek, yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class EncoderExceptionFallback : public System::Text::EncoderFallback
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Geri dönüş tamponu oluşturur. |
| [EncoderExceptionFallback](./encoderexceptionfallback/)() | Yapıcı. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Örneğin döndürebileceği azami karakter sayısını al. |
## Ayrıca Bakınız

* Class [EncoderFallback](../encoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
