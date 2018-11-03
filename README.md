# Python note-taking 25.Oct.2018
#安装 https://www.python.org/downloads/
#print
print(1024)
print('hello world')
print('I'm Q.H') 报错
#绿色是字符串 黑色可能是命令，或者是变量。
print("I'm Q.H") 
print('I\'m Q.H')
#str + str ,string字符串 它是编程语言中表示文本的数据类型
print('Qiaoxuan'+'Hu')
#str + int  报错
print('Q.Hu'+22) 报错
type()
print（'Q.Hu'+'22'）
print('Q.Hu'+str(22))
#int + int -INTEGER整型数，数据是不包含小数部分的数值型数据,float
print(1+2)
print('1+2')
print(int('1')+2)
>>> print(int(1.2) + 2)	  
3
print(int('1.2')+2) 报错
print(float('1.2')+2)

#基础数学运算 + - * / 平方** 取余数%  取整// 更多运算功能上网找
1 + 1
1 - 1
2 * 2
4/3
2**10 = 1024
8%2 = 0
10%3 = 1
10//3 = 3

#variable自变量，把数据和运算存在一个内存中_new File - run model
apple = 1 #把1放到这个自变量当中
print(apple) #输出这个自变量
#命名
apple_fruit, APPLE_FRUIT, appleFruit 
appleEgg = 12 +3
print(appleEgg)
#一次定义多个自变量
a,b,c=1,2,3
print(a,b,c)
a = 1
b = a*2
print(a,b)

#3.Nov.2018
#while循环 当条件满足的时候，我会一直做某件事情 ，python有两种循环语句，while和for
condition =1
while condition < 10:    ##python是一个非常注重语言结构和语言形式的语言，在while/for的第一行的结尾一定要有冒号，告诉python我的话还没说完
    print(condition)     #会自动-空格4个，相当于tab，无论输入什么都是while循环内部的语句，如果没有四个空格，就是for循环外面的。
    condition = condition + 1  #现在的condition被赋值成以前的condition+1
知道condition不满足这个条件，就会跳出这个循环。

#True正确，False否定, 没出口，终止循环Ctrl C
while True:
    print（“I’m True”）

#For循环-给定了区间，当这个函数=【1，10】,变量=1的时候，做什么，等于2的时候，做什么，3的时候，做什么。for循环相当于迭代器的作用
#python中的list用中括号
example_list=[1,2,3,4,5,6,23,45,56,67,12847]
#让i在example_list里按顺序迭代list里面的某个值，每次迭代i的时候，就print一个值，看看会print出来什么。
for i in example_list:
    print(i)  
    
for i in example_list:
    print(i)  
print（‘outer of for’） #内部所有的输出完，才能输出循环外部的语句。
#结构很重要
for i in example_list:
    print(i)  
    print('inner of for') 
    
print（‘outer of for’） 

#删除了一些语句，前面有很多tab   
for i in example_list:
        print(i)  
        print('inner of for')

Mac：选中，command+[

#内部有用的函数range，和list相似，是个电脑自动生成的迭代器。
for i in range(1,10):   #rang的规则，是1到9，左闭右开的。注意，丢一位。
    print(i)
    
#range(start,stop[,step]) [步长] 可有可无
for i in range(1,10,1):  
    print(i)
    
for i in range(1,10,2):  
    print(i)
    
for i in range(1,10,5):  
    print(i)
    
for i in range(1,10,-1):  
    print(i)

#基础语句，判断语句if，当。。。的时候，做什么
x=1
y=2
z=3

if x>y:
    print('x is greater than y')  #注意四个空格，执行会empty
    
if x<y:
    print('x is less than y') 
    
if True:
   print('x is less than y') 
   
if x<y<z:    #按实际逻辑来说，可以的。python是一个高级语言，它可以理解你多方面的含义
    print('x is less than y,and y is less than z') 
    
z = 0  
if x<y>z:   
    print('x is less than y,and y is less than z')
#这是一个基础的判断，我们可以用符号来判断。
  
x = 2
y = 2
if x<=y:   
    print('x is less or equal to y')
    
<,>,<=,>=

#报错，相当于把Y的值赋给x,这是一个自变量的运算,不是一个判断语句。
if x=y:
    print('x is less or equal to y')

#如果想用判断语句
if x==y:
    print('x is equal to y')

#不等于
if x != z:
    print('x is not equal to z')
   
#多加一层条件,如果true，怎么怎么样，false，怎么怎么样
x=1
y = 2
z =3
if x>y:
    print('x is greater than y')
else:
    print（‘x is less or equal to y’）

#True    
x=4
y = 2
z =3
if x>y:
    print('x is greater than y')
else:   #同等的条件执行的语句，要在同样的位置，对齐。
    print（‘x is less or equal to y’）
   
