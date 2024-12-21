# Tonelli---Shanks
Tonelli - Shanks算法实现案例
#随机生成一个素数，也可以指定一个
p=number.getPrime(10)
这里生成素数的可以改
然后下面：
#a为二次剩余
while True:
    a=random.randint(1,p-1)
    if legendre_symbol(a,p)==1:
        break

读者可以把整份代码包装成一个函数，不过上面两个地方需要修改，作为参数输入即可，a一定要是p的二次剩余！！！
因为是测试案例，我就采取了随机生成
