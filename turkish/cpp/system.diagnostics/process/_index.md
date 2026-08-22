---
title: "System::Diagnostics::Process sınıfı"
linktitle: "Process"
second_title: "Aspose.PUB için C++"
description: "System::Diagnostics::Process sınıfı. İşlem bilgilerini ve manipülasyonunu kapsüller. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak C++'da geçirin."
type: docs
weight: 300
url: /tr/cpp/system.diagnostics/process/
---
## Process class


Kapsüller işlem bilgilerini ve manipülasyonunu. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class Process : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_EnableRaisingEvents](./get_enableraisingevents/)() const | İşlem sonlandığında Exited olayının tetiklenip tetiklenmeyeceğini alır. |
| [get_ExitCode](./get_exitcode/)() const | İşlem çıkış kodunu alır. |
| [get_PrivateMemorySize64](./get_privatememorysize64/)() const | İşlemin özel bellek kümesi boyutunu alır. |
| [get_ProcessName](./get_processname/)() const | İşlem adını alır. |
| [get_StandardError](./get_standarderror/)() const | İşlem hata çıktısını okumak için bir okuyucu sağlar. Henüz uygulanmadı. |
| [get_StandardOutput](./get_standardoutput/)() const | İşlem standart çıktısını okumak için bir okuyucu sağlar. Henüz uygulanmadı. |
| [get_StartInfo](./get_startinfo/)() const | İşlem başlangıç bilgilerini alır. |
| [get_WorkingSet64](./get_workingset64/)() const | İşlem bellek çalışma kümesi boyutunu alır. |
| static [GetCurrentProcess](./getcurrentprocess/)() | Mevcut işlem hakkında bilgi alır. Yalnızca [Windows](../../system.windows/). |
| [GetOutputText](./getoutputtext/)() const | İşlem çıktı metnini alır. |
| [set_EnableRaisingEvents](./set_enableraisingevents/)(bool) | İşlem sonlandığında Exited olayının tetiklenip tetiklenmeyeceğini ayarlar. |
| [Start](./start/)() | Önceden tanımlı parametrelerle işlemi başlatır. |
| static [Start](./start/)(const String\&, const String\&) | Belirtilen yol ve argümanlarla işlemi başlatır. |
| static [Start](./start/)(const SharedPtr\<ProcessStartInfo\>\&) | Belirtilen yol ve argümanlarla işlemi başlatır. |
| [WaitForExit](./waitforexit/)(int) | İşlemin çıkmasını bekler. Henüz uygulanmadı. |
| [WaitForExit](./waitforexit/)() | İşlemin çıkmasını bekler, bitene kadar geri dönmez. |
| virtual [~Process](./~process/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PUB for C++](../../)
