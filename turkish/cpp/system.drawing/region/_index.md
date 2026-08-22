---
title: "System::Drawing::Region class"
linktitle: "Region"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Region sınıfı. Grafik şeklin iç kısmını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirin."
type: docs
weight: 2100
url: /tr/cpp/system.drawing/region/
---
## Region class


Grafik şeklin iç kısmını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class Region : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() const | Mevcut nesnenin bir kopyasını döndürür. |
| [Complement](./complement/)(const RectangleF\&) | Mevcut nesnenin temsil ettiği bölgeyi, belirtilen dikdörtgen tarafından tanımlanan ve bu bölgeyle kesişmeyen kısmıyla değiştirir. |
| [Complement](./complement/)(const Rectangle\&) | Mevcut nesnenin temsil ettiği bölgeyi, belirtilen dikdörtgen tarafından tanımlanan ve bu bölgeyle kesişmeyen kısmıyla değiştirir. |
| [Complement](./complement/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Mevcut nesnenin temsil ettiği bölgeyi, belirtilen yol tarafından tanımlanan ve bu bölgeyle kesişmeyen kısmıyla değiştirir. |
| [Complement](./complement/)(const SharedPtr\<Region\>\&) | Mevcut nesnenin temsil ettiği bölgeyi, belirtilen bölgenin bu bölgeyle kesişmeyen kısmıyla değiştirir. |
| [Dispose](./dispose/)() | Geçerli nesne tarafından edinilen tüm işletim sistemi kaynaklarını serbest bırakır. |
| [Equals](./equals/)(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) | Belirtilen bölgenin, belirtilen çizim yüzeyinde mevcut nesnenin temsil ettiği bölgeyle aynı olup olmadığını belirler. |
| [Exclude](./exclude/)(const RectangleF\&) | Mevcut nesnenin temsil ettiği bölgeyi, belirtilen dikdörtgen tarafından tanımlanan bölgenin dışlanması sonucuyla değiştirir. |
| [Exclude](./exclude/)(const Rectangle\&) | Mevcut nesnenin temsil ettiği bölgeyi, belirtilen dikdörtgen tarafından tanımlanan bölgenin dışlanması sonucuyla değiştirir. |
| [Exclude](./exclude/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Mevcut nesnenin temsil ettiği bölgeyi, belirtilen yol tarafından tanımlanan bölgenin dışlanması sonucuyla değiştirir. |
| [Exclude](./exclude/)(const SharedPtr\<Region\>\&) | Mevcut nesnenin temsil ettiği bölgeyi, belirtilen bölgenin dışlanması sonucuyla değiştirir. |
| [GetBounds](./getbounds/)(const SharedPtr\<Graphics\>\&) const | Bir [Graphics](../graphics/) nesnesinin çizim yüzeyinde bu [Region](./) nesnesini sınırlayan bir dikdörtgeni temsil eden bir [RectangleF](../rectanglef/) yapısını alır. |
| [GetRegionData](./getregiondata/)() const | Mevcut nesnenin temsil ettiği bölgeyi tanımlayan verileri içeren bir RegionData nesnesi döndürür. |
| [GetRegionScans](./getregionscans/)(const SharedPtr\<Drawing2D::Matrix\>\&) const | Belirtilen matris dönüşümü uygulandıktan sonra bu [Region](./) nesnesini yaklaşık olarak temsil eden bir dizi [RectangleF](../rectanglef/) yapısı döndürür. |
| [Intersect](./intersect/)(const RectangleF\&) | Mevcut nesnenin temsil ettiği bölgeyi, bu bölge ile belirtilen dikdörtgen tarafından tanımlanan bir bölgenin kesişimi sonucuyla değiştirir. |
| [Intersect](./intersect/)(const Rectangle\&) | Mevcut nesnenin temsil ettiği bölgeyi, bu bölge ile belirtilen dikdörtgen tarafından tanımlanan bir bölgenin kesişimi sonucuyla değiştirir. |
| [Intersect](./intersect/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen yol tarafından tanımlanan bir bölgenin kesişim sonucuyla değiştirir. |
| [Intersect](./intersect/)(const SharedPtr\<Region\>\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen bölgenin kesişim sonucuyla değiştirir. |
| [IsEmpty](./isempty/)(const SharedPtr\<Graphics\>\&) const | Belirtilen çizim yüzeyinde, mevcut nesne tarafından temsil edilen bölgenin boş iç mekâna sahip olup olmadığını belirler. |
| [IsInfinite](./isinfinite/)(const SharedPtr\<Graphics\>\&) const | Belirtilen çizim yüzeyinde, mevcut nesne tarafından temsil edilen bölgenin sonsuz iç mekâna sahip olup olmadığını belirler. |
| [IsVisible](./isvisible/)(const Point\&) const | Belirtilen noktanın, mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(const PointF\&) const | Belirtilen noktanın, mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(const Rectangle\&) | Belirtilen dikdörtgenin herhangi bir kısmının, mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(const RectangleF\&) | Belirtilen dikdörtgenin herhangi bir kısmının, mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(const Point\&, const SharedPtr\<Graphics\>\&) const | Belirtilen grafikleri kullanarak, belirtilen noktanın mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(const PointF\&, const SharedPtr\<Graphics\>\&) const | Belirtilen grafikleri kullanarak, belirtilen noktanın mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(const Rectangle\&, const SharedPtr\<Graphics\>\&) | Belirtilen grafikleri kullanarak, belirtilen dikdörtgenin herhangi bir kısmının mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(const RectangleF\&, const SharedPtr\<Graphics\>\&) | Belirtilen grafikleri kullanarak, belirtilen dikdörtgenin herhangi bir kısmının mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(float, float) const | Belirtilen noktanın, mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [IsVisible](./isvisible/)(float, float, const SharedPtr\<Graphics\>\&) const | Belirtilen grafikleri kullanarak, belirtilen noktanın mevcut nesne tarafından temsil edilen bölge içinde bulunup bulunmadığını belirler. |
| [MakeEmpty](./makeempty/)() | Mevcut nesneyi boş iç mekâna başlatır. |
| [MakeInfinite](./makeinfinite/)() | Bu bölge nesnesini sonsuz iç mekâna başlatır. |
| [Region](./region/)() | [Region](./) sınıfının yeni bir örneğini oluşturur. |
| [Region](./region/)(const RectangleF\&) | Belirtilen dikdörtgen tarafından tanımlanan bir bölgeyi temsil eden [Region](./) sınıfının yeni bir örneğini oluşturur. |
| [Region](./region/)(const Rectangle\&) | Belirtilen dikdörtgen tarafından tanımlanan bir bölgeyi temsil eden [Region](./) sınıfının yeni bir örneğini oluşturur. |
| [Region](./region/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Belirtilen yol tarafından tanımlanan bir bölgeyi temsil eden [Region](./) sınıfının yeni bir örneğini oluşturur. |
| [Region](./region/)(const SkPath\&) |  |
| [Region](./region/)(const SharedPtr\<Drawing2D::RegionData\>\&) | Belirtilen RegionData nesnesi tarafından tanımlanan bir bölgeyi temsil eden [Region](./) sınıfının yeni bir örneğini oluşturur. |
| [Transform](./transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Bu bölgeyi belirtilen matris ile dönüştürür. |
| [Transform](./transform/)(const SkMatrix\&) | Bu bölgeyi belirtilen matris ile dönüştürür. |
| [Translate](./translate/)(int, int) | Bölgenin koordinatlarını belirtilen miktarda kaydırır. |
| [Translate](./translate/)(float, float) | Bölgenin koordinatlarını belirtilen miktarda kaydırır. |
| [Union](./union/)(const RectangleF\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen dikdörtgen tarafından tanımlanan bir bölgenin birleşim işlemi sonucuyla değiştirir. |
| [Union](./union/)(const Rectangle\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen dikdörtgen tarafından tanımlanan bir bölgenin birleşim sonucuyla değiştirir. |
| [Union](./union/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen yol tarafından tanımlanan bir bölgenin birleşim sonucuyla değiştirir. |
| [Union](./union/)(const SharedPtr\<Region\>\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen bölgenin birleşim sonucuyla değiştirir. |
| [Xor](./xor/)(const RectangleF\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen dikdörtgen tarafından tanımlanan bölgenin kesişmeyen kısımlarıyla değiştirir. |
| [Xor](./xor/)(const Rectangle\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen dikdörtgen tarafından tanımlanan bölgenin kesişmeyen kısımlarıyla değiştirir. |
| [Xor](./xor/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen yol tarafından tanımlanan bölgenin kesişmeyen kısımlarıyla değiştirir. |
| [Xor](./xor/)(const SharedPtr\<Region\>\&) | Mevcut nesne tarafından temsil edilen bölgeyi, bu bölge ile belirtilen bölgenin kesişmeyen kısımlarıyla değiştirir. |
| virtual [~Region](./~region/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
