---
title: "System::Net::FileWebRequest::EndGetRequestStream yöntemi"
linktitle: "EndGetRequestStream"
second_title: "Aspose.PUB için C++"
description: "System::Net::FileWebRequest::EndGetRequestStream yöntemi. Belirtilen asenkron akış elde etme işleminin C++'ta tamamlanmasını bekler."
type: docs
weight: 500
url: /tr/cpp/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream method


Belirtilen akış elde etme asenkron işlemi tamamlanana kadar bekler.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Bir akış elde etmek için eşzamansız bir işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi. |

### ReturnValue

Kaynağa veri yazmak için akış.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
