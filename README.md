# Frequency_Distribution_Table
This program creates frequency distribution table with up to two decimal places in given values

**DEPENDENCIES**:
1. Tkinter
2. Numpy
3. Math


**CONSTANT VALUES FOR ALL STATEMENTS:**

CONST_0 = Count of elements (This is the cardinality of the given values)
CONST_1 = Decimal places (This is how many the decimal places of the given values)
CONST_2 = Values (These are the given values)


**CONDITIONS**:

INPUT CONDITIONS:
1. The CONST_0 input should match the CONST_2 input count, otherwise will be asked repeatedly until condition get satisfied.
2. The CONST_1 input should match the decimal points of ALL of the values in CONST_2 input, otherwise will get an error.

OUTPUT CONDITIONS:
1. The user should have Tkinter module installed in the local machine for the GUI to appear.


**LIMITATIONS**:

1. The program will not work if there are inconsistent given values. (Ex. 20, 52.1, 21.23...)
2. The program is only limited to less than or equal two decimal places in given values. (To be specific: 0, 1, 2 decimal places only)
3. The program has a limitation of 30 frequencies. If the number of rows exceed 30, some frequencies will not be shown, hence the program will not work properly.
4. The GUI might become large in width and height where it exceeds the user's screen size. The output might not be shown properly on the screen.
5. The GUI is non-resizable so it could lead to width and height issues as suggested in number 4.
6. The program uses CLI input and GUI output. Not recommended for users who wants to input in GUI.
7. The program will only work using CLI. (Recommended using IDE to run the program)
8. The program will only work using python 3 since it is coded using Python programming language.


**INSTRUCTIONS**:

--There could be minimum of 5 inputs up to 7 inputs depending on certain reasons--

INPUT (Case 1):
1. CONST_0
2. CONST_1
3. CONST_2
4. Specified number of rows (if "Y")
5. Number of rows (This is the specified number of rows)
6. Specified number of class size (if "Y")
7. Class size (This is the specified class size)

INPUT (Case 2):
1. CONST_0
2. CONST_1
3. CONST_2
4. Not specified number of rows (if "N")
5. Not specified class size (if "N")

INPUT (Case 3):
1. CONST_0
2. CONST_1
3. CONST_2
4. Specified number of rows (if "Y")
5. Number of rows (This is the specified number of rows)
6. Not specified class size (if "N")

INPUT (Case 4):
1. CONST_0
2. CONST_1
3. CONST_2
4. Not specified number of rows (if "N")
5. Specified class size (if "Y")
6. Class size (This is the specified class size)


**SUGGESTIONS**:
1. Redirect input from a text
2. Use IDE in running the program (Pycharm recommended)
3. Enjoy and have fun!
