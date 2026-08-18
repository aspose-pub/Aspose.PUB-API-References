---
title: "System::Security::Cryptography::X509Certificates::X509Certificate2 Klasse"
linktitle: "X509Certificate2"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::X509Certificates::X509Certificate2 Klasse. Stellt ein X509-Zertifikat dar. Objekte dieser Klasse sollten nur mit der System::MakeObject() Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 400
url: /de/cpp/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 class


Stellt ein X509-Zertifikat dar. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Archived](./get_archived/)() const | Gibt einen Wert zurück, der angibt, dass das Zertifikat archiviert ist. |
| [get_Extensions](./get_extensions/)() const | Gibt die Sammlung von Erweiterungsobjekten zurück, die dem Zertifikat zugeordnet sind. |
| [get_FriendlyName](./get_friendlyname/)() const | Gibt den Anzeigenamen des Zertifikats zurück. |
| [get_HasPrivateKey](./get_hasprivatekey/)() const | Überprüft, ob das Zertifikat einen privaten Schlüssel besitzt. |
| [get_IssuerName](./get_issuername/)() const | Gibt den Namen der Partei zurück, die das Zertifikat ausgestellt hat. |
| [get_NotAfter](./get_notafter/)() const | Gibt das lokale Datum und die Uhrzeit zurück, nach denen ein Zertifikat nicht mehr gültig ist. |
| [get_NotBefore](./get_notbefore/)() const | Gibt das lokale Datum und die Uhrzeit zurück, zu denen ein Zertifikat gültig wird. |
| [get_PrivateKey](./get_privatekey/)() const | Gibt den mit dem Zertifikat verbundenen privaten Schlüssel zurück. |
| [get_PublicKey](./get_publickey/)() const | Gibt ein Zertifikat‑[PublicKey](../publickey/)‑Objekt zurück. |
| [get_RawData](./get_rawdata/)() const | Gibt die Rohdaten des Zertifikats zurück. |
| [get_SerialNumber](./get_serialnumber/)() const | Gibt die Seriennummer eines Zertifikats zurück. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Gibt den Algorithmus zurück, der zur Erstellung der Signatur eines Zertifikats verwendet wird. |
| [get_SubjectName](./get_subjectname/)() const | Gibt den Betreffnamen aus einem Zertifikat zurück. |
| [get_Thumbprint](./get_thumbprint/)() const | Gibt den Fingerabdruck des Zertifikats zurück. |
| [get_Version](./get_version/)() const | Gibt die Versionsnummer des Zertifikatsformats zurück. |
| static [GetCertContentType](./getcertcontenttype/)(const ByteArrayPtr\&) | Gibt den Typ des im angegebenen Byte‑Array enthaltenen Zertifikats zurück. |
| static [GetCertContentType](./getcertcontenttype/)(const String\&) | Gibt den Typ des in der angegebenen Datei enthaltenen Zertifikats zurück. |
| [GetDSAPrivateKey](./getdsaprivatekey/)() const | Gibt den privaten [RSA](../../system.security.cryptography/rsa/)‑Schlüssel zurück; |
| [GetDSAPublicKey](./getdsapublickey/)() const | Gibt den öffentlichen [RSA](../../system.security.cryptography/rsa/)‑Schlüssel zurück. |
| [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Gibt den privaten [RSA](../../system.security.cryptography/rsa/)‑Schlüssel zurück; |
| [GetECDsaPublicKey](./getecdsapublickey/)() const | Gibt den öffentlichen [RSA](../../system.security.cryptography/rsa/)‑Schlüssel zurück. |
| [GetNameInfo](./getnameinfo/)(X509NameType, bool) const | Gibt den Betreff‑ oder Aussteller‑Namen aus dem Zertifikat zurück. |
| [GetRSAPrivateKey](./getrsaprivatekey/)() const | Gibt den privaten [RSA](../../system.security.cryptography/rsa/)‑Schlüssel zurück; |
| [GetRSAPublicKey](./getrsapublickey/)() const | Gibt den öffentlichen [RSA](../../system.security.cryptography/rsa/)‑Schlüssel zurück. |
| [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Importiert Informationen aus der angegebenen Zertifikatsdatei. |
| [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) override | Importiert Informationen aus der angegebenen Zertifikatsdatei. |
| [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Importiert Informationen aus den angegebenen Zertifikatsdaten. |
| [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) override | Importiert Informationen aus den angegebenen Zertifikatsdaten. |
| [Import](./import/)(const String\&) override | Importiert Informationen aus der angegebenen Zertifikatsdatei. |
| [Import](./import/)(const ByteArrayPtr\&) override | Importiert Informationen aus den angegebenen Zertifikatsdaten. |
| [Reset](./reset/)() override | Setzt den Zertifikatszustand zurück. |
| [set_Archived](./set_archived/)(bool) const | Setzt einen Wert, der angibt, dass das Zertifikat archiviert ist. |
| [set_FriendlyName](./set_friendlyname/)(const String\&) | Setzt den Anzeigenamen des Zertifikats. |
| [set_PrivateKey](./set_privatekey/)(const SharedPtr\<AsymmetricAlgorithm\>\&) | Setzt oder löscht den privaten Schlüssel, der dem Zertifikat zugeordnet ist. |
| [ToString](./tostring/)(bool) const override | Gibt die Zertifikatsinformationen im Textformat zurück. |
| [ToString](./tostring/)() const override | Gibt die Zertifikatsinformationen im Textformat zurück. |
| [Verify](./verify/)() const | Überprüft die Zertifikatskette. |
| [X509Certificate2](./x509certificate2/)() | Erstellt ein leeres [X509Certificate2](./). |
| [X509Certificate2](./x509certificate2/)(const String\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const SharedPtr\<X509Certificate\>\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Konstruktor. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Konstruktor. |
## Siehe auch

* Class [X509Certificate](../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PUB for C++](../../)
