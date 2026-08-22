---
title: "System::DynamicWeakPtr sınıfı"
linktitle: "DynamicWeakPtr"
second_title: "Aspose.PUB için C++"
description: "System::DynamicWeakPtr sınıfı. Saklanan nesnenin şablon argümanlarının gösterici modlarını izleyen ve her atamadan sonra güncelleyen akıllı gösterici sınıfı. Bu tür, diğer nesnelerin silinmesini yönetmek için bir göstericidir. C++'ta yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir."
type: docs
weight: 2200
url: /tr/cpp/system/dynamicweakptr/
---
## DynamicWeakPtr class


Saklanan nesnenin şablon argümanlarının işaretçi modlarını izleyen ve her atamadan sonra güncelleyen akıllı işaretçi sınıfı. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığıt üzerinde ayrılmalı ve fonksiyonlara ya değer olarak ya da const referansla geçirilmelidir.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


| Parametre | Açıklama |
| --- | --- |
| Pointee | tür. |
| trunkMode | Akıllı göstericinin kendisinin modu, paylaşımlı veya zayıf. |
| weakLeafs | Zayıf gösterici moduna ayarlanması gereken saklanan türün şablon argümanlarının indeksleri. |
## Nested classes

* Class [Reference](./reference/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Null akıllı gösterici oluşturur. |
| [DynamicWeakPtr](./dynamicweakptr/)(Pointee_ *) | Verilen nesneyi işaret eden akıllı gösterici oluşturur. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr_\&) | Akıllı göstericiyi kopya yapıcı ile oluşturur. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr\<Q\>\&) | Akıllı göstericiyi kopya yapıcı ile oluşturur. |
| [DynamicWeakPtr](./dynamicweakptr/)(const DynamicWeakPtr_\&) | Akıllı göstericiyi kopya yapıcı ile oluşturur. |
| [DynamicWeakPtr](./dynamicweakptr/)(SmartPtr_\&&) | Akıllı göstericiyi taşıma yapıcı ile oluşturur. |
| [operator=](./operator=/)(SmartPtr_\&&) | Akıllı göstericiyi taşıma ataması yapar. |
| [operator=](./operator=/)(const SmartPtr_\&) | Akıllı göstericiyi kopya ataması yapar. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Akıllı göstericiyi kopya ataması yapar. |
| [operator=](./operator=/)(typename SmartPtr_::Pointee_ *) | Akıllı göstericiyi atar. |
| [operator=](./operator=/)(std::nullptr_t) | Akıllı göstericiyi null olarak ayarlar. |
| [operator==](./operator==/)(std::nullptr_t) const | Akıllı işaretçinin null olup olmadığını kontrol eder. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Kendi tür takma adı. |
| [Pointee_](./pointee_/) | İşaret edilen tip. |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) temel sınıf takma adı. |

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
