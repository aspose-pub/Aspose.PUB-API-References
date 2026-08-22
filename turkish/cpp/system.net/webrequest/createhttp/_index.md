---
title: "System::Net::WebRequest::CreateHttp metodu"
linktitle: "CreateHttp"
second_title: "Aspose.PUB için C++"
description: "System::Net::WebRequest::CreateHttp metodu. Belirtilen URI'yi kullanarak C++'ta WebRequest sınıfının yeni bir örneğini oluşturur."
type: docs
weight: 300
url: /tr/cpp/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) method


Belirtilen URI'yi kullanarak [WebRequest](../) sınıfının yeni bir örneğini oluşturur.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| requestUriString | String | [WebRequest](../) sınıfının yeni bir örneğini oluşturmak için kullanılan URI. |

### ReturnValue

Yeni oluşturulmuş bir WebRequest-class örneği.
## Açıklamalar



Belirtilen URI, [http://](http://) veya [https://](https://) dışındaki herhangi bir şemayla başlarsa NotSupportedException fırlatılacaktır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) method


Belirtilen URI'yi kullanarak [WebRequest](../) sınıfının yeni bir örneğini oluşturur.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| requestUri | System::SharedPtr\<Uri\> | [WebRequest](../) sınıfının yeni bir örneğini oluşturmak için kullanılan URI. |

### ReturnValue

Yeni oluşturulmuş bir WebRequest-class örneği.
## Açıklamalar



Belirtilen URI, [http://](http://) veya [https://](https://) dışındaki herhangi bir şemayla başlarsa NotSupportedException fırlatılacaktır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [Uri](../../../system/uri/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
