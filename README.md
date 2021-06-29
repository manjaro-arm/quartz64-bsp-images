# Manjaro ARM Quartz64 BSP
[![iso_build](https://github.com/manjaro-arm/quartz64-bsp-images/workflows/image_build_all/badge.svg)](https://github.com/manjaro-arm/quartz64-bsp-images/actions)

## description

Release Branch for Manjaro ARM images for the Quartz64 BSP

## where can I download an image?

Images are build and uploaded to [github releases](https://github.com/manjaro-arm/quartz64-bsp-images/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d quartz64-bsp -e $EDITION`
