---
title: "System::Net::FileWebRequest::BeginGetRequestStream yöntemi"
linktitle: "BeginGetRequestStream"
second_title: "Aspose.PUB için C++"
description: "System::Net::FileWebRequest::BeginGetRequestStream yöntemi. Kaynağa veri yazmak için bir akış elde etmeyi sağlayan asenkron işlemi C++'ta başlatır."
type: docs
weight: 300
url: /tr/cpp/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream method


Kaynağa veri yazmak için bir akış elde etmeye yönelik asenkron bir işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
