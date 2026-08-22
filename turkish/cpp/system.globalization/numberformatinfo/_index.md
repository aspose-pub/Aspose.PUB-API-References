---
title: "System::Globalization::NumberFormatInfo sınıfı"
linktitle: "NumberFormatInfo"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::NumberFormatInfo sınıfı. Sayıların nasıl biçimlendirileceği hakkında bilgi tutar. Ayarlama işlemleri yalnızca okunamaz olmayan nesnelerde etkinleştirilir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığına (stack) ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1900
url: /tr/cpp/system.globalization/numberformatinfo/
---
## NumberFormatInfo class


Sayının nasıl biçimlendirileceği hakkında bilgi tutar. Ayarlama işlemleri yalnızca okunamaz olmayan nesnelerde etkinleştirilir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığına (stack) ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() override | Biçim bilgilerini kopyalar. |
| [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Para birimi ondalık basamak sayısını alır. |
| [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Para birimi ondalık ayırıcıyı alır. |
| [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Para birimi grup ayırıcıyı alır. |
| [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Grup başına para birimi ondalık basamak sayısını alır. |
| [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Para birimi negatif desenini alır. |
| [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Para birimi pozitif desenini alır. |
| [get_CurrencySymbol](./get_currencysymbol/)() const | Para birimi simgesini alır. |
| static [get_CurrentInfo](./get_currentinfo/)() | Geçerli iş parçacığının kültür tanımlı sayı biçim bilgilerini alır. |
| [get_DigitSubstitution](./get_digitsubstitution/)() const | Bir rakamın şeklinin nasıl görüntüleneceğini belirten bir değeri alır. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Değişmez kültür tanımlı sayı biçim bilgilerini alır. |
| [get_IsReadOnly](./get_isreadonly/)() const | Biçimin yalnızca okunabilir olup olmadığını kontrol eder. |
| [get_NaNSymbol](./get_nansymbol/)() const | NaN (Not-a-Number) sembolünü alır. |
| [get_NativeDigits](./get_nativedigits/)() const | Rakam sembollerini alır (0'dan 9'a). |
| [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Negatif sonsuzluk sembolünü alır. |
| [get_NegativeSign](./get_negativesign/)() const | Negatif işareti alır. |
| [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Ondalık basamak sayısını alır. |
| [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Ondalık ayırıcıyı alır. |
| [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Sayı grubu ayıracını alır. |
| [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Her grup için basamak sayısını alır. |
| [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Negatif sayı desenini alır. |
| [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Yüzde değerlerinde ondalık basamak sayısını alır. |
| [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Yüzde değerlerinde ondalık ayırıcıyı alır. |
| [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Yüzde değerlerinde grup ayırıcıyı alır. |
| [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Yüzde değeri grupları başına basamak sayısını alır. |
| [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Yüzde negatif desenini alır. |
| [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Yüzde pozitif desenini alır. |
| [get_PercentSymbol](./get_percentsymbol/)() const | Yüzde simgesini alır. |
| [get_PerMilleSymbol](./get_permillesymbol/)() const | Promil simgesini alır. |
| [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Pozitif sonsuzluk simgesini alır. |
| [get_PositiveSign](./get_positivesign/)() const | Pozitif işareti alır. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Belirli tipte biçimleyiciyi alır. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Biçim sağlayıcıyla ilişkili biçimleyiciyi alır. |
| [NumberFormatInfo](./numberformatinfo/)() | Varsayılan yapıcı (invariant [NumberFormatInfo](./)). |
| [operator=](./operator=/)(const NumberFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(NumberFormatInfoPtr) | Biçimleyicinin yalnızca okunabilir sürümünü alır. |
| [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Para birimi ondalık basamak sayısını ayarlar. |
| [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const String\&) | Para birimi ondalık ayırıcıyı ayarlar. |
| [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const String\&) | Para birimi grup ayırıcıyı ayarlar. |
| [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const ArrayPtr\<int\>\&) | Grup başına para birimi ondalık basamak sayısını ayarlar. |
| [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Para birimi negatif desenini ayarlar. |
| [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Para birimi pozitif desenini ayarlar. |
| [set_CurrencySymbol](./set_currencysymbol/)(const String\&) | Para birimi simgesini ayarlar. |
| [set_DigitSubstitution](./set_digitsubstitution/)(DigitShapes) | Bir rakamın şeklinin nasıl görüntüleneceğini belirten bir değeri ayarlar. |
| [set_NaNSymbol](./set_nansymbol/)(const String\&) | Not-a-Number (NaN) simgesini ayarlar. |
| [set_NativeDigits](./set_nativedigits/)(const ArrayPtr\<String\>\&) | Rakam simgelerini (0'dan 9'a) ayarlar. |
| [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const String\&) | Negatif sonsuzluk simgesini ayarlar. |
| [set_NegativeSign](./set_negativesign/)(const String\&) | Negatif işaretini ayarlar. |
| [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Ondalık basamak sayısını ayarlar. |
| [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const String\&) | Ondalık ayırıcıyı ayarlar. |
| [set_NumberGroupSeparator](./set_numbergroupseparator/)(const String\&) | Sayı grubu ayırıcıyı ayarlar. |
| [set_NumberGroupSizes](./set_numbergroupsizes/)(const ArrayPtr\<int\>\&) | Her grup için rakam sayısını ayarlar. |
| [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Sayı negatif desenini ayarlar. |
| [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Yüzde değerlerinde ondalık basamak sayısını ayarlar. |
| [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const String\&) | Yüzde değerlerinde ondalık ayırıcıyı ayarlar. |
| [set_PercentGroupSeparator](./set_percentgroupseparator/)(const String\&) | Yüzde değerlerinde grup ayırıcıyı ayarlar. |
| [set_PercentGroupSizes](./set_percentgroupsizes/)(const ArrayPtr\<int\>\&) | Yüzde değeri grubundaki rakam sayısını ayarlar. |
| [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Yüzde negatif desenini ayarlar. |
| [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Yüzde pozitif desenini ayarlar. |
| [set_PercentSymbol](./set_percentsymbol/)(const String\&) | Yüzde simgesini ayarlar. |
| [set_PerMilleSymbol](./set_permillesymbol/)(const String\&) | Promil simgesini ayarlar. |
| [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const String\&) | Pozitif sonsuzluk simgesini ayarlar. |
| [set_PositiveSign](./set_positivesign/)(const String\&) | Pozitif işaretini ayarlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
