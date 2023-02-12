# get-gpu-drivers
A simple and convenient Python CLI script that automates the process of updating graphics card drivers. This script was designed to save time when updating computers on a campus between semesters.

### Features
- Supports both AMD and NVIDIA graphics cards (tested on Windows 10)
- Automatically fetches the latest driver for the following GPU models:
  - AMD Radeon Pro W5500
  - NVIDIA Quadro K620
  - AMD Radeon R5 430
  - NVIDIA Quadro P4000
  - NVIDIA T1000

  (Note: Other GPUs may or may not work, as they have not been tested)
  
- Automatically opens the downloaded executable for installation
- Script fetches the auto-installer for AMD cards

### Software
- Python 3.10
- Selenium
- auto-py-to-exe

### How to Use
1. Git clone the project.
2. Install [pipenv](https://pypi.org/project/pipenv/).
3. In the project's root directory. Run `pipenv install`.
4. Once dependencies are installed, you can run `pipenv shell`
5. Run `python start.py` 
6. Optionally, you can use auto-py-to-exe to create an exe file. Read more [here](https://pypi.org/project/auto-py-to-exe/)
