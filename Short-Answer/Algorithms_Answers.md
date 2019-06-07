Add your answers to the Algorithms exercises here.

## Exercise I

a) O(n)
Loop iterates n times

b) O(n^3)
Inside of the first loop, it iterates n 2 times so, O(n*n*n) = O(n^3), last loop doesn't have any n input,

c) O(n)
Recursive call, everytime call itself n time.


## Exercise II

I would apply merge sort. First, I will drop from half of the building height, if egg breaks, I will go down, else will move up. then I will keep continue same process until I find where egg won't break.

_n_ = stories
_n_  >= _f_ egg breaks 
_n_ < _f_ egg don't break