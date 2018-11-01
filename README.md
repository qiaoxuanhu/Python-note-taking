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


#while循环
condition =1
while condition < 10:
    print(condition)
    condition = condition + 1
