---
title: "System::IterateOver yöntemi"
linktitle: "IterateOver"
second_title: "Aspose.PUB için C++"
description: "System::IterateOver yöntemi. Bu işlev özelliği, bir enumerable (veya iterable) nesneyi sarmalar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, C++'de varsayılan hedef türüyle Enumerable için."
type: docs
weight: 20600
url: /tr/cpp/system/iterateover/
---
## System::IterateOver(const Enumerable *) method


Bu işlev özelliği, bir enumerable (veya iterable) nesneyi sarmalar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, varsayılan hedef türüyle Enumerable için.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanmış nesnenin türü |

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::IterateOver(const Enumerable *) method


Bu işlev özelliği, bir enumerable (veya iterable) nesneyi sarmalar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, begin(), end() yöntemleri olmayan Enumerable için hedef tür argümanı ile (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tür, iterator tarafından döndürülmelidir |
| Enumerable | Sarmalanmış nesnenin türü |

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Bu işlev özelliği, bir enumerable (veya iterable) nesneyi sarmalar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, begin(), end() yöntemleri olmayan Enumerable için hedef tür argümanı ile (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tür, iterator tarafından döndürülmelidir |
| Enumerable | Sarmalanmış nesnenin türü |

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Bu işlev özelliği, bir enumerable (veya iterable) nesneyi sarmalar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, begin(), end() yöntemleri olmayan Enumerable için varsayılan hedef tür argümanı ile (auto& value : IterateOver(enumerable)) ve aşağıdaki C# koduna benzer şekilde foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanmış nesnenin türü |

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Bu işlev özelliği, bir enumerable (veya iterable) nesneyi sarmalar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, begin(), end() yöntemleri olan Enumerable için varsayılan hedef tür argümanı ile (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanmış nesnenin türü |

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Bu işlev özelliği, bir enumerable (veya iterable) nesneyi sarmalar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, begin(), end() yöntemleri olan Enumerable için hedef türü, iteratorün orijinal value_type'ı ile aynı olan.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanmış nesnenin türü |
| T | Iterator tarafından döndürülmesi gereken hedef tür |

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Bu işlev özelliği, bir enumerable (veya iterable) nesneyi sarmalar, böylece range-based for döngüsüyle kullanılabilir. Bu aşırı yükleme, begin(), end() yöntemleri olan Enumerable için farklı bir hedef tür ve iteratorün orijinal value_type'ı ile birlikte.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parametre | Açıklama |
| --- | --- |
| Enumerable | Sarmalanmış nesnenin türü |
| T | Iterator tarafından döndürülmesi gereken hedef tür |

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
