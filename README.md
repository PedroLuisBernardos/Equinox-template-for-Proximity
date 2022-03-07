# Equinox Template

![repo size](https://img.shields.io/github/repo-size/PedroLuisBernardos/Equinox-template-for-Proximity)

## 👥 Authors

`.psd` templates by [myojin223](https://github.com/myojin223).

`.png` images made by [PedroLuisBernardos](https://github.com/PedroLuisBernardos) and [ImKyle4815](https://github.com/ImKyle4815).

## :clipboard: Prerequisites

You'll need [Proximity 0.5.4+](https://github.com/PedroLuisBernardos/Ready-to-Use-Proximity).

## :wrench: Installation

You need to clone this repo

```bash
git clone https://github.com/PedroLuisBernardos/Equinox-template-for-Proximity.git
```

or you can [download the zip file](https://github.com/PedroLuisBernardos/Equinox-template-for-Proximity/archive/refs/heads/master.zip). You'll need to `unzip` it to have access to the folder.

## Other templates

The [EquinoxTextless template](https://github.com/PedroLuisBernardos/EquinoxTextless-template-for-Proximity) is also avaible.
 
| ![preview image](/Preview%20Images/Esper%20Sentinel%20(MH2%20Equinox).png) | ![preview image](/Preview%20Images/Omnath,%20Locus%20of%20Creation%20(ZNR%20Equinox).png) | ![preview image](/Preview%20Images/Waterlogged%20Grove%20(MH1%20Equinox).png) |
| --- | --- | --- |
| ![preview image](/Preview%20Images/Crop%20Rotation%20(2XM%20EquinoxTextless).png) | ![preview image](/Preview%20Images/Purphoros,%20God%20of%20the%20Forge%20(SLD%20EquinoxTextless).png) | ![preview image](/Preview%20Images/Wrenn%20and%20Six%20(MH1%20EquinoxTextless).png) |

## How to modify the image size and position

You need to modify the line `60` on the `template.xml` file:
```xml
<Image id="art" x="0" y="125" width="3288" height="4488" url="${image_uris.art_crop}">
```

Move your image horizontally `x` and verticaly `y` and see what's the best result for you :)

This is an example on why to change those values could be useful
| y="0" | y="125" | y="300" |
| --- | --- | --- |
| ![preview image](/Preview%20Images/y0.png) | ![preview image](/Preview%20Images/y125.png) | ![preview image](/Preview%20Images/y300.png) |

## How to use the back template for Power/Toughness

The pt template is not read by default. In the `/pt` folder you can find the default front pt templates. If you want to use the pt templates for the back cards you will need to replace those files with the files present in the `/pt/back` folder.

| using front pt | using back pt |
| --- | --- |
| ![preview image](/Preview%20Images/front%20pt.png) | ![preview image](/Preview%20Images/back%20pt.png) |

## How to use the Planeswalker template

The pw template is not read by default. In the `/pinlines` folder you can find lots of sub-folders. You will need to replace, in each one of those sub-folders, the default templates with the pw templates present in the `/pinlines/pwX/front` or `/pinlines/pwX/back` folders (there are a pw3 and a pw4 folders available), depending if you overwrite a **back** folder or not.

| using default template | using pw3 template | using pw4 template |
| --- | --- | --- |
| ![preview image](/Preview%20Images/default%20template.png) | ![preview image](/Preview%20Images/pw3%20template.png) | ![preview image](/Preview%20Images/pw4%20template.png) |

| using default back template | using back pw3 template | using back pw4 template |
| --- | --- | --- |
| ![preview image](/Preview%20Images/default%20back%20template.png) | ![preview image](/Preview%20Images/back%20pw3%20template.png) | ![preview image](/Preview%20Images/back%20pw4%20template.png) |
