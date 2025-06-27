# python- #  1
all python  practics  question  with detail






# import time
# from operator import truediv
# from queue import PriorityQueue
# from sys import addaudithook
# from traceback import print_list
#
# from numpy.ma.core import append
# from pytz import country_names
#
# # from harry import wellcome
# import functools
# from idlelib.debugger_r import close_subprocess_debugger
# from logging import exception
# from multiprocessing.connection import address_type, reduce_pipe_connection
# from os import write
# from timeit import default_number
#
# from pandas.io.formats.format import return_docstring
# from pyexpat.errors import messages
import time
from cmath import isnan
from sys import getsizeof
from time import sleep, process_time
from unittest.mock import inplace

import numpy as np

# a=123
# a1=10
# c=True
# d=complex(8,2)
# b="harray"
# print(a+a1)
# print(b)
# print("the data type of the  a",type(a))
# print("the data type of the  b",type(b))
# print("the data type of the  c",type(c))
# print("the data type of the  d",type(d))
#
# list1=[8,7,6,[-5,-6],["apple","mango"]]
# print(list1)
# print("the type of the data type  list1 =",type(list1))
#
# taple1=(("furite","mango","banana"),("vagetable","khobi","palak"))
# print(taple1)
# print("the data type of the  taple1",type(taple1))
#
# dict1={"name":"ali","age":20,"canvote":True}
# print(dict1)
# print("the data type of the  dict=",type(dict1))
# from dataclasses import replace
#
# from pandas.tseries.holiday import next_monday
#
# #  typecasting
#
# # a="1"
# # b="2"
# # y=int(a)
# # z=int(b)
# # print(y+z)
#
#
#
# #  input
#
# # a=input("Enter your name :")
# # print(a)
# #
#
# #
# # a=input("Enter the number a:")
# # b=input("Enter the number b :")
# # print(int(a)+int(b))
#
#
# #      string
# # name="haaray"
# # print("hello,"+name)
# #
# # apple=('''he said he
# #       hi harray
# #       i am good  "want to eat the apple''')
# # # print(apple)
# # # print(name[3])
# #
# # for character in apple:
# #     print(character)
#
#
#
# # name="alishoaib,ghulamali"
# # print(name[3:10])
# # print(len(name))
# #
# # print(name[0:len(name)-3])
# # print(name[0:-3])
#
#
#    #    UPPER CASE
#
# a = "harry  aaaaaaaaaaa   harry"
# print(a.upper())
# print(a.lower())
# print(a.rstrip("a"))
# print(a.replace("harry","jhon"))
# print(a.split(" "))
#
# print(a.capitalize())
#
# b="wellcome to the console !!!"
# print(len(a))
# print(b.center(75))
# c=print(len(b.center(75)))
# print(a.count("a"))
#
# print(b.endswith("1"))

#
# a="wellcome to console"
# print(a.endswith("consol",4,18))
#
# print(a.find("is"))


# a="wellcometo theconsole9"
# print(a.isalnum())
# a="wellcometotheconsole"
# print(a.isalpha())
#
# print(a.islower())

# a="will you marri me \n  what money do you have"
# print(a.isprintable())
# print(a)

# a="   "
# print(a.isspace())


#      IF Else statement

# a=int(input("Enter your age :"))
# print("your age is :",a)
# if(a<18):
#     print("you can not drive the car")
# else:
#     print("you can drive the car")


# apple=10
# budget=200
# if(budget-apple>193):
#     print("shoaib , 1 kg apple buy and put into cart")
# elif(budget-apple>195):
#     print("ok , you can buy it")
# else:
#     print("no money to by this apple")


# number=int(input("Enter any number"))
# if(number<0):
#     print("Number is positive")
# elif(number==999):
#     print("Number is special")
# else:
#     print("number is zero")
# print("now i am happy")




#      nested  if

# num=int(input("Emter any number :"))
# if(num<0):
#     print("number is negative")
# elif(num>0):
#     if(num<10):
#         print("the number is between 1 to 10")
#     elif(num<20):
#         print("the number is between  11 to 20")
#     else:
#         print("number is greater then 20")
# else:
#     print("number is zero")
# import time
#
# timestramp = time.strftime('%H:%M:%S')
# print("current time is :",timestramp)
#
# timestramp = int(time.strftime('%H'))
# print(timestramp)
#
# timestramp = time.strftime('%M')
# print(timestramp)
#
# timestramp = time.strftime('%S')
# print(timestramp)


#   match case statement

# x=int(input("Enter  any number"))
# match x:
#     case 0:
#         print("x is zero")
#     case 4:
#         print("case is 4")
#     case _ if x!=90:
#         print(x," is not 90")
#     case _ if x!=80:
#         print(x,"is not  80")
#     case _:
#         print(x)



#     for loop
# name="shoaib ali"
# for i in name:
#     print(i)
#     if(i=="i"):
#         print("this is something is spical word")


# colors=["green","blue","organ","white","yellow"]
# for color in colors:
#     print(color)
#     for i in color:
#         print(i)

#          rang()

# for k in range(10):
#     print(k+1)
#
# for k in range(1 ,9):
#         print(k+1)



# for k in range(1,12,3):
#     print(k)



#                    while loop


# x=int(input("Enter any number :"))
# while(x<=20):
#     print(x)
#     x=x+1
# print("loop is terminates")


# i

# ========================  brack statement=============
# =

# for i in range(15):
#     if(i==10):
#         print("skip the line 10")
#         continue
#     print("5 *",i,"=",5*i)
# print("complete the table 5 ")

#
# for i in range(1, 100, 1):
#     print(i,end="  " )
#     if i == 50:
#         break
#     else:
#         print("hello shoaib")
# print("thank you")


# i=0
# while True:
#     print(i)
#     i=i+1
#     if i==100:
#         print("while is end")
#         break



# def calculatorgmean(a,b):
#     mean=(a*b)/(a+b)
#     print("that find gmean :",mean)
#
# def greater(a,b):
#     if (a > b):
#         print(a, "a is greator")
#     else:
#         print(b, "b is greator")

#
# a=int(input("Enter any number :"))
# b=int(input("Enter any number :"))
# greater(a,b)
# calculatorgmean(a,b)

# c=15
# d=20
# greater(a,b)
# calculatorgmean(c,d)




# ========================argument==================

# def name(fname, mname, lname):
#     print("hello", fname, mname, lname)
#
# name( lname="bhatti",fname="shoaib",mname="ali")


# ======================  lenght variable argument===========================

# def average(*number):
#     sum = 0
#
#     for i in number:
#         sum=sum+i
#     print("the averages is : ",sum/len(number))
# average(5,5,5,25)



# ===================list =========================

# list2=["asad","shoaib","zain","ali","shani"]
# print(list2)
# print(list1)
# print(type(list1))
# print(list2[4])
# print(list1[5])
# print(list2[-5])

# list1=[3,4,6,8,9,7,True,"harry",10,11,17,20]
# if 7 in list1:
#     print("yes")
# else:
#     print("No")


# list1=[3,4,6,8,9,7,True,"harry",10,11,17,20]
#
# print(list1)
# print(list1[1:11:3])


# ====================append list================

# list1=[19,18,15,11,1,2,3,4,5,6,1,1]
# print(list1)
# list1.append(7)
# print(list1)
# list1.sort(reverse=True)
# list1.reverse()
# print(list1.index(1))
# print(list1)
# print(list1.count(1))
# list1=[19,18,15,11,1,2,3,4,5,6,1,1]
# m=list1.copy()
# m[0]=0
# print(list1)
# print(m)


