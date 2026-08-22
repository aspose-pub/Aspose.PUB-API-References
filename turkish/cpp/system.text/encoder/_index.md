---
title: "System::Text::Encoder sınıfı"
linktitle: "Encoder"
second_title: "Aspose.PUB için C++"
description: "System::Text::Encoder sınıfı. Karakter dizisini bayt dizisine kodlamayı kapsüller. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 900
url: /tr/cpp/system.text/encoder/
---
## Encoder class


Karakter dizisini bayt dizisine kodlamayı kapsüller. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
class Encoder : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) | Karakterleri baytlara dönüştürür. |
| virtual [Convert](./convert/)(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) | Karakterleri baytlara dönüştürür. |
| [get_Fallback](./get_fallback/)() const | Hata işleme geri dönüşünü alır. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Geri dönüş tamponunu alır. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int, bool) | Bir tamponu kodlamak için gereken bayt sayısını alır. |
| virtual [GetByteCount](./getbytecount/)(const char_t *, int, bool) | Bir tamponu kodlamak için gereken bayt sayısını alır. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) | Bir tamponu kodlarken elde edilen baytları al. |
| virtual [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int, bool) | Bir tamponu kodlarken elde edilen baytları al. |
| virtual [Reset](./reset/)() | Kodlayıcının iç durumunu temizler. |
| [set_Fallback](./set_fallback/)(const EncoderFallbackPtr\&) | Hata işleme geri dönüşünü ayarlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
