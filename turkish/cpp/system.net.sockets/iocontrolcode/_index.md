---
title: "System::Net::Sockets::IOControlCode enum"
linktitle: "IOControlCode"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::IOControlCode enum. C++'de IO kontrol kodlarını listeler."
type: docs
weight: 900
url: /tr/cpp/system.net.sockets/iocontrolcode/
---
## IOControlCode enum


Listeler [IO](../../system.io/) kontrol kodlarını.

```cpp
enum class IOControlCode : int64_t
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| AsyncIO | -2147195267 | Soketin asenkron I/O modunu etkinleştirin veya devre dışı bırakın. |
| NonBlockingIO | -2147195266 | Soketi bloklamayan olarak işaretleyin. |
| DataToRead | 1074030207 | Okunmak için mevcut bayt sayısını döndürür. |
| OobDataRead | 1074033415 | Alınmayı bekleyen bant dışı veri hakkında bilgi döndürür. |
| AssociateHandle | -2013265919 | Bu soketi bir yardımcı arayüzün belirtilen tutamağıyla ilişkilendirin. |
| EnableCircularQueuing | 671088642 | Gelen mesaj kuyrukları dolduğunda, en eski kuyruğa alınmış datagramı gelen bir datagramla değiştir. |
| Flush | 671088644 | Bu soket ile ilişkili gönderim kuyruğunun mevcut içeriğini atar. |
| GetBroadcastAddress | 1207959557 | Geçerli soketin adres ailesi için yayın adresini içeren bir SOCKADDR yapısını döndürür. |
| GetExtensionFunctionPointer | -939524090 | İlgili hizmet sağlayıcı tarafından desteklenen belirtilen uzantı işlevine bir işaretçi al. |
| GetQos | -939524089 | Soket ile ilişkili QOS yapısını al. |
| GetGroupQos | -939524088 | Soket grubu için QOS özniteliklerini döndürür. |
| MultipointLoopback | -2013265911 | Yerel bilgisayarda bir uygulama tarafından (aynı soket olmamak zorunda) çoklu yayın oturumunda gönderilen verilerin, döngü geri arabiriminde çoklu yayın hedef grupuna katılan bir soket tarafından alınıp alınmayacağını kontrol eder. |
| MulticastScope | -2013265910 | Bir yönlendirici tarafından bir çoklu yayın paketinin kaç kez iletilebileceğini, TTL veya atlama sayısı olarak da bilinen, kontrol eder. |
| SetQos | -2013265909 | Soket için QOS özniteliklerini ayarlar. |
| SetGroupQos | -2013265908 | Soket grubu için QOS özniteliklerini ayarlar. |
| TranslateHandle | -939524083 | Bir eş arayüz bağlamında geçerli olan soket için bir tutamaç döndürün. |
| RoutingInterfaceQuery | -939524076 | Belirtilen uzak adrese bağlanmak için kullanılabilecek arayüz adreslerini döndürün. |
| RoutingInterfaceChange | -2013265899 | Uzak bir uç noktaya erişmek için kullanılan yerel arayüz değiştiğinde bir bildirim almayı etkinleştirin. |
| AddressListQuery | 1207959574 | Soketin bağlanabileceği yerel arayüzlerin listesini döndürün. |
| AddressListChange | 671088663 | Soketin protokol ailesi için yerel arayüzlerin listesi değiştiğinde bir bildirim almayı etkinleştirin. |
| QueryTargetPnpHandle | 1207959576 | Alttaki sağlayıcının SOCKET tutamacını alın. |
| NamespaceChange | -2013265895 | Bir ad alanı sorgusu geçersiz olduğunda soketin bildirim alıp almayacağını kontrol edin. |
| AddressListSort | -939524071 | Bağlantı kurmak için en uygun kullanılabilir adresi belirlemek amacıyla IPv6 ve IPv4 hedef adreslerinin bir listesini sıralayın. |
| ReceiveAll | -1744830463 | Ağda tüm IPv4 paketlerinin alınmasını etkinleştir. |
| ReceiveAllMulticast | -1744830462 | Ağda tüm çoklu yayın IPv4 paketlerinin alınmasını etkinleştir. |
| ReceiveAllIgmpMulticast | -1744830461 | Ağda tüm IGMP paketlerinin alınmasını etkinleştir. |
| KeepAliveValues | -1744830460 | TCP keep-alive paketlerinin gönderilmesini ve gönderim aralığını kontrol et. |
| AbsorbRouterAlert | -1744830459 | Bu değer, Winsock 2 'SIO_ABSORB_RTRALERT' sabitine eşittir. |
| UnicastInterface | -1744830458 | Giden tek yön (unicast) paketleri için kullanılan arayüzü ayarla. |
| LimitBroadcasts | -1744830457 | Bu değer, Winsock 2 'SIO_LIMIT_BROADCASTS' sabitine eşittir. |
| BindToInterface | -1744830456 | Soketi belirtilen arayüz indeksine bağla. |
| MulticastInterface | -1744830455 | Giden çoklu yayın paketleri için kullanılan arayüzü ayarla. |
| AddMulticastGroupOnInterface | -1744830454 | İndeksiyle tanımlanan bir arayüzü kullanarak çoklu yayın grubuna katılın. |
| DeleteMulticastGroupFromInterface | -1744830453 | Soketi bir çoklu yayın grubundan kaldırın. |

## Ayrıca Bakınız

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PUB for C++](../../)