#  =======================tuple  =======================
# tup1=(1,2,2,3,4,5,6,7,"greeen","yellow")
# print(tup1)
# print(type(tup1))
# print(tup1[8])
# for i in tup1:
#     print(i, end="  ")

# tup1=(1,2,2,3,4,5,6,7,"greeen","yellow")
# print(tup1[-1])
# print(tup1[len(tup1)-1])
# if 7 in tup1:
#     print("yes")
# else:
#print("no")


# tup1=(1,2,2,3,4,5,6,7,"greeen","yellow")

# tup2=tup1[1:7]
# print(tup2)

# tuple1=("ali","shoaib","shani","zain","asad","abdullah")
# tuple2=list(tuple1)
# tuple2.append("zubair")
# print(tuple2)
# tuple2.pop(3)
# print(tuple2)
# tuple2[3]="abu haraar"
# print(tuple2)
# tuple1=tuple(tuple2)
# print(tuple1   )



# ==================tuple  indexing ======================

# tuple1=(1,2,3,4,5,6,7,8,9,91,6,7,9)
# print(tuple1.index(9,0,11))


#    ==================  exercise    1  =======================
#
# t=time.strftime('%H:%M:%S')
# print(t)
# if(3<12):
#     print("good morning")
# elif(13<17):
#     print("good aftarnoon")
# else:
#     print("goodnight")

#   =================  formate string  =======================

# leter="my name is  {1} and his country  {0}"
# name="shoaib"
# country="pakistan"
# print(leter.format(country,name))

# =====================f_ string================================


# name="shoaib"
# country="pakistan"
#print(f"my name is {name} and his country   {country}")



# =================  doc string ======================

# def square(n):
#     print(n)
#     '''Take the number n  and return the squre  number'''
#     print(n*n)
#
# print(square.__doc__)
# square(5)


# ============================   recursive  function  =========================

# def factorial(n):
#     if(n==0 or n==1):
#         return 1
#     else:
#         return n*factorial(n-1)
# print(factorial(4))


# ==================   quiz   ==================
#    =======================create the formula of fabonacci ==============


# def fabonacci(n):
#     if n==0:
#         return 0
#     elif n==1:
#         return 1
#     else:
#         return fabonacci(n-1)+fabonacci(n-2)
# # for i in range(6):
# #     print(fabonacci(i))
# print(fabonacci(7))



# def fabonacci(n):
#     if n == 0:
#         return 0
#     elif n == 1:
#         return 1
#     else:
#         return fabonacci(n-1) + fabonacci(n-2)  # Corrected formula

# Printing the first 6 Fibonacci numbers
#  # Use range instead of looping over 'n'
#     print(fabonacci(i))

# Printing the 5th Fibonacci number separately
# print(fabonacci(5))  # Output should be 5


# ===================   set   =========================

# seet={1,2,2,3,4,5,6,6}
#
# print(seet)
# print(type(seet))


#  =====================union   and  updation ======================

# set1={1,2,3,4,5}
# set2={3,4,5,6,7,8,9,10}
# print(set1.union(set2))

# print(set1,set2)
# set1.update(set2)
# print(set1)


# =====================   intersectio and  updation  ==========================

# cities1={"mandi","baseerpur","depalpur","okara"}
# cities2={"thiekmor","tilwindi","kasoor","mindi","orkara"}
# # cities3=cities1.symmetric_difference(cities2)
# cities3=cities1.difference(cities2)
# print(cities3)


# ==================  isdisjion()  ======================

# cities1={"mandi","baseerpur","depalpur","okara"}
# cities2={"thiekmor","tilwindi","kasoor","mandi","orkara"}
#
# cities3=cities1.isdisjoint(cities2)
# print(cities3)


# ====================  issuperset()  =====================


# set1={1,2,3,4,5,6,7,8}
# set2={2,4,6,8}
# set3=set1.issuperset(set2)
# print(set3)

# =================  add()  =====================

# set1={1,2,3,4,5,6,7,8}
# set1.add(999)
# set1.discard(3)
# print(set1)

# =======================pop ==========================

# name={"ali","shoaib","bhatti","hamza", "shani"}
# item=name.pop()
# print(item)

#   =========================  dictionery  ===================

# ep1={233:70,178:75,348:89}
# ep2={567:78,678:99,143:95}
# ep1.update(ep2)
# ep1.clear()
# print(ep1)


# num1=(1,2,3,4,5,5)
# for i in num1:
#     print(i)
#     if i==2:
#         print("condition is break")
#         break
# else:
#     print("loop is end  ")


#   ====================   error handling  ===============================
#
# a=input("Enter any number :")
# print(f"print the table of the {a}")
#
# try:
#     for i in range(1,10):
#         print(f"{int(a)} * {i} ={int(a)*i}")
#
# except:
#     print("soory i am wronted input")
#
# print("hello every one  ")
# print("hello shoaib")



#  =======================  finally   :==========================

# def function1():
#     try:
#         l = [1, 2, 3, 4, 5, 6, 7]
#         i = int(input("Enter any values  :"))
#         print(l[i])
#         return 1
#     except:
#         print("print some error are  occour")
#         return 00
#     finally:
#         print("all the values are excecuted")
#
# x=print(function1())
# print(x)


#   ======================= Raise custom error ======================
#
# a=int(input("Enter any values   betweeen 5 and 9 :  "))
# if a<5 or a>9:
#     raise errorvalue("value shold be betwwen 5 and 9 ")
#


# a=input("Enter the values of quites :")
# if a== quites:
#     raise errorvalue("you put the true  input")
#


#   ==========================   exercise   =3  ====================
# questions=[
# ["which language use to create the faceboob","python","javascript","php","french","None",4],
# ["which language use to create the faceboob","python","javascript","php","french","None",4],
# ["which language use to create the faceboob","python","javascript","php","french","None",4],
# ]
# for i in range(len(questions)):
#    level=[1000,2000,3000,5000,10000,20000,40000,80000,160000,320000]
#    print(level[i])
# money=0
# i=0
# question=questions[i]
# print(f"questions for RS.{level[i]}")
# print(f"a.{question[1]}  b.{question[2]}")
# print(f"c.{question[3]}     d.{question[4]}")
#
# reply=int(input("Enter any value between 1-4  :"))
# if(reply==question[-1]):
#     print(f"correct answer you have won RS:{level[i]}")
#     if i==4:
#         money=10000
#     elif i==9:
#         money==320000
#     elif i==14:
#         money=10000000
#
# else:
#     print("wrong answer !")
#


#    =========================  short hand if else  ===================




# a = 20
# b = 300
# print("a") if a > b else print("=") if a == b else print("b")

# age=18
# print("your drive for the car") if age>=18 else print("can not drive")


#   ====================  enumerate fuction   ===========================

#    ============  normal     ================

# marks = [23, 45, 67, 89, 9, 12, 45, 60, 99]
# index=0
# for mark in marks:
#     print("Print all the marks:", mark)
#     if index==3:
#         print("This ia special number")
#     index += 1

#   ===============   Enumeriate   function  ====================
#
# marks = [23, 45, 67, 89, 9, 12, 45, 60, 99]
#
# for index,mark in enumerate(marks):
#     print(mark)
#     if index == 3:
#         print("this is special number")




# furits=["apple","orang","mango","banana"]
#
# for index,furit in enumerate(furits, start=1 ):
#     print(index,furit)



