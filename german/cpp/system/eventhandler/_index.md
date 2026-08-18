---
title: "System::EventHandler Typedef"
linktitle: "EventHandler"
second_title: "Aspose.PUB für C++"
description: "System::EventHandler Typedef. Stellt eine Methode dar, die auf ein Ereignis reagiert und es verarbeitet. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs in C++ zu verwalten."
type: docs
weight: 11100
url: /de/cpp/system/eventhandler/
---
## EventHandler typedef


Stellt eine Methode dar, die auf ein Ereignis reagiert und es verarbeitet. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
using System::EventHandler =  MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
