# Applied Statistics

Author: Irene Kilgannon

Student ID: G00220627

This repository contains the assessment tasks for the Applied Statistics module, part of the [Higher Diploma in Science in Data Analytics](https://www.atu.ie/courses/higher-diploma-in-science-data-analytics) at [Atlantic Technological University](https://www.atu.ie/).

This module is taught by Ian McLoughlin and the assessment brief and course materials is available [on Github](https://github.com/ianmcloughlin/applied-statistics/tree/main).

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

To run the file, on your local system the following programs were downloaded and installed:
1. [Anaconda](https://www.anaconda.com/download) - Python distribution
2. [Visual Studio Code](https://code.visualstudio.com/download) - Code editor
3. [git](https://git-scm.com/) - Version control
4. [Cmder](https://cmder.app/) - Terminal emulator

Clone this repository:

```
git clone https://github.com/IreneKilgannon/applied_statistics.git
```

## Dependencies

Install all the required packages:

 ```
 pip install -r requirements.txt
 ```

## Usage

1. __Create and activate a virtual environment__ in the ``applied_statistics`` directory:
```
python -m venv venv
venv\Scripts\activate
```
2. __Install dependencies:__

```
pip install -r requirements.txt
```

3. __Open the notebook (problems.ipynb)__ in Visual Studio Code and select the __venv__ kernel.

4. __If the venv kernel does not appear__, install Jupyter and register the kernel manually:

```
pip install notebook ipykernel
python -m ipykernel install --user --name=venv --display-name="Python (venv)"
```

5. __Run the notebook.__


## Get Help

Contact me at g00220627@atu.ie or submit an [issue](https://github.com/IreneKilgannon/applied_statistics/issues).