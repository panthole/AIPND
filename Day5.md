## Day5

1. a=['a','b ','c ','d']，b=[1, 2, 3, 4]，print(zip(a, b))的结果是什么?

2. 如果 c=[('a',1), ('b',2), ('c',3), ('d',4)]，那么如何用 zip 函数将其拆分?

3. Enumerate 函数会返回元组，这些元组包含列表的哪两部分?

4. For i in enumerate('udacity') : print(i)的结果是什么?

5. a=['a','b ','c ','d']，b=[1, 2, 3, 4]，请用 for 循环和 zip 函数实现输出:['a',1], ['b',2], ['c',3]

6. a=['a','b ','c ','d']，b=[1, 2, 3, 4]，请采用 dict 和 zip 函数实现将两个列表组合成字典。

7. a=[1,2,3,4,5], b=[], for i in range(len(a)): b.append(a[i]) print(b), 请使用列表推导式修改上述代码，实现和其相同的功能。

8. s = [x+2 for x in range(10) if x % 2 == 0 else x + 1], print(s)的结果是?

9. s = [x+2 for x in range(10) if x % 2 == 0]，请调整代码结构，将 else x+1放到合适的位置并输出 s。

10. names = ["Rick Sanchez", "Morty Smith", "Summer Smith"]，请使用 split 函数提取每个人的姓氏，以列表形式输出。

11. elements = {"hydrogen": 1, "helium": 2, "carbon": 6}，请根据元素在周期表中的位置输出相应元素，输出位置大于 4 的元素。

12. vowels="aeiou", sentence="I am a student" ,nonvowels=' '.join([ l for l in sentence if not l in vowels]) , 该列表推导式的作用是什么?

13. 请使用列表推导式，找到 100 以内可以整除 3 的数字。

14. Enumerate 函数默认起始的索引值为 0，如果想要制定起始索引，应该怎么做?

15. enumerate 和 zip 返回的对象类型分别是什么?

16. enumerate 和 zip 返回类型在 Py2 与 Py3 中的区别是什么?
