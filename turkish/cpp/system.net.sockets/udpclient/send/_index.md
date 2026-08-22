---
title: "System::Net::Sockets::UdpClient::Send yöntemi"
linktitle: "Gönder"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::UdpClient::Send yöntemi. C++'ta bir UDP veri paketini uzak bir ana bilgisayara gönderir."
type: docs
weight: 700
url: /tr/cpp/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method


Uzak bir ana bilgisayara bir UDP datagramı gönderir.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Gönderilecek [Byte](../../../system/byte/) tipinde bir dizi. |
| baytlar | int32_t | Veri paketindeki bayt sayısı. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method


Belirtilen uzak ana bilgisayardaki belirtilen bağlantı noktasına bir UDP datagramı gönderir.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Gönderilecek [Byte](../../../system/byte/) tipinde bir dizi |
| baytlar | int32_t | Veri paketindeki bayt sayısı. |
| ana bilgisayar adı | String | Uzak ana bilgisayarın adı. |
| bağlantı noktası | int32_t | Uzak bir bağlantı noktası numarası. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method


Uzak uç noktadaki ana bilgisayara bir UDP datagramı gönderir.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Gönderilecek [Byte](../../../system/byte/) tipinde bir dizi |
| baytlar | int32_t | Veri paketindeki bayt sayısı. |
| endPoint | System::SharedPtr\<IPEndPoint\> | [IPEndPoint](../../../system.net/ipendpoint/) veri paketini göndereceğiniz ana bilgisayarı ve bağlantı noktasını temsil eder. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
