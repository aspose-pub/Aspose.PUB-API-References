---
title: "System::Net::Sockets::UdpClient::Connect yöntemi"
linktitle: "Bağlan"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::UdpClient::Connect yöntemi. C++'ta belirtilen ana bilgisayarda belirtilen bağlantı noktasına bir bağlantı kurar."
type: docs
weight: 300
url: /tr/cpp/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) method


Belirtilen ana bilgisayardaki belirtilen bağlantı noktasına bir bağlantı kurar.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ana bilgisayar adı | String | Bağlanmayı düşündüğünüz uzak DNS ana bilgisayarının adı. |
| bağlantı noktası | int32_t | İletişim kurmayı düşündüğünüz yerel bağlantı noktası numarası. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method


Belirtilen bağlantı noktasındaki belirtilen adresteki ana bilgisayara bir bağlantı kurar.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addr | System::SharedPtr\<IPAddress\> | Veri göndereceğiniz uzak ana bilgisayarın [IPAddress](../../../system.net/ipaddress/) adresi. |
| bağlantı noktası | int32_t | İletişim kurmayı düşündüğünüz yerel bağlantı noktası numarası. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) method


Uzak bir uç noktaya bağlantı kurar.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| endPoint | System::SharedPtr\<IPEndPoint\> | UDP bağlantısını bağladığınız uç nokta. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
