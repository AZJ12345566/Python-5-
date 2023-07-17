# Python-5-
Python学习笔记(5)
# p20 input函数的使用
# 输入函数格式变量=input('balabala')
present=input('balabala')
print(presen,type(present))
#在输出栏中balabala的后面输出“我最牛”，那么计算机在下一行就会输出“我最牛”




# p21 input函数的高级使用
#从键盘录入两个整数，计算两个整数的和
a=input('请输入一个加数:')
b=input('请输入另一个加数:')
print(a+b)
#此行输出是1020，所以这里的+号起的是连接作用，需要解决用强制类型转换
a=int(input('请输入一个加数:')) #将转换之后的·1结果存储到a中
b=int(input('请输入另一个加数:'))
# 这里可以在输入完成之后进行转换
print(type(a),type(b))
print(a+b)



# p22 运算符_算术操作符
print(1+1) #加法运算
print(1-1) #减法运算
print(2*4) #乘法运算
print(1/2) #除法运算
print(11//2) #整除运算(这个运算只取整，不取余)
print(11%2) #取模运算(只取余)
print(2**2) #表示2的2次方
print(2**3) #表示的是2的3次方 2*2*2


print(9//4) #2
print(-9//-4) #2
print(9//-4) #-3 (一正一负的整数格式，向下取整)
print(-9//4) #-3

print(9%-4) #-3 (公式。余数=被除数-除数*商        9-(-4)*(-3)-->-3)
print(-9%4) #3                                -9-4*(-3)-->3
