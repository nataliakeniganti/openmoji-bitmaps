# Bitmap renders of OpenMoji

Automated render of [OpenMoji](https://github.com/hfg-gmuend/openmoji) SVG sources as PNG images, powered by GitHub Actions. \
OpenMoji repository is checked for a new release every day.

## Available renders
### Downloads

Each target is zipped as part of the [release](https://github.com/nataliakeniganti/openmoji-bitmaps/releases). \
You can also pick individual files browsing the `main` branch.

Files can be distributed through jsDelivr. \
Latest: \
`https://cdn.jsdelivr.net/gh/nataliakeniganti/openmoji-bitmaps@master/<target>/<file>` \
Specific version: \
`https://cdn.jsdelivr.net/gh/nataliakeniganti/openmoji-bitmaps@<tag>/<target>/<file>` \
Examples: \
`https://cdn.jsdelivr.net/gh/nataliakeniganti/openmoji-bitmaps@master/128x128_png32/1F382.png` \
`https://cdn.jsdelivr.net/gh/nataliakeniganti/openmoji-bitmaps@16.0.0/128x128_png32/1F9D0.png`

### Targets

Folder name structure: `<width>x<height>_<format>`

| \<format\> | Description | Background | Lossy |
| :---: | :--- | :---: | :---: |
| png32 | 8 bit/channel RGBA PNG | trans | N |
| png8 | Indexed PNG with 8 bit/channel adaptive RGB palette + 8 bit adaptive A palette | trans | Y |

### Sources

OpenMoji repository used is [hfg-gmuend/openmoji](https://github.com/hfg-gmuend/openmoji). \
Sources are the `color/svg` directory taken from latest release tag of the `master` branch.

## Licensing

OpenMoji graphics are licensed under [Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). \
Refer to https://github.com/hfg-gmuend/openmoji for more information about authors.
