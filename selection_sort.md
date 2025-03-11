# Selection Sort

Selection sort psuedocode

```
# Write the psuedocode 
START
SelectionSort(array, n)
    for i from 0 to n-2 do
        minIndex ← i
        for j from i+1 to n-1 do
            if array[j] < array[minIndex] then
                minIndex ← j
        end for
        if minIndex ≠ i then
            swap(array[i], array[minIndex])
    end for
END
```
