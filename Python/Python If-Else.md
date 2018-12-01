**Task:** 
Given an integer,n , perform the following conditional actions:

If n is odd, print Weird
If n is even and in the inclusive range of  to , print Not Weird
If n  is even and in the inclusive range of  to , print Weird
If n is even and greater than , print Not Weird

**Solution:**
```python
n = int(input())
if n %2 != 0 or 5<n<21:
    print ("Weird")
else:
    print ("Not Weird")
```
