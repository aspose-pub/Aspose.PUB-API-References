---
title: "System::setter_post_increment_wrap Methode"
linktitle: "setter_post_increment_wrap"
second_title: "Aspose.PUB für C++"
description: "System::setter_post_increment_wrap Methode. Der Translator übersetzt C#''s Post-Inkrement‑Ausdrücke, die auf die Eigenschaft einer Instanz abzielen, für die Setter und Getter definiert sind, in einen Aufruf dieser Funktion (Überladung für const‑Getter) in C++."
type: docs
weight: 34400
url: /de/cpp/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) method


Der Translator übersetzt C#'s Post-Inkrement‑Ausdrücke, die auf die Eigenschaft einer Instanz abzielen, für die Setter und Getter definiert sind, in einen Aufruf dieser Funktion (Überladung für const‑Getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft. |
| Host | - Klasse der zu modifizierenden Instanz |
| HostConstGet | - Der Host selbst oder dessen Basistyp, in dem der Getter der Eigenschaft definiert ist |
| HostSet | - Der Host selbst oder dessen Basistyp, in dem der Setter der Eigenschaft definiert ist |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | Host *const | Instanz, für die Getter und Setter aufgerufen werden. |
| pGetter | T(HostConstGet::*)() const | Funktionszeiger, der auf die Getter‑Funktion der Eigenschaft zeigt |
| pSetter | void(HostSet::*)(T) | Funktionszeiger, der auf die Setter‑Funktion der Eigenschaft zeigt |

### ReturnValue

Der Wert der Eigenschaft vor dem Inkrementieren

## Siehe auch

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


Der Übersetzer übersetzt die Postinkrement‑Ausdrücke von C# für die Eigenschaft einer Instanz, die Setter und Getter definiert hat, in einen Aufruf dieser Funktion (Überladung für nicht‑konstante Getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft. |
| Host | - Klasse der zu modifizierenden Instanz |
| HostGet | - Der Host selbst oder dessen Basistyp, in dem der Getter der Eigenschaft definiert ist |
| HostSet | - Der Host selbst oder dessen Basistyp, in dem der Setter der Eigenschaft definiert ist |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | Host *const | Instanz, für die Getter und Setter aufgerufen werden. |
| pGetter | T(HostGet::*)() | Funktionszeiger, der auf die Getter‑Funktion der Eigenschaft zeigt |
| pSetter | void(HostSet::*)(T) | Funktionszeiger, der auf die Setter‑Funktion der Eigenschaft zeigt |

### ReturnValue

Der Wert der Eigenschaft vor dem Inkrementieren

## Siehe auch

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) method


Der Übersetzer übersetzt die Postinkrement‑Ausdrücke von C# für die Eigenschaft einer Klasse, die Setter und Getter definiert hat, in einen Aufruf dieser Funktion.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Eigenschaft |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pGetter | T(*)() | Funktionszeiger, der auf die freie Getter‑Funktion der Eigenschaft zeigt |
| pSetter | void(*)(T) | Funktionszeiger, der auf die freie Setter‑Funktion der Eigenschaft zeigt |

### ReturnValue

Der Wert der Eigenschaft vor dem Inkrementieren

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
