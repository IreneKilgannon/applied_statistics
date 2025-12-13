# Applied Statistics

__Author:__ Irene Kilgannon

__Student ID:__ G00220627

This repository contains the assessment tasks for the Applied Statistics module, part of the [Higher Diploma in Science in Data Analytics](https://www.atu.ie/courses/higher-diploma-in-science-data-analytics) at [Atlantic Technological University](https://www.atu.ie/).

This module is taught by Ian McLoughlin and the assessment brief and course materials is available on [Github](https://github.com/ianmcloughlin/applied-statistics/tree/main).

## Assessment Overview

This assessment consists of four problems:

1. Extending the Lady Tasting Tea
2. Normal Distribution
3. t-Tests
4. ANOVA

The full brief for each problem is available [here](https://github.com/ianmcloughlin/applied-statistics/blob/main/assessment/problems.md).

All solutions are documented in [problems.ipynb](https://github.com/IreneKilgannon/applied_statistics/blob/main/problems.ipynb) in this repository. 

## File Overview

    applied_statistics
    ├── img                     # Images used in the notebook.
    ├── .gitignore              # Files and folders ignored by Git.
    ├── README.md               # Repository overview (this file).
    ├── problems.ipynb          # Jupyter notebook containing solutions.
    ├── requirements.txt        # Python dependencies required to run the notebook.

## Installation

To run the file, on your local system the following programs download and install:
1. [Anaconda](https://www.anaconda.com/download) - Python distribution
2. [Visual Studio Code](https://code.visualstudio.com/download) - Code editor
3. [git](https://git-scm.com/) - Version control
4. [Cmder](https://cmder.app/) - Terminal emulator

Clone this repository:

```
git clone https://github.com/IreneKilgannon/applied_statistics.git
```

## Dependencies

All dependencies are listed in ``requirements.txt``.

They are installed after the virtual environment has been created.

## Usage

1. __Create and activate a virtual environment__ in the ``applied_statistics`` directory:

```bash
python -m venv venv
venv\Scripts\activate  # Windows
# source venv/bin/activate  # macOS/Linux
```
2. __Install dependencies:__

```bash
pip install -r requirements.txt
```

3. __Open the notebook (problems.ipynb)__ in Visual Studio Code and select the __venv__ kernel.

   Open command palette → ``Python: Select Interpreter`` →  ``Enter interpreter path``

    Navigate to ``venv`` → ``venv\Scripts\python.exe``

4. __Run the notebook.__

5. __Deactivate the virtual environment:__.

```bash
deactivate
```

## Get Help

Contact me at g00220627@atu.ie or submit an [issue](https://github.com/IreneKilgannon/applied_statistics/issues).