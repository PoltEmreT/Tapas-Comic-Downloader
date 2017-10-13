# Tapastic-Comic-Downloader
This is a downloader to download and update whole comics from https://tapas.io/. (Not official!)

## Attention:
**This script could be illegal in certain cases, please first read the terms of service on https://tapas.io/ !**

## Usage:
1. Installing Python3:
 * Can be installed on Debian and Ubuntu and other Linux distribution that use 'apt' like this:
 ```
 # apt install python3
 ```
 * On Arch:
 ```
 # pacman -S python
 ```
2. Get input link
 * Go to the comic you want to download (any page)
 * Rightclick on the comic name in the upper left corner and select "Copy linkaddress" (Or similar) or just use the name behind series in the url.
 * Examples: `https://tapas.io/series/Erma`, `RavenWolf`, ...
3. Start the download
 * Usage of `tapas-dl.py`:
 ```
 tapas-dl.py [-h] URL/name [URL/name ...]
 ```
 * The script will create an folder with the name and urlName (`name [urlName]`) of the comic in the current shell location (like git) and download all images of the comic into it.
