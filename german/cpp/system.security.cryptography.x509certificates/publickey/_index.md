---
title: "System::Security::Cryptography::X509Certificates::PublicKey Klasse"
linktitle: "PublicKey"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::X509Certificates::PublicKey Klasse. Stellt die öffentlichen Schlüsselinformationen eines X509-Zertifikats dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führen kann. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 100
url: /de/cpp/system.security.cryptography.x509certificates/publickey/
---
## PublicKey class


Stellt die öffentlichen Schlüsselinformationen eines X509-Zertifikats dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führen kann. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class PublicKey : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_EncodedKeyValue](./get_encodedkeyvalue/)() const | Liefert den ASN.1-kodierten öffentlichen Schlüsselwert. |
| [get_EncodedParameters](./get_encodedparameters/)() const | Liefert die ASN.1-kodierten öffentlichen Schlüsselparameter. |
| [get_Key](./get_key/)() const | Liefert einen [RSACryptoServiceProvider](../../system.security.cryptography/rsacryptoserviceprovider/) oder [DSACryptoServiceProvider](../../system.security.cryptography/dsacryptoserviceprovider/). |
| [get_Oid](./get_oid/)() const | Liefert den Bezeichner (OID) des öffentlichen Schlüssels. |
| [PublicKey](./publickey/)(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) | Konstruktor. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PUB for C++](../../)
