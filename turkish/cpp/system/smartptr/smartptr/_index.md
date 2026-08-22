---
title: "System::SmartPtr::SmartPtr yapıcı"
linktitle: "SmartPtr"
second_title: "Aspose.PUB için C++"
description: "System::SmartPtr::SmartPtr yapıcı. Referans verilen dizinin tipini farklı bir tipte yeni dizi oluşturarak dönüştürür. C#'ta desteklenmeyen bir dizi tip dönüşümü C++'ta mevcut olduğunda faydalıdır."
type: docs
weight: 100
url: /tr/cpp/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor


Referans verilen dizinin tipini farklı tipte yeni bir dizi oluşturarak dönüştürür. C#'ta desteklenmeyen bir dizi tip dönüşümü C++'ta faydalı olabilir.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parametre | Açıklama |
| --- | --- |
| Y | Kaynak dizinin tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const SmartPtr\<Array\<Y\>\>\& | Farklı öğe tipine sahip bir kopya oluşturmak için diziye işaretçi. |
| mod | SmartPtrMode | İşaretçi modu. |

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Class [Array](../../array/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor


ptr'nin ilk değeriyle sahiplik bilgisini paylaşan, ancak alakasız ve yönetilmeyen p işaretçisini tutan bir [SmartPtr](../) oluşturur.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const SmartPtr\<P\>\& | Sahipliği paylaşmak için başka bir akıllı işaretçi. |
| p | Pointee_ * | Yönetilecek nesneye işaretçi. |
| mod | SmartPtrMode | İşaretçi modu. |

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor


[SmartPtr](../) nesnesini kopya yapıcıyla oluşturur. Her iki işaretçi de sonradan aynı nesneyi gösterir. İzin verildiğinde tip dönüşümü yapar.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parametre | Açıklama |
| --- | --- |
| Q | x tarafından işaret edilen nesnenin tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Kopyaya işaretçi. |
| mod | SmartPtrMode | İşaretçi modu. |

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) constructor


Kopya, [SmartPtr](../) nesnesi oluşturur. Her iki işaretçi de daha sonra aynı nesneyi gösterir.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Kopyaya işaretçi. |
| mod | SmartPtrMode | İşaretçi modu. |

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::SmartPtr(const Y\&) constructor


Boş dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


| Parametre | Açıklama |
| --- | --- |
| Y | EmptyArrayInitializer türünün yer tutucusu. |

## Ayrıca Bakınız

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor


Belirtilen nesneyi işaret eden [SmartPtr](../) oluşturur veya ham işaretçiyi [SmartPtr](../)'a dönüştürür.

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nesne | Pointee_ * | Pointee. |
| mod | SmartPtrMode | İşaretçi modu. |

## Ayrıca Bakınız

* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructor


[SmartPtr](../) nesnesini taşıyarak oluşturur. Aslında, iki işaretçi aynı kipteyse takas eder. Çağrıdan sonra x kullanılamaz olabilir.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | SmartPtr_\&& | Taşınacak işaretçi. |
| mod | SmartPtrMode | İşaretçi modu. |

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Gerekli kipte bir [SmartPtr](../) nesnesi oluşturur.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mod | SmartPtrMode | İşaretçi modu. |

## Ayrıca Bakınız

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Gerekli kipte bir null işaretçi [SmartPtr](../) nesnesi oluşturur.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mod | std::nullptr_t | İşaretçi modu. |

## Ayrıca Bakınız

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
