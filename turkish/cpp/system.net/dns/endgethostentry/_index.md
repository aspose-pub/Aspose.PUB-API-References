---
title: "System::Net::Dns::EndGetHostEntry yöntemi"
linktitle: "EndGetHostEntry"
second_title: "Aspose.PUB için C++"
description: "System::Net::Dns::EndGetHostEntry yöntemi. C++ içinde yeni bir IPHostEntry-sınıfı örneği oluşturmak için belirtilen eşzamansız işlemin tamamlanmasını bekler."
type: docs
weight: 700
url: /tr/cpp/system.net/dns/endgethostentry/
---
## Dns::EndGetHostEntry method


Belirtilen asenkron işlemin yeni bir IPHostEntry-class örneği oluşturması tamamlanana kadar bekler.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostEntry(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) nesnesi, asenkron bir işlemi temsil eder. |

### ReturnValue

Yeni oluşturulmuş bir IPHostEntry sınıfı örneği.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
