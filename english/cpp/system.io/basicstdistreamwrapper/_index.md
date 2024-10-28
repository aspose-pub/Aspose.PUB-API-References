---
title: System::IO::BasicSTDIStreamWrapper class
linktitle: BasicSTDIStreamWrapper
second_title: Aspose.PUB for C++
description: 'System::IO::BasicSTDIStreamWrapper class. Represents a System.IO.Stream-like wrapper for std::basic_istream and its derived objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper class


Represents a [System.IO.Stream](../stream/)-like wrapper for std::basic_istream and its derived objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Methods

| Method | Description |
| --- | --- |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) | Constructs a new instance of the [BasicSTDIStreamWrapper](./). |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const BasicSTDIStreamWrapper\&) | Copy constructor. Deleted. |
| [Flush](./flush/)() override | Clears this stream's buffers and writes all buffered data to the underlying storage. Not supported! |
| [operator=](./operator=/)(const BasicSTDIStreamWrapper\&) | Copy assignment operator. Deleted. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | If wrapping mode is binary, reads the specified number of bytes from the stream, otherwise read the specified number of characters and converts them to uint8_t type. Writes result of the reading to the specified byte array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Reads the specified number of bytes from the stream and writes them to the specified byte array. |
| [ReadByte](./readbyte/)() override | If wrapping mode is binary, reads a single byte from the last decoded character storage, otherwise read a single character from the stream and convert it to uint8_t type. |
| [SetLength](./setlength/)(int64_t) override | Sets the length of the stream represented by the current object. Not supported! |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | If wrapping mode is binary, writes to the stream the specified subrange of bytes from the specified byte array, otherwise convert the specified subrange of bytes from the specified byte array to char_type type ant then writes result to the stream. Not supported! |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Writes the specified subrange of bytes from the specified byte array to the stream. |
| [WriteByte](./writebyte/)(uint8_t) override | If wrapping mode is binary, writes to the stream the specified unsigned 8-bit integer value, otherwise convert it to char_type type and then write the result to the stream. Not supported! |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | A stream with no underlying storage. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | RTTI information. |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## See Also

* Class [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)