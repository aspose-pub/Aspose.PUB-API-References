---
title: "System::Net::Dns::BeginGetHostEntry yöntemi"
linktitle: "BeginGetHostEntry"
second_title: "Aspose.PUB için C++"
description: "System::Net::Dns::BeginGetHostEntry yöntemi. C++ içinde ana bilgisayar adı veya IP adresi içeren belirtilen dizeyi kullanarak yeni bir IPHostEntry-sınıfı örneği oluşturmak için eşzamansız bir işlem başlatır."
type: docs
weight: 300
url: /tr/cpp/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) method


Belirtilen dizeyi (ana bilgisayar adı veya IP adresi içeren) kullanarak yeni bir IPHostEntry-class örneği oluşturmak için asenkron bir işlem başlatır.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostNameOrAddress | String | Bir ana bilgisayar adı veya IP adresi içeren dize. |
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
## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) method


Belirtilen IP adresini kullanarak yeni bir IPHostEntry-class örneği oluşturmak için asenkron bir işlem başlatır.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| adres | System::SharedPtr\<IPAddress\> | IP adresi. |
| requestCallback | AsyncCallback | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| stateObject | System::SharedPtr\<Object\> | Kullanıcı tarafından sağlanan veri, her asenkron işlemi benzersiz şekilde tanımlamak için kullanılır. |

### ReturnValue

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [IPAddress](../../ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
