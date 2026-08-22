---
title: "System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule method"
linktitle: "CreateFloatingDateRule"
second_title: "Aspose.PUB için C++"
description: "System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule method. C++'de belirli bir ayın belirli bir haftasındaki belirli bir günde gerçekleşen zaman değişikliğini temsil eden bir kayan tarih kuralını (floating-date rule) temsil eden TransitionTime sınıfının bir örneğini oluşturur."
type: docs
weight: 1100
url: /tr/cpp/system/timezoneinfo/transitiontime/createfloatingdaterule/
---
## TransitionTime::CreateFloatingDateRule method


Belirli bir ayın belirli bir haftasındaki belirli bir günde gerçekleşen zaman değişikliğini temsil eden bir kayan tarih kuralını (floating-date rule) temsil eden [TransitionTime](../) sınıfının bir örneğini oluşturur.

```cpp
static TransitionTime System::TimeZoneInfo::TransitionTime::CreateFloatingDateRule(DateTime time_of_day, int month, int week, DayOfWeek day_of_week)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| time_of_day | DateTime | Zaman değişikliğinin gerçekleştiği belirli zaman. |
| ay | int | Zaman değişikliğinin gerçekleştiği yılın ayı. |
| week | int | Zaman değişikliğinin gerçekleştiği ayın haftası. |
| day_of_week | DayOfWeek | Zaman değişikliğinin gerçekleştiği haftanın günü. |

### ReturnValue

Açıklanan zaman değişikliğini temsil eden [TransitionTime](../) sınıfının bir örneği.

## Ayrıca Bakınız

* Class [TransitionTime](../)
* Class [DateTime](../../../datetime/)
* Enum [DayOfWeek](../../../dayofweek/)
* Class [TransitionTime](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PUB for C++](../../../../)
