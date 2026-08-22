---
title: "System::Net::Sockets::Socket::BeginReceive yöntemi"
linktitle: "BeginReceive"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::Socket::BeginReceive yöntemi. C++'ta asenkron bir yazma işlemi başlatır."
type: docs
weight: 800
url: /tr/cpp/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive method


Asenkron bir yazma işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Alınan verinin atanacağı bir tampon. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| boyut | int32_t | Belirtilen dizide, 'offset' parametresinden başlayan bayt sayısı. |
| socketFlags | SocketFlags | Alma davranışı. |
| geri çağırma | AsyncCallback | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| durum | System::SharedPtr\<Object\> | Her asenkron alım işlemini benzersiz şekilde tanımlamak için kullanılan, kullanıcı tarafından sağlanan veri. |

### ReturnValue

Başlatılan asenkron alım işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
