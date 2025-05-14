# Ex:4(a) Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
Developed By: V Mythili
Reg NO: 212223040123

```
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")


r = float(input())


obj = cse()
obj.mech(r)
```


## Output

![image](https://github.com/user-attachments/assets/87f34dca-3ecc-4987-bcd4-3b6503525501)

## Result

Thus the program executed successfully.

# EX:4(b) Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
Developed By: V Mythili
Reg No: 212223040123

```
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```
## Output

![image](https://github.com/user-attachments/assets/118b5f2b-2d74-4aef-8b19-68fac8eee70e)

![image](https://github.com/user-attachments/assets/ef8ae75b-ce29-4f00-966e-f6874ee270f3)

## Result

Thus the program executed successfully.

# Ex:4(c) 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
Developed By: V Mythili
Reg No: 212223040123

```
input_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}
sorted_items = sorted(input_dict.items())
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sorted_items:
    print(f"({key}, {value})", end=' ')
```

## Output

![image](https://github.com/user-attachments/assets/d36b1603-4a2c-4db2-842a-da45289fb26f)

![image](https://github.com/user-attachments/assets/501782d5-059c-4ebc-8093-d0db7efbdb26)


## Result

Thus the program executed successfully.

# Ex:4(d) Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
Developed By: V Mythili
Reg No: 212223040123

```
try:
    # Taking 3 elements input from the user
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

    # Trying to access index 4
    print(L[4])

except IndexError:
    print("check index range")
```

## Output

![image](https://github.com/user-attachments/assets/4e8949b4-950d-4398-b0c0-9e16344f40b6)


## Result

Thus the program executed successfully.

# Ex:4(e) File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
Developed By: V Mythili
Reg No: 212223040123

```
f=open("story.txt","r")
count=0
for lines in f:
    if lines[0] not in "T":
        count+=1
    print(count)
```

## Output

![image](https://github.com/user-attachments/assets/6c4ae004-95a0-45c4-acfd-967d38c8da1a)

## Result

Hence the program executed successfully.
