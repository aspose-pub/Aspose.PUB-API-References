---
title: "System::IO::BasicSystemIStreamWrapper class"
linktitle: "BasicSystemIStreamWrapper"
second_title: "Aspose.PUB için C++"
description: "System::IO::BasicSystemIStreamWrapper sınıfı. C++'ta iç tampon olarak BasicSystemIOStreamBuf kullanan bir std::istream-benzeri sarmalayıcıyı temsil eder."
type: docs
weight: 600
url: /tr/cpp/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper class


İç tampon olarak [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) kullanan bir std::istream-benzeri sarmalayıcıyı temsil eder.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIStreamWrapper\&&) | İşaretçileri sıfırlamak ve [swap()](./swap/) fonksiyonunu çağırmak için taşıma yapıcı ve taşıma atama operatöründe kullanılır. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Yeni bir [BasicSystemIStreamWrapper](./) örneği oluşturur. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const BasicSystemIStreamWrapper\&) | Kopya yapıcı. Silindi. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(BasicSystemIStreamWrapper\&&) | Taşıma yapıcı. |
| [operator=](./operator=/)(const BasicSystemIStreamWrapper\&) | Kopya atama operatörü. Silindi. |
| [operator=](./operator=/)(BasicSystemIStreamWrapper\&&) | Taşıma atama operatörü. |
| [swap](./swap/)(BasicSystemIStreamWrapper\&) | *this ve **right**'ı takas etmek için çağrı, eğer eşit değillerse. |
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
