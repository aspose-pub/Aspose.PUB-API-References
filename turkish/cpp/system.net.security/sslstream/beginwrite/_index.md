---
title: "System::Net::Security::SslStream::BeginWrite yöntemi"
linktitle: "BeginWrite"
second_title: "Aspose.PUB için C++"
description: "System::Net::Security::SslStream::BeginWrite yöntemi. C++'da eşzamansız bir yazma işlemi başlatır."
type: docs
weight: 400
url: /tr/cpp/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite method


Asenkron bir yazma işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Verinin yazılacağı bayt dizisi. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| sayım | int32_t | Yazılacak bayt sayısı. |
| asyncCallback | AsyncCallback | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| asyncState | System::SharedPtr\<Object\> | Kullanıcı tarafından sağlanan veri, her eşzamanlı olmayan yazma işlemini benzersiz şekilde tanımlamak için kullanılır. |

### ReturnValue

Başlatılan eşzamanlı olmayan yazma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PUB for C++](../../../)
