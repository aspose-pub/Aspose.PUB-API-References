---
title: System::Xml::XmlWhitespace class
linktitle: XmlWhitespace
second_title: Aspose.PUB for C++
description: 'System::Xml::XmlWhitespace class. Represents white space in element content in C++.'
type: docs
weight: 4300
url: /cpp/system.xml/xmlwhitespace/
---
## XmlWhitespace class


Represents white space in element content.

```cpp
class XmlWhitespace : public System::Xml::XmlCharacterData
```

## Methods

| Method | Description |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Creates a duplicate of this node. |
| [get_LocalName](./get_localname/)() override | Returns the local name of the node. |
| [get_Name](./get_name/)() override | Returns the qualified name of the node. |
| [get_NodeType](./get_nodetype/)() override | Returns the type of the node. |
| [get_PreviousText](./get_previoustext/)() override | Returns the text node that immediately precedes this node. |
| [get_Value](./get_value/)() override | Returns the value of the node. |
| [set_Value](./set_value/)(String) override | Sets the value of the node. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Saves all the children of the node to the specified [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Saves the node to the specified [XmlWriter](../xmlwriter/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlCharacterData](../xmlcharacterdata/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)