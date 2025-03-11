# Insertion Sort

Insertion sort psuedocode

```
# Write the psuedocode 
START
InsertionSort(array, n)
    FOR i from 1 to n-1 do
        key ← array[i]
        j ← i - 1
        WHILE j ≥ 0 and array[j] > key do
            array[j + 1] ← array[j]
            j ← j - 1
        END WHILE
        array[j + 1] ← key
    END FOR
END
```
