---
title: "System::Net::HttpWebRequest::EndGetRequestStream yöntemi"
linktitle: "EndGetRequestStream"
second_title: "Aspose.PUB için C++"
description: "System::Net::HttpWebRequest::EndGetRequestStream yöntemi. C++'ta bir akış elde etmek için belirtilen eşzamansız işlemin tamamlanmasını bekler."
type: docs
weight: 600
url: /tr/cpp/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream method


Belirtilen akış elde etme asenkron işlemi tamamlanana kadar bekler.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
