# MERGE SORT

## PROGRAM STATEMENT:

To write the mergeSort Module of Merge Sort in CPP.

## ALGORITHM:  

1.	Start the program.
2.	If l < r, perform the following steps:
a.	Calculate the middle index m = l + (r - l) / 2.
b.	Recursively call mergeSort() on the left subarray (from l to m).
c.	Recursively call mergeSort() on the right subarray (from m + 1 to r).
d.	Call the merge() function to merge the two sorted subarrays (from l to m and from m+1 to r).
3.	End the program

## PROGRAM:
```

void mergeSort(int arr[], int l, int r){ if (l<r){
int m=l+(r-l)/2; mergeSort(arr,l,m); mergeSort(arr,m+1,r); merge(arr,l,m,r);
}
}
``` 

## OUTPUT :
![image](https://github.com/user-attachments/assets/7c24ebc1-3d54-4ca3-acde-d24ef60ecd52)

## RESULT:

Thus, the C++ program To write the mergeSort Module of Merge Sort in CPP.is created successfully.


