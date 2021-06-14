# Messenger graphs & statistics

![Version](https://img.shields.io/badge/python-3.9-blue)
![GitHub issues](https://img.shields.io/github/issues/Byczax/messenger_graphs_statistics)
![GitHub Repo stars](https://img.shields.io/github/stars/Byczax/messenger_graphs_statistics?style=social)

## Description

This code is used with data downloaded from facebook to generate statistics in form of graphs.

## Usage

### 1.Download data

Download conversation data from [**here**](https://www.facebook.com/dyi/?referrer=yfi_settings).

### 2.Conversion

1. Process this file(s) with `fix_stupid_facebook_unicode_encoding.py` in console.
(write `fix_stupid_facebook_unicode_encoding.py` without argument for help)

2. Insert all generated files into **1 folder** in the same directory as folder `src`. (name folder as you like and write it's name in `main.py`)

### 3.Creating data

Change parameters in main.py file for your needs

run file main.py and get your graphs :smile:

(if you want to save graphs in `.png` format, change parameter in `main.py` file to *True*)

### 4.Available data

Right now i created modules for:

1. All sended messages
2. All reactions given to others
3. All received reactions
4. Counting specific reaction
5. Counting specific word
6. Counting all emoji used in conversation

### TODO

- Count sended images, gifs
- Count sended files
- deleted messages
- Count sended links to websites
- Added and removed members
