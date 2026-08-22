---
title: "System::WeakPtr::WeakPtr yapıcı"
linktitle: "WeakPtr"
second_title: "Aspose.PUB için C++"
description: "System::WeakPtr::WeakPtr yapıcı. C++'da x'in işaret ettiği aynı göstericiyi referans alan zayıf gösterici oluşturur."
type: docs
weight: 100
url: /tr/cpp/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor


x işaretçisinin işaret ettiği aynı nesneyi referans alan zayıf işaretçi oluşturur.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


| Parametre | Açıklama |
| --- | --- |
| Q | Kaynak göstericinin işaret ettiği tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Pointer to copy pointee value from. |

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## WeakPtr::WeakPtr(const SmartPtr_\&) constructor


ptr işaretçisinin işaret ettiği aynı nesneyi referans alan zayıf işaretçi oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Pointer to copy pointee value from. |

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor


Zayıf işaretçiyi kopya yapıcı ile oluşturur.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


| Parametre | Açıklama |
| --- | --- |
| Q | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const WeakPtr\<Q\>\& | Pointer to copy pointee value from. |

## Ayrıca Bakınız

* Class [WeakPtr](../)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## WeakPtr::WeakPtr(const WeakPtr_\&) constructor


Zayıf işaretçiyi kopya yapıcı ile oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const WeakPtr_\& | Pointer to copy pointee value from. |

## Ayrıca Bakınız

* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## WeakPtr::WeakPtr(Pointee_ *) constructor


Verilen nesneye zayıf işaretçi oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | Pointee_ * | [Object](../../object/) için zayıf gösterici oluştur. |

## Ayrıca Bakınız

* Typedef [Pointee_](../pointee_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## WeakPtr::WeakPtr(SmartPtr_\&&) constructor


Zayıf işaretçiyi taşıma yapıcı ile oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | SmartPtr_\&& | İşaret edilen değerin taşınacağı gösterici. |

## Ayrıca Bakınız

* Typedef [SmartPtr_](../smartptr_/)
* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## WeakPtr::WeakPtr(std::nullptr_t) constructor


Null işaretçi oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## Ayrıca Bakınız

* Class [WeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
