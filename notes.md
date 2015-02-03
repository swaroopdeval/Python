#Python Notes:
##Functions:
####Print:
print ("string1",variable1,variable2,"string2") #default space b/w str1 and variable 1 & so on

print ("string1 {0} {1} string2".formate(variable1,variable2))

print ("string1 "+variable1+str(variable2) +" string2") #default space b/w str1 and variable 1 & so on #assume variable1 is string and 2 is number

####Input
x = input()        //x will be string

x = float(input())

x = int(input("give input:"))

####Change datatype
x = int(y) or float(y) or str(y)

####precision after decimal
print("%.2f" % a)  //if a is 9 then output is 9.00. If a is 9.9765 then output is 9.98

print("%.2f" % (a+b))

####Iterables:
Everything you can use "for... in..." on is an iterable: lists, strings, files... 

Means all datastructures on which we can apply for loop called iterables.

####Generators:
Generators are iterators, but you can only iterate over them once. It's because they do not store all the values in memory.
####yield vs return:
yield returns generators
