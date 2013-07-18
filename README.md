 	     8888888888b     d888 .d8888b.
 	       888  8888b   d8888d88P  Y88b
 	       888  88888b.d88888888    888
 	888d888888  888Y88888P888888
 	888P"  888  888 Y888P 888888  88888
 	888    888  888  Y8P  888888    888
 	888    888  888   "   888Y88b  d88P
 	888  8888888888       888 "Y8888P88

# rIMG - Image Resizer

This is a shell/bash script you can run to automatically resize images based on their current size.  The current settings is for 1024, when you run the script it will scan the directory you supply for any images that are larger than 1024 (width or height), and resizes them to 1024.

This is still being developed, hopefully more features to come ...

## Installation
``` bash
wget https://raw.github.com/tripflex/rimg/master/rimg
chmod +x rimg
```

## Usage
``` bash
./rimg <path>
```