---
title: "System::Net::Sockets::Socket::EndReceive yöntemi"
linktitle: "EndReceive"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::Socket::EndReceive yöntemi. C++'ta belirtilen eşzamansız alma işlemi tamamlanana kadar bekler."
type: docs
weight: 1500
url: /tr/cpp/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) method


Belirtilen asenkron alma işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Asenkron bir alma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Belirtilen asenkron alma işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Asenkron bir alma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi. |
| errorCode | SocketError\& | Alma işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