# from  math import sqrt, pi

# from   math import pi ,sqrt as s
#
# result=s(16)*pi
# print(result)


#   ===================     dir function  ======================
# from  harry import wellcome,harry
# import  math
# print(dir(math))
# print(harry)

#     ==================    data transfer from one modules to another modules  ============

# import harry
# harry.wellcome()



#     ==================     os  modules ==========================

# import os
# if(not os.path.exists("asad")):


# for i in range(0,100):
#     os.rename(f"data/totorial{i + 1}", f"data/totorial/day{i + 1}")
#         # os.mkdir(f"asad {i+1}")  that create the floder


# import os
# if(not os.path.exists("dataa")):
#     os.mkdir("dataa")
#
# for i in range(0,100):
#     os.rename(f"dataa/day{i+1}",f"dataa/totrial{i+1}")



#    ================== excrise =  4    ===================

# st=input("Enter any string  =")
# word=st.split(" ")
# coding=True
# if(coding):
#     nwords=[]
#     for words in word:
#         if(len(words)>=3):
#             r1="deg"
#             r2="xyz"
#             stnew=r1+words[1:]+words[0]+r2
#
#             nwords.append(stnew)
#
#         else:
#             nwords.append(words[::-1])
#     print(" ".join(stnew))
#
# else:
#
#         nwords = []
#         for words in word:
#             if (len(words) >= 3):
#                 stnew=words[3:-3]
#
#                 stnew =  stnew[-1:] + stnew[-1]
#
#                 nwords.append(stnew)
#
#             else:
#                 nwords.append(words[::-1])
#         print(" ".join(stnew))


#
# st = input("Enter any string  = ")
# word = st.split(" ")
# coding = False
#
# if coding:
#     nwords = []
#     for words in word:
#         if len(words) >= 3:
#             r1 = "deg"
#             r2 = "xyz"
#             stnew = r1 + words[1:] + words[0] + r2
#             nwords.append(stnew)
#         else:
#             nwords.append(words[::-1])
#     print(" ".join(nwords))  # Corrected print statement
#
# else:
#     nwords = []
#     for words in word:
#         if len(words) >= 6:  # Ensure word is long enough for slicing
#             stnew = words[3:-3]  # Remove first 3 and last 3 characters
#
#             if len(stnew) > 0:  # Check if there are characters left after slicing
#                 stnew = stnew[-1] + stnew[-1]  # Repeat the last character
#             else:
#                 stnew = words  # If slicing removes everything, keep the original word
#
#             nwords.append(stnew)
#         else:
#             nwords.append(words[::-1])  # Reverse short words
#
#     print(" ".join(nwords))  # Corrected print statement






#      ================                local and global variable==================


# x=10
# def my_function():
#     global y
#     y=10
#     print(y)
#     print("x is use in functon =",x)
#
# my_function()
# print("the values of y",y)



# =============    opening   files  =====================


# f=open('myfile.txt','a')
# text=f.write("heloo shoaib")
# print(text)
# f.close()

#
# with open('textfile3','a') as f:
#     f.write("hello shoaib")


# ===               readline method  ===============

# f=open('textfile3','r')
# while True:
#     line=f.readline()
#
#     if not line:
#
#         print("shoaib")
#         break
#     print(line)


# f=open('textfile3','r')
# print(f)
# text=f.read()
# print(text)

# i=0
# while True:
#     i=i+1
#     line=f.readline()
#     if not line:
#         break
#     m1=int( line.split(",")[0])
#     m2=int( line.split(",")[1])
#     m3=int( line.split(",")[2])
#
#     print(f"marks of math {i}  and {m1*2}")
#
#     print(f"marks of english {i}  and {m2*2}")
#
#     print(f"marks of urdu {i}  and {m3*2}")
#
#     print(line)

  #   =====================write data in to the files=====================

# f=open('textfile3','w')
# line=['line1\n','line2\n','line\n']
# f.writelines(line)
# f.close()


#  ======  seekk()  and tell()  method   =================
# with open('textfile3', 'r') as f:
#     f.seek(10)  # Move cursor to the 10th byte
#     print(f.tell())
#     text = f.read(5)  # Read 5 characters
# print(text)


# with open('textfile3', 'w') as f:
#     f.write('hello   shoaib')
#     f.truncate(5)




#     ==================   lambda function  ====================


# def apply(fx,value):
#     return 10+fx(value)
#
# double=lambda x:x*2
# print(double(5))
#
#
#
#
# print(apply(double,2))



#    ================   map  method()=====
# print(cube(2))
# l=[1,2,3,4,5,6]
# newlist=list(map(cube,l))
# print(newlist)
# def cube(x):
#     return x*x*x
# newlist=[]
#
#
# l=[1,2,3,4,5]
# for item in l:
#
# print(newlist)


#    ===============   fillter   method =====================
# def fillter(a):
#     return a>=4
# newlist=[]
# l=[1,2,3,4,5,6]

#   ================================    sampl   method
  # for i in l:
#     if fillter(i):  # If the condition is True (a >= 4)
#         newlist.append(i)
# print(newlist)


#    ===================   fillter mthod  ==================

# def fillter_fuc(a):
#     return a>=4

# l=[1,2,3,4,5,6]
#
# result=filter(lambda a:a>=4 ,l)
# print(list(result))

#   =================   reducd mthod===================

# from functools import reduce
#
#
# numbers=[1,2,3,4,5]
# def mysum(x,y):
#     return x+y
# sum=reduce(mysum,numbers)
# print(sum)



# a="4"
# b=4
# print(a is b)
# print(a==b)


#   =========================   class  and  object  =======================
#
# class person:
#     name="shoaib"
#     lastname="ali"
#     occopation="data scientist"
#     network=20000
#     def info(itself):
#         print(f"{itself.name} is a {itself.occopation}")
#
# a=person()
#
# a.name="asad"
# print(a.name,a.lastname,a.network,a.occopation)
# a.info()
#



#        =====================         class    ================


# class ATM:
#     def __init__(self):
#         self.pin = ''
#         self.balance = 0
#         # print("ma too execute ho gaya")
#         self.menu()
#
#     def menu(self):  # Added 'self' parameter
#         user_input = input("""
#                How can I help you?
#                1. Press 1 to create a PIN
#                2. Press 2 to change the PIN
#                3. Press 3 to check the balance
#                4. Press 4 to withdraw balance
#                5. Press 5 to exit
#                """)
#
#     if user_input=='1':
#         self.creat_pin()
#
#     elif user_input=='2':
#         pass
#
#     elif user_input == "3":
#         pass
#
#     elif user_input=='4':
#         pass
#
#     else:
#         exit()
#
#     def creat_pin(self):
#         user_pin=input("create the pin ")
#         self.pin=user_pin
#
#         user_balance = input(input("Enter any balance from user"))
#         self.balance =user_balance
#
#         print("pin create sucssfully ")
#
#
#
# # Creating an object of ATM class to run the constructor
# atm = ATM()



