---
title: "System::Net::Dns::BeginGetHostByName metodu"
linktitle: "BeginGetHostByName"
second_title: "Aspose.PUB için C++"
description: "System::Net::Dns::BeginGetHostByName metodu. Belirtilen ana bilgisayar adını kullanarak yeni bir IPHostEntry sınıfı örneği oluşturmak için C++'da asenkron bir işlem başlatır."
type: docs
weight: 200
url: /tr/cpp/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName method


Belirtilen ana bilgisayar adını kullanarak yeni bir IPHostEntry-class örneği oluşturmak için asenkron bir işlem başlatır.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostName | String | Bir ana bilgisayar adı. |
| requestCallback | AsyncCallback | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| stateObject | System::SharedPtr\<Object\> | Kullanıcı tarafından sağlanan veri, her asenkron işlemi benzersiz şekilde tanımlamak için kullanılır. |

### ReturnValue

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
