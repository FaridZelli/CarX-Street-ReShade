# CarX Street ZINHAR ReShade
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/FaridZelli/CarX-Street-ReShade/total?style=for-the-badge&logo=github&label=Total%20Downloads&labelColor=blue&color=green&cacheSeconds=7200)](https://github.com/FaridZelli/CarX-Street-ReShade/releases/latest)
  
A subtle ReShade preset with an emphasis on warmth, true to the game's Mediterranean climate.  

## Installation
[Download from releases](https://github.com/FaridZelli/CarX-Street-ReShade/releases/latest)
### Windows:
- Extract the archive and copy the files over to your game directory.

### Linux (Steam/Proton):
- Extract the archive and copy the files over to your game directory.  
- Set the following launch options in Steam:
```
WINEDLLOVERRIDES="d3dcompiler_47,dxgi=n,b" %command%
```
ⓘ [ProtonGE](https://github.com/GloriousEggroll/proton-ge-custom) is recommended to avoid stutters.

## [Screenshots (click for comparison tool)](https://faridzelli.github.io/CarX-Street-ReShade/)

| ReShade Off | ReShade On |
| --- | --- |
| ![ReShade Off](https://github.com/FaridZelli/CarX-Street-ReShade/blob/main/screenshots/image1.jpg) | ![ReShade On](https://github.com/FaridZelli/CarX-Street-ReShade/blob/main/screenshots/image2.jpg) |
| ![ReShade Off](https://github.com/FaridZelli/CarX-Street-ReShade/blob/main/screenshots/image3.jpg) | ![ReShade On](https://github.com/FaridZelli/CarX-Street-ReShade/blob/main/screenshots/image4.jpg) |
| ![ReShade Off](https://github.com/FaridZelli/CarX-Street-ReShade/blob/main/screenshots/image5.jpg) | ![ReShade On](https://github.com/FaridZelli/CarX-Street-ReShade/blob/main/screenshots/image6.jpg) |

## Expected performance
| Variant | Framerate | Impact | GPU | Video Settings | Resolution |
| --- | --- | --- | --- | --- | --- |
| ReShade Off | 36 FPS | - | RX 6700 XT | Maxed Out | 2160p |
| ReShade On | 34 FPS | ≤5% | RX 6700 XT | Maxed Out | 2160p |
  
Results may vary depending on your system configuration.

## About
This preset makes use of the following shaders:

- qUINT Lightroom
  - qUINT Lightroom is a comprehensive set of color grading algorithms, modeled after industry-standard applications like Adobe Lightroom and DaVinci Resolve.

- iMMERSE Sharpen
  - iMMERSE Sharpen is a depth-aware sharpening filter that utilizes both depth and color information to increase local contrast in desired areas, minimizing common artifacts typically found in sharpening algorithms, such as haloing around objects.

- Clarity2
  - Clarity2 enhances image clarity and detail by applying a combination of sharpening and contrast adjustment techniques to the image.

## Special thanks
- [Crosire](https://github.com/crosire)
  - [ReShade](https://github.com/crosire/reshade)
- [Pascal Gilcher](https://github.com/martymcmodding)
  - [qUINT](https://github.com/martymcmodding/qUINT)
  - [iMMERSE](https://github.com/martymcmodding/iMMERSE)
- [Ioxa](https://github.com/Ioxa53)
  - [Shaders](https://github.com/Ioxa53/reshade-shaders/tree/patch-1)