#
# class ATM:
#     def __init__(self):
#         print(id(self))
#         self.pin = ''
#         self.balance = 0
#         self.menu()  # Calls the menu when an object is created
#
#     def menu(self):
#         user_input = input("""
#                How can I help you?
#                1. Press 1 to create a PIN
#                2. Press 2 to change the PIN
#                3. Press 3 to check the balance
#                4. Press 4 to withdraw balance
#                5. Press 5 to exit
#                """)
#
#         if user_input == "1":
#             self.create_pin()
#         elif user_input == "2":
#             self.change_pin()
#         elif user_input == "3":
#             self.check_balance()
#         elif user_input == "4":
#             self.with_draw()
#         elif user_input == "5":
#             pass
#         else:
#            exit()
#
#     def create_pin(self):
#         user_pin=input("Enter any pin code :")
#         self.pin=user_pin
#
#
#         user_balances=input("Enter any balances  :")
#         self.balance=user_balances
#         self.menu()
#         print("You can create sucessfully pin cod")
#
#
#     def change_pin(self):
#         old_pin=input("Enter old pin :")
#
#         if old_pin==self.pin:
#             new_pin=input("Enter new pin  :")
#             self.pin=new_pin
#             print("change the print sucessfully")
#             self.menu()
#
#         else:
#             print("Can not change  the pin code")
#             self.menu()



#
#     def check_balance(self):
#         user_pin=input("Enter the  pin :")
#         if user_pin==self.pin:
#             print(f"check the balance  :{self.balance}")
#             self.menu()
#         else:
#             print("chal nekal yaha sy")
#         self.menu()
#
#     def with_draw(self):
#         user_pin=input("Enter the pin code :")
#         if user_pin==self.pin:
#             amount=input("Enter the amount :")
#             if amount<=self.balance:
#                 self.balance=self.balance-amount
#                 print(" withdraw sucessfully :" ,self.balance )
#                 self.menu()
#             else:
#                 print("abi grib hoo ma")
#         else:
#             print("can not withdraw balances")
#             self.menu()
#
#
# # Creating an object of ATM class
# atm = ATM()
# id(atm)
#
#
#
#
#



#    =====================parameterized constructor     ================

# class Fruction:
#     def __init__(self, x, y):
#         self.num = x
#         self.denum = y
#
#
#     def __str__(self):
#         return 'That show the value in fraction :   {}/{}'.format(self.num,self.denum)
#
#
#     def __add__(self, other):
#         new_num=self.num*other.denum + other.num*self.denum
#         new_denum=self.denum*other.denum
#         return 'add two value of the  fraction :   {}/{}'.format(new_num, new_denum)
#
#     def __sub__(self, other):
#         new_num = self.num * other.denum - other.num * self.denum
#         new_denum = self.denum * other.denum
#
#         return 'substraction two value of the  fraction :   {}/{}'.format(new_num, new_denum)
#
#
#
#     def __mul__(self,other):
#         new_num=self.num*other.num
#         new_denum=self.denum*other.denum
#         return 'multiplication two value of the  fraction :   {}/{}'.format(new_num, new_denum)
#
#     def __truediv__(self, other):
#         new_num = self.num * other.denum
#         new_denum = self.denum * other.num
#         return 'multiplication two value of the  fraction :   {}/{}'.format(new_num, new_denum)
#
#
#     def convert_to_decimal(self):
#         return self.num/self.denum
#
#
#
#
#
#
# fr1=Fruction(4,6)
# print(fr1)
#
# fr2=Fruction(3,5)
# print(fr2)
#
# r=fr1-fr2
# print(r)
#
#
# r=fr1*fr2
# print(r)
#
# r=fr1/fr2
# print(r)
#
#


#    ===============    create a program of geomatric  of two dimenstion (x,y) x representation of axis
#    y representation of y axis    =============


#
#
#
#
# class Point:
#     def __init__(self, x, y):
#         self.x_cod = x
#         self.y_cod = y
#
#     def __str__(self):
#         return '<{},{}>'.format(self.x_cod, self.y_cod)
#
#     def euclidean_distance(self, other):
#         return ((self.x_cod - other.x_cod) ** 2 + (self.y_cod - other.y_cod) ** 2) ** 0.5
#
#     def distances_from_origin(self):
#         return (self.x_cod ** 2 + self.y_cod ** 2) ** 0.5
#
#
# class Line:
#     def __init__(self, a, b, c):
#         self.a = a
#         self.b = b
#         self.c = c
#
#     def __str__(self):
#         return '{}x + {}y + {} = 0'.format(self.a, self.b, self.c)
#
#     def line_of_point(self, point):
#         if self.a * point.x_cod + self.b * point.y_cod + self.c == 0:
#             print("The point lies on the line")
#         else:
#             print("The point does not lie on the line")
#
#     def shortest_distances(self, point):
#         return abs(self.a * point.x_cod + self.b * point.y_cod + self.c) / (self.a ** 2 + self.b ** 2) ** 0.5
#
#
# # Creating Point instances
# p1 = Point(1,1)
# p2 = Point(2, 2)
#
# print(p1)
# print(p2)
# print("Euclidean Distance:", p1.euclidean_distance(p1))
#
# # Distance from origin
# print("The distance from point p1 to origin:", p1.distances_from_origin())
# print("The distance from point p2 to origin:", p2.distances_from_origin())
#
# # Creating Line instance
# l = Line(1, 1, -2)

# print(l)
# l.line_of_point(p1)
#
# # Finding the shortest distance
# print("Shortest distance from p1 to line:", l.shortest_distances(p1))
#




#  ==================  agr app pakistan sy haa app ko boly ga  well come to Geee ayh noo agr app doseery country sy haa app
#      ==========================                   wellcome  to pakistan


# class Person:
#     def __init__(self,User_name=input("Enter any User_Name :"),User_country=input("Enter any country Name :")):
#         self.Name=User_name
#         self.Country=User_country
#
#     def greeting(self):
#          if self.Country=="pakistan":
#              print(self.Name,"WellCome to Gee ayh noo  in ",self.Country)
#          else:
#              print("WellCome to Pakistan",self.Name)
#
# p=Person()
# p.greeting()
# print(p.Name)

# p.gender='male'
# print(p.gender)


#   ====================   references  variable    =================================

# class Person:
#     def __init__(self):
#         self.name="shoaib"
#         self.gender="male"
#


#
#
#
# p=Person()
# print(p.name)
#
# q=p
#
# print(q.name)
#
#
# q.name="ali"
# print(q.name)
# print(p.name)
#
#
#




#   =================  pass by references   ===================

#
# class Person:
#     def __init__(self,Name ,Gender):
#         self.User_Name=Name
#         self.User_Gender=Gender
#
#
# def greeting(Person):
#     print(id(Person))
#     # print(f"My Name is  : {Person.User_Name} and is gender is  :{Person.User_Gender}")
#     Person.name="ali"
#     print(Person.name)
#
#
# p=Person('shoaib','male')
# print(id(p))
# print(greeting(p))
#
# print(p.name)





# ===================    instance variable  =================


#
# class Person:
#     def __init__(self,Name ):
#         self.User_Name=Name
#         # self.User_Gender=Gender
#
#
#
# p1=Person('shoaib')
# print(p1)
# print(p1.User_Name)
# p2=Person('bhatti')
# print(p2.User_Name)




#   =====================   encapsulation ==========================


