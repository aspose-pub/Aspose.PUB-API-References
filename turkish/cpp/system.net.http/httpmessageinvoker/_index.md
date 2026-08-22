---
title: "System::Net::Http::HttpMessageInvoker sınıfı"
linktitle: "HttpMessageInvoker"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::HttpMessageInvoker sınıfı. Uygulamaların bir HTTP işleyici zincirinde Send yöntemini çağırmasına izin verir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 600
url: /tr/cpp/system.net.http/httpmessageinvoker/
---
## HttpMessageInvoker class


Uygulamaların bir HTTP işleyici zincirinde Send yöntemini çağırmasına izin verir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class HttpMessageInvoker : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Dispose](./dispose/)() override | Mevcut örneği serbest bırakır. Bu yöntem, gerekirse işleyiciyi de serbest bırakır. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>) | RTTI bilgisi. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Yeni bir örnek oluşturur. |
| virtual [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) | Belirtilen isteği gönderir. |
## Ayrıca Bakınız

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PUB for C++](../../)
