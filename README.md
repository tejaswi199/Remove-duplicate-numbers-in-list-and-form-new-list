#Approach-1
n=int(input())
a=list(map(int,input().split()))
x=[]
for i in range(n):
  if a[i] not in x:
    x.append(a[i])
print(x)

#Approach-2
n=int(input())
a=list(map(int,input().split()))
x=[]
for i in a:
  if i not in x:
    x.append(i)
print(x)
