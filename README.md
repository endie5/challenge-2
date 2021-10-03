# Module 2 Challenge

The main purpose of this application is to assist the user with applying for loans. AFter prompting the user to enter their information, it will compare the entries with data grabbed from a CSV file, containing the 
requirements of all available lenders. Afterwards, the application will save a file of the loans the user qualifies for.



	
---

## Technologies

This application is entirely coded in Python- it uses the libraries `sys`, `fire`, `questionary`, `csv`, and `pathlib`. The Python version is 3.8.8.

---

## Installation Guide

We use the `pip` package-management system to install the `fire` and `questionary` libraries. 

```bash
pip install fire
pip install questionary
```

From there on, we can just import the remaining packages that we require. 

```python
import sys
import fire
import questionary
import csv
from pathlib import Path
```

---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

When you run the main module file app.py, the user must enter a file path to a rate sheet. There is already a rate sheet provided in the data folder but the user may choose to use another rate sheet if they wish.
Afterwards, the user is prompted by the program to enter their information. Loan factors are calculated and the qualified loans are saved as a list of lists. If you wish to save the qualified loans onto a CSV file,
the user must specify the file path where the file is to be saved.
![](https://i.imgur.com/xc6fFnv.jpg)

To modify the functions, the other module files are located in the qualifier folder.

---

## Contributors

The starting unmodified code can be found on the [Columbia Fintech Bootcamp online portal](https://courses.bootcampspot.com/courses/825/files/898978/download).


---

## License
Please use this code however you wish.
