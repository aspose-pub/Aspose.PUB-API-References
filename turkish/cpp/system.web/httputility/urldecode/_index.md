---
title: "System::Web::HttpUtility::UrlDecode yöntemi"
linktitle: "UrlDecode"
second_title: "Aspose.PUB için C++"
description: "System::Web::HttpUtility::UrlDecode yöntemi. URI parçacığını bayt dizisinden C++'ta çözer."
type: docs
weight: 300
url: /tr/cpp/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) method


Bayt dizisinden URI parçacığını çözer.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | const System::ArrayPtr\<uint8_t\>\& | Kodlanmış URI parçacığı. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Kullanılacak kodlama. |

### ReturnValue

Çözülmüş URI parçacığı.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PUB for C++](../../../)
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) method


Bayt dizisinden URI parçacığını çözer.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | const System::ArrayPtr\<uint8_t\>\& | Kodlanmış URI parçacığı. |
| ofset | int32_t | Verilen bayt dizisindeki offset. |
| sayım | int32_t | Okunacak bayt sayısı. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Kullanılacak kodlama. |

### ReturnValue

Çözülmüş URI parçacığı.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PUB for C++](../../../)
## HttpUtility::UrlDecode(String) method


Dizgiden URI parçacığını çözer.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | String | Kodlanmış URI parçacığı. |

### ReturnValue

Çözülmüş URI parçacığı.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PUB for C++](../../../)
## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) method


Dizgiden URI parçacığını çözer.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | String | Kodlanmış URI parçacığı. |
| e | System::SharedPtr\<Text::Encoding\> | Kullanılacak kodlama. |

### ReturnValue

Çözülmüş URI parçacığı.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PUB for C++](../../../)
