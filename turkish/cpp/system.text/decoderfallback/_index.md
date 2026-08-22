---
title: "System::Text::DecoderFallback class"
linktitle: "DecoderFallback"
second_title: "Aspose.PUB için C++"
description: "System::Text::DecoderFallback sınıfı. Kod çözme hatasını ele almak için geri dönüş API'si sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 500
url: /tr/cpp/system.text/decoderfallback/
---
## DecoderFallback class


Kod çözme hatasını ele almak için geri dönüş API'si sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class DecoderFallback : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [CreateFallbackBuffer](./createfallbackbuffer/)() | Geri dönüş algoritmasıyla ilişkili tamponu alır. |
| static [get_ExceptionFallback](./get_exceptionfallback/)() | Varsayılan istisna geri dönüş uygulamasını alır. |
| virtual [get_MaxCharCount](./get_maxcharcount/)() const | Geri dönüş tarafından döndürülebilecek azami karakter sayısını alır. |
| static [get_ReplacementFallback](./get_replacementfallback/)() | Varsayılan yerine koyma geri dönüş uygulamasını alır. |
| static [get_StandardSafeFallback](./get_standardsafefallback/)() | Varsayılan standart güvenli geri dönüş uygulamasını alır. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
