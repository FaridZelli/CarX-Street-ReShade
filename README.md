# CarX Street ZINHAR ReShade
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/FaridZelli/CarX-Street-ReShade/total?style=for-the-badge&logo=github&label=Total%20Downloads&labelColor=blue&color=green&cacheSeconds=18000)](https://github.com/FaridZelli/CarX-Street-ReShade/releases/latest)
  
A ReShade preset that significantly enhances the game's visuals while maintaining the original artistic vision.

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

## Screenshots

| ReShade Off | ReShade On |
| --- | --- |
| ![ReShade Off](https://github.com/FaridZelli/CarX-Street-ReShade/blob/main/images/Screenshot_20240917_124906.png) | ![ReShade On](https://github.com/FaridZelli/CarX-Street-ReShade/blob/main/images/Screenshot_20240917_124910.png) |

### Expected performance:
| GPU | Video Settings | Resolution | Average FPS |
| --- | --- | --- | --- |
| RX 6700 XT | Max + TAA | 1440p | 45~55 |
  
Results may vary depending on your system configuration.

## About
This preset makes use of the following shaders:

- GloomAO
  - GloomAO is a screen space directional occlusion shader that includes Temporal Anti-Aliasing (TAA) and basic global illumination.

- iMMERSE Sharpen
  - iMMERSE Sharpen is a depth-aware sharpening filter that utilizes both depth and color information to increase local contrast in desired areas, minimizing common artifacts typically found in sharpening algorithms, such as haloing around objects.

- qUINT Lightroom
  - qUINT Lightroom is a comprehensive set of color grading algorithms, modeled after industry-standard applications like Adobe Lightroom and DaVinci Resolve.

- Clarity2
  - Clarity2 enhances image clarity and detail by applying a combination of blurring, sharpening, and contrast adjustment techniques to the image.

## Special thanks
- [Crosire](https://github.com/crosire)
  - [ReShade](https://github.com/crosire/reshade)
- [Pascal Gilcher](https://github.com/martymcmodding)
  - [qUINT](https://github.com/martymcmodding/qUINT)
  - [iMMERSE](https://github.com/martymcmodding/iMMERSE)
- [BlueSkyDefender](https://github.com/BlueSkyDefender)
  - [AstrayFX](https://github.com/BlueSkyDefender/AstrayFX)
- [Ioxa](https://github.com/Ioxa53)
  - [Shaders](https://github.com/Ioxa53/reshade-shaders/tree/patch-1)
