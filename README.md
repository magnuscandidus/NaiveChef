# NaiveChef
for i in range(int(input())):
    n,a,b=map(int,input().split())
    l=list(map(int,input().split()))
    i=l.count(a)
    j=l.count(b)
    k=(i*j)/(n*n)
