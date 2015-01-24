#Python Notes:
##Functions:
######Print:
print ("string1",variable1,variable2,"string2")

print ("string1 {0} {1} string2".formate(variable1,variable2))

######Input
x = input()        //x will be string

x = float(input())

x = int(input("give input:"))

######Change datatype
x = int(y) or float(y) or str(y)

######precision after decimal
print("%.2f" % a)  //if a is 9 then output is 9.00. If a is 9.9765 then output is 9.98 
print("%.2f" % (a+b))
