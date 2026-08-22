---
title: "System::IO::Stream::EndRead yöntemi"
linktitle: "EndRead"
second_title: "Aspose.PUB için C++"
description: "System::IO::Stream::EndRead yöntemi. Belirtilen eşzamanlı okuma işlemi tamamlanana kadar bekler C++'da."
type: docs
weight: 600
url: /tr/cpp/system.io/stream/endread/
---
## Stream::EndRead method


Belirtilen asenkron okuma işlemi tamamlanana kadar bekler.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<System::IAsyncResult\> | Bir [IAsyncResult](../../../system/iasyncresult/) nesnesi, eşzamanlı olmayan bir okuma işlemini temsil eder |

### ReturnValue

**asyncResult** tarafından temsil edilen okuma işlemi sırasında okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
