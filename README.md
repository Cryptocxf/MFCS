# The-mathematical-foundation-of-cyberspace-security
## 课程介绍
* **课程名称**：北航《网络空间安全数学基础》——2020秋季  
* **任课老师**：高莹老师  
* **课程助教**：cxf_BY2039101  
* **主要内容**：本课程的面向对象为网络空间安全专业或相关专业的研究生(硕士或博士)，其内容包括密码学的信息论基础、代数学基础、椭圆曲线、格、图论和博弈论等。本课程以增强学生对数学知识在密码学中的深刻认识和具体作用，着力培养学生的逻辑思维能力和数学推理能力。  
-----------------------------------------------
## 教学课件  
* **1. 密码学的信息论基础.pdf**	—	[点击下载](https://pan.baidu.com/s/1hztSVzB_QzE_5nPYW_6-Rw)，提取码：`njbn`  
* **2. 密码学的信息论基础.pdf**	—	[点击下载](https://pan.baidu.com/s/1MBsgRFT654PJUjaYS5mXrA)，提取码：`obzh`
* **3. 代数学基础.pptx**	—	[点击下载](https://pan.baidu.com/s/1Q3ymBlQkJW0KyD_c8tJKXg)，提取码：`5o8w`  
* **4. 椭圆曲线(1).pdf**	—	[点击下载](https://pan.baidu.com/s/1nG7cG0y58ECeL5QIljCcAA)，提取码：`s1u9` 
* **5. 椭圆曲线(2).pdf**	—	[点击下载](https://pan.baidu.com/s/1F3HVa7MoDsaG8dkpZ5KQCA)，提取码：`s75o` 
* **6. 格(1).ppt**  
* **7. 格(2).ppt**	—	[点击下载](https://pan.baidu.com/s/1I8tHQLrKPx2uaAmIt5FFbQ)，提取码：`6g9e`  
* **8. 格(3).ppt**
* **9. 图论的基本模型与算法.ppt**	—	[点击下载](https://pan.baidu.com/s/1Gz6LSKWqEdy2F2YKFQVSXw)，提取码：`b289`  
* **10.博弈论介绍.ppt**	—	[点击下载](https://pan.baidu.com/s/1OXAtGFGTLDkJzXKTKJmGug)，提取码：`bt0v`  
-----------------------------------------------
## 参考资料  
* **《An introduction to mathematical cryptography(Second edition)》**	—	[点击下载](https://pan.baidu.com/s/1IqVOJ7vGvNj-9M-WUUBAlQ)，提取码：`heu7`  
* **《A course in game theory》by Martin J. Osborne,	Ariel	Rubinstein**	—	[点击下载](https://pan.baidu.com/s/1HMRL7TNjYEFhLQM5FcVYUQ)，提取码：`29n7`  
* **《A course in game theory》中文版**	—	[点击下载](https://pan.baidu.com/s/14BRA817gR7R_Z4H6Vdd34A)，提取码：`085z`
-----------------------------------------------
## 作业参考解答  
###  第一次作业:密码学的信息论基础 
* **题1.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/1.1.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/1.1.2.png)  

* **题2.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/1.2.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/1.2.2.png)  

* **题3.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/1.3.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/1.3.2.png)
###  第二次作业：代数学基础(1)  
* **题1.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/2.1.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/2.1.2.png)  

* **题2.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/2.2.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/2.2.2.png)  

###  第三次作业：代数学基础(2)  
* **题1.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/3.1.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/3.1.2.png)  

* **题2.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/3.2.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/3.2.2.png)  

###  第四次作业：椭圆曲线  
* **题1.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/4.1.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/4.1.11.png)    
* 计算椭圆曲线点数python参考代码如下：
```python
x = 0
y = 0
while x<31:
	c = ((x*x*x)+2*x+7)%31
	while y<30:
		if((y*y)%31)==c:
			print('当x =',x,'时，x^3+2x+7(mod31)= ',c,'，y =',y)
		y=y+1
	y=0
	x = x + 1
```  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/4.1.111.png)
* 计算椭圆曲线中的点加运算python参考代码如下：
```python
y=0
x=0
x1=17
y1=26
x2=2
y2=9
F=31
while y<F: #求P+P
	if ((2*y1)*y)%F == 1:
		z =(y*(3*x1*x1+2))%F
		A = (z*z-2*x1)%F
		B = (z*(x1-A)-y1)%F
		print('P+P = ',A,B)
	y=y+1
while x<F: #求P+Q
	if ((x2-x1)*x)%F == 1:
		z =(x*(y2-y1))%F
		C = (z*z-x1-x2)%F
		D = (z*(x1-C)-y1)%F
		print('P+Q = ',C,D)
	x=x+1
```  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/4.1.1111.png)  

* **题2.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/4.2.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/4.2.2.png)  

###  第五次作业：格(1)  
* **题1.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/5.1.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/5.1.2.png)    

* **题2.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/5.2.1.png)
	 
* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/5.2.21.png) 
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/5.2.22.png)
###  第六次作业：格(2)  
* **题1.**   
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/6.1.1.png)  

* **解**  
![martix](https://github.com/CryptoXF/The-mathematical-foundation-of-cyberspace-security/blob/main/math/6.1.2.png)
* LLL算法例子python参考代码如下：
```python
k = 2
v1 = [20,16,3]
v2 = [15,0,10]
v3 = [0,18,9]
v2_star = list(v2)
def Change(x,y):
    e = list(x)
    x = list(y)
    y = e
    return x,y
while k<3:
    a = 0
    b = 0
    c = 0
    sum_v1 = 0
    sum_v2 = 0
    sum_v3 = 0
    sum_v2_star = 0
    sum_v3_star = 0
    for i in range(3):
        a = a + v2[i] * v1[i]
        sum_v1 = sum_v1 + v1[i] * v1[i]
    u21 = a / sum_v1
    print('u21 =',u21)
    if (abs(u21) <= 0.5):  # 判断是否满足尺度约化
        for i in range(3):
            v2_star[i] = v2[i] - u21 * v1[i]
            sum_v2_star = sum_v2_star + v2_star[i] * v2_star[i]
        if (sum_v2_star >=(0.75-u21*u21)* sum_v1):# 判断是否满足Lovasz条件
            for i in range(3):
                b = b + v3[i] * v1[i]
                c = c + v3[i] * v2_star[i]
            u31 = b / sum_v1
            u32 = c / sum_v2_star
            print('u31 =', u31)
            print('u32 =', u32)
            if (abs(u31) <= 0.5 and abs(u32) <= 0.5):
                for i in range(3):
                    sum_v3 = sum_v3 + (v3[i] - u31*v1[i]) * (v3[i] - u31*v1[i])
                if (sum_v3 >= 0.75 * sum_v2_star):
                    k = k + 1
                    print('v1=', v1)
                    print('v2=', v2)
                    print('v3=', v3)
                else:
                    (v2,v3) =Change(v2,v3)
            else:
                for i in range(3):
                    v3[i] = v3[i] - int(u32 + 0.5) * v2[i]-int(u31 + 0.5) * v1[i]
        else:
            (v1,v2) = Change(v1,v2)
    else:
        for i in range(3):
            v2[i] = v2[i] - int(u21 + 0.5) * v1[i]
```  
-----------------------------------------------
# 总结  
	本课程学习的重点是要将老师上课讲的知识点弄懂、理解和吸收，并按照教学课件上的内容梳理贯通，课后及时的完成作业、加以巩固。另外，祝愿大家都能从本课程中有所收获！
-----------------------------------------------