# ==========  inthis code we make  a private variable like a balanes      and the consept of
#    getter()  and setter()    method    =================
#
# class ATM:
#     def __init__(self):
#         print(id(self))
#         self.pin = ''
#         self.__balance = 0
#         # self.menu()  # Calls the menu when an object is created
#
#
#     def get_balance(self):
#         return self.__balance
#
#
#     def set_balance(self,new_value):
#         if type(new_value)== int:
#             self.__balance=new_value
#         else:
#             print("batah app ko bohat marayga")
#
#     def menu(self):
#         user_input = input("""
#                How can I help you?
#                1. Press 1 to create a PIN
#                2. Press 2 to change the PIN
#                3. Press 3 to check the balance
#                4. Press 4 to withdraw balance
#                5. Press 5 to exit
#                """)
#
#         if user_input == "1":
#             self.create_pin()
#         elif user_input == "2":
#             self.change_pin()
#         elif user_input == "3":
#             self.check_balance()
#         elif user_input == "4":
#             self.with_draw()
#         elif user_input == "5":
#             pass
#         else:
#            exit()
#
#     def create_pin(self):
#         user_pin=input("Enter any pin code :")
#         self.pin=user_pin
#
#
#         user_balances=input("Enter any balances  :")
#         self.__balance=user_balances
#         self.menu()
#         print("You can create sucessfully pin cod")
#
#
#     def change_pin(self):
#         old_pin=input("Enter old pin :")
#
#         if old_pin==self.pin:
#             new_pin=input("Enter new pin  :")
#             self.pin=new_pin
#             print("change the print sucessfully")
#             self.menu()
#
#         else:
#             print("Can not change  the pin code")
#             self.menu()
#
#
#
#
#     def check_balance(self):
#         user_pin=input("Enter the  pin :")
#         if user_pin==self.pin:
#             print(f"check the balance  :{self.__balance}")
#             self.menu()
#         else:
#             print("chal nekal yaha sy")
#         self.menu()
#
#     def with_draw(self):
#         user_pin=input("Enter the pin code :")
#         if user_pin==self.pin:
#             amount=input("Enter the amount :")
#             if amount<=self.__balance:
#                 self.__balance=self.balance-amount
#                 print(" withdraw sucessfully :" ,self.__balance )
#                 self.menu()
#             else:
#                 print("abi grib hoo ma")
#         else:
#             print("can not withdraw balances")
#             self.menu()
#

# Creating an object of ATM class
# atm = ATM()
# atm.balance="hahaha"
# print(atm.balance)




# id(atm)
# print(atm.change_pin())

# p=atm._ATM__balance="hahaha"
# print("that show the balances  :",p)

# atm = ATM()
#
# # Testing balance retrieval
# p1 = atm.get_balance()
# print("Initial Balance:", p1)
#
# # Updating balance and checking again
# atm.set_balance('hahahaha')
# p2 = atm.get_balance()
# print("Updated Balance:", p2)
#









#
#
# class ATM:
#     def __init__(self):
#         print(id(self))
#         self.pin = ''
#         self.__balance = 0  # Private attribute for balance
#         # self.menu()  # Calls the menu when an object is created
#
#     def get_balance(self):
#         return self.__balance  # Corrected the attribute reference
#
#     def set_balance(self, new_value):
#         self.__balance = new_value  # Corrected the method logic
#
#     def menu(self):
#         user_input = input("""
#                How can I help you?
#                1. Press 1 to create a PIN
#                2. Press 2 to change the PIN
#                3. Press 3 to check the balance
#                4. Press 4 to withdraw balance
#                5. Press 5 to exit
#                """)
#
#         if user_input == "1":
#             self.create_pin()
#         elif user_input == "2":
#             self.change_pin()
#         elif user_input == "3":
#             self.check_balance()
#         elif user_input == "4":
#             self.with_draw()
#         elif user_input == "5":
#             exit()
#         else:
#             print("Invalid option, please try again.")
#             self.menu()
#
#     def create_pin(self):
#         user_pin = input("Enter a new PIN: ")
#         self.pin = user_pin
#
#         user_balance = input("Enter your initial balance: ")
#         if user_balance.isdigit():  # Ensuring balance is numeric
#             self.__balance = int(user_balance)
#             print("You have successfully created a PIN and set the balance.")
#         else:
#             print("Invalid balance input. Setting balance to 0.")
#
#         self.menu()
#
#     def change_pin(self):
#         old_pin = input("Enter old PIN: ")
#
#         if old_pin == self.pin:
#             new_pin = input("Enter new PIN: ")
#             self.pin = new_pin
#             print("PIN changed successfully.")
#         else:
#             print("Incorrect old PIN. Cannot change PIN.")
#
#         self.menu()
#
#     def check_balance(self):
#         user_pin = input("Enter your PIN: ")
#         if user_pin == self.pin:
#             print(f"Your current balance: {self.__balance}")
#         else:
#             print("Incorrect PIN. Access denied.")
#
#         self.menu()
#
#     def with_draw(self):
#         user_pin = input("Enter your PIN: ")
#         if user_pin == self.pin:
#             amount = input("Enter the amount to withdraw: ")
#             if amount.isdigit():
#                 amount = int(amount)
#                 if amount <= self.__balance:
#                     self.__balance -= amount
#                     print(f"Withdrawal successful. New balance: {self.__balance}")
#                 else:
#                     print("Insufficient funds.")
#             else:
#                 print("Invalid amount. Please enter a number.")
#         else:
#             print("Incorrect PIN. Withdrawal denied.")
#
#         self.menu()
#
#
# # Creating an object of ATM class
# atm = ATM()
#
# # Testing balance retrieval
# p1 = atm.get_balance()
# print("Balance:", p1)
#
# # Updating balance and checking again
# atm.set_balance(100)
# p2 = atm.get_balance()
# print("Updated Balance:", p2)


# =====================  instances  ========================


#
#
# class Person:
#     def __init__(self):
#         self.__User_Name ="shoaib"
#
#
# p1 = Person()
#
#
# p1.__User_Name="asad"
# print(p1.__User_Name)
#
#




#===================  collection of object    =======================


#   =================    throught list []

# class Person:
#     def __init__(self,name,gender):
#         self.name=name
#         self.gender=gender
#
#
# p1=Person('shoaib','male')
# p2=Person('asad','male')
# p3=Person('abdullah','male')
#
# l=[p1,p2,p3]
# print(l)
#
# for i in l:
#     print(i.name,i.gender)


#=====================  throught  dictioery  ===============================


#
# class Person:
#     def __init__(self,name,gender):
#         self.name=name
#         self.gender=gender
#
#
# p1=Person('shoaib','male')
# p2=Person('asad','male')
# p3=Person('abdullah','male')
#
# d={'p1':p1,'p2':p2,'p3':p3}
# for i in d:
#     print(d[i].name,d[i].gender)
#



