# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
arr=np.array(eval(input()))
print("Given array\n ",end='')
print(arr)
print()
print(np.sort(arr,axis=1))
```
## Output

<img width="743" height="432" alt="Screenshot (966)" src="https://github.com/user-attachments/assets/a41f75bb-699e-4220-9043-8270d66454d8" />

## Result

Thus the NumPy* program that sorts the elements in each row of a given 2D array in ascending order has been executed successfully.

