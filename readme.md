# Python playlistMaker

## Overview
* Crawls through a directory (root) and adds a playlist at all root/folder/ level folders containing references to all files in root/folder/

## Features

* Recursive crawl through all folders
* Only add .m3u at root/folder level

## Changelog

### What's New
* Added to GitHub (2012.10.24)

### In Development
* Option for with or without recursion
* Add playlist at each folder level with .mp3
* Different playlist formats

## Installation

### Dependencies
* Python: Uses os and re modules

### Use
* Double-click playlistMaker.py, it will ask for a folder to crawl, select and go,
* A log file of all .m3u playlist made is stored in the same directory as playlistMaker.py

### Settings
* Open settings.py
* Default directory: Where the program will crawl if no folder supplied
* Valid audio formats: A list of valid extensions, add or remove if you only want to include specific files