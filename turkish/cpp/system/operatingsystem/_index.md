---
title: "System::OperatingSystem sınıfı"
linktitle: "OperatingSystem"
second_title: "Aspose.PUB için C++"
description: "System::OperatingSystem sınıfı. Belirli bir işletim sistemini temsil eder ve onun hakkında bilgi sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek, yığına (stack) ya da new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 5100
url: /tr/cpp/system/operatingsystem/
---
## OperatingSystem class


Belirli bir işletim sistemini temsil eder ve onun hakkında bilgi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek, yığına (stack) ya da new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class OperatingSystem
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Platform](./get_platform/)() const | Geçerli nesne tarafından temsil edilen işletim sisteminin platform tanımlayıcısını döndürür. |
| [get_ServicePack](./get_servicepack/)() const | Geçerli nesne tarafından temsil edilen işletim sisteminin servis paketi adını döndürür. |
| [get_Version](./get_version/)() const | Geçerli nesne tarafından temsil edilen işletim sisteminin sürümünü temsil eden bir [Version](../version/) nesnesine sabit referans döndürür. |
| [get_VersionString](./get_versionstring/)() const | Geçerli nesne tarafından temsil edilen işletim sisteminin sürümünün dize temsilini döndürür. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&) | Belirli bir platform kimliği ve sürüm olarak belirtilen bir işletim sistemini temsil eden bir örnek oluşturur. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&, const String\&) | Belirli bir platform kimliği, sürüm ve servis paketi olarak belirtilen bir işletim sistemini temsil eden bir örnek oluşturur. |
| [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen işletim sisteminin sürümünün dize temsilini döndürür. |
## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
