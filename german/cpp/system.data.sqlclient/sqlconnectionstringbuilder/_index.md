---
title: "System::Data::SqlClient::SqlConnectionStringBuilder Klasse"
linktitle: "SqlConnectionStringBuilder"
second_title: "Aspose.PUB für C++"
description: "System::Data::SqlClient::SqlConnectionStringBuilder Klasse. SQL-basierter Verbindungs-Builder. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 100
url: /de/cpp/system.data.sqlclient/sqlconnectionstringbuilder/
---
## SqlConnectionStringBuilder class


SQL-basierter Verbindungs-Builder. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SqlConnectionStringBuilder : public System::Data::Common::DbConnectionStringBuilder
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_DataSource](./get_datasource/)() const | Gibt die Datenquelle zurück (z. B. Hostname und Port). |
| [get_Encrypt](./get_encrypt/)() const | Überprüft, ob die Verschlüsselung in der Zeile aktiviert ist. |
| [get_InitialCatalog](./get_initialcatalog/)() const | Gibt den Namen der mit der Verbindung verbundenen Datenbank zurück. |
| [get_NetworkLibrary](./get_networklibrary/)() const | Ermittelt den Namen der verwendeten Netzwerkbibliothek. |
| [get_Password](./get_password/)() const | Ermittelt das zum Verbinden mit der Datenbank verwendete Passwort. |
| [get_TrustServerCertificate](./get_trustservercertificate/)() const | Prüft, ob die Verbindung mithilfe eines vertrauenswürdigen Serverzertifikats geschützt ist. |
| [get_UserID](./get_userid/)() const | Ermittelt die für die Verbindung verwendete Benutzer-ID. |
| [idx_get](./idx_get/)(String) override | RTTI-Informationen. |
| [idx_set](./idx_set/)(String, Object::ptr) override | Setzt das Schlüsselobjekt. |
| [set_DataSource](./set_datasource/)(const String\&) | Gibt die Datenquelle zurück (z. B. Hostname und Port). |
| [set_Encrypt](./set_encrypt/)(bool) | Schaltet die Verschlüsselung ein oder aus. |
| [set_InitialCatalog](./set_initialcatalog/)(const String\&) | Setzt den Namen der mit der Verbindung verknüpften Datenbank. |
| [set_NetworkLibrary](./set_networklibrary/)(const String\&) | Wählt die zu verwendende Netzwerkbibliothek aus. |
| [set_Password](./set_password/)(const String\&) | Setzt das zum Verbinden mit der Datenbank zu verwendende Passwort. |
| [set_TrustServerCertificate](./set_trustservercertificate/)(bool) | Bestimmt, ob die Verbindung mithilfe eines vertrauenswürdigen Serverzertifikats geschützt ist. |
| [set_UserID](./set_userid/)(const String\&) | Setzt die für die Verbindung zu verwendende Benutzer-ID. |
## Siehe auch

* Class [DbConnectionStringBuilder](../../system.data.common/dbconnectionstringbuilder/)
* Namespace [System::Data::SqlClient](../)
* Library [Aspose.PUB for C++](../../)
