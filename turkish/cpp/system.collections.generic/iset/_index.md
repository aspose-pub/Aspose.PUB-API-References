---
title: "System::Collections::Generic::ISet sınıfı"
linktitle: "ISet"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::ISet sınıfı. Benzersiz öğeler kümesini içeren bir koleksiyonun arayüzü. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2700
url: /tr/cpp/system.collections.generic/iset/
---
## ISet class


Benzersiz öğeler kümesini içeren bir koleksiyonun arayüzü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [ExceptWith](./exceptwith/)(IEnumerablePtr) | Bir grup öğeyi kaldırır. |
| virtual [IntersectWith](./intersectwith/)(IEnumerablePtr) | Farklı bir kapsayıcıda bulunmayan öğeleri kaldırır. |
| virtual [IsProperSubsetOf](./ispropersubsetof/)(IEnumerablePtr) | Geçerli kümenin diğer kapsayıcının katı alt kümesi olup olmadığını denetler. |
| virtual [IsProperSupersetOf](./ispropersupersetof/)(IEnumerablePtr) | Geçerli kümenin diğer kapsayıcının katı üst kümesi olup olmadığını denetler. |
| virtual [IsSubsetOf](./issubsetof/)(IEnumerablePtr) | Geçerli kümenin diğer kapsayıcının alt kümesi olup olmadığını denetler. |
| virtual [IsSupersetOf](./issupersetof/)(IEnumerablePtr) | Geçerli kümenin diğer kapsayıcının üst kümesi olup olmadığını denetler. |
| virtual [Overlaps](./overlaps/)(IEnumerablePtr) | Kümenin diğer kapsayıcıyla çakışıp çakışmadığını denetler. |
| virtual [SetEquals](./setequals/)(IEnumerablePtr) | Kümenin ve kapsayıcının aynı öğeleri içerip içermediğini denetler. |
| virtual [SymmetricExceptWith](./symmetricexceptwith/)(IEnumerablePtr) | İki kapsayıcının simetrik farkını hesaplar. Her iki kapsayıcıda da bulunan tüm öğeleri kaldırır, ancak aynı zamanda **other** içinde bulunan ancak geçerli kümede olmayan tüm öğeleri ekler. |
| virtual [UnionWith](./unionwith/)(IEnumerablePtr) | Henüz geçerli kümede bulunmayan, belirtilen koleksiyondan öğeler ekler. |
| virtual [~ISet](./~iset/)() | Yıkıcı. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | RTTI bilgisi. |

## Ayrıca Bakınız

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
