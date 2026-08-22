---
title: "System::Diagnostics::TraceListener class"
linktitle: "TraceListener"
second_title: "Aspose.PUB için C++"
description: "System::Diagnostics::TraceListener sınıfı. Hata ayıklama ve izleme bilgilerine yanıt vermek için bir arayüz. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak C++'da geçirin."
type: docs
weight: 800
url: /tr/cpp/system.diagnostics/tracelistener/
---
## TraceListener class


Debug ve izleme bilgilerine yanıt vermek için bir arayüz. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class TraceListener : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Fail](./fail/)(System::String) | Hata ayıklayıcıya başarısızlık mesajı yazar. |
| virtual [Fail](./fail/)(System::String, System::String) | Hata ayıklayıcıya başarısızlık mesajı yazar. |
| virtual [Write](./write/)(System::String) | RTTI bilgisi. |
| virtual [WriteLine](./writeline/)(System::String) | Hata ayıklayıcıya satır yazar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PUB for C++](../../)
