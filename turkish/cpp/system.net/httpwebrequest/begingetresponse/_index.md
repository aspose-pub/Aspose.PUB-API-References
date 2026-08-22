---
title: "System::Net::HttpWebRequest::BeginGetResponse yöntemi"
linktitle: "BeginGetResponse"
second_title: "Aspose.PUB için C++"
description: "System::Net::HttpWebRequest::BeginGetResponse yöntemi. C++'ta kaynak için eşzamansız bir istek başlatır."
type: docs
weight: 500
url: /tr/cpp/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse method


Kaynak için asenkron bir isteği başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
