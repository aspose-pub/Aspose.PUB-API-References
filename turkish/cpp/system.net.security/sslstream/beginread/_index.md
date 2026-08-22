---
title: "System::Net::Security::SslStream::BeginRead yöntemi"
linktitle: "BeginRead"
second_title: "Aspose.PUB için C++"
description: "System::Net::Security::SslStream::BeginRead yöntemi. C++'de bir eşzamanlı okuma işlemi başlatır."
type: docs
weight: 300
url: /tr/cpp/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead method


Asenkron bir okuma işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Verilerin okunacağı bayt dizisi. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| sayım | int32_t | Okunacak bayt sayısı. |
| asyncCallback | AsyncCallback | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| asyncState | System::SharedPtr\<Object\> | Kullanıcı tarafından sağlanan ve her asenkron okuma işlemini benzersiz şekilde tanımlamak için kullanılan veri. |

### ReturnValue

Başlatılan asenkron okuma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PUB for C++](../../../)
