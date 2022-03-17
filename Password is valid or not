l=input()
s=[]  
for i in l:
    s.append(i)
l=0
u=0
d=0
c=0
   
for i in s:
    if i.islower():
        l+=1
        continue
    elif i.isupper():
        u+=1
        continue
    elif i.isdigit():
           d+=1
           continue
    else:
          c+=1
          continue
if l>=1 and u>=1 and d>=1 and c>=1:
    print("password is valid")
else:
    print("password is invalid")  
print("lower case=",l)
print("uppercase=",u) 
print("digits=",d)
print("symbols=",c)
