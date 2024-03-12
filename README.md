# python-dictionary-even-odd
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res=0
for i in d:
  if i%2==0:
    res=res+d[i]
print(res)    


#odd values  product

d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res=1
for i in d:
  if i%2!=0:
    res=res*d[i]
print(res)    

#if we give random no input it given sequential output

d={}
n=int(input())
for i in range(1,n+1):
  d[i]=i+1 
print(d)  

#given any input in that it takes odd values and multiply with values

d={}
n=int(input())
for i in range(1,n+1):
  if i%2!=0:
    d[i]=i*10
print(d)    
