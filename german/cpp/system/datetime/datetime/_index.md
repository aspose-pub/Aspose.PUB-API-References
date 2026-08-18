---
title: "System::DateTime::DateTime Konstruktor"
linktitle: "DateTime"
second_title: "Aspose.PUB für C++"
description: "System::DateTime::DateTime Konstruktor. Erstellt eine Instanz, die den kleinstmöglichen Datums- und Uhrzeitwert darstellt, gleich MinValue in C++."
type: docs
weight: 100
url: /de/cpp/system/datetime/datetime/
---
## DateTime::DateTime() constructor


Erstellt eine Instanz, die den kleinsten möglichen Datums‑ und Zeitwert darstellt, gleich MinValue.

```cpp
System::DateTime::DateTime()
```

## Siehe auch

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(const DateTime\&) constructor


Kopiert eine Instanz.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dt | const DateTime\& | Eine Instanz der [DateTime](../)-Klasse, um den dargestellten Datum‑ und Zeitwert zu kopieren von |

## Siehe auch

* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int, int, int) constructor


Erstellt eine Instanz, die einen Datums‑ und Zeitwert darstellt, der als bestimmtes Jahr, Monat und Tag angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Jahr | int | Das Jahr, das von der zu erstellenden Instanz dargestellt werden soll. |
| Monat | int | Der Monat des **year**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Tag | int | Der Tag des **month**, der von der zu erstellenden Instanz dargestellt werden soll. |

## Siehe auch

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Erstellt eine Instanz, die einen Datums‑ und Zeitwert darstellt, der als bestimmtes Jahr, Monat und Tag im angegebenen Kalender angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Jahr | int | Das Jahr, das von der zu erstellenden Instanz dargestellt werden soll. |
| Monat | int | Der Monat des **year**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Tag | int | Der Tag des **month**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Kalender | const SharedPtr\<Globalization::Calendar\>\& | Der Kalender, der verwendet wird, um das angegebene **year**, **month** und **day** zu interpretieren. |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int) constructor


Erstellt eine Instanz, die einen Datums‑ und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute und Sekunde angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Jahr | int | Das Jahr, das von der zu erstellenden Instanz dargestellt werden soll. |
| Monat | int | Der Monat des **year**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Tag | int | Der Tag des **month**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Stunde | int | Die Stunde des **day**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Minute | int | Die Minute der **hour**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Sekunde | int | Die Sekunde der **minute**, die von der zu erstellenden Instanz dargestellt werden soll. |

## Siehe auch

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) constructor


Erstellt eine Instanz, die einen Datums‑ und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute und Sekunde im angegebenen Kalender angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Jahr | int | Das Jahr, das von der zu erstellenden Instanz dargestellt werden soll. |
| Monat | int | Der Monat des **year**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Tag | int | Der Tag des **month**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Stunde | int | Die Stunde des **day**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Minute | int | Die Minute der **hour**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Sekunde | int | Die Sekunde der **minute**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Kalender | const SharedPtr\<Globalization::Calendar\>\& | Der Kalender, der verwendet wird, um das angegebene **year**, **month** und **day** zu interpretieren. |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) constructor


Erstellt eine Instanz, die einen Datums‑ und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute und Sekunde angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Jahr | int | Das Jahr, das von der zu erstellenden Instanz dargestellt werden soll. |
| Monat | int | Der Monat des **year**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Tag | int | Der Tag des **month**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Stunde | int | Die Stunde des **day**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Minute | int | Die Minute der **hour**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Sekunde | int | Die Sekunde der **minute**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Typ | DateTimeKind | Der Wert, der angibt, ob die bereitgestellten Datums- und Uhrzeitparameter eine lokale Zeit, UTC-Zeit oder keine von beiden angeben. |

## Siehe auch

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) constructor


Erstellt eine Instanz, die einen Datums‑ und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute, Sekunde und Millisekunde im angegebenen Kalender angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Jahr | int | Das Jahr, das von der zu erstellenden Instanz dargestellt werden soll. |
| Monat | int | Der Monat des **year**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Tag | int | Der Tag des **month**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Stunde | int | Die Stunde des **day**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Minute | int | Die Minute der **hour**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Sekunde | int | Die Sekunde der **minute**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Millisekunde | int | Die Millisekunde der **second**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Typ | const SharedPtr\<Globalization::Calendar\>\& | Der Wert, der angibt, ob die bereitgestellten Datums- und Uhrzeitparameter eine lokale Zeit, UTC-Zeit oder keine von beiden angeben. |
| Kalender | DateTimeKind | Der Kalender, der verwendet wird, um das angegebene **year**, **month** und **day** zu interpretieren. |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) constructor


Erstellt eine Instanz, die einen Datums‑ und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute, Sekunde und Millisekunde angegeben ist.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Jahr | int | Das Jahr, das von der zu erstellenden Instanz dargestellt werden soll. |
| Monat | int | Der Monat des **year**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Tag | int | Der Tag des **month**, der von der zu erstellenden Instanz dargestellt werden soll. |
| Stunde | int | Die Stunde des **day**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Minute | int | Die Minute der **hour**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Sekunde | int | Die Sekunde der **minute**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Millisekunde | int | Die Millisekunde der **second**, die von der zu erstellenden Instanz dargestellt werden soll. |
| Typ | DateTimeKind | Der Wert, der angibt, ob die bereitgestellten Datums- und Uhrzeitparameter eine lokale Zeit, UTC-Zeit oder keine von beiden angeben. |

## Siehe auch

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind, bool) constructor


Erstellen Sie eine Instanz, die einen Datums- und Uhrzeitwert darstellt, der als Anzahl von Ticks angegeben ist. FÜR INTERNEN GEBRAUCH.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ticks | int64_t | Die Anzahl der 100‑ns‑Intervalle, die seit dem 1. Januar 0001 00:00:00.000 im georgischen Kalender vergangen sind. |
| Typ | DateTimeKind | Der Wert, der angibt, ob der Parameter **ticks** eine lokale Zeit, UTC‑Zeit oder keine von beiden angibt. |
| is_ambiguous_local_dst | bool | Wahr, wenn das angegebene Datum und die Uhrzeit mehrdeutig sind und auf viele UTC‑Zeiten abgebildet werden können. |

## Siehe auch

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## DateTime::DateTime(int64_t, DateTimeKind) constructor


Erstellt eine Instanz, die einen Datums‑ und Zeitwert darstellt, der als Anzahl von Ticks angegeben ist.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ticks | int64_t | Die Anzahl der 100‑ns‑Intervalle, die seit dem 1. Januar 0001 00:00:00.000 im georgischen Kalender vergangen sind. |
| Typ | DateTimeKind | Der Wert, der angibt, ob der Parameter **ticks** eine lokale Zeit, UTC‑Zeit oder keine von beiden angibt. |

## Siehe auch

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
