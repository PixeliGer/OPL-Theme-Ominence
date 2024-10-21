# Ominence Theme

<p align="center">
  <img src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/logo.png">
</p>

<div align=center>
  
  ![BUILT WITH](https://img.shields.io/badge/BUILT%20WITH-%E2%9D%A4-cd6133?labelColor=ff793f&style=for-the-badge&logoColor=f0f0f0)
  [![][made-with]][gimp]
  [![Github All Releases](https://img.shields.io/github/downloads/PixeliGer/OPL-Theme-Ominence/total?style=for-the-badge)]()
  
  [gimp]: https://www.gimp.org/
  [made-with]: https://img.shields.io/badge/gimp-5C5543?style=for-the-badge&logo=gimp&logoColor=white&logoSize=auto&label=Made%20With
  
  [![][download-ominence]][ominence]
  
  [ominence]: https://github.com/PixeliGer/OPL-Theme-Ominence/releases/latest
  [download-ominence]: https://img.shields.io/badge/Download%20🡇-35BF5C?style=for-the-badge
  
</div>

**Ominence** theme for Open PS2 Loader, inspired by the **Eminence 2** skin for Kodi, showcases a sleek and contemporary design. This theme emphasizes simplicity and elegance, providing users with a visually appealing and intuitive interface, ensuring a clean and modern user experience that enhances both functionality and style.

## 🌱 Inspiration

<p align="middle">
  <img width="48%" src="https://www.videoconverterfactory.com/kodi/imgs-self/eminence-2-mod/eminence-2-mod-00.jpg">
  <img width="48%" src="https://i.imgur.com/5HSXS60.png">
  <img width="48%" src="https://i.imgur.com/5t4cNNq.png">
</p>

## ✨ Features
* Minimalist and compact design
* Show the data of each game in a simple way
* 2 variants, Simple and Extended (to show cover and screenshot)
* 8 different colors
* Working with HD/Full-HD on 16:9 and 4:3
* Support for separate MX4SIO, USB, Apps and PS1 sections
* Compatible with the latest versions of [Open Ps2 Loader 1.2 Beta](https://github.com/ps2homebrew/Open-PS2-Loader/releases)

## 🎨 Different Color Variants

<p align="middle">
  <img src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/ominence_colors.png"> 
</p>

## 📸 Screenshots

#### Ominence

<p align="middle">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot1.png"> 
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot3.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot5.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot7.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot9.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot11.png">
</p>

#### Ominence Extended

<p align="middle">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot2.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot4.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot6.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot8.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot10.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Ominence/blob/main/assets/screenshots/screenshot12.png">  
</p>

## 💾 Installation

#### 1. Initially, ensure your OPL folder is structured like this on your Device or in your Shared folder
```
APPS/
ART/
CD/
CFG/
CHT/
DVD/
POPS/
THM/
VMC/
```
#### 2. Download one of the zip files that contains one the Theme variants from the [Releases](https://github.com/PixeliGer/OPL-Theme-Ominence/releases/latest) page or using the green DOWNLOAD button at the top, (make sure it's one with the `thm_` prefix in its name)
```
thm_Ominence
thm_Ominence-Extended
```
#### 3. Extract the ZIP file and move the theme folder to your THM directory.
```
THM/
├─ thm_Ominence/
├─ thm_Ominence-Extended/
```

> [!NOTE]  
> Themes must be placed inside a folder named `THM` (in uppercase) for any of the devices: SMB share, HDD, USB, SD (MX4SIO), once the device starts, OPL will list the themes found in these locations

SMB (Network Share)
In the root directory or drive you set as your PS2SMB share, in a THM folder

```
PS2SMB/THM/thm_Ominence/
```

USB, SD device
In the root of the drive or partition set for OPL, in a THM folder

```
mass:/THM/thm_Ominence/
```

HDD (Internal hard drive)
Place the THM folder in the `OPL Partition` of the HDD `+OPL`, you can create the partition if it doesn't exist, by using `uLaunchELF`: [FileBrowser > MISC > HddManager]

```
hdd0:/+OPL/THM/thm_Ominence/
```

> [!IMPORTANT]  
> Themes on any of these devices won’t display unless the device is enabled, so make sure to enable the device where your themes are stored through the OPL settings.


#### 4. Launch OPL, if it was already open, restart it.
#### 5. Go to OPL Settings and then Display Settings. In the ‘Theme’ option, find and select your theme, then click `OK` to apply it.


## 💡 Recommendations

To enhance your experience with the theme, consider these recommendations:

* Make sure you are using an updated or recent version of [Open Ps2 Loader 1.2 Beta](https://github.com/ps2homebrew/Open-PS2-Loader/releases)
* Download the assets from the `ART` folder (Background Image, Cover, Screenshots, etc.) using the latest version of [OPL Manager](https://oplmanager.com/site/)
* Use OPL Manager to edit the `CFG` files for each game, to correctly display the description, rating and release.
* Enable Widescreen mode in OPL Settings for better text visibility.
* ⚠️ Avoid installing themes on the Memory Card, as their storage size can impact the proper functioning of the themes and cause issues with OPL.
