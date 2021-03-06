# Equinox Template

![repo size](https://img.shields.io/github/repo-size/PedroLuisBernardos/Equinox-template-for-Proximity)

## 👥 Authors

* `.psd` templates by CantaPerMe#3540 (discord).
* Ready to use Proximity template made by [myojin223](https://github.com/myojin223) and adapted by mysel, [PedroLuisBernardos](https://github.com/PedroLuisBernardos).
* `.png` images made by  and [ImKyle4815](https://github.com/ImKyle4815).

## :clipboard: Prerequisites

You'll need [Proximity 0.5.4+](https://github.com/PedroLuisBernardos/Ready-to-Use-Proximity).

## :wrench: Installation

You need to clone this repo

```bash
git clone https://github.com/PedroLuisBernardos/Equinox-template-for-Proximity.git
```

or you can [download the zip file](https://github.com/PedroLuisBernardos/Equinox-template-for-Proximity/archive/refs/heads/master.zip). You'll need to `unzip` it to have access to the folder.

Place this folder into the `Ready-to-Use-Proximity/templates/` folder and **name it** `Equinox`.

## Other templates

The [EquinoxTextless template](https://github.com/PedroLuisBernardos/EquinoxTextless-template-for-Proximity) is also avaible.

| ![preview image](/Preview%20Images/esper.png) | ![preview image](/Preview%20Images/nicol.png) | ![preview image](/Preview%20Images/waterlogged.png) |
| --- | --- | --- |
| ![preview image](/Preview%20Images/crop.png) | ![preview image](/Preview%20Images/purphoros.png) | ![preview image](/Preview%20Images/wrenn.png) |

## How to modify the image size and position

You need to modify the line `60` on the `template.xml` file.

```xml
<Image id="art" x="352" y="605" width="2584" height="1882" url="${image_uris.art_crop}">
```

Move your image horizontally `x` and verticaly `y` and see what's the best result for you. You can also change the `width` and the `height` to adjust your image position. Note that the maximum you can go is `3288x4488`.

This is an example on why to change those values could be useful. I personnally prefer the *y="300"* one.

| y="0" | y="125" | y="300" |
| --- | --- | --- |
| ![preview image](/Preview%20Images/0.png) | ![preview image](/Preview%20Images/crop.png) | ![preview image](/Preview%20Images/300.png) |

## How to use the back template for Power/Toughness

The Power/Thoughness (pt) template for the back side of the cards is not used by default. In the `/pt` folder you can find the default front side pt templates. If you want to use the pt templates for the back side you will need to replace the files in the `/pt` folder with the files in the `/pt/back` folder (I sudgest you to save the default files somewhere).

| using front pt | using back pt |
| --- | --- |
| ![preview image](/Preview%20Images/front.png) | ![preview image](/Preview%20Images/back.png) |

## How to use the Planeswalker template

I adapted the CantaPerMe#3540 `.psd` templates to make it easier for you to create your own pw templates. You will need to make some photoshop or to ask someone to make it for you in the `Request` section [of the discord](https://discord.gg/QwV3KnwsDC). Those templates can be found [in this Google Drive](https://drive.google.com/drive/folders/1VCrE84mhYUwONlbEyYIGCNSI_YwhG4j4).

In this example, I should have modified the `x` and the `y` variables to adjust the image position with the default template, but the point is to show you that the pw symbols are not added by default.

| using default template | using pw template |
| --- | --- |
| ![preview image](/Preview%20Images/default%20template.png) | ![preview image](/Preview%20Images/pw%20template.png) |
