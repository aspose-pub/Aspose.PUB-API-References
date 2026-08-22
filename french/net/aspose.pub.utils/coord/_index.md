---
title: "Classe Coord"
second_title: "Référence de l'API Aspose.PUB pour .NET"
description: "Classe Aspose.Pub.Utils.Coord. Cette classe est conçue pour représenter les données liées aux coordonnées des champs PUB. Chaque champ dans PUB possède des coordonnées avec 2 paires de coordonnées : les coordonnées du coin supérieur gauche XLeft YTop et les coordonnées du coin inférieur droit XRight YBottom. Toutes les coordonnées sont représentées dans un système métrique spécial, English Metric UnitEMUs. Des méthodes supplémentaires ont été ajoutées à cette classe pour transformer les valeurs de coordonnées des unités métriques anglaises en pouces."
type: docs
weight: 350
url: /fr/net/aspose.pub.utils/coord/
---
## Coord class

Cette classe est conçue pour représenter les données liées aux coordonnées des champs PUB. Chaque champ dans PUB possède des coordonnées qui comprennent 2 paires de coordonnées : les coordonnées du coin supérieur gauche (XLeft, YTop) et les coordonnées du coin inférieur droit (XRight, YBottom). Toutes les coordonnées sont exprimées dans un système métrique spécial – Unité Métrique Anglaise (EMUs). Des méthodes supplémentaires ont été ajoutées à cette classe pour transformer les valeurs de coordonnées des unités métriques anglaises en pouces.

```csharp
public class Coord : ICloneable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Coord](coord/#constructor)() | Constructeur |
| [Coord](coord/#constructor_1)(int, int, int, int) | Constructeur |

## Propriétés

| Nom | Description |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | Coordonnée X du coin supérieur gauche en EMUs |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | Coordonnée X du coin inférieur droit en EMUs |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | Coordonnée Y du coin inférieur droit en EMUs |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | Coordonnée Y du coin supérieur gauche en EMUs |

## Méthodes

| Nom | Description |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | Calcule la hauteur de la figure (objet Coord actuel) et renvoie le résultat en pouces |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | Calcule la largeur de la figure (objet Coord actuel) et renvoie le résultat en pouces |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | Transforme la valeur de la coordonnée X du système métrique naturel PUB en pouces |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | Transforme la valeur de la coordonnée X du système métrique naturel PUB en pouces |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | Transforme la valeur de la coordonnée Y du système métrique naturel PUB en pouces |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | Transforme la valeur de la coordonnée Y du système métrique naturel PUB en pouces |
| [Clone](../../aspose.pub.utils/coord/clone/)() | Copie de l'objet créée |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | Renvoie la hauteur de l'objet Coord actuel en métriques PUB naturelles |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | Renvoie la largeur de l'objet Coord actuel en métriques PUB naturelles |

### Voir aussi

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


