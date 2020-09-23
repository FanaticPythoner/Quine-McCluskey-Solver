# Quine-McCluskey-Solver
Simple command line Quine-McCluskey algorithm (https://en.wikipedia.org/wiki/Quine%E2%80%93McCluskey_algorithm) solver. The solver generate an Excel file with the steps and final equation.


### Language: ### 

- Tested in Python 3.8, should work in all Python 3 version.
  
  
# Usage

Once you open the project, you will find a class named *QMCSolver* inside the file *QMCSolver.py*. Simply create an instance of it with the good parameters. The parameters are:
  1. lstTrue: List of indices of values that needs to be equal to 1 in the truth table
  2. lstDontCare: List of indices of values that needs to be equal to "Don't care" (X) in the truth table
  3. lstVars: List of variables to use
  4. outputPath: Output excel path
  5. lang: language for the excel export. Can be either "en" (English) or "fr" (French)
  
Once you create the instance, simply call the *calculate* method to solve the problem and generate the Excel file. Here's the example provided in the *demo.py* file:

![alt text](https://i.imgur.com/HPwA0S4.png)


Output Excel file after running the previous code:

![alt text](https://i.imgur.com/YSRCPyq.png)

![alt text](https://i.imgur.com/p88GyKZ.png)

![alt text](https://i.imgur.com/bfuD3Gu.png)

![alt text](https://i.imgur.com/lwTaQBk.png)

![alt text](https://i.imgur.com/938KrLl.png)

![alt text](https://i.imgur.com/suUAxZw.png)
