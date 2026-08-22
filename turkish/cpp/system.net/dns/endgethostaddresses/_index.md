---
title: "System::Net::Dns::EndGetHostAddresses yöntemi"
linktitle: "EndGetHostAddresses"
second_title: "Aspose.PUB için C++"
description: "System::Net::Dns::EndGetHostAddresses yöntemi. C++'ta yeni bir IPHostEntry sınıfı örneği oluşturmak için belirtilen eşzamanlı olmayan işlemin tamamlanmasını bekler."
type: docs
weight: 500
url: /tr/cpp/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses method


Belirtilen asenkron işlemin yeni bir IPHostEntry-class örneği oluşturması tamamlanana kadar bekler.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | An [IAsyncResult](../../../system/iasyncresult/) nesnesi, asenkron bir işlemi temsil eder. |

### ReturnValue

Yeni oluşturulmuş bir IPHostEntry sınıfı örneği.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../ipaddress/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
