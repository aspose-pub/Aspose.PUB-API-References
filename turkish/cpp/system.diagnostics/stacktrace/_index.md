---
title: "System::Diagnostics::StackTrace sınıfı"
linktitle: "StackTrace"
second_title: "Aspose.PUB için C++"
description: "System::Diagnostics::StackTrace sınıfı. Yığın çerçevelerinin koleksiyonu. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 600
url: /tr/cpp/system.diagnostics/stacktrace/
---
## StackTrace class


Yığın çerçevelerinin koleksiyonu. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class StackTrace : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_FrameCount](./get_framecount/)() const | Yığın izindeki çerçeve sayısını alır. |
| virtual [GetFrame](./getframe/)(uint32_t) | Yığın çerçevesini alır. |
| [operator=](./operator=/)(const StackTrace\&) const | Atama yok. |
| [StackTrace](./stacktrace/)() | Mevcut yığın durumunu açıklayan yığın izini oluşturur. |
| [StackTrace](./stacktrace/)(bool) | Mevcut yığın durumunu açıklayan yığın izini oluşturur. |
| [StackTrace](./stacktrace/)(const StackTrace\&) | Kopyalama yok. |
| virtual [~StackTrace](./~stacktrace/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PUB for C++](../../)
