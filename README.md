# duplicate-numbers-in-a-list
l=[]
n=int(input('Enter how many numbers you want:'))
a=list(map(int,input('Enter any number:').split()))
count=0
for i in range(0,n-1):
    for j in range(i+1,n):
        if a[i]==a[j]:
            count=count+1
if count==0:
    print('No')
else:
    print('Yes')