#
# class ATM:
#     count=1
#
#
#     def __init__(self):
#         print(id(self))
#         self.pin = ''
#         self.__balance = 0
#         self.cid=ATM.count
#         ATM.count=ATM.count+1
#
#         # self.menu()  # Calls the menu when an object is created
#
#
#     def get_balance(self):
#         return self.__balance
#
#
#     def set_balance(self,new_value):
#         if type(new_value)== int:
#             self.__balance=new_value
#         else:
#             print("batah app ko bohat marayga")
#
#     def menu(self):
#         user_input = input("""
#                How can I help you?
#                1. Press 1 to create a PIN
#                2. Press 2 to change the PIN
#                3. Press 3 to check the balance
#                4. Press 4 to withdraw balance
#                5. Press 5 to exit
#                """)
#
#         if user_input == "1":
#             self.create_pin()
#         elif user_input == "2":
#             self.change_pin()
#         elif user_input == "3":
#             self.check_balance()
#         elif user_input == "4":
#             self.with_draw()
#         elif user_input == "5":
#             pass
#         else:
#            exit()
#
#     def create_pin(self):
#         user_pin=input("Enter any pin code :")
#         self.pin=user_pin
#
#
#         user_balances=input("Enter any balances  :")
#         self.__balance=user_balances
#         self.menu()
#         print("You can create sucessfully pin cod")
#
#
#     def change_pin(self):
#         old_pin=input("Enter old pin :")
#
#         if old_pin==self.pin:
#             new_pin=input("Enter new pin  :")
#             self.pin=new_pin
#             print("change the print sucessfully")
#             self.menu()
#
#         else:
#             print("Can not change  the pin code")
#             self.menu()
#
#
#
#
#     def check_balance(self):
#         user_pin=input("Enter the  pin :")
#         if user_pin==self.pin:
#             print(f"check the balance  :{self.__balance}")
#             self.menu()
#         else:
#             print("chal nekal yaha sy")
#         self.menu()
#
#     def with_draw(self):
#         user_pin=input("Enter the pin code :")
#         if user_pin==self.pin:
#             amount=input("Enter the amount :")
#             if amount<=self.__balance:
#                 self.__balance=self.balance-amount
#                 print(" withdraw sucessfully :" ,self.__balance )
#                 self.menu()
#             else:
#                 print("abi grib hoo ma")
#         else:
#             print("can not withdraw balances")
#             self.menu()
#
# c1=ATM()
# print(c1)
# print(c1.cid)
# print(c1.cid)
# c2=ATM()
# print(c2)
# print(c2.cid)
# c3=ATM()
# print(c3)
# print(c3.cid)
#
#
#




#   =====================  aggregation    =========================
# class Customer:
#     def __init__(self,name,gender,address):
#         self.name = name
#         self.gender = gender
#         self.address = address
#
#     def print_address(self):
#         print(self.address.get_city(), self.address.pin, self.address.state)
#
#     def edit_profile(self, new_name, new_city, new_pin, new_state):
#         self.name = new_name
#         self.address.edit_address(new_city, new_pin, new_state)
#         print(f"Profile updated: {self.name}, Address: {self.address.get_city()}, {self.address.pin}, {self.address.state}")
#
# class Address:
#     def __init__(self, city, pin, state):
#         self.__city = city
#         self.pin = pin
#         self.state = state
#
#     def get_city(self):
#         return self.__city
#
#     def edit_address(self, new_city, new_pin, new_state):
#         self.__city = new_city
#         self.pin = new_pin
#         self.state = new_state
#
# # Create an address object
# Add1 = Address('mandi ahmad abad', '0786', 'sahiwal')
#
# # Create a customer object
# Cust1 = Customer('shoaib', 'male', Add1)
#
# # Print the initial address of the customer
# Cust1.print_address()
#
# # Edit the customer's profile
# Cust1.edit_profile('asad', 'baseerpur', 9899, 'okara')
#
#
#



# ===============================     inheritances  ==============================
#
# class User:
#     def __init__(self):
#         self.name='shoaib Bhatti'
#
#     def login(self):
#         print("login to this pages")
#
#
# class Student(User):
#
#     def enrollment(self):
#         print("enroll to your courses")
#
# s=Student()
# print(s.name)
# print(s.login())
# print(s.enrollment())
#



#       =================  other example   ======================

#
# class phone:
#     def __init__(self,price,brand,cambra):
#         print("inside the constructor")
#         self.price=price
#         self.brand=brand
#         self.cambra=cambra
#
#
#
#     def buy(self):
#         print("buy the phone")
#
#
# class smartphone(phone):
#     def __init__(self,os,ram):
#         self.os=os
#         self.ram=ram
#         print("inside the child constructor")
#
#     def smartphonee(self):
#         print("buy the smart hone")
#
#
# S=smartphone('andriod','8gp')
# print(S)
# print(S.os)
# print(S.ram
#       )



# =+++++=======================   more agiain example ===============================


# class Parent:
#     def __init__(self,num):
#         self.__num=num
#
#
#     def get_num(self):
#         return self.__num
#
# class chlild(Parent):
#     def son(self):
#         print("This is child class")
#
# C=chlild(100)
# print(C.get_num())
# print(C.son())



# =========================  example ==================


# class A:
#     def __init__(self):
#         self.var1=1000
#
#     def display1(self,var1):
#         print("Class A :",self.var1)
#
# class B(A):
#     def display2(self,var1):
#         print("Class B ",self.var1)
#
# child=B()
# print(child.display1(200))



#   ==================    super keyword  in heritance     ==================



#
#
# class phone:
#     def __init__(self,price,brand,cambra):
#         print("inside the constructor")
#         self.price=price
#         self.brand=brand
#         self.cambra=cambra
#
#
#
#     def buy(self):
#         print("buy the phone")
#
#
# class smartphone(phone):
#
#
#     def buy(self):
#         super().buy()
#         print("buy the smart hone")
#
#
#
# S=smartphone(20000,'iphone','100px')
# print(S.buy())



# ====================  more example of   super keyword=============

#
# class phone:
#     def __init__(self,price,brand,cambra):
#         print("inside the parent  constructor")
#         self.price=price
#         self.brand=brand
#         self.cambra=cambra
#
#
#
#     def buy(self):
#         print("buy the phone")
#
#
# class smartphone(phone):
#     def __init__(self,price,brand,cambra,os,ram):
#         print("inside the child constructor")
#         super().__init__(price,brand,cambra)
#         self.os=os
#         self.ram=ram
#
#         print("inside the child constructor")
#
#     def smartphonee(self):
#         print("buy the smart hone")
#
#
# S=smartphone(20000,'samsung','20px','andriod','8gp')
# print(S)
# print(S.os)
# print(S.ram)



# ============================ pracitices quetion===========
# class A:
#     def __init__(self, num):
#         self.__num = num  # use self.__num to store the value
#
#     def get_num(self):
#         return self.__num  # access the instance variable using self
#
# class B(A):
#     def __init__(self, num, val):
#         super().__init__(num)
#         self.__val = val  # use self.__val to store the value
#
#     def get_val(self):
#         return self.__val  # access the instance variable using self
#
# child = B(100, 200)
# print(child.get_num())  # no need to pass a parameter here
# print(child.get_val())


# ============================ multilevel inheritances      =================

# class prodect:
#     def review(self):
#         print("prodect customer review")
#
#
# class phone(prodect):
#     def __init__(self,price,brand,camera):
#         self.price=price
#         self.brand=brand
#         self.camera=camera
#
#     def buy(self):
#         print("buy the phone")
#
#
# class smartphone(phone):
#     pass
#
#
# s=smartphone(20000,'samsung','20px')
#
# print(s.review())






# =====================    hierarchical inheritancs   ================================

#
# class phone:
#     def __init__(self, price, brand, camera):
#         self.price=price
#         self.brand=brand
#         self.camera=camera
#         print("inside the parent constructor")
#
#     def buy(self):
#         print("buy the phone")
#
#
# class smartphone(phone):
#     pass
#
#
# class featurephone(phone):
#     pass
#
#
# s=smartphone(20000,'samsung','8gp')
# print(s.buy())
#
# f=featurephone(20000,'samsung','8gp')
# print(f.buy())




# =========================   multiple inheritances  ======================
#
# class phone:
#     def __init__(self, price, brand, camera):
#         self.price=price
#         self.brand=brand
#         self.camera=camera
#         print("inside the parent constructor")
#
#     def buy(self):
#         print("buy the phone")
#
# class prodect:
#      def review(self):
#          print("prodect customer review")
#
#
#
# class smartphone(phone,prodect):
#     pass
#
#
# s=smartphone(20000,'samsung','8gp')
# print(s.buy())
# print(s.review())





