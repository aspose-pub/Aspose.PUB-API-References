---
title: "System::IO::BasicSystemIOStreamWrapper Klasse"
linktitle: "BasicSystemIOStreamWrapper"
second_title: "Aspose.PUB für C++"
description: "System::IO::BasicSystemIOStreamWrapper Klasse. Stellt einen std::iostream-ähnlichen Wrapper dar, der BasicSystemIOStreamBuf als internen Puffer in C++ verwendet."
type: docs
weight: 500
url: /de/cpp/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper class


Stellt einen std::iostream-ähnlichen Wrapper dar, der [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) als internen Puffer verwendet.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AssignRV](./assignrv/)(BasicSystemIOStreamWrapper\&&) | Wird im Move-Konstruktor und Move-Zuweisungsoperator verwendet, um Zeiger zurückzusetzen und [swap()](./swap/) aufzurufen. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) | Erstellt eine neue Instanz von [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const BasicSystemIOStreamWrapper\&) | Kopierkonstruktor. Gelöscht. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(BasicSystemIOStreamWrapper\&&) | Move‑Konstruktor. |
| [operator=](./operator=/)(const BasicSystemIOStreamWrapper\&) | Kopierzuweisungsoperator. Gelöscht. |
| [operator=](./operator=/)(BasicSystemIOStreamWrapper\&&) | Move-Zuweisungsoperator. |
| [swap](./swap/)(BasicSystemIOStreamWrapper\&) | Aufruf von swap *this und **right**, wenn sie nicht gleich sind. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [char_type](./char_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
| [traits_type](./traits_type/) |  |
## Siehe auch

* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
