---
title: Aspose::Pub::AssemblyConstants class
linktitle: AssemblyConstants
second_title: Aspose.PUB for C++
description: 'Aspose::Pub::AssemblyConstants class. Defines the constants that participate in the license check for the component. These used to be defined directly as assembly attributes, but I moved them into separate class because in .NET Compact Framework I cannot access assembly attributes. Now the licensing code when compiled for the .NET Compact Framework uses these constants instead of the assembly attributes in C++.'
type: docs
weight: 100
url: /cpp/aspose.pub/assemblyconstants/
---
## AssemblyConstants class


Defines the constants that participate in the license check for the component. These used to be defined directly as assembly attributes, but I moved them into separate class because in .NET Compact Framework I cannot access assembly attributes. Now the licensing code when compiled for the .NET Compact Framework uses these constants instead of the assembly attributes.

```cpp
class AssemblyConstants : public System::Object
```

## Fields

| Field | Description |
| --- | --- |
| static [Family](./family/) |  |
| static [Platform](./platform/) |  |
| static [Producer](./producer/) | The producer of the **Pdf** file. |
| static [Product](./product/) | This is used by **Aspose** licensing code to verify the license is for the correct product. |
| static [ReleaseDate](./releasedate/) | This is used by **Aspose** licensing code to check for subscription expiry. You need to set this to the date you publish a release or a hotfix. |
| static [Title](./title/) |  |
| static [Version](./version/) | The version of the assembly. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
