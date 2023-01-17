# Merge Sort
## Question A 
### Sort the steps of the given sequence according to the merge algorithm



```
[16,21,11,8,12,22]  

Step 1 : [16,21,11,8,12,22]
Step 2 : [16,21,11][8,12,22] 
Step 3 : [16][21,11][8][12,22]
Step 4 : [21][11][12][22]
Step 5 : [11,21][12,22]
Step 6 : [11,16,21][8,12,22]
Step 7 : [8,11,12,16,21,22]
```
Running time complexity of this alogirtm : O(nlogn)
```
Best    case  : O(nlogn)
Avarage case  : O(nlogn)
Worst   case  : O(N²)
