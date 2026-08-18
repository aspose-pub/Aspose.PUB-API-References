---
title: "System::Drawing::Region::Equals-Methode"
linktitle: "Equals"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Region::Equals-Methode. Bestimmt, ob die angegebene Region identisch ist mit der Region, die vom aktuellen Objekt auf der angegebenen Zeichenfläche in C++ dargestellt wird."
type: docs
weight: 600
url: /de/cpp/system.drawing/region/equals/
---
## Region::Equals method


Bestimmt, ob die angegebene Region identisch ist mit der vom aktuellen Objekt auf der angegebenen Zeichenfläche dargestellten Region.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r | const SharedPtr\<Region\>\& | Die Region, mit der diese Region verglichen werden soll |
| g | const SharedPtr\<Graphics\>\& | Eine Zeichenfläche |

### ReturnValue

True, wenn das Innere der angegebenen Region identisch ist mit dem Inneren der Region, die vom aktuellen objcet dargestellt wird, wenn die mit dem **g**-Parameter verbundene Transformation angewendet wird; andernfalls - false

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Class [Region](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PUB for C++](../../../)
