---
title: "System::Xml::Xsl::IXsltContextVariable Klasse"
linktitle: "IXsltContextVariable"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Xsl::IXsltContextVariable Klasse. Stellt eine Schnittstelle zu einer angegebenen Variablen bereit, die im Stylesheet während der Laufzeitausführung in C++ definiert ist."
type: docs
weight: 200
url: /de/cpp/system.xml.xsl/ixsltcontextvariable/
---
## IXsltContextVariable class


Bietet eine Schnittstelle zu einer angegebenen Variable, die im Stylesheet zur Laufzeit definiert ist.

```cpp
class IXsltContextVariable : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XsltContext\>) | Evaluiert die Variable zur Laufzeit und gibt ein Objekt zurück, das den Wert der Variable darstellt. |
| virtual [get_IsLocal](./get_islocal/)() | Gibt einen Wert zurück, der angibt, ob die Variable lokal ist. |
| virtual [get_IsParam](./get_isparam/)() | Gibt einen Wert zurück, der angibt, ob die Variable ein Extensible Stylesheet Language Transformations (XSLT)-Parameter ist. Dies kann ein Parameter für ein Stylesheet oder eine Vorlage sein. |
| virtual [get_VariableType](./get_variabletype/)() | Gibt den XPathResultType zurück, der den XML Path Language ([XPath](../../system.xml.xpath/))-Typ der Variable darstellt. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PUB for C++](../../)
