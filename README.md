 Explanation:
Outer loop (i = 1 to n-1): Iterates through each element of the array, starting from the second element.
Inner loop (while j >= 0 and arr[j] > key): This compares the current element (key) with the elements in the sorted part of the array (from arr[0] to arr[i-1]).
Shift elements: If the current element is larger than key, it shifts that element to the right to make space for the key.
Insert the key: Once the correct position is found, key is inserted into the sorted part.
