# Linear Programming Calculations for ``Further analysis on the second frequency of union-closed set families''

This repository contains the Linear Program calculations, scripts, and results accompanying the paper:
``Further analysis on the second frequency of union-closed set families'' (arXiv link:)

## How to Use

The linear programs are written in GNU MathProg, a modelling language intended for describing linear mathematical programming models.

Each file contains a linear program for corresponding Lemma/case analysis except for ||linprog L_0||, in which there are 2. 
In the title of each linear program, there is a record for the intended bound for $m$ as a reference.
To check the linear programs, follow these steps:

a. Copy the linear program models to the 'Model' tab in the online optimizer https://online-optimizer.appspot.com/
b. Run 'Solve Model'
c. The bound of m is shown in 'Optimal objective value' in 'Model Overview'. See other tabs for more details.
