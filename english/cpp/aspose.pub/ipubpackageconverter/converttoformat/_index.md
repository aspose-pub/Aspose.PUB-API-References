---
title: Aspose::Pub::IPubPackageConverter::ConvertToFormat method
linktitle: ConvertToFormat
second_title: Aspose.PUB for C++
description: 'Aspose::Pub::IPubPackageConverter::ConvertToFormat method. Converts each document from the inputDocumentCollection  list to the specified format and saves the results in the appropriate storage. Type of storage to save is specified by outputType  parameter. References to converted documents are placed in the returned PackageDocumentCollection object. If the mergeFiles  flag is set, then all converted documents will be merged into single document in the same order in which they were placed in the inputDocumentCollection  list in C++.'
type: docs
weight: 100
url: /cpp/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter::ConvertToFormat method


Converts each document from the *inputDocumentCollection*  list to the specified format and saves the results in the appropriate storage. Type of storage to save is specified by *outputType*  parameter. References to converted documents are placed in the returned [PackageDocumentCollection](../../packagedocumentcollection/) object. If the *mergeFiles*  flag is set, then all converted documents will be merged into single document in the same order in which they were placed in the *inputDocumentCollection*  list.

```cpp
virtual System::SharedPtr<PackageDocumentCollection> Aspose::Pub::IPubPackageConverter::ConvertToFormat(System::SharedPtr<PackageDocumentCollection> inputDocumentCollection, bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputDocumentCollection | System::SharedPtr\<PackageDocumentCollection\> | Collection of input documents. |
| mergeFiles | bool | Specifies, whether to merge all output documents into the single one. |
| outputFormat | PubExportFormats | Output format. |
| outputType | PubDocumentType | Output storage type. |

### ReturnValue

References to the converted documents in the [PackageDocumentCollection](../../packagedocumentcollection/)object.



## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PackageDocumentCollection](../../packagedocumentcollection/)
* Enum [PubExportFormats](../../pubexportformats/)
* Enum [PubDocumentType](../../pubdocumenttype/)
* Class [IPubPackageConverter](../)
* Namespace [Aspose::Pub](../../)
* Library [Aspose.PUB for C++](../../../)