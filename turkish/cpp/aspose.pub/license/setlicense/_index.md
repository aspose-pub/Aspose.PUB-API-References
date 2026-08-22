---
title: "Aspose::Pub::License::SetLicense yöntemi"
linktitle: "SetLicense"
second_title: "Aspose.PUB için C++"
description: "Aspose::Pub::License::SetLicense yöntemi. Bileşeni C++'ta lisanslar."
type: docs
weight: 200
url: /tr/cpp/aspose.pub/license/setlicense/
---
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Bileşeni lisanslar.

```cpp
void Aspose::Pub::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | System::SharedPtr\<System::IO::Stream\> | Lisansı içeren bir akış. |
## Açıklamalar



Bu yöntemi bir akıştan lisans yüklemek için kullanın.

<javaName>void setLicense(java.io.InputStream stream)</javaName>
## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [License](../)
* Namespace [Aspose::Pub](../../)
* Library [Aspose.PUB for C++](../../../)
## License::SetLicense(System::String) method


Bileşeni lisanslar.

```cpp
void Aspose::Pub::License::SetLicense(System::String licenseName)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseName | System::String | Tam veya kısa bir dosya adı<ms> ya da gömülü kaynağın adı</ms> olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |
## Açıklamalar


Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

<ms>

2. **Aspose** bileşen derlemesini içeren klasör.

3. İstemcinin çağıran derlemesini içeren klasör.

4. Giriş (başlangıç) derlemesini içeren klasör.

5. İstemcinin çağıran derlemesindeki gömülü kaynak.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Açık yol.

2. İstemcinin çağıran derlemesindeki gömülü kaynak.

</ms>

<java>

2. **Aspose** bileşen JAR dosyasını içeren klasör.

3. İstemcinin çağıran JAR dosyasını içeren klasör.

</java>

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [License](../)
* Namespace [Aspose::Pub](../../)
* Library [Aspose.PUB for C++](../../../)
