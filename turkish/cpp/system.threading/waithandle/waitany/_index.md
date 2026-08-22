---
title: "System::Threading::WaitHandle::WaitAny method"
linktitle: "WaitAny"
second_title: "Aspose.PUB için C++"
description: "System::Threading::WaitHandle::WaitAny yöntemi. C++'da tutamaçlardan herhangi birinin tetiklenmesini bekler."
type: docs
weight: 200
url: /tr/cpp/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


İşaretçilerden herhangi birinin tetiklenmesini bekler.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Beklenmesi gereken tutamaçlar. |

### ReturnValue

waitHandles içindeki her öğe sinyal aldığında true; aksi takdirde yöntem hiç dönmez.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


İşaretçilerden herhangi birinin tetiklenmesini bekler.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Beklenmesi gereken tutamaçlar. |
| millisecondsTimeout | int | [Zaman Aşımı](../../timeout/) bekleme süresi, milisaniye cinsinden; -1 sonsuz beklemeyi, 0 kontrol edip dönmeyi, pozitif değerler ise zaman aşımını ifade eder. |

### ReturnValue

Herhangi bir tutamaç tetiklendiğinde true, zaman aşımı aşıldığında false.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


İşaretçilerden herhangi birinin tetiklenmesini bekler.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Beklenmesi gereken tutamaçlar. |
| timeout | TimeSpan | Beklenecek milisaniye sayısını temsil eden bir [System::TimeSpan](../../../system/timespan/), ya da süresiz beklemeyi temsil eden -1 milisaniyeyi gösteren bir [System::TimeSpan](../../../system/timespan/). |

### ReturnValue

Herhangi bir tutamaç tetiklendiğinde true, zaman aşımı aşıldığında false.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
