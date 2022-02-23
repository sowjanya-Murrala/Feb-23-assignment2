n=int(input("enter number:"))
l=[]
for i in range(n):
    j=int(input("enter number:"))
    l.append(j)
for i in range(n-1,-1,-1):
    print(l[i])        

output:
enter number:6
enter number:3
enter number:8
enter number:2
enter number:5
enter number:7
enter number:1
1
7
5
2
8
3
