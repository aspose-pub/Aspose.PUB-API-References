---
title: "System::Net::Dns::EndGetHostByName yöntemi"
linktitle: "EndGetHostByName"
second_title: "Aspose.PUB için C++"
description: "System::Net::Dns::EndGetHostByName yöntemi. C++ içinde yeni bir IPHostEntry-sınıfı örneği oluşturmak için belirtilen eşzamansız işlemin tamamlanmasını bekler."
type: docs
weight: 600
url: /tr/cpp/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName method


Belirtilen asenkron işlemin yeni bir IPHostEntry-class örneği oluşturması tamamlanana kadar bekler.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
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
