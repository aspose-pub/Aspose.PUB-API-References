---
title: "System::Net::WebRequest::EndGetRequestStream method"
linktitle: "EndGetRequestStream"
second_title: "Aspose.PUB için C++"
description: "System::Net::WebRequest::EndGetRequestStream method. C++'ta bir akış elde etmek için belirtilen asenkron işlemin tamamlanmasını bekler."
type: docs
weight: 1200
url: /tr/cpp/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream method


Belirtilen akış elde etme asenkron işlemi tamamlanana kadar bekler.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
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
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
