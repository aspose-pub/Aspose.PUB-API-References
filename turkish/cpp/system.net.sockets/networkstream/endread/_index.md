---
title: "System::Net::Sockets::NetworkStream::EndRead yöntemi"
linktitle: "EndRead"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::NetworkStream::EndRead yöntemi. Belirtilen eşzamanlı olmayan okuma işlemi C++'ta tamamlanana kadar bekler."
type: docs
weight: 600
url: /tr/cpp/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead method


Belirtilen asenkron okuma işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Bir [IAsyncResult](../../../system/iasyncresult/) nesnesi, eşzamanlı olmayan bir okuma işlemini temsil eder |

### ReturnValue

**asyncResult** tarafından temsil edilen okuma işlemi sırasında okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
