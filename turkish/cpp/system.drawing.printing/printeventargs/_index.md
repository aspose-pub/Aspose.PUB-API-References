---
title: "System::Drawing::Printing::PrintEventArgs sınıfı"
linktitle: "PrintEventArgs"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Printing::PrintEventArgs sınıfı. BeginPrint ve EndPrint olayları için veri sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate (ayrılmalıdır). Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 800
url: /tr/cpp/system.drawing.printing/printeventargs/
---
## PrintEventArgs class


BeginPrint ve EndPrint olayları için veri sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate (ayrılmalıdır). Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class PrintEventArgs : public System::ComponentModel::CancelEventArgs
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_PrintAction](./get_printaction/)() | Geçerli nesne tarafından temsil edilen bir yazdırma eylemini belirten bir değer döndürür. |
| [PrintEventArgs](./printeventargs/)() | Yeni bir [PrintEventArgs](./) nesnesi oluşturur. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Boş bir [EventArgs](../../system/eventargs/) paylaşımlı işaretçiyi (null işaretçi) temsil eden bir statik üye. |
## Ayrıca Bakınız

* Class [CancelEventArgs](../../system.componentmodel/canceleventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PUB for C++](../../)
