numbers
=======

Generates simple statistical summaries of lists of numbers. 

Requires Python 2.7+ (might work with lower versions, probably won't 
work with 3.x), IPython and numpy. 

Reads a list of real numbers from stdin, one per line. Can also read 
from a path passed as the first argument. 

Pass -H to show a basic histogram; pass -I to drop into an IPython 
shell with your numbers available as the numpy array 'num_array' and
the statistical summary available as the dict 'num_summary'. 

Example:

└─> ./numbers 
3
5
2.45
21
23
1p: 2.472000
1q: 3.000000
3q: 21.000000
99p: 22.920000
mean: 10.890000
median: 5.000000
std: 9.132820

