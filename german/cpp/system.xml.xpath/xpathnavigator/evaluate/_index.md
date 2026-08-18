---
title: "System::Xml::XPath::XPathNavigator::Evaluate Methode"
linktitle: "Evaluate"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XPath::XPathNavigator::Evaluate Methode. Wertet den XPathExpression aus und gibt das typisierte Ergebnis in C++ zurück."
type: docs
weight: 1200
url: /de/cpp/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) method


Wertet den [XPathExpression](../../xpathexpression/) aus und gibt das typisierte Ergebnis zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Ein [XPathExpression](../../xpathexpression/), der ausgewertet werden kann. |

### ReturnValue

Das Ergebnis des Ausdrucks ([Boolean](../../../system/boolean/), Zahl, Zeichenfolge oder Knotensatz). Dies entspricht jeweils den Objekten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) oder [XPathNodeIterator](../../xpathnodeiterator/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) method


Verwendet den bereitgestellten Kontext, um den [XPathExpression](../../xpathexpression/) auszuwerten, und gibt das typisierte Ergebnis zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | Ein [XPathExpression](../../xpathexpression/), der ausgewertet werden kann. |
| context | SharedPtr\<XPathNodeIterator\> | Ein [XPathNodeIterator](../../xpathnodeiterator/), der auf den ausgewählten Knotensatz zeigt, auf dem die Auswertung durchgeführt werden soll. |

### ReturnValue

Das Ergebnis des Ausdrucks ([Boolean](../../../system/boolean/), Zahl, Zeichenfolge oder Knotensatz). Dies entspricht jeweils den Objekten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) oder [XPathNodeIterator](../../xpathnodeiterator/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::Evaluate(String) method


Wertet den angegebenen [XPath](../../)-Ausdruck aus und gibt das typisierte Ergebnis zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | String | Eine Zeichenfolge, die einen auswertbaren [XPath](../../)-Ausdruck darstellt. |

### ReturnValue

Das Ergebnis des Ausdrucks ([Boolean](../../../system/boolean/), Zahl, Zeichenfolge oder Knotensatz). Dies entspricht jeweils den Objekten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) oder [XPathNodeIterator](../../xpathnodeiterator/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) method


Wertet den angegebenen [XPath](../../)-Ausdruck aus und gibt das typisierte Ergebnis zurück, wobei das angegebene [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt zur Auflösung von Namensraumpräfixen im [XPath](../../)-Ausdruck verwendet wird.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | String | Eine Zeichenfolge, die einen auswertbaren [XPath](../../)-Ausdruck darstellt. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | Das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt, das zur Auflösung von Namensraumpräfixen im [XPath](../../)-Ausdruck verwendet wird. |

### ReturnValue

Das Ergebnis des Ausdrucks ([Boolean](../../../system/boolean/), Zahl, Zeichenfolge oder Knotensatz). Dies entspricht jeweils den Objekten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) oder [XPathNodeIterator](../../xpathnodeiterator/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
