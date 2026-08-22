---
title: "System::Net::Sockets::SocketOptionName enum"
linktitle: "SocketOptionName"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::SocketOptionName enum. C++'daki Socket sınıfı için soket seçenek adlarını tanımlar."
type: docs
weight: 1600
url: /tr/cpp/system.net.sockets/socketoptionname/
---
## SocketOptionName enum


[Socket](../socket/) sınıfı için soket seçenek adlarını tanımlar.

```cpp
enum class SocketOptionName
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Debug | 1 | Hata ayıklama bilgilerini kaydet. |
| AcceptConnection | 2 | Bir soketin gelen bir bağlantıyı dinleyip dinlemediğini gösterir. |
| ReuseAddress | 4 | Bir soketin zaten kullanımda olan adrese bağlanıp bağlanamayacağını gösterir. |
| KeepAlive | 8 | Bir soket bağlantısı için 'Keep-Alive' paketlerini etkinleştirir. |
| DontRoute | 16 | Bir paketin doğrudan arayüz adreslerine gönderilip gönderilmediğini gösterir. |
| Broadcast | 32 | Bir soketin yayın mesajlarını gönderip gönderemeyeceğini gösterir. |
| UseLoopback | 64 | Mümkün olduğunda donanımı atlar. |
| Linger | 128 | Sistem, kapatma girişiminde süreci, veriyi iletebilir hale gelene kadar engelleyecektir. |
| OutOfBandInline | 256 | Normal veri akışında bant dışı verileri alır. |
| DontLinger | n/a | Bir soketin beklemeden kapatılıp kapatılmayacağını gösterir. |
| ExclusiveAddressUse | n/a | Bir soket, bağlanan adresi yalnızca kendisi kullanacaktır. |
| SendBuffer | 4097 | Gönderme tampon boyutunu belirtir. |
| ReceiveBuffer | 4098 | Alma tampon boyutunu belirtir. |
| SendLowWater | 4099 | Gönderme işlemleri için minimum veri miktarını belirtir. |
| ReceiveLowWater | 4100 | Alma işlemleri için minimum veri miktarını belirtir. |
| SendTimeout | 4101 | Eşzamanlı gönderme işlemleri için zaman aşımını belirtir. |
| ReceiveTimeout | 4102 | Eşzamanlı alma işlemleri için zaman aşımını belirtir. |
| Error | 4103 | Hata durumunu döndürür ve temizler. |
| Tür | 4104 | Bir soket türü döndürür. |
| ReuseUnicastPort | 12295 | Sistemin giden bağlantılar için geçici bağlantı noktası tahsisatını erteleyip ertelemeyeceğini gösterir. |
| MaxConnections | 2147483647 | Bu seçenek desteklenmiyor. Dinleme için maksimum kuyruk uzunluğunu belirtmek amacıyla kullanılmıştı. |
| IPOptions | 1 | Giden datagramlara eklenmesi gereken IP seçeneğini belirtir. |
| HeaderIncluded | 2 | Başlık, giden datagramlara eklenir. |
| TypeOfService | 3 | IP başlığının hizmet alanı tipini değiştirin. |
| IpTimeToLive | 4 | IP yaşam süresi. |
| MulticastInterface | 9 | Giden çoklu yayın paketleri için arayüzü ayarlayın. |
| MulticastTimeToLive | 10 | IP çoklu yayın yaşam süresi. |
| MulticastLoopback | 11 | IP çoklu yayın döngü geri dönüşü. |
| AddMembership | 12 | Bir IP grup üyeliği ekleyin. |
| DropMembership | 13 | Bir IP grup üyeliğini bırakın. |
| DontFragment | 14 | IP datagramlarını parçalamayın. |
| AddSourceMembership | 15 | IP grup/kaynağına katılın. |
| DropSourceMembership | 16 | IP grup/kaynağını bırakın. |
| BlockSource | 17 | IP grup/kaynağını engelleyin. |
| UnblockSource | 18 | IP grup/kaynağının engelini kaldırın. |
| PacketInformation | 19 | IPv4 için paket bilgilerini al. |
| HopLimit | 21 | Paketin HOP sayısını içeren bir tam sayı döndürür. |
| IPProtectionLevel | 23 | IPv6 soketinin belirtilen kapsamla sınırlanmasını sağlar. |
| IPv6Only | 27 | Soket yalnızca IPv6 paketleri göndermek ve almak için sınırlıdır. |
| NoDelay | 1 | Gönderilen paketlerin birleştirilmesi için Nagle algoritmasını devre dışı bırakır. |
| BsdUrgent | 2 | RFC-1222'de tanımlandığı gibi acil veriyi kullanın. |
| Expedited | 2 | RFC-1222'de tanımlandığı gibi hızlı veriyi kullanın. |
| NoChecksum | 1 | UDP veri paketlerini sıfır kontrol toplamı ile gönder. |
| ChecksumCoverage | 20 | UDP kontrol toplamı kapsamını ayarlayın veya alın. |
| UpdateAcceptContext | 28683 | Bir istemci soketini, dinleme soketinin aynı özellikleriyle günceller. |
| UpdateConnectContext | 28688 | Bir istemci soketini, dinleme soketinin aynı özellikleriyle günceller. |

## Ayrıca Bakınız

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PUB for C++](../../)