# =======================  ractices  question  ================================

#
# class A:
#     def m1(self):
#         return 20
#
# class B(A):
#     def m1(self):
#         return 30
#
#     def m2(self):
#         return 20
# class C(B):
#     def m2(self):
#         return 30

#
# obi1=A()
# obj2=B()
# obi3=C()
#
# print(obi1.m1()+obj2.m1()+obi3.m2())



# =========================  method overloading  ========================

#
# class shape:
#
#     def area(self,a,b=0):
#         if b==0:
#             return 3.14*a*a
#         else:
#              return a*b
#
# s=shape()
# print("area of the circle :",s.area(2))
# print("area of the retangular :",s.area(3,5))
#




# ====================  open the file  ======================


# f= open('sample.txt','w')
# f.write('hello shoaib')
# f.close()



# ==============  write the multi line string =======================
#
# f=open('sample1','w')
# f.write('hello world')
# f.write('\n how are you')
# f.close()


#    =======================    if already file is present
#
# f=open('sample1','w')
# f.write('hello asad')
# f.close()


#   ====================     exiting file we enter another content ==================

#
# f=open('sample.txt','a')
# f.write('\ni am fine')
# f.close()
#



# ==================   we add the list in the file   ===============================

#
# l=['hi\n','hello\n','how are you\n','i am fine \n','and you \n ','and fine']
#
# f=open('sample.txt','w')
# f.writelines(l)
# f.close()



# ==================  read method===========================
#
# f=open('sample.txt','r')
# r=f.read()
# print(r)
#


#
# f=open('sample.txt','r')
# r=f.read(10)
# print(r)



# ===================   read linne method ==========================
#
#
#
# f=open('sample.txt','r')
# print(f.readline(),end='')
# print(f.readline(),end='')
# print(f.readline(),end='')
# f.close()



#    ====================  how to fetch the data  from the file throught readline  ==================

#
# f=open('sample.txt','r')
# while True:
#     data=f.readline()
#     if data=='':
#         break
#     else:
#         print(data,end='')
# f.close()



# ====================   close the file with keyword with  =========================
#
# with open('sample1','w') as f:
#     f.write('shoaib bhai')




# =====================  ais tarah hi read ky sath kary gay  ==============================


#
# with open('sample.txt','r') as f:
#     print(f.read())
#


# ++============================  read the first ten character  =========================

#
# with open('sample.txt', 'r') as f:
#     print(f.read(10))
#     print(f.read(10))




# ====================  practices  question  ============================================

#
#
# big_list=['hello world\n' for i in range(1000)]
# with open('big.txt','w') as f:
#     f.writelines(big_list)
#



# ====================   ftch first 100 character  form big_txt files  =====================



# with open('big.txt','r') as f:
#     chank_size=100
#     while len(f.read(chank_size))>0:
#         print(f.read(chank_size),end='****')
#         f.read(chank_size)
#


#   ================== tell()   and seek()  method  ===========================
#
# with open('sample.txt','r') as f:
#     print(f.read(10))
#     print(f.tell())
#
#     f.seek(0)
#     print(f.read(10))



# ========================   seek() method during the write  =====================

#
# with open('sample.txt','w') as f:
#     print(f.write('hello'))
#     f.seek(2)
#     print(f.write('x'))



#   ========  read data in binery from  ============================================
#
# with open('group.jpg','rb') as f:
#     with open('group_pic.jpg','wb') as wb:
#         wb.write(f.read())
#
#




# ==========================     write  the numerical data   ==========================


#
# with open('sample1','w') as f:
#     print(f.write('5'))


# ==========================   read the numberical data ===============================

#
# with open('sample1','r') as f:
#     print(int(f.read())+5)
#
#



# ===============================   how to write the dictiomary =========================

# d={"name":"shoaib","age":"23","gender":"male"}
#
# with open('sample1','w') as f:
#     f.write(str(d))



# ======================    how to write the dictionery ===================================
#
# d={"name":"shoaib","age":"23","gender":"male"}
#
# with open('sample1','r') as f:
#     print(f.read())



# ========================  kis tarah hum list ko json ma tabdeel kartay haa =========
#
# import json
# l=[1,2,3,4,5,6,7,8,9,10]
# with open('demo.json','w') as f:
#     json.dump(l,f)


# ===================  kis tarah hum dictionary ko json ma tabdeel kartay haa ==========
# import json
# d={"name":"shoaib","age":"23","gender":"male"}
# with open('demo.json','w') as f:
#     json.dump(d,f,indent=4)




# ===================  kis tarah hum dictionary ko json  sy ython data types ma tabdeel karty haa ==========
#
# import json
#
# with open('demo.json', 'r') as f:
#     d = json.load(f)  # Use json.load() instead of json.loads()
#     print(d)
#



# ====================  tuple ko app kis tarah serialization kartay haa =====================================
# import json
# tuple=(1,2,3,4,5,6,7)
# with open('sample1','w') as f:
#     json.dump(tuple,f)



# =================  abb hm ny class ky object ko  ko  json ma tabdeel krna aa haa  ==========================
#
# class Person:
#     def __init__(self,fname,lname,age,gender):
#         self.fname=fname
#         self.lname=lname
#         self.age=age
#         self.gender=gender
#
#
#
# person=Person('shoaib','ali',23,'male')
#
#
#
#
# import json
# def show_object(person):
#     if isinstance(person,Person):
#         return "{} {}  age->{}  gender->{}".format(person.fname,person.lname,person.age,person.gender)
# with open('demo.json','w') as f:
#     json.dump(person,f,default=show_object)
#
#


#  ===================    ais object ko dictionery ma bee serialized kr sakty haa=================

#
# class Person:
#     def __init__(self,fname,lname,age,gender):
#         self.fname=fname
#         self.lname=lname
#         self.age=age
#         self.gender=gender
#
#
#
# person=Person('shoaib','ali',23,'male')
#
#
#
#
# import json
# def show_object(person):
#     if isinstance(person,Person):
#         return {'name':person.fname + ' ' + person.lname,'age':person.age,'gender':person.gender}
# with open('demo.json','w') as f:
#     json.dump(person,f,default=show_object,indent=4)
#





# ===================   concept of serialized  pickling  writing   is remaining   =====================================================
#
# class person:
#     def __init__(self,name,age):
#         self.name=name
#         self.age=age
#
#     def display_info(self):
#         print(f"Hi my namis {self.name} and my age is {self.age} year old")

#
# p=person('shoaib',23)
# print(p)
#
# import pickle
# with open('person.pkl','wb') as f:
#     pickle.dump(p,f)


# =======================   concept of deserialized picklind read ==========================
#
# import pickle
#
# class person:
#     def __init__(self, name, age):
#         self.name = name
#         self.age = age
#
#     def display_info(self):
#         print(f"Hi, my name is {self.name} and my age is {self.age} years old")
#
# p=person('shoaib',23)
# # Deserialize the object from the file using pickle.load
# with open('person.pkl', 'rb') as f:
#     p = pickle.load(f)  # Use pickle.load() instead of pickle.loads()
#     p.display_info()
#
#
#




# =============================     exception  handling ==========================

#
# with open('sample1','w') as f:
#     f.write('hello world')
# try:
#     with open('sample2','r') as f:
#         print(f.read())
# except:
#     print("sorry no file exit ")






