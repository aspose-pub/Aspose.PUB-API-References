---
title: "System::ComponentModel::BackgroundWorker sınıfı"
linktitle: "BackgroundWorker"
second_title: "Aspose.PUB için C++"
description: "System::ComponentModel::BackgroundWorker sınıfı. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve C++'da fonksiyonlara argüman olarak geçirmek için bu işaretçiyi kullanın."
type: docs
weight: 200
url: /tr/cpp/system.componentmodel/backgroundworker/
---
## BackgroundWorker class


Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class BackgroundWorker : public System::ComponentModel::Component
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BackgroundWorker](./backgroundworker/)() | RTTI bilgisi. |
| [get_WorkerReportsProgress](./get_workerreportsprogress/)() const | Bu [System::ComponentModel::BackgroundWorker](./) nesnesinin ilerleme güncellemelerini raporlayıp raporlayamayacağını gösteren bir değer alır. |
| [ReportProgress](./reportprogress/)(int) | Bu **System::ComponentModel::BackgroundWorker::ProgressChanged** olayını tetikler. |
| [ReportProgress](./reportprogress/)(int, const System::SharedPtr\<System::Object\>\&) | Kullanıcı durumu nesnesiyle **System::ComponentModel::BackgroundWorker::ProgressChanged** olayını tetikler. |
| [RunWorkerAsync](./runworkerasync/)() | Arka plan işleminin yürütülmesini başlatır. |
| [RunWorkerAsync](./runworkerasync/)(const System::SharedPtr\<System::Object\>\&) | Arka plan işleminin yürütülmesini başlatır. |
| [set_WorkerReportsProgress](./set_workerreportsprogress/)(bool) | Bu [System::ComponentModel::BackgroundWorker](./) nesnesinin ilerleme güncellemelerini raporlayıp raporlayamayacağını gösteren bir değer ayarlar. |
| [~BackgroundWorker](./~backgroundworker/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [Component](../component/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PUB for C++](../../)
