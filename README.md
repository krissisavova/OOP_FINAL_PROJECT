# This repository represents my final project on C++ for my object-oriented-programming course at FMI.
# The name of this project is "Spreadsheet Work Application"

1. Data presentation
The data of a table will be saved in a text file as follows:

- Each row in the file represents a separate row in the table.
- Each line in the file contains comma-separated data. These data are interpreted as values in the row cells.
- Each row in the table can contain a different number of cells. Therefore, each line in the file can contain a different number of elements separated by commas.
- An empty row in the file represents an empty row in the table. (ie, the order in which all cells are empty).
- There may be no data between two commas in the file. In this way, an empty cell is represented.
- There can be any number of whitespace between data and commas.

2. Data types in the table
Each cell in the table has a type, and a table can have cells of different types at the same time. Your application must be able to support the following types:

- Integers
- Fraction numbers
- Strings
- Formulas: addition (+), subtraction (-), multiplication (*), division (/) and exponentiation (^).
