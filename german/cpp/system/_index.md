---
title: "System-Namespace"
linktitle: "System"
second_title: "Aspose.PUB für C++"
description: "Wie man den System-Namespace in C++ verwendet."
type: docs
weight: 500
url: /de/cpp/system/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Activator](./activator/) | Enthält Methoden zum Erzeugen von Objekttypen. |
| [Array](./array/) | Klasse, die eine Array-Datenstruktur darstellt. Objekte dieser Klasse sollten nur mit den Funktionen [System::MakeArray()](./makearray/) und [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ArraySegment](./arraysegment/) | Stellt ein Segment des eindimensionalen Arrays dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Attribute](./attribute/) | Eine Basisklasse für benutzerdefinierte Attribute. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BitConverter](./bitconverter/) | Enthält Methoden, die Konvertierungen einer Byte‑Sequenz zu einem Werttyp und umgekehrt durchführen. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [Boolean](./boolean/) | Klasse, die statische Mitglieder des Typs [System.Boolean](./boolean/) .[Net](../system.net/) enthält. |
| [BoxedEnum](./boxedenum/) | Stellt einen verpackten Enumerationswert dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BoxedValue](./boxedvalue/) | Stellt einen verpackten Wert dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BoxedValueBase](./boxedvaluebase/) | Eine Basisklasse, die ein Interface definiert und einige grundlegende Methoden einer abgeleiteten Klasse implementiert, die einen verpackten Wert darstellt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Buffer](./buffer/) | Enthält Methoden, die rohe Byte‑Arrays manipulieren. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [Byte](./byte/) | Enthält Methoden zur Arbeit mit dem vorzeichenlosen 8‑Bit‑Integer. |
| [Char](./char/) | Bietet Methoden zur Manipulation von Zeichen, die als UTF‑16‑Codeeinheiten dargestellt werden. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [Comparison](./comparison/) | Stellt einen Zeiger auf die Methode dar, die zwei Objekte desselben Typs vergleicht. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/) zur Verwaltung von Objekten dieses Typs. |
| [Console](./console/) | Bietet Methoden zum Ausgeben von Daten in den Standardausgabestream. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [ConsoleOutput](./consoleoutput/) | Stellt den Standardausgabestream dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [DateTime](./datetime/) | Stellt einen spezifischen Datums‑ und Zeitwert auf dem Zeitkontinuum dar. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/) zur Verwaltung von Objekten dieses Typs. |
| [DateTimeOffset](./datetimeoffset/) | Enthält das Datum und die Uhrzeit relativ zur koordinierten Weltzeit. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [DBNull](./dbnull/) | Stellt einen nicht vorhandenen Wert dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Decimal](./decimal/) | Stellt eine Dezimalzahl dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/), um Objekte dieses Typs zu verwalten. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) Klassenimplementierung. Ermöglicht es, Spezialiserungen von BoxingValue zu deklarieren, ohne gemeinsamen Code zu duplizieren. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_returntype(argumenttypes...)_/) | Stellt einen Zeiger auf eine Funktion, Methode oder ein Funktionsobjekt dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/), um Objekte dieses Typs zu verwalten. |
| [DynamicWeakPtr](./dynamicweakptr/) | Smart‑Pointer‑Klasse, die die Zeigermodi von Template‑Argumenten des gespeicherten Objekts verfolgt und nach jeder Zuweisung aktualisiert. Dieser Typ ist ein Zeiger, der die Löschung anderer Objekte verwaltet. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const‑Referenz übergeben werden. |
| [EnumValues](./enumvalues/) | Stellt Metainformationen über die Aufzählungskonstanten des Aufzählungstyps **E** bereit. |
| [EnumValuesBase](./enumvaluesbase/) | Eine Basisklasse für eine Klasse, die Metainformationen eines Aufzählungstyps repräsentiert. |
| [EventArgs](./eventargs/) | Die Basisklasse für Klassen, die einen Kontext darstellen, der an die Ereignisabonnenten übergeben wird, wenn ein Ereignis ausgelöst wird. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ExceptionWrapper](./exceptionwrapper/) | Template, das einen Wrapper für Ausnahmen darstellt, die von der Klasse Exception abgeleitet sind. |
| [FlagsAttribute](./flagsattribute/) | Zeigt an, dass eine Aufzählung als Bitfeld behandelt werden kann; das heißt, als Menge von. |
| [Func](./func/) | Funktions‑Delegate. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/), um Objekte dieses Typs zu verwalten. |
| [GC](./gc/) | Stellt eine emulierte Garbage Collection dar, die eher wie ein Stub funktioniert und de facto nichts tut. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [Guid](./guid/) | Stellt einen global eindeutigen Bezeichner dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/), um Objekte dieses Typs zu verwalten. |
| [IAsyncResult](./iasyncresult/) | Stellt den Status einer asynchronen Operation dar. Objekte dieser Klasse sollten ausschließlich über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ICloneable](./icloneable/) | Definiert eine Methode, die das Klonen von Objekten ermöglicht – das Erstellen einer Kopie eines Objekts. Objekte dieser Klasse sollten ausschließlich über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IComparable](./icomparable/) | Definiert eine Methode, die zwei Objekte vergleicht. Objekte dieser Klasse sollten ausschließlich über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IConvertible](./iconvertible/) | Definiert Methoden, die den Wert des implementierenden Referenz- oder Werttyps in einen Common Language Runtime-Typ konvertieren, der einen äquivalenten Wert besitzt. Objekte dieser Klasse sollten ausschließlich über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ICustomFormatter](./icustomformatter/) | Definiert eine Methode, die eine benutzerdefinierte Formatierung der Zeichenkettenrepräsentation eines durch das angegebene Objekt dargestellten Wertes durchführt. Objekte dieser Klasse sollten ausschließlich über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IDisposable](./idisposable/) | Definiert eine Methode, die Ressourcen freigibt, die dem aktuellen Objekt gehören. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IEquatable](./iequatable/) | Definiert eine Methode, die die Gleichheit von zwei Objekten bestimmt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IFormatProvider](./iformatprovider/) | Definiert eine Methode, die Formatierungsinformationen bereitstellt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IFormattable](./iformattable/) | Definiert eine Methode, die den Wert des aktuellen Objekts mit dem angegebenen Formatstring und Formatanbieter formatiert. |
| [Int16](./int16/) | Enthält Methoden zur Arbeit mit dem 16‑Bit‑Integer. |
| [Int32](./int32/) | Enthält Methoden zur Arbeit mit dem 32‑Bit‑Integer. |
| [Int64](./int64/) | Enthält Methoden zur Arbeit mit dem 64‑Bit‑Integer. |
| [LockContext](./lockcontext/) | Schutzobjekt, das die C#‑lock()-Anweisung implementiert. |
| [MarshalByRefObject](./marshalbyrefobject/) | Bietet Zugriff auf Objekte über Anwendungsdomänengrenzen hinweg in remoting‑aktivierten Anwendungen. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_returntype(argumenttypes...)_/) | Stellt eine Sammlung von Delegaten dar. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/), um Objekte dieses Typs zu verwalten. |
| [Nullable](./nullable/) | Vorwärtsdeklaration. |
| [NullableUtils](./nullableutils/) | Stellt die C#‑Klasse [System.Nullable](./nullable/) (ohne Typargumente) als statische Klasse dar. Der Originalname kann nicht verwendet werden, da in C++ Klassen-Templates nicht überladen werden können. Unterstützt einen Werttyp, dem null zugewiesen werden kann. Diese Klasse kann nicht abgeleitet werden. |
| [Object](./object/) | Basisklasse, die die Verwendung von Methoden ermöglicht, die für die Klasse [System.Object](./object/) in C# verfügbar sind. Alle nicht triviale Klassen, die in der übersetzten Umgebung verwendet werden, sollten von ihr erben. |
| [ObjectExt](./objectext/) | Stellt statische Methoden bereit, die C#‑[Object](./object/)-Methoden für nicht‑Object‑C++‑Typen (Strings, Zahlen usw.) nachahmen. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals auf irgendeine Weise Instanzen davon erstellen. |
| [ObjectType](./objecttype/) | Stellt statische Methoden bereit, die Objekt‑Typ‑Getter implementieren. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [OperatingSystem](./operatingsystem/) | Stellt ein bestimmtes Betriebssystem dar und liefert Informationen darüber. Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Random](./random/) | Stellt einen Pseudo‑Zufallszahlengenerator dar. Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](./smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ScopedCulture](./scopedculture/) | Stellt eine im Geltungsbereich verwendete Kultur dar. |
| [SmartPtr](./smartptr/) | Pointer-Klasse zum Einhüllen von Typen, die im Heap alloziert werden. Verwenden Sie sie, um den Speicher für Klassen zu verwalten, die von [Object](./object/) erben. Dieser Zeigertyp folgt intrusiven Zeigersemantiken. Der Referenzzähler wird entweder im [Object](./object/) selbst oder in einer Zählerstruktur gespeichert, die eng mit der [Object](./object/)-Instanz verknüpft ist. In jedem Fall bilden alle [SmartPtr](./smartptr/)-Instanzen eine einzige Besitzgruppe, unabhängig davon, wie sie erstellt wurden, was sich vom Verhalten der std::shared_ptr‑Klasse unterscheidet. Das Konvertieren eines rohen Zeigers zu [SmartPtr](./smartptr/) ist sicher, solange andere [SmartPtr](./smartptr/)-Instanzen gemeinsame Referenzen auf dasselbe Objekt halten. Eine [SmartPtr](./smartptr/)-Klasseninstanz kann sich in einem von zwei Zuständen befinden: Shared‑Pointer und Weak‑Pointer. Damit ein Objekt lebendig bleibt, muss die Anzahl der gemeinsamen Referenzen positiv sein. Sowohl schwache als auch geteilte Zeiger können verwendet werden, um auf das referenzierte Objekt zuzugreifen (Methoden aufzurufen, Felder zu lesen oder zu schreiben usw.), aber schwache Zeiger nehmen nicht am Referenzzählen der geteilten Zeiger teil. Das [Object](./object/) wird gelöscht, wenn der letzte „shared“ [SmartPtr](./smartptr/)-Zeiger darauf zerstört wird. Stellen Sie also sicher, dass dies nicht geschieht, wenn keine anderen geteilten [SmartPtr](./smartptr/)-Zeiger auf das Objekt existieren, z. B. während der Objektkonstruktion oder -zerstörung. Verwenden Sie System::Object::ThisProtector‑Wächterobjekte (im C++‑Code) oder das CppCTORSelfReference‑ bzw. CppSelfReference‑Attribut (im zu übersetzenden C#‑Code), um dieses Problem zu beheben. Ebenso sollten Sie Schleifenreferenzen durch die Verwendung der [System::WeakPtr](./weakptr/)-Zeigerklasse oder des [System::SmartPtrMode::Weak](./smartptrmode/)-Zeigermodus (im C++‑Code) bzw. des CppWeakPtr‑Attributs (im zu übersetzenden C#‑Code) auflösen. Wenn zwei oder mehr Objekte sich gegenseitig über „shared“-Zeiger referenzieren, werden sie niemals gelöscht. Sollte der Zeigertyp (weak oder shared) zur Laufzeit gewechselt werden müssen, verwenden Sie die Methode [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) oder die Klasse [System::DynamicWeakPtr](./dynamicweakptr/). Die [SmartPtr](./smartptr/)-Klasse enthält keine virtuellen Methoden. Sie sollten sie nur erben, wenn Sie eine eigene Speicherverwaltungsstrategie erstellen. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const‑Referenz übergeben werden. |
| [SmartPtrInfo](./smartptrinfo/) | Dienstklasse zum Testen und Ändern des Inhalts von [SmartPtr](./smartptr/), ohne den endgültigen Typ zu kennen. Wird für Garbage Collection und die Erkennung von Schleifenreferenzen usw. verwendet. Denken Sie daran, dass es sich um einen „Pointer‑to‑Pointer“ handelt. Wir können den Basistyp von [SmartPtr](./smartptr/) nicht verwenden, da er keinen hat; stattdessen nutzen wir diese „Info“-Klasse. |
| [String](./string/) | [String](./string/)-Klasse, die in der gesamten Bibliothek verwendet wird. Sie ist ein Ersatz für C#‑[System.String](./string/) beim Übersetzen von Code. Aus Optimierungsgründen wird sie nicht als Unterklasse von [Object](./object/) betrachtet. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](./smartptr/)-Klasse, um Objekte dieses Typs zu verwalten. |
| [StringComparer](./stringcomparer/) | Vergleicht Zeichenketten mit verschiedenen Vergleichsmodi. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [StringHashCompiletime](./stringhashcompiletime/) | Eine Hilfsklasse, die einen Hashwert aus einem C-String erzeugt. |
| [TimeSpan](./timespan/) | Stellt ein Zeitintervall dar. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/) zur Verwaltung von Objekten dieses Typs. |
| [TimeZone](./timezone/) | Stellt eine Zeitzone dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [TimeZoneInfo](./timezoneinfo/) | Stellt eine Information dar, die eine bestimmte Zeitzone beschreibt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Tuple](./tuple/) | Klasse, die eine Tupel-Datenstruktur darstellt. Die maximale Anzahl von Elementen beträgt 8. |
| [TupleFactory](./tuplefactory/) | Stellt statische Methoden zum Erzeugen von Tupelobjekten bereit. |
| [TypeInfo](./typeinfo/) | Stellt einen bestimmten Typ dar und liefert Informationen darüber. |
| [Uri](./uri/) | Einheitlicher Ressourcenbezeichner. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [UriBuilder](./uribuilder/) | Stellt Methoden zum Erzeugen und Modifizieren von universellen Ressourcenidentifikatoren (URIs) bereit. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [UriParser](./uriparser/) | Wird verwendet, um ein neues URI-Schema zu analysieren. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](./makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](./smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [UriShim](./urishim/) | Dienstklasse. |
| [ValueType](./valuetype/) | Basisklasse für Werttypen mit [Object](./object/)-Vererbung, die aus Leistungsgründen abgeschnitten wird. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/), um Objekte dieses Typs zu verwalten. |
| [Version](./version/) | Stellt eine Versionsnummer dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/), um Objekte dieses Typs zu verwalten. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | Unterklasse von [System::SmartPtr](./smartptr/), die sich beim Erzeugen in den Weak‑Modus versetzt. Bitte beachten Sie, dass diese Klasse nicht garantiert, dass ihre Instanz immer im Weak‑Modus bleibt, da [set_Mode()](./smartptr/set_mode/) weiterhin zugänglich ist. Dieser Typ ist ein Zeiger, um das Löschen anderer Objekte zu verwalten. Er sollte auf dem Stack zugewiesen und an Funktionen entweder per Wert oder per const‑Referenz übergeben werden. |
| [WeakReference](./weakreference/) | Stellt eine schwache Referenz dar, die ein Objekt referenziert, während das Objekt dennoch gelöscht werden kann. |
| [WeakReference< T >](./weakreference_t_/) | Stellt eine schwache Referenz dar, die ein Objekt referenziert, während das Objekt dennoch gelöscht werden kann. |
| [WeakReference<>](./weakreference__/) | Stellt eine schwache Referenz dar, die ein Objekt referenziert, während das Objekt dennoch gelöscht werden kann. |
## Enums

