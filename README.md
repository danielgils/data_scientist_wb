# Technical exercise for Extended Term Consultant position
This repo has three different files corresponding to Part I and II of this technical exercise.

## Setup
To run the file `part1_script.ipynb` of the *Part I* follow these steps:
1. Clone this repo in your local computer.
1. Make sure you have installed Python 3.10.6 or a later version. If you don't have it or have a different version, you can use `pyenv` to manage different python versions in the same machine (see [here for Unix based OS](https://realpython.com/intro-to-pyenv/), or [here for Windows](https://github.com/pyenv-win/pyenv-win)). Preferably, use `pyenv local 3.10.6` inside the folder of this repo, to assign this version to the folder.
1. Create a virtual environment using `venv`. You can run in the terminal the following `python3 -m venv venv` where the second `venv` corresponds to the name of the virtual enviroment.
1. Activate the virtual environment. In Unix based OS you can run in the Terminal `source venv/bin/activate`. In Windows you can run in Powershell `.\venv\Scripts\activate`.
1. Install the required libraries. You can run in the Terminal/Powershell `pip install -r requirements.txt`.

## Answers to the test
Once the setup is done, you can do the following:
- Part I:
    - `part1_script.ipynb` is the Jupyter notebook where the data is retrieved and analyzed.
    - `Part1_output.pdf` is the one pager containing the analysis.
- Part II:
    - `part2.md` is the review of the claims made in the email.
    
## Notes
- This practical test was developed using Python 3.10.6 in VS Code on Ubuntu Server 22.04.1 LTS, with the help of ChatGPT.
- The code was tested in macOS Monterrey (v12.5) using `pyenv local 3.10.6`.
- The code was tested in Windows 10 using `pyenv local 3.10.6`.