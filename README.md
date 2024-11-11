# Ex.No: 12 Pytest Python program for Addition
### DATE: 22/10/2024
### REGISTER NUMBER : 212221040069
### AIM:
To write a python program for addition of two numbers and test the test cases using Pytest.
### Algorithm:
```
1.Write the python program for addition of two numbers.
2.Make sure thatfunction name should be “def test_*():” and the line to be tested should have assertkeyword at the beginning.
3.Write some test cases for to be tested and save it as“test_add.py”.
4.Open command prompt and change the directory to where pytestand program is saved and type “pytest test_add.py” and run it. 
5.Stop the program.
```
### Program:
```
def add(a,b):
    return a+b
    def test_3_plus_5_equals_8():
      assert add(3,5) == 8
    def test_2_plus_3_equals_5():
      assert add(2,3) == 6
```
### Output:
![image](https://github.com/user-attachments/assets/9613f095-d70a-4df7-9f6c-d275cad0b223)

### Result:
Thus, the python program for addition is tested using pytest and executed and output is verified successfully.


