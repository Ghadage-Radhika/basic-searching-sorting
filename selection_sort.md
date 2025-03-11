# Selection Sort

Selection sort psuedocode

```
# Write the psuedocode 
START
SelectionSort(array, n)
    FOR i from 0 to n do
        minIndex = i
        FOR j from i+1 to n-1 do
            IF array[j] < array[minIndex] then
                minIndex = j
            END IF
        END FOR
        IF minIndex ≠ i then
            swap(array[i], array[minIndex])
        END IF
    END FOR
END
```