# ============================   another  practies question  =========================


#
# with open('sample1','w') as f:
#     f.write('hello world')
# try:
#     m=5
#
#     with open('sample1','r') as f:
#         print(f.read())
#         print(m)
#         print(5/2)
#         L = [1, 2, 3, 4, 5]
#         L[100]
# except FileNotFoundError:
#     print("file not found")
# except NameError:
#     print("variable not define")
# except ZeroDivisionError:
#     print("this is logic error ")
# except Exception as e:
#     print(e)
#
# except Exception as e:
#     print(e.with_traceback)



# ============================   else  block  in exception handling  ===========================
#
#
# try:
#     f=open('sample2','r')
# except FileNotFoundError:
#     print("file not found")
# except Exception:
#     print("kuch bee nhi milla")
# else:
#     print(f.read())


#   ==============================   finally block   in exception handling   =========================


#
#
# try:
#     f=open('sample1','r')
# except FileNotFoundError:
#     print("file not found")
# except Exception:
#     print("kuch bee nhi milla")
# else:
#     print(f.read())
#
# finally:
#     print("yah too har hall ma hi print ho gah")
#



# =============================     raise errror ================

#
# raise ZeroDivisionError('ma asay hi try kr ra hoo ')


# =========================    practices question  =================
#
#
# class bank:
#     def __init__(self,balance):
#         self.balance=balance
#
#
#     def withdraw(self,amount):
#         self.amount=amount
#
#         if amount < 0:
#             raise Exception('balances is not negative ')
#         if self.balance < amount:
#             raise Exception('app ky account ma paise nhinhaa')
#         self.balance=self.balance - amount
#
#
# b=bank(10000)
# try:
#     b.withdraw(-5000)
# except Exception as e:
#     print(e)
# else:
#     print(b.balance)




# ===================    practices question ==========================
# class SecurityError(Exception):
#     def __init__(self,message):
#         print(message)
#
#     def logout(self):
#         print('logout')
#
# class google:
#     def __init__(self,name,gmail,password,device):
#         self.name=name
#         self.gmail=gmail
#         self.password=password
#         self.device=device
#
#
#     def login(self,gmail,password,device):
#         if device !=self.device:
#             raise SecurityError('you can select the wrong device')
#         if gmail==self.gmail and password==self.password:
#             print('wellcome')
#         else:
#             print('print the login Error')
#
#
#
# obj=google('shoaib','shoaib@gmail.com',1234,'andriod')
#
# try:
#     obj.login('shoaib@gmail.com',1234,'window')
# except SecurityError as e:
#     print(e.logout())
# else:
#     print(obj.name)
#
# finally:
#     print('connection  is closed  ')
#
#
#





# ============================    explain of locial and global variable    ===================================


#
# a=2
# def temp():
#     global a
#     a+=1
#     print(a)
#
# temp()
# print(a)



# ================  inside the value  function parameter  is local and global  ====================
#
# def temp(z):
#     print(z)
#
# a=10
# temp(5)
# print(a)



# ===================  see all the builtin function =============================
#
#
# import builtins
# print(dir(builtins))


# ====================    enclosed function  =====================================

#
# def outer():
#     def inner():
#         print("inner function")
#     inner()
#     print("print outter function")
#
# outer()
# print("main program")




# =====================      change the loical  variable but we can change the   change the global variable====

#
# def outer():
#     a=1
#     def inner():
#         nonlocal a
#         a=1
#         a+=1
#         print("inner",a)
#     inner()
#     print("outer",a)
# outer()
# print("main program")




# ======================  decorator  ==============================
#
# def my_decorator(func):
#     def wrapper():  # Corrected the spelling of 'wraper' to 'wrapper'
#         print("***********************************")
#         func()  # Call the original function
#         print("***********************************")
#     return wrapper # Return the wrapper function, not call it
#
# def hello():
#     print("hello world")
#
#
# def name():
#     print("shoaib ali")
#
# a = my_decorator(hello)  # Apply the decorator
# a()  # Call the wrapped function
#
#
# b=my_decorator(name)
# b()










#   ======================   practices question  decorator  ==========================
# import time
# from traceback import print_tb
#
#
# def timer(func):
#     def wrapper(*args):
#         start=time.time()
#         func(*args)
#         print("time is take ",func.__name__,time.time()-start,"sce")
#     return wrapper
#
# @timer
# def hello():
#     print("hello wlod")
#     time.sleep(2)
#
# hello()
#
# @timer
# def display():
#     print("displaying something")
#     time.sleep(4)
# display()

#
#
# @timer
# def square(num):
#     time.sleep(1)
#     print(num**2)
#
# square(2)


# ===========================  practices question of decorator  =====================

#
# def sanity_check(data_type):
#     def outer_wrapper(func):
#         def inner_wrapper(*args):
#             if type(args[0])==data_type:
#                 func(*args)
#             else:
#                 raise TypeError("cannot match the data type")
#
#         return inner_wrapper
#     return outer_wrapper
#
# @sanity_check(int)
# def square(num):
#     print(num**2)
#
# square(2)
#





# =====================    iteration   =====================

#
# a=[1,2,3,4,5]
# for i in a:
#     print(i)


# ==========================  iterator  ======================
# import sys
# l=[x for x in range(100000)]
# print(l)
# print(sys.getsizeof(l)/64)
# #

#
# x=range(1,100000)
# # for i in x:
# #     print(i*2)
# print(sys.getsizeof(x)/64)

#
# l=[1,2,3,4,5]
# print(type(l))
# print(iter(l))



# =================   this is iterable or not iterable  ================

# a=(1,2,3,4)
# print(dir(a))
#



# ===============    how make the iterator=============

# Corrected code using a set (only hashable elements)
# a = {1, 2, 3, 4}
# print(iter(a))



# =========================   how  to work the for loop   in python==============================
#
# a=[1,2,3,4,5,6,7,8]
# iter_a=iter(a)
# print(next(iter_a))
# print(next(iter_a))
# print(next(iter_a))
# print(next(iter_a))
# print(next(iter_a))

#
#
# def mara_khadka_for_loop(iterable):
#     iterator=iter(iterable)
#     while True:
#         try:
#             print(next(iterator))
#         except StopIteration:
#
#             break
#
#
# a=[1,2,3,4,5]
# b=(1,2,3,4,5,6,7,89,10)
# c=range(1,11)
# e={0:1,1:2}
#
# mara_khadka_for_loop(e)


#
# num=[1,2,3,4,5,6,7]
# iter_object1=iter(num)
#
# print(id(iter_object1),"iter 1")
# print(id(iter(iter_object1)),"iter 2")



#  ================================     generator    ==========================

#
# def gen_demo():
#     yield "first statement"
#     yield "secnd statmnt"
#     yield "third statement"
#
#
# gen=gen_demo()
# print(next(gen))
# print(next(gen))
# print(next(gen))
# print(next(gen))




# ===================  generator  ==============================================
# def square(num):
#     for i in range(num+1):  # Create a range of numbers from 0 to num
#         yield i**2  # Yield the square of each number
#
# den = square(10)
# print(next(den))
# print(next(den))
# print(next(den))
# for i in den:
#     print(i)
#
#





# ====================   how to work the range function in the generator =========================

#
# def mara_range(start,end):
#     for i in range(start,end):
#         yield i
#
# gen=mara_range(10,25)
# for i in gen:
#     print(i)


#
# L=(i**2 for i in range(1,101))
# for i in L:
#     print(i)

