---
title: "System::ComponentModel::BackgroundWorker::ReportProgress yöntemi"
linktitle: "ReportProgress"
second_title: "Aspose.PUB için C++"
description: "System::ComponentModel::BackgroundWorker::ReportProgress yöntemi. C++'ta System::ComponentModel::BackgroundWorker::ProgressChanged olayını tetikler."
type: docs
weight: 400
url: /tr/cpp/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) method


Bu **System::ComponentModel::BackgroundWorker::ProgressChanged** olayını tetikler.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| percentProgress | int | Arka plan işleminin tamamlandığı yüzde, 0 ile 100 arasında. |

## Ayrıca Bakınız

* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PUB for C++](../../../)
## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) method


Kullanıcı durumu nesnesiyle **System::ComponentModel::BackgroundWorker::ProgressChanged** olayını tetikler.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| percentProgress | int | Arka plan işleminin tamamlandığı yüzde, 0 ile 100 arasında. |
| userState | const System::SharedPtr\<System::Object\>\& | System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object) yöntemine geçirilen durum nesnesi. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PUB for C++](../../../)
