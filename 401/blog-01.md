# Blog-01 Sort Insert

Hi all my name is Zoe Gonzalez, and welcome to my blog today we will be going the process of a step by step evaluation from pseudo code to Javascript. 

## Declaration

### Pseudo code

    InsertionSort(int[] arr)
### JavaScript
    function insertionSort(arr, n)

First we start with an insertion Sort function declaration and then we move on. 

### Pseudo code

    FOR i = 1 to arr.length 

    int j <-- i - 1

    int temp <-- arr[i]  

### JavaScript

    let i, a, j;

    for(i = 1; i < n; i++)

The next step is to let I, the second variable and declaration of a temp j value for the nested loop. We will use this as a condition to stop the loop. 


### Pseudo code
     arr[j + 1] <-- arr[j] 

      j <-- j - 1 


### JavaScript

    while (j >= 0 && arr [j] > a)
    {
    arr[j+1] = arr[j];
    j = j - 1;
    }

The second part is a nested loop but this loop is a while loop here is where we determine the location of the sorted list. It compares the left and right values to approriately determine where to place it. 

### Pseudo code

    arr[j + 1] <-- temp

### JavaScript

    arr[j +1] = a;

here is where we reassign the sorted array and essentially create the new sorted array. 
