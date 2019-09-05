# dictionary
with a given integral number n, write a program to generate a dictionary that contains (i,i*i) such that is an integral no. between 1 and n(both including) and then the program should print the dictionary




n=int(input("enter the list:")
d=dict()
for i in range(1, n+1):
d[i]=i*i
print(d)
