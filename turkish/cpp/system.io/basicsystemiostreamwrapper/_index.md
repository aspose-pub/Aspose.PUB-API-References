---
title: "System::IO::BasicSystemIOStreamWrapper sınıfı"
linktitle: "BasicSystemIOStreamWrapper"
second_title: "Aspose.PUB için C++"
description: "System::IO::BasicSystemIOStreamWrapper sınıfı. C++'ta iç tampon olarak BasicSystemIOStreamBuf kullanan bir std::iostream-benzeri sarmalayıcıyı temsil eder."
type: docs
weight: 500
url: /tr/cpp/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper class


İç tampon olarak [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) kullanan bir std::iostream-benzeri sarmalayıcıyı temsil eder.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamWrapper\&&) | İşaretçileri sıfırlamak ve [swap()](./swap/) fonksiyonunu çağırmak için taşıma yapıcı ve taşıma atama operatöründe kullanılır. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Yeni bir [BasicSystemIOStreamWrapper](./) örneği oluşturur. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const BasicSystemIOStreamWrapper\&) | Kopya yapıcı. Silindi. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(BasicSystemIOStreamWrapper\&&) | Taşıma yapıcı. |
| [operator=](./operator=/)(const BasicSystemIOStreamWrapper\&) | Kopya atama operatörü. Silindi. |
| [operator=](./operator=/)(BasicSystemIOStreamWrapper\&&) | Taşıma atama operatörü. |
| [swap](./swap/)(BasicSystemIOStreamWrapper\&) | *this ve **right**'ı takas etmek için çağrı, eğer eşit değillerse. |
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
