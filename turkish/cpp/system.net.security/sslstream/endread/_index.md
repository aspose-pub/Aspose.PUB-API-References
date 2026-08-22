---
title: "System::Net::Security::SslStream::EndRead yöntemi"
linktitle: "EndRead"
second_title: "Aspose.PUB için C++"
description: "System::Net::Security::SslStream::EndRead yöntemi. C++'de belirtilen eşzamanlı okuma işlemi tamamlanana kadar bekler."
type: docs
weight: 700
url: /tr/cpp/system.net.security/sslstream/endread/
---
## SslStream::EndRead method


Belirtilen asenkron okuma işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Bir [IAsyncResult](../../../system/iasyncresult/) nesnesi, eşzamanlı olmayan bir okuma işlemini temsil eder |

### ReturnValue

**asyncResult** tarafından temsil edilen okuma işlemi sırasında okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PUB for C++](../../../)
