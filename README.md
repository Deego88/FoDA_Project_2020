# FoDA_Project_2020

* **Author:** Richard Deegan
* **Github:** Deego88
* **Email:** G00387896@gmit.ie
**Lecturer:** Ian McLoughlin
------------------------------------------------------------------------------------------------
**Fundamentals of Data Analysis:** 

This Jupyter Notebook has been created to perform and explain simple linear regression using Python on the "powerproduction dataset" available [here](https://github.com/Deego88/FoDA_Project_2020/blob/master/FoDA_Project_Data.txt) 

The full Project instructions can be found at 

**Table of Contents**
------------------------------------------------------------------------------------------------

[Project - Programming for Data Analysis](#Project-Programming-for-Data-Analysis)

[1. Introduction](#1-introduction)

[2. Project Repository](#2-project-repository)

[3. Real-World Phenomenon](#3-real-world-phenomenon)

[4. Problem Statement](#4-Problem-Statement)

[5. User Guide](#5-User-Guide)

  [5.1 Downloading the Repository](#5.1-Downloading-the-Repository)

  [5.2  Running the Program](#5.2-Running-the-Program)

  [5.3  Libraries](#5.3-Libraries)

[6. References](#7-References)


## 1 Introduction
-----------------------------------------------------------------------------------------------
The Jupyter Notebook provide an explanation of a simple linear regression and an analysis of its accuracy. 3 lines of best fit though "Guesstimation" were fitted to the powerproduction dataset. This was then compared ot he actaul line of best fit by using the Polyfit function in Python. The Jupyter Notebook then suggests that a different type of regression analysis might be more suited as the **Polynomial Regression** analysis is conducted up to the fifth degree:

y = mx + c
y = ax**2 + bx + c
y = ax**3 + bx**2+ cx + d
y = ax**4 + bx**3+ cx**2 + dx + e

## 2 Project Repository
------------------------------------------------------------------------------------------------
The project repository is the source where all the work associated with
the project will be stored. It contains the following files and can be
located [here](https://github.com/Deego88/FoDA_Project_2020):

  **File**    |     **Description**
  ---------   |   --------------------------------------------------------
  .gitignore | A Text File explicitly explaining to Git which files or folders to ignore in the Assignment
  Project Instructions.pdf | A PDF copy of the Poject Instructions
  LICENSE     |    MIT License for the project
  FoDA_Project_2020.ipynb | Jupyter Notebook created to  in Python
  README.md   |    This file; A Description of the project and instructions

## 3  Real-World Phenomenon
------------------------------------------------------------------------------------------------
 For the purpose of this project the author chose to sumulate the real world phenomena of "factors affecting the success of applicants for a job interview".

Four main variables were Identified:

- 1)Average hours spent in preparation
- 2)Level of Qualifications
- 3)Level of relevant job experience
- 4)First Impressions

## 4 Problem Statement
------------------------------------------------------------------------------------------------
As part of the project, the student was given a set of instructions, the full set can be see here [here](https://github.com/Deego88/FoDA_Project_2020/tree/master/Images_FoDA_Project_2020). In short, the instructions of the project state the following:
In this project you must perform and explain simple linear regression using Python on the powerproduction dataset. 
Provide an explanation of the regression and an analysis of its accuracy.
Enhance the submission by comparing linear regression to other types of regression. 

## 5 User Guide
------------------------------------------------------------------------------------------------
This section will describe the steps required to download and run the files in the repository.

### 5.1 Downloading the Repository
The repository is stored at the following: https://github.com/Deego88/FoDA_Project_2020

To download the repository, do the following:
1.  Click on the above link to open the repository
2.  Once in the repository, click on the green “clone or download” button on the right side of the screen.
3.  Select "Download ZIP". This will open a prompt allowing you to save the file to a desired location on your computer.
4.  Navigate to where  the ZIP files are located on your computer and extract the compressed (.zip) files.

### 5.2 Running the Program
Once the repository has been downloaded, you will need to ensure that you are running it in the correct environment. It should be noted that this repository has been written using Python 3.8.2 and consequently it will require a Python version of 3.7 at a minimum to run as designed. The repository also requires a number of external Python libraries [seen below](#5.3-Libaries) to execute correctly. Once the correct version of Python has been installed complete with necessary libraries and the ZIP has been downloaded and extracted the user can run the program. The running of any of the programs from the command line can be executed as follows:
1.  Open a command prompt (cmd) or equivalent on your computer.([Cmdr](https://cmder.net) is recommended for Windows computers, Mac Computers via the terminal)
2.  Navigate to the desired location through the use of the change directory (cd) command.
3. Run Jupyter Notebook by typing the following at the command prompt (do not close the command prompt window throughout):
```
jupyter notebook
```
4. A notebook server should automatically launch in your default web browser (URL should be http://localhost:8888). If this does not happen, read the command prompt output. You can copy and paste the above URL into your web browser to access Jupyter Notebook.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
```
FoDA_Project_2020.ipynb
```
7. The notebook should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.

### 5.3 Libraries
The following Python libraries were used in the writing of the projects code and are required to successfully run the programs:

-import numpy as np
-import pandas as pd
-import matplotlib.pyplot as plt
-import seaborn as sns


## 6 References
------------------------------------------------------------------------------------------------
References will be indicated numerically throughout the Jupyter Notebook and will be listed in full at the end.

