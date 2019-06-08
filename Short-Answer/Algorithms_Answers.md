Add your answers to the Algorithms exercises here.

## Exercise I

a) O(n)
Loop iterates n times

b) O(n^3)
Inside of the first loop, it iterates n 2 times so, O(n*n*n) = O(n^3), last loop doesn't have any n input,

c) O(n)
Recursive call, everytime call itself n time.


## Exercise II

Binary search. The reason - the floors are already sorted.
    - find the middle floor
    - drop egg
    - if egg breaks:
        go down
    - else change middle floor to bottom. 

     repeat same process until _f_ is found.

 Time complexity will be : 0 (log n)