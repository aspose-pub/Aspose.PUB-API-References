---
title: "System::MakeArray method"
linktitle: "MakeArray"
second_title: "Aspose.PUB için C++"
description: "System::MakeArray yöntemi. Belirtilen argümanları C++'ta yapıcıya geçiren yeni bir Array nesnesi oluşturan bir fabrika işlevi."
type: docs
weight: 21300
url: /tr/cpp/system/makearray/
---
## System::MakeArray(Args\&&...) method


Belirtilen argümanları yapıcıya geçiren yeni bir [Array](../array/) nesnesi oluşturan bir fabrika işlevi.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun oluşturduğu [Array](../array/) nesnesinin eleman tipinin |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | Args\&&... | Oluşturulan [Array](../array/) nesnesinin yapıcısına geçirilen argümanlar |

### ReturnValue

Oluşturulan [Array](../array/) nesnesine işaret eden bir akıllı işaretçi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::MakeArray(Integral, Args\&&...) method


Belirtilen argümanları yapıcıya geçiren yeni bir [Array](../array/) nesnesi oluşturan bir fabrika işlevi.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun oluşturduğu [Array](../array/) nesnesinin eleman tipinin |
| Integral | Dizi boyutunun türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | Integral | Oluşturulan dizinin boyutu. |
| args | Args\&&... | Oluşturulan [Array](../array/) nesnesinin yapıcısına geçirilen argümanlar |

### ReturnValue

Oluşturulan [Array](../array/) nesnesine işaret eden bir akıllı işaretçi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::MakeArray(std::initializer_list\<T\>) method


Belirtilen başlatma listesindeki öğelerle yeni bir [Array](../array/) nesnesi oluşturan, dolduran ve bu [Array](../array/) nesnesine işaret eden bir akıllı işaretçi döndüren bir fabrika işlevi.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun oluşturduğu [Array](../array/) nesnesinin eleman tipinin |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlat | std::initializer_list\<T\> | Diziyi doldurmak için öğeleri içeren başlatma listesi |

### ReturnValue

Oluşturulan [Array](../array/) nesnesine işaret eden bir akıllı işaretçi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
