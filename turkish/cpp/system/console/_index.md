---
title: "System::Console sınıfı"
linktitle: "Console"
second_title: "Aspose.PUB için C++"
description: "System::Console sınıfı. Verileri standart çıktı akışına yazdırmak için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. C++'ta hiçbir şekilde onun örneklerini oluşturmamalısınız."
type: docs
weight: 1400
url: /tr/cpp/system/console/
---
## Console class


Verileri standart çıktı akışına göndermek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir tiptir. Onun hiçbir şekilde örneklerini oluşturmayın.

```cpp
class Console
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Beep](./beep/)() | UYGULANMADI. |
| static [get_Error](./get_error/)() | Standart hata akışını temsil eden nesneye işaret eden bir paylaşımlı gösterici döndürür. |
| static [get_In](./get_in/)() | Standart giriş akışını temsil eden nesneye işaret eden bir paylaşımlı gösterici döndürür. |
| static [get_Out](./get_out/)() | Standart çıktı akışını temsil eden nesneye işaret eden bir paylaşımlı gösterici döndürür. |
| static [Mute](./mute/)(bool) | Standart çıktı akışını susturur veya sesini açar. |
| static [ReadKey](./readkey/)() | UYGULANMADI. |
| static [SetError](./seterror/)(const SharedPtr\<System::IO::TextWriter\>\&) | Belirtilen nesneyi sınıfın Error özelliğine atar. |
| static [SetIn](./setin/)(const SharedPtr\<System::IO::TextReader\>\&) | In özelliğini belirtilen TextReader nesnesine ayarlar. |
| static [SetOut](./setout/)(const SharedPtr\<System::IO::TextWriter\>\&) | Belirtilen nesneyi sınıfın Out özelliğine atar. |
| static [Write](./write/)(const SharedPtr\<T\>\&) | Belirtilen nesnenin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(bool) | bool değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(char_t) | Belirtilen karakter değerini standart çıktı akışına yazar. |
| static [Write](./write/)(const ArrayPtr\<char_t\>\&) | Belirtilen karakter dizisinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(const Decimal\&) | [Decimal](../decimal/) değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(double) | Çift duyarlıklı kayan nokta değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(float) | Tek duyarlıklı kayan nokta değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(int32_t) | 32 bit tam sayı değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(int64_t) | 64 bit tam sayı değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(const String\&) | Belirtilen dize nesnesini standart çıktı akışına yazar. |
| static [Write](./write/)(const char_t *) | Belirtilen C-dizesini standart çıktı akışına yazar. |
| static [Write](./write/)(const TypeInfo\&) | [TypeInfo](../typeinfo/) değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(uint32_t) | İmzasız 32 bit tam sayı değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(uint64_t) | İmzasız 64 bit tam sayı değerinin dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Belirtilen karakter dizisinin belirtilen aralığının dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(const String\&, Args\&&...) | Belirtilen formatına göre biçimlendirilmiş belirtilen argümanların dize temsilini standart çıktı akışına yazar. |
| static [Write](./write/)(const char *) |  |
| static [WriteLine](./writeline/)() | Geçerli satır sonlandırıcısını standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const SharedPtr\<T\>\&) | Belirtilen nesnenin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(bool) | Bool değerinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(char_t) | Belirtilen karakter değerini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) | Belirtilen karakter dizisinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const Decimal\&) | [Decimal](../decimal/) değerinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(double) | Çift duyarlıklı kayan nokta değerinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(float) | Tek duyarlıklı kayan nokta değerinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(int32_t) | 32 bit tam sayı değerinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(int64_t) | 64 bit tam sayı değerinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const String\&) | Belirtilen dize nesnesini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const char_t *) | Belirtilen C-dizesini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const TypeInfo\&) | [TypeInfo](../typeinfo/) değerinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(uint32_t) | İmzasız 32 bit tam sayı değerinin dize temsilini, ardından geçerli satır sonlandırıcısını, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(uint64_t) | İmzasız 64-bit tamsayı değerinin dize temsilini, mevcut satır sonlandırıcısını ekleyerek, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int, int) | Belirtilen karakter dizisinin belirtilen aralığının dize temsilini, mevcut satır sonlandırıcısını ekleyerek, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const Exception\&) | Belirtilen Exception nesnesinin dize temsilini, mevcut satır sonlandırıcısını ekleyerek, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const String\&, Args\&&...) | Belirtilen argümanların, belirtilen formata göre biçimlendirilmiş dize temsilini, mevcut satır sonlandırıcısını ekleyerek, standart çıktı akışına yazar. |
| static [WriteLine](./writeline/)(const char *) |  |
## Açıklamalar



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Hello mesajını yazdır.
  Console::WriteLine(u"Hello, world!");

  // 'std::array' sınıfının bir örneğini oluştur.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Dizinin elemanlarını yazdır.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
This code example produces the following output:
Hello, world!
1 2 3 4 5
*/
```

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
