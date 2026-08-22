---
title: "System::Net::Sockets::NetworkStream::BeginWrite metodu"
linktitle: "BeginWrite"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::NetworkStream::BeginWrite metodu. C++'ta eşzamanlı olmayan bir yazma işlemi başlatır."
type: docs
weight: 400
url: /tr/cpp/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite method


Asenkron bir yazma işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Yazılacak verileri içeren bir tampon. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| boyut | int32_t | Yazılacak bayt sayısı. |
| geri çağırma | AsyncCallback | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| durum | System::SharedPtr\<Object\> | Kullanıcı tarafından sağlanan veri, her eşzamanlı olmayan yazma işlemini benzersiz şekilde tanımlamak için kullanılır. |

### ReturnValue

Başlatılan eşzamanlı olmayan yazma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
