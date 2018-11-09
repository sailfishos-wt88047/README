# SailfishOS for Xiaomi Redmi 2/PRIME

This repository uses gitlab-ci to build the sailfish images for the Xiaomi Redmi 2/Prime


![enter image description here](https://preview.ibb.co/fbkdCK/Untitled_design.png)


## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Qualcomm MSM8916 Snapdragon 410
CPU     | Quad-core 1.2 GHz ARM® Cortex™ A53
GPU     | 400MHz Adreno 306
Memory  | 1/2 GB RAM
Shipped Android Version | 4.4.4
Storage | 8/16 GB
MicroSD | Up to 32 GB
Battery | Removable Li-Ion 2200mAh battery
Dimensions | 134 x 67.2 x 9.4 mm
Display | 720 x 1280 pixels, 4.7 inches (~312 ppi pixel density)
Rear Camera | 8 MP, f/2.2, 28mm, autofocus, LED flash
Front Camera | 2 MP, 720p


# Files

[wt88047.env](https://gitlab.com/abhishek9650/sailfishos-wt88047-ci/blob/master/wt88047.env) contains all the environment variables required for the process. On every release, version number is changed in the master branch and a new tag is created with the release number to trigger the build process.

[Jolla-@RELEASE@-wt88047-@ARCH@.ks](https://gitlab.com/abhishek9650/sailfishos-wt88047-ci/blob/master/Jolla-@RELEASE@-wt88047-@ARCH@.ks) file is the kickstart file which is used by PlatformSDK image, this files contains device specific repositories, Repositories can be changed by from devel to testing or vice versa.

[run-mic.sh](https://gitlab.com/abhishek9650/sailfishos-wt88047-ci/blob/master/run-mic.sh) is a simple bash script, which executes the build.

# [Download the latest build](https://gitlab.com/sailfishos-porters-ci/sailfishos-wt88047-ci/-/jobs/100311437/artifacts/download) | 2.2.1.18 - [![pipeline status](https://gitlab.com/sailfishos-porters-ci/sailfish-scorpion_windy_ci/badges/master/pipeline.svg)](https://gitlab.com/sailfishos-porters-ci/sailfishos-wt88047-ci/pipelines/30863778)

# [https://github.com/sailfishos-wt88047](https://github.com/sailfishos-wt88047)
