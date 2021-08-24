# Code Challenge: Class 26

## Insertion Sort

### Pseudocode

```py
InsertionSort(int[] arr)

    FOR i = 1 to arr.length

      int j <-- i - 1
      int temp <-- arr[i]

      WHILE j >= 0 AND temp < arr[j]
        arr[j + 1] <-- arr[j]
        j <-- j - 1

      arr[j + 1] <-- temp
```

Starting for loop
for i = 1
declare variable j assign value of i -1
declare variable temp assign value of array representing the index
starting while loop
check if j is >= 0 and temp < array[j]
find the value from array which represents index value of 1
assign j = 0
find the value of arr[0 + 1]

[8,4,23,42,16,15]
 0 1  2  3  4  5

for i = 1
 int j = i -1 #(1 -1)
 int temp = arr[i] # 4

 while j >= 0 AND temp < arr[j] # 8
  arr[j + 1] # arr[1] --> 4
  j = -1 # 0 - 1
  arr[]
