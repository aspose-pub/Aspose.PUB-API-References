---
title: "System::Threading::WaitHandle::WaitOne method"
linktitle: "WaitOne"
second_title: "Aspose.PUB için C++"
description: "System::Threading::WaitHandle::WaitOne yöntemi. C++'da tutamaç sınırsız bir süre için tetiklenene kadar bekler."
type: docs
weight: 600
url: /tr/cpp/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() method


İşaretçinin sınırsız bir süre boyunca tetiklenmesini bekler.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### ReturnValue

Zaman aşımı oluşmadığı için her zaman true döner.

## Ayrıca Bakınız

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## WaitHandle::WaitOne(int) method


İşaretçinin tetiklenmesini bekler.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| millisecondsTimeout | int | [Zaman Aşımı](../../timeout/) bekleme süresi, milisaniye cinsinden; -1 sonsuz beklemeyi, 0 kontrol edip dönmeyi, pozitif değerler ise zaman aşımını ifade eder. |

### ReturnValue

Tutamaç tetiklendiğinde true, zaman aşımı aşıldığında false.

## Ayrıca Bakınız

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## WaitHandle::WaitOne(int, bool) method


İşaretçinin tetiklenmesini bekler.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| millisecondsTimeout | int | [Zaman Aşımı](../../timeout/) bekleme süresi, milisaniye cinsinden; -1 sonsuz beklemeyi, 0 kontrol edip dönmeyi, pozitif değerler ise zaman aşımını ifade eder. |
| exitContext | bool | True ise, bekleme tutamaç üzerindeki kilidi, onu beklemeden önce bırakmalıdır. |

### ReturnValue

Tutamaç tetiklendiğinde true, zaman aşımı aşıldığında false.

## Ayrıca Bakınız

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## WaitHandle::WaitOne(TimeSpan) method


İşaretçinin tetiklenmesini bekler.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| timeout | TimeSpan | Beklenecek milisaniye sayısını temsil eden bir [System::TimeSpan](../../../system/timespan/), ya da süresiz beklemeyi temsil eden -1 milisaniyeyi gösteren bir [System::TimeSpan](../../../system/timespan/). |

### ReturnValue

Tutamaç tetiklendiğinde true, zaman aşımı aşıldığında false.

## Ayrıca Bakınız

* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
