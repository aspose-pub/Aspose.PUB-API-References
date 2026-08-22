---
title: "System::Net::FileWebRequest::BeginGetResponse metodu"
linktitle: "BeginGetResponse"
second_title: "Aspose.PUB için C++"
description: "System::Net::FileWebRequest::BeginGetResponse metodu. C++'de kaynak için eşzamansız bir istek başlatır."
type: docs
weight: 400
url: /tr/cpp/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse method


Kaynak için asenkron bir isteği başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
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
