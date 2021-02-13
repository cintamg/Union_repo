# Union_repo
To find no. of elements in the union of two sets.
x=int(input())
set_x=set(map(int,input().split()))
y=int(input())
set_y=set(map(int,input().split()))
print(len(set_x.union(set_y)))
