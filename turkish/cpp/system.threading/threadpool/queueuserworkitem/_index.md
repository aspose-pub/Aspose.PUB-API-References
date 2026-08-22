---
title: "System::Threading::ThreadPool::QueueUserWorkItem method"
linktitle: "QueueUserWorkItem"
second_title: "Aspose.PUB için C++"
description: "System::Threading::ThreadPool::QueueUserWorkItem method. C++'da parametresiz geri çağırma ile mevcut olan iş öğesini kuyruğa ekler."
type: docs
weight: 600
url: /tr/cpp/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) method


İş öğesini, parametresi olmayan geri çağırma ile mevcut olan kuyruğa ekler.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geri çağırma | WaitCallback | İş olarak kullanılacak geri çağırma işlevi. |

### ReturnValue

Her zaman true döndürür.

## Ayrıca Bakınız

* Typedef [WaitCallback](../../waitcallback/)
* Class [ThreadPool](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) method


İş öğesini, parametresi olmayan geri çağırma ile mevcut olan kuyruğa ekler.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geri çağırma | WaitCallback | İş olarak kullanılacak geri çağırma işlevi. |
| durum | const System::SharedPtr\<System::Object\>\& | İş işlevi parametresi. |

### ReturnValue

Her zaman true döndürür.

## Ayrıca Bakınız

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPool](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PUB for C++](../../../)