| Aufzählung | Beschreibung |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Aufzählung, die Werte enthält, die verschiedene Formate von base‑64‑kodierten Daten darstellen. |
| [DateTimeKind](./datetimekind/) | Aufzählungswerte, die die Arten von Datum und Uhrzeit darstellen. |
| [DayOfWeek](./dayofweek/) | Aufzählung, die einen Wochentag darstellt. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | Gibt den Speicherort der Umgebungsvariablen an. |
| [MidpointRounding](./midpointrounding/) | Gibt das Verhalten von Rundungsfunktionen an. |
| [PlatformID](./platformid/) | Stellt eine Betriebssystemplattform dar. |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) Zeigertyp: weak oder shared. Definiert, ob der Zeiger gezählt wird, wenn entschieden wird, ob das Objekt gelöscht werden soll oder nicht. |
| [StringComparison](./stringcomparison/) | Definiert den Stil des Zeichenkettenvergleichs. |
| [StringSplitOptions](./stringsplitoptions/) | Bestimmt das Verhalten beim Aufteilen von Zeichenketten. |
| [TypeCode](./typecode/) | Stellt den Typ eines Objekts dar. |
| [UriComponents](./uricomponents/) | Stellt URI‑Komponenten dar. |
| [UriFormat](./uriformat/) | Gibt an, wie die URI escaped wird. |
| [UriHostNameType](./urihostnametype/) | Stellt den Typ des Hostnamens dar. |
| [UriKind](./urikind/) | Stellt die Arten von URIs dar. |
| [UriPartial](./uripartial/) | Stellt die Teile einer URI für die Methode [Uri.GetLeftPart](./uri/getleftpart/) dar. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Action](./action/) | Delegattyp, der Methoden referenziert, die keinen Rückgabewert haben. |
| [ArrayPtr](./arrayptr/) | Alias für den Typ 'Zeiger auf Array'. |
| [AsyncCallback](./asynccallback/) | Ein Delegattyp, der eine Methode darstellt, die aufgerufen wird, wenn ein asynchroner Vorgang abgeschlossen ist. |
| [BadImageFormatException](./badimageformatexception/) | Die Ausnahme, die ausgelöst wird, wenn das Dateiabbild einer dynamischen Linkbibliothek (DLL) oder eines ausführbaren Programms ungültig ist. Wickeln Sie die Instanzen der BadImageFormatException‑Klasse niemals in [System::SmartPtr](./smartptr/) ein. |
| [ByteArrayPtr](./bytearrayptr/) | Ein Alias für ein Smart‑Pointer‑Objekt, das auf ein Array von vorzeichenlosen 8‑Bit‑Integern zeigt. |
| [Converter](./converter/) | Stellt einen Zeiger auf das aufrufbare Objekt dar, das ein einzelnes Argument vom Typ **TInput** akzeptiert und einen Wert vom Typ **TOutput** zurückgibt. |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) zeigt. |
| [DecoderFallbackPtr](./decoderfallbackptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::DecoderFallback](../system.text/decoderfallback/) zeigt. |
| [DecoderPtr](./decoderptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::Decoder](../system.text/decoder/) zeigt. |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) zeigt. |
| [DirectoryInfoPtr](./directoryinfoptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IO::DirectoryInfo](../system.io/directoryinfo/) zeigt. |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) zeigt. |
| [EncoderFallbackPtr](./encoderfallbackptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::EncoderFallback](../system.text/encoderfallback/) zeigt. |
| [EncoderPtr](./encoderptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::Encoder](../system.text/encoder/) zeigt. |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) zeigt. |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) zeigt. |
| [EncodingInfoPtr](./encodinginfoptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::EncodingInfo](../system.text/encodinginfo/) zeigt. |
| [EncodingPtr](./encodingptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::Text::Encoding](../system.text/encoding/) zeigt. |
| [Event](./event/) | Stellt ein Ereignis dar – ein Mechanismus, über den Abonnenten über ein interessantes Auftreten mittels einer Delegatenaufruf benachrichtigt werden. |
| [EventArgsPtr](./eventargsptr/) | Shared-Pointer auf eine Instanz der Klasse [EventArgs](./eventargs/). |
| [EventHandler](./eventhandler/) | Stellt eine Methode dar, die auf ein Ereignis reagiert und es verarbeitet. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](./smartptr/), um Objekte dieses Typs zu verwalten. |
| [Exception](./exception/) | Alias, der anstelle von Details::Exception verwendet werden soll. |
| [ExceptionPtr](./exceptionptr/) | Typalias, der von Ausnahme-Wrappers verwendet wird. |
| [FileInfoPtr](./fileinfoptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IO::FileInfo](../system.io/fileinfo/) zeigt. |
| [FileStreamPtr](./filestreamptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IO::FileStream](../system.io/filestream/) zeigt. |
| [FileSystemInfoPtr](./filesysteminfoptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IO::FileSystemInfo](../system.io/filesysteminfo/) zeigt. |
| [IAsyncResultPtr](./iasyncresultptr/) | Shared-Pointer auf [IAsyncResult](./iasyncresult/). |
| [IFormatProviderPtr](./iformatproviderptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IFormatProvider](./iformatprovider/) zeigt. |
| [MakeConstRef_t](./makeconstref_t/) | Hilfstyp für den Modifier [MakeConstRef](./makeconstref/). |
| [MemoryStreamPtr](./memorystreamptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IO::MemoryStream](../system.io/memorystream/) zeigt. |
| [Predicate](./predicate/) | Stellt einen Zeiger auf ein Prädikat dar – ein aufrufbares Objekt, das ein einzelnes Argument akzeptiert und einen booleschen Wert zurückgibt. |
| [SharedPtr](./sharedptr/) | Alias für Smart-Pointer, die in der Bibliothek häufig verwendet werden. |
| [StreamPtr](./streamptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IO::Stream](../system.io/stream/) zeigt. |
| [StreamReaderPtr](./streamreaderptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IO::StreamReader](../system.io/streamreader/) zeigt. |
| [StreamWriterPtr](./streamwriterptr/) | Ein Alias für einen Smart-Pointer, der auf eine Instanz der Klasse [System::IO::StreamWriter](../system.io/streamwriter/) zeigt. |
| [StringComparerPtr](./stringcomparerptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz der Klasse [StringComparer](./stringcomparer/). |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | Alias für Shared-Pointer auf eine Instanz der Klasse [TimeZoneInfo](./timezoneinfo/). |
| [TimeZonePtr](./timezoneptr/) | Shared-Pointer auf eine Instanz der Klasse [TimeZone](./timezone/). |
## Functions

| Funktion | Beschreibung |
| --- | --- |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| AsCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Cast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CastEnumerableTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| CheckedCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Compare | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| const_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ConstCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Default | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Default | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Discard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DoTryFinally | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| dynamic_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| DynamicCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| EnumGetName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< double, double > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Equals< float, float > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ExplicitCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForceStaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ForEachMemberGVName | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| get_pointer | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| GetHashCode | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| is_vp_test | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsEnumMetaInfoDefined | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNaN | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsNegativeInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsPattern | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IsPositiveInfinity | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| IterateOver | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeObject | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeScopeGuard | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MakeSharedPtr | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| MemberwiseClone | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::DateTime > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| ObjectType::GetType< System::String > | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator!= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator* | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator+ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator- | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator/ | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<< | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator<= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator== | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>= | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| operator>> | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| PrintTo | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| Ref | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| SafeInvoke | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_decrement_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_post_increment_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| setter_wrap | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| static_pointer_cast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCast_noexcept | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
| StaticCastArray | System.Collections.Generic.List`1[Doxygen2HugoConverter.Markup.SimpleMarkupEntry] |
