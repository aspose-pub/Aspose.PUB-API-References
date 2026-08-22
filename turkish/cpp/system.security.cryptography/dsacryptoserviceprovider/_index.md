---
title: "System::Security::Cryptography::DSACryptoServiceProvider sınıfı"
linktitle: "DSACryptoServiceProvider"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider sınıfı. CSP biçiminde DSA algoritması. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmaya asla izin vermeyin, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1000
url: /tr/cpp/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider class


[DSA](../dsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CreateSignature](./createsignature/)(ByteArrayPtr) override | Belirtilen veri için [DSA](../dsa/) imzası oluştur. |
| [Dispose](./dispose/)() override | Nesneyle ilişkili verileri serbest bırakır. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | Yapıcı. Varsayılan parametreleri kullanır. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const DSAParameters\&) | Yapıcı. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Yapıcı. Henüz uygulanmadı. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t) | Yapıcı. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Yapıcı. Henüz uygulanmadı. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Anahtar hakkında bilgi içeren bloğu dışa aktarır. Henüz uygulanmadı. |
| [ExportParameters](./exportparameters/)(bool) override | CSP parametrelerini dışa aktarır. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | [CspKeyContainerInfo](../cspkeycontainerinfo/) nesnesini alır. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Nesneyle ilişkili anahtar değişim algoritmasını denetler. |
| [get_KeySize](./get_keysize/)() override | Anahtar boyutunu alır. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Anahtarın CSP nesnesinde kalıcı olup olmadığını denetler. |
| [get_PublicOnly](./get_publiconly/)() const | CSP nesnesinde yalnızca açık anahtarın bulunup bulunmadığını denetler. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Kullanılacak imza algoritmasını alır. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Anahtarın kullanıcı deposu yerine makine deposunda kalıcı olup olmadığını denetler. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Anahtar hakkında bilgi içeren bloğu içe aktarır. Henüz uygulanmadı. |
| [ImportParameters](./importparameters/)(DSAParameters) override | Veri yapısından tüm parametreleri içe aktarır. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Anahtarın CSP nesnesinde kalıcı olup olmadığını tanımlar. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Anahtarın kullanıcı deposu yerine makine deposunda kalıcı olup olmadığını tanımlar. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Belirtilen giriş değerinin imzasını hesaplar. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&) | Belirtilen giriş değerinin imzasını hesaplar. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Belirtilen giriş değerinin imzasını hesaplar. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | RTTI bilgisi. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | RTTI bilgisi. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | RTTI bilgisi. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Belirtilen giriş değerinin imzasını hesaplar. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Veri imzasını kontrol eder. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Belirtilen verinin imzasının geçerli olduğunu doğrular. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Belirtilen verinin imzasının geçerli olduğunu doğrular. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Belirtilen ikili akışın imzasının geçerli olduğunu doğrular. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Veri imzasını kontrol eder. |
| [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) override | Belirtilen veri için [DSA](../dsa/) imzasını doğrula. |
## Ayrıca Bakınız

* Class [DSA](../dsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PUB for C++](../../)
