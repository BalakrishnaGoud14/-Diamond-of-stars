# -Diamond-of-stars
# Question
# Print the following pattern for the given number of rows.
Note: N is always odd.


Pattern for N = 5



The dots represent spaces.



Input format :
N (Total no. of rows and can only be odd)
Output format :
Pattern in N lines
Constraints :
1 <= N <= 49
Sample Input 1:
5
Sample Output 1:
  *
 ***
*****
 ***
  *
Sample Input 2:
3
Sample Output 2:
  *
 ***
  *
  
 # Code in Python :
 
 ## Read input as specified in the question.
## Print output as specified in the question.
n=int(input())
i=1
n1=(n+1)/2

while(i<=n1) :
    sp=1
    while(sp<=n1-i) :
        print(" ",end='')
        sp=sp+1
    st=1
    while(st<=(2*i-1)) :
        print("*",end="")
        st=st+1
    print()
    i=i+1
    
j = (n+1)/2 -1
n2= (n+1)/2 -1
while( j<=n2 and j>0 ) :
    sp=1
    while(sp<=n2-j+1) :
        print(" ",end="")
        sp=sp+1
    st=1
    while(st<=2*j-1) :
        print("*",end="")
        st=st+1
    print()
    j=j-1
  
  
  
  
  
  
  
  
  
  
