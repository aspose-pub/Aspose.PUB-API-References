---
title: "System::Net::Sockets::Socket::ReceiveFrom yöntemi"
linktitle: "ReceiveFrom"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::Socket::ReceiveFrom yöntemi. Belirtilen uç noktadan veri alır ve C++'ta belirtilen bayt dizisine yazar."
type: docs
weight: 4400
url: /tr/cpp/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| boyut | int32_t | 'offset' indeksinden itibaren belirtilen bayt dizisine atanacak alınacak baytların sayısı. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| boyut | int32_t | 'offset' indeksinden itibaren belirtilen bayt dizisine atanacak alınacak baytların sayısı. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::ArrayView\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| boyut | int32_t | 'offset' indeksinden itibaren belirtilen bayt dizisine atanacak alınacak baytların sayısı. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::ArrayView\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| boyut | int32_t | 'offset' indeksinden itibaren belirtilen bayt dizisine atanacak alınacak baytların sayısı. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::ArrayView\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::ArrayView\<uint8_t\> | Alınan verinin atanacağı bayt dizisi. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::StackArray\<uint8_t, N\>\& | Alınan verinin atanacağı bayt dizisi. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| boyut | int32_t | 'offset' indeksinden itibaren belirtilen bayt dizisine atanacak alınacak baytların sayısı. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::StackArray\<uint8_t, N\>\& | Alınan verinin atanacağı bayt dizisi. |
| boyut | int32_t | 'offset' indeksinden itibaren belirtilen bayt dizisine atanacak alınacak baytların sayısı. |
| socketFlags | SocketFlags | Alma davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::StackArray\<uint8_t, N\>\& | Alınan verinin atanacağı bayt dizisi. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | Uzak uç nokta. |

### ReturnValue

Alınan baytların sayısı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
