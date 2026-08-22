---
title: "System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule yöntemi"
linktitle: "CreateAdjustmentRule"
second_title: "Aspose.PUB için C++"
description: "System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule yöntemi. C++'da belirtilen parametrelerle tanımlanan bir zaman ayarlama kuralını temsil eden AdjustmentRule sınıfının bir örneğini oluşturur."
type: docs
weight: 1000
url: /tr/cpp/system/timezoneinfo/adjustmentrule/createadjustmentrule/
---
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&) method


Belirtilen parametrelerle tanımlanan bir zaman ayarlama kuralını temsil eden [AdjustmentRule](../) sınıfının bir örneğini oluşturur.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| date_start | DateTime | Ayarlama kuralının yürürlüğe girdiği tarih ve saat. |
| date_end | DateTime | Ayarlama kuralının etkisini kaybettiği tarih ve saat. |
| daylight_delta | TimeSpan | Saat diliminin yaz saati uygulamasını oluşturmak için gereken süre. |
| daylight_transition_start | const TransitionTime\& | Yaz saatinden standart saate geçiş hakkında bilgi. |
| daylight_transition_end | const TransitionTime\& | Standart saatten yaz saatine geçiş hakkında bilgi. |

### ReturnValue

[AdjustmentRule](../) sınıfının, açıklanan saat dilimi ayarlama kuralını temsil eden bir örneği.

## Ayrıca Bakınız

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PUB for C++](../../../../)
## AdjustmentRule::CreateAdjustmentRule(DateTime, DateTime, TimeSpan, const TransitionTime\&, const TransitionTime\&, TimeSpan, bool) method


Belirtilen parametrelerle tanımlanan bir zaman ayarlama kuralını temsil eden [AdjustmentRule](../) sınıfının bir örneğini oluşturur.

```cpp
static AdjustmentRulePtr System::TimeZoneInfo::AdjustmentRule::CreateAdjustmentRule(DateTime date_start, DateTime date_end, TimeSpan daylight_delta, const TransitionTime &daylight_transition_start, const TransitionTime &daylight_transition_end, TimeSpan base_utc_offset_delta, bool no_daylight_transitions)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| date_start | DateTime | Ayarlama kuralının yürürlüğe girdiği tarih ve saat. |
| date_end | DateTime | Ayarlama kuralının etkisini kaybettiği tarih ve saat. |
| daylight_delta | TimeSpan | Saat diliminin yaz saati uygulamasını oluşturmak için gereken süre. |
| daylight_transition_start | const TransitionTime\& | Yaz saatinden standart saate geçiş hakkında bilgi. |
| daylight_transition_end | const TransitionTime\& | Standart saatten yaz saatine geçiş hakkında bilgi. |
| base_utc_offset_delta | TimeSpan | Varsayılan UTC ofsetinden delta. |
| no_daylight_transitions | bool | Ayarlama kuralının yaz saatine geçişi varsayıp varsımadığını belirtir. |

### ReturnValue

[AdjustmentRule](../) sınıfının, açıklanan saat dilimi ayarlama kuralını temsil eden bir örneği.

## Ayrıca Bakınız

* Typedef [AdjustmentRulePtr](../../adjustmentruleptr/)
* Class [DateTime](../../../datetime/)
* Class [TimeSpan](../../../timespan/)
* Class [TransitionTime](../../transitiontime/)
* Class [AdjustmentRule](../)
* Class [TimeZoneInfo](../../)
* Namespace [System](../../../)
* Library [Aspose.PUB for C++](../../../../)
