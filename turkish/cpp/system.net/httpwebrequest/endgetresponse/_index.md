---
title: "System::Net::HttpWebRequest::EndGetResponse yöntemi"
linktitle: "EndGetResponse"
second_title: "Aspose.PUB için C++"
description: "System::Net::HttpWebRequest::EndGetResponse yöntemi. C++'ta belirtilen eşzamansız kaynak isteği tamamlanana kadar bekler."
type: docs
weight: 700
url: /tr/cpp/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse method


Kaynak için belirtilen asenkron isteğin tamamlanmasını bekler.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
