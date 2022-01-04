# Two-sum
#import array
def twosum(n,s):
    count=0
    for i in range(0,len(n)):
        for j in range(i+1,len(n)):
            if n[i]+n[j]==s:
                count+=1
    print( count)

n = [1,2,3,4]
s=5
print(twosum(n,s))

  
OUTPUT
 2
None
> 
