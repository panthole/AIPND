## Day3

1. 输出两个列表之间的不同元素，如:[1, 2, 3], [2, 3, 'a'] 则输出['a', 1]
 * list(set(L1)-set(L2))+list(set(L2)-set(L1))

2. if(x>3): print("True") else: print("False"),若 x=2，则该段代码的执行结果是?
 * false

3. if(x>5): print("True") elif x>0 and x<5 print("False") else: print("Error"), 若是想要输出"False"，则 x 可以取哪些整数?
 * 1,2,3,4

4. x=0，if x:print("False") else:print("True")，该段代码的输出结果是?
 * false

5. x=0，y=1, if x and y:print("False") elif x or y:print("True")，该段代码的输出结果是?
 * true

6. x=0, if not x: print("True") else: print("False"),该段代码的输出结果是?
 * true

7. x=None，y=1，z=3，if not(x and y or z): print("False") else: print("True"), 该段代码的输出结果为?
 * false

8. cities = ['Beijing', 'Shanghai', 'Shenzhen', 'Guangzhou']，请使用 for 语句遍历 cities，输出 cities 中的元素。
 * for city in cities: print(city.title())

9. print(list(range(1,12,3)))的结果是?
 * [1,4,7,10]

10. L=[1,2,3,4,5], list[range(len(L))]的结果是?
 * [0, 1, 2, 3, 4]

11. print(cities[i])的输出结果是?
```
cities = ['Beijing', 'Shanghai', 'Shenzhen', 'Guangzhou'] 
for i in range(len(cities)-1): 
	print(cities[i])
```
 * ['Beijing', 'Shanghai', 'Shenzhen']

12. 请在空白处填写合适的代码，利用cities 中的元素创建一个 city 列表。
```
cities = ['Beijing', 'Shanghai', 'Shenzhen', 'Guangzhou']
city=[]
for i in range(len(cities)): 
  city.__________ 
```
 * append(cities[i])

13. while 语句执行的流程是怎样的?
 * 当满足while中的判定条件时，执行while中的语句，每执行完一次，重新判定是否满足条件，满足继续执行，不满足则退出while。

14. error =0，1 while error:print("hello") 2while (not 1): print("hello"), 两个代码块的执行结果分别是什么?为什么产生这种结果?
 * ①的结果是没有输出，直接跳出循环，是因为error=0，条件为假，不执行while中的语句；②的结果是无限输出hello，因为not 0的值为1，即条件永远为真，则一直执行while中的语句。

15. y 的最终输出结果是?
```
x=[3,1,6,5,19,2,4]
y=[]
i=0
while(x[i]<10): 
  y.append(x[i]) 
  print(y)
  i +=1
```
 * y=[3,1,6,5]

16. if-else语句执行的流程是怎样的?
 * 先判断if中的条件，若满足条件，则执行if中的语句；若不满足条件，则执行else中的语句。

17. 请用代码计算 1 +3 +5...+99+101
```
sum=0
for i in range(1,102,2):
     sum +=i 
print(sum)
```

18. 请倒叙打印 ['Beijing','Shanghai','Shenzhen'，‘Guangzhou’]
```
city= ['Beijing', 'Shanghai', 'Shenzhen', 'Guangzhou']
print(city.reverse())
```
