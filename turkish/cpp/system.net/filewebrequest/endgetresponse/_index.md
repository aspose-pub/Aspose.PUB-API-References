---
title: "System::Net::FileWebRequest::EndGetResponse metodu"
linktitle: "EndGetResponse"
second_title: "Aspose.PUB için C++"
description: "System::Net::FileWebRequest::EndGetResponse yöntemi. Belirtilen asenkron isteğin kaynağa tamamlanmasını C++'ta bekler."
type: docs
weight: 600
url: /tr/cpp/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse method


Kaynak için belirtilen asenkron isteğin tamamlanmasını bekler.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Bir [IAsyncResult](../../../system/iasyncresult/) nesnesi, kaynağa yönelik asenkron bir isteği temsil eder. |

### ReturnValue

Web yanıtı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WebResponse](../../webresponse/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
