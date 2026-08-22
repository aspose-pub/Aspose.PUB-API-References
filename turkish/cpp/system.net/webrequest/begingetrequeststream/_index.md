---
title: "System::Net::WebRequest::BeginGetRequestStream method"
linktitle: "BeginGetRequestStream"
second_title: "Aspose.PUB için C++"
description: "System::Net::WebRequest::BeginGetRequestStream method. C++'ta kaynağa veri yazmak için bir akış elde etmeyi başlatan asenkron bir işlem başlatır."
type: docs
weight: 1000
url: /tr/cpp/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream method


Kaynağa veri yazmak için bir akış elde etmeye yönelik asenkron bir işlemi başlatır.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geri çağırma | AsyncCallback | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| durum | System::SharedPtr\<Object\> | Kullanıcı tarafından sağlanan veri, her asenkron işlemi benzersiz şekilde tanımlamak için kullanılır. |

### ReturnValue

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
