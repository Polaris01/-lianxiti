# -lianxiti
廖雪峰python练习题
##01温度转换代码
f = float(input('请输入华氏温度: '))
c = (f - 32) / 1.8
print('%.1f华氏度 = %.1f摄氏度' % (f, c))
##求圆的面积
d = float(input('请输入半径:'))
s = d*d*3.14
l = 2*d*3.14
print('面积是：%.lf 周长是：%.lf' % (s,l))
