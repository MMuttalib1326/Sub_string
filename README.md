# Sub_string

M = input('enter the string:')
N=input('enter the pattern:')
l=[]
for i in range(len(M)):
    l.append(M[i:i+len(N)])
print(l.count(N))
