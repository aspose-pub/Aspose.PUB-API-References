---
title: "System::Net::WebRequest::EndGetResponse yöntemi"
linktitle: "EndGetResponse"
second_title: "Aspose.PUB için C++"
description: "System::Net::WebRequest::EndGetResponse yöntemi. C++'ta kaynak için belirtilen eşzamansız isteğin tamamlanmasını bekler."
type: docs
weight: 1300
url: /tr/cpp/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse method


Kaynak için belirtilen asenkron isteğin tamamlanmasını bekler.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
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
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
