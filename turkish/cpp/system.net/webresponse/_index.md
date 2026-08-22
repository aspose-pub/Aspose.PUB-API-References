---
title: "System::Net::WebResponse class"
linktitle: "WebResponse"
second_title: "Aspose.PUB için C++"
description: "System::Net::WebResponse sınıfı. Bir web yanıtını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 4000
url: /tr/cpp/system.net/webresponse/
---
## WebResponse class


Bir web yanıtını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class WebResponse : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Close](./close/)() | Yanıt akışını kapatır. |
| [Dispose](./dispose/)() override | Hiçbir şey yapmaz. |
| virtual [get_ContentLength](./get_contentlength/)() | RTTI bilgisi. |
| virtual [get_ContentType](./get_contenttype/)() | Kaynağın MIME türünü döndürür. |
| virtual [get_Headers](./get_headers/)() | Mevcut yanıtla ilişkili başlıkların koleksiyonunu döndürür. |
| virtual [get_ResponseUri](./get_responseuri/)() | Kaynağın URI'sını döndürür. |
| virtual [get_SupportsHeaders](./get_supportsheaders/)() | Mevcut yanıtın başlıkları destekleyip desteklemediğini gösteren bir değer döndürür. |
| virtual [GetResponseStream](./getresponsestream/)() | Yanıt akışını döndürür. |
## Ayrıca Bakınız

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
