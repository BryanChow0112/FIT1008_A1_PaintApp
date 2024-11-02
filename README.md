# PaintFlow

PaintFlow is a simple and playful image editing application, drawing inspiration from [Chicory: A Colorful Tale](https://chicorygame.com/). Like the game’s world where users paint their surroundings, PaintFlow gives users a sandbox to manage, transform and experiment with images.

Through structured data management (using stacks, queues and lists), PaintFlow makes it simple to undo and redo actions, apply transformations and add layers of color and effects, all optimized for smooth performance.


## Badges

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


## Features

* Canvas Manipulation: Explore a digital canvas, transforming it with various tools and colors.
* Undo/Redo Magic: Quickly reverse or reapply actions with stack-based undo/redo operations.
* Flow of Creativity: Effortlessly move through layers and apply custom image transformations.
* Efficient Performance: Designed to handle complex operations seamlessly for a fluid, creative experience.


## Setup

Note: For all of these you may need to replace `python` with `py` or `python3` depending on your operating system and python version.

```bash
python -m pip install virtualenv
python -m venv venv
```

Next, activate your virtual environment (Must be done every time you open the terminal)

Windows Bash
```
source venv/Scripts/activate
```

Windows CMD
```
venv/Scripts/activate
```

Windows Powershell
```
venv/Scripts/activate.ps1
```

Mac / Linux bash
```
source venv/bin/activate
```

Then install the requirements!
```
python -m pip install -r requirements.txt
```

## Running the program

To run the interactive version:

```bash
python main.py
```

To run the visual tests:

```bash
python -m visuals.basic
python -m visuals.complex
python -m visuals.styles
```

To run the unit tests:

```bash
python run_tests.py
```
