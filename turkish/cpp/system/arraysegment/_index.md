---
title: "System::ArraySegment sınıfı"
linktitle: "ArraySegment"
second_title: "Aspose.PUB için C++"
description: "System::ArraySegment sınıfı. Tek boyutlu bir dizinin bir segmentini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 300
url: /tr/cpp/system/arraysegment/
---
## ArraySegment class


Tek boyutlu bir dizinin bir segmentini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename T>class ArraySegment : public System::Object
```


| Parametre | Açıklama |
| --- | --- |
| T | Dizi segmenti öğelerinin türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>) |  |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>, int32_t, int32_t) |  |
| [ArraySegment](./arraysegment/)() |  |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(ArraySegment\<T\>) |  |
| [get_Array](./get_array/)() |  |
| [get_Count](./get_count/)() |  |
| [get_Offset](./get_offset/)() |  |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../object/gethashcode/) yönteminin bir benzeridir. Özel nesnelerin hashlenmesini sağlar. |
## Açıklamalar



```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Diziyi oluştur ve doldur.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Tüm diziyi içeren dizi segmentini oluştur.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Dizi segmenti öğelerini yazdır.
  Print(fullArray);

  // Dizi segmentini oluştur.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Dizi segmenti öğelerini yazdır.
  Print(segment);

  return 0;
}
/*
This code example produces the following output:
First Second Third
Second Third
*/
```

## Ayrıca Bakınız

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
