---
title: "System::Net::Sockets::Socket::SendTo yöntemi"
linktitle: "SendTo"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::Socket::SendTo yöntemi. Belirtilen veriyi belirtilen uç noktaya C++ içinde gönderir."
type: docs
weight: 4700
url: /tr/cpp/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Gönderilecek veri. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| boyut | int32_t | Belirtilen dizide, 'offset' parametresinden başlayan bayt sayısı. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Gönderilecek veri. |
| boyut | int32_t | Belirtilen dizideki bayt sayısı. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Gönderilecek veri. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::ArrayPtr\<uint8_t\> | Gönderilecek veri. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::ArrayView\<uint8_t\> | Gönderilecek veri. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| boyut | int32_t | Belirtilen dizide, 'offset' parametresinden başlayan bayt sayısı. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::ArrayView\<uint8_t\> | Gönderilecek veri. |
| boyut | int32_t | Belirtilen dizideki bayt sayısı. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::ArrayView\<uint8_t\> | Gönderilecek veri. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::ArrayView\<uint8_t\> | Gönderilecek veri. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::StackArray\<uint8_t, N\>\& | Gönderilecek veri. |
| ofset | int32_t | Belirtilen dizideki bayt cinsinden ofset. |
| boyut | int32_t | Belirtilen dizide, 'offset' parametresinden başlayan bayt sayısı. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::StackArray\<uint8_t, N\>\& | Gönderilecek veri. |
| boyut | int32_t | Belirtilen dizideki bayt sayısı. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::StackArray\<uint8_t, N\>\& | Gönderilecek veri. |
| socketFlags | SocketFlags | Gönderme davranışı. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | System::Details::StackArray\<uint8_t, N\>\& | Gönderilecek veri. |
| remoteEP | System::SharedPtr\<EndPoint\> | Uzak uç nokta. |

### ReturnValue

Gönderilen bayt sayısı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PUB for C++](../../../)
