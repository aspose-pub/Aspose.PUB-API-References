---
title: "System::Security::Permissions::SecurityPermission sınıf"
linktitle: "SecurityPermission"
second_title: "Aspose.PUB için C++"
description: "System::Security::Permissions::SecurityPermission sınıf. Güvenlik iznini tanımlayan sınıf. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 100
url: /tr/cpp/system.security.permissions/securitypermission/
---
## SecurityPermission class


Güvenlik iznini tanımlayan sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüan olarak geçirin.

```cpp
class SecurityPermission : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Flags](./get_flags/)() | RTTI bilgisi. |
| [IsUnrestricted](./isunrestricted/)() | İznin sınırsız olup olmadığını kontrol eder. |
| [SecurityPermission](./securitypermission/)(PermissionState) | Yapıcı. |
| [SecurityPermission](./securitypermission/)(SecurityPermissionFlag) | Yapıcı. |
| [set_Flags](./set_flags/)(SecurityPermissionFlag) | İzinle ilişkili bayrakları ayarlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Security::Permissions](../)
* Library [Aspose.PUB for C++](../../)
