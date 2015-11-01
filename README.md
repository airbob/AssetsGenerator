> **changes:** I changed original code to extend the possibility to generate normal image asset based on source image and 1x scale size. For instance, I have a 512x512 back.png and want to generate an image asset with 1x scale size of 44x44, execute as ```python generator.py --image back.png --size 44``` and the script will do the rest of the work. Below is original description of the [project](https://github.com/APSL/AssetsGenerator):

AssetsGenerator
===============

Simple Python script to generate iOS icon image assets

## Install

Install [Pillow](http://pillow.readthedocs.org/installation.html#simple-installation) first. Then clone the repo.

## Usage

Run

```python generator.py --icon ICON```

to generate the icon assets. Replace ``ICON`` with your icon filename.

To create launch image assets run

```python generator.py --launchimage IMAGE```

replacing ``IMAGE`` with your ``@3x`` launch image file.
