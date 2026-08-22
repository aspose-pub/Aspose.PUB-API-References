---
title: "System::IO::Stream::BeginRead yöntemi"
linktitle: "BeginRead"
second_title: "Aspose.PUB için C++"
description: "System::IO::Stream::BeginRead yöntemi. C++'da bir eşzamanlı okuma işlemi başlatır."
type: docs
weight: 100
url: /tr/cpp/system.io/stream/beginread/
---
## Stream::BeginRead method


Asenkron bir okuma işlemi başlatır.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Okunacak tampon |
| ofset | int | **buffer** içinde 0 tabanlı bir ofset, okunan verinin yazılmaya başlanacağı konumu gösterir. |
| sayım | int | Okunacak bayt sayısı |
| geri çağırma | System::AsyncCallback | İşlem tamamlandığında çağrılacak bir geri arama |
| durum | System::SharedPtr\<System::Object\> | Kullanıcı tarafından sağlanan veri, her bir eşzamanlı okuma işlemini benzersiz şekilde tanımlamak için kullanılır |

### ReturnValue

Başlatılan eşzamanlı okuma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
