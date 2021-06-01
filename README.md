# python-algorithm-3
Output by dividing by 10
import sys
n= list(sys.stdin.readline())
k=len(n)
for i in range(1, k):
    print(n[i-1],end="")
    if i%10==0:
        print("")
