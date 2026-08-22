---
title: "System::IO::BasicSystemOStreamWrapper sınıfı"
linktitle: "BasicSystemOStreamWrapper"
second_title: "Aspose.PUB için C++"
description: "System::IO::BasicSystemOStreamWrapper sınıfı. C++'da BasicSystemIOStreamBuf'ı iç tampon olarak kullanan bir std::ostream-benzeri sarmalayıcıyı temsil eder."
type: docs
weight: 700
url: /tr/cpp/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper class


[BasicSystemIOStreamBuf](../basicsystemiostreambuf/) iç tamponu olarak kullanan bir std::ostream-benzeri sarmalayıcıyı temsil eder.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemOStreamWrapper\&&) | İşaretçileri sıfırlamak ve [swap()](./swap/) fonksiyonunu çağırmak için taşıma yapıcı ve taşıma atama operatöründe kullanılır. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | [BasicSystemOStreamWrapper](./) sınıfının yeni bir örneğini oluşturur. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const BasicSystemOStreamWrapper\&) | Kopya yapıcı. Silindi. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(BasicSystemOStreamWrapper\&&) | Taşıma yapıcı. |
| [operator=](./operator=/)(const BasicSystemOStreamWrapper\&) | Kopya atama operatörü. Silindi. |
| [operator=](./operator=/)(BasicSystemOStreamWrapper\&&) | Taşıma atama operatörü. |
| [swap](./swap/)(BasicSystemOStreamWrapper\&) | *this ve **right**'ı takas etmek için çağrı, eğer eşit değillerse. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [char_type](./char_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
| [traits_type](./traits_type/) |  |
## Ayrıca Bakınız

* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
