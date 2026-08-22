---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::connect yöntemi"
linktitle: "bağla"
second_title: "Aspose.PUB için C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::connect yöntemi. Belirtilen delegeyi C++'ta koleksiyona ekler."
type: docs
weight: 400
url: /tr/cpp/system/multicastdelegate_returntype(argumenttypes...)_/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) method


Belirtilen delegeyi koleksiyona ekler.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geri çağırma | Callback | Koleksiyona eklenecek delegeler |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) method


Belirtilen nesnenin belirtilen statik olmayan metodunu delegeler koleksiyonuna ekler.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


| Parametre | Açıklama |
| --- | --- |
| MemberType | Delege koleksiyonuna eklenecek statik olmayan yöntemin türü |
| ClassType | The type of the object method of which is to be added to the delegate |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| üye | MemberType ClassType::* | Belirtilen nesnenin statik olmayan yöntemine bir işaretçi |
| obj | ClassType * | A pointer to an object member method of which is to be added to the delegate collection |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Belirtilen nesnenin belirtilen statik olmayan metodunu delegeler koleksiyonuna ekler.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


| Parametre | Açıklama |
| --- | --- |
| MemberType | Delege koleksiyonuna eklenecek statik olmayan yöntemin türü |
| ClassType | The type of the object method of which is to be added to the delegate collection |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| üye | MemberType ClassType::* | Belirtilen nesnenin statik olmayan yöntemine bir işaretçi |
| obj | const SharedPtr\<ClassType\>\& | A shared pointer to an object member method of which is to be added to the delegate collection |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) method


Belirtilen MulticastDelegate nesnesini delegeler koleksiyonuna ekler.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | MulticastDelegate\& | An instance of the MulticastDelegate class to add to the delegate collection |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) method


Belirtilen fonksiyon nesnesini delegeler koleksiyonuna ekler. Fonksiyon nesnesi, koleksiyona eklenmeden önce Callback delege tipine dönüştürülür.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


| Parametre | Açıklama |
| --- | --- |
| R | The return type of the function object to add to the collection |
| Args | The argument list of the function object to add to the collection |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| f | std::function\<R(Args...)> | The function object to add to the collection |

### ReturnValue

Kendine bir referans

## Ayrıca Bakınız

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
