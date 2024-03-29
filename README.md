# Python GIFs: Crafting Simple Animations from Scratch

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Examples](#examples)
- [License](#license)
- [Contact](#contact)

## Installation
1. Clone this repository: `git clone https://github.com/ohmma0tokita/gif-creation-project.git`
2. Navigate to the project directory: `cd gif-creation-project`
3. Install dependencies: `pip install -r requirements.txt`

## Usage
1. Customize the frames in the `frames/` directory to create your animation.
2. Add an audio file if you want, .wav format
3. Run the GIF creation script: `python gif.py` after changing the necessary
4. Continuously lick on [spacebar] to run the gif
5. Enjoy

## Features
- Create GIFs from individual frames, add music if you want.
- Adjust frame duration and order for custom animations.
- Support for various image formats (PNG, JPEG, etc.).
- Lightweight and easy-to-understand codebase.

## Examples
**Creating a GIF:**
```python
# Import the necessary modules
from gif_utils import create_gif

# Create a GIF
# you can use the anime or neon frames folders provided in the repo
create_gif("frames-folder-name", music_file="music-file",speed="transition-speed")
```

## Licence
This project is licensed under the MIT License

## Contact
Feel free to contact me at f.sghiri01@email.com.
