## Day2

1. 什么叫可变对象?什么叫不可变对象?Python中哪些对象是可变的?哪些是不可变的?
 * 可变对象可以对其进行插入，删除等操作，不可变对象不可以对其进行有改变的操作。Python中列表，字典，集合等都是可变的，元组，字符串，整型等都是不可变的。

2. 列表索引是从下标几开始?给定列表L=[1,2,3,4,5],print(L[0:3])的输出结果是什么?
 * 下标从0开始，print(L[0:3])输出[1,2,3]。

3. L=[1,2,3,4,5]，print(L[5])的结果是什么?为什么?如果要取出最后一个元素，应该如何输出?
 * 结果会报错，因为列表下标是0~length-1，L(5）会造成下标越界，可以有两种方法输出最后一个元素：print(L(4))或者print(L[-1])。

4. sentence1 = "I wish to register a complaint." 请分别写出sentence1[30] 和 sentence1[-11]的结果。
 * sentence1[30]='.', sentence1[-11]=' '。

5. sentence1 = ["I", "wish", "to", "register", "a", "complaint", "."] 请分别取出 ["I","wish"]和["complaint","."]。
 * sentence1[0:2], sentence1[-1:-3]

6. L=["former", "latter", "starboard"]，请完成:为 L 在末端添加一个元素“port”。
 * L.append("port")

7. L1=[1,2,3,4,5], L2=["star","moon"], L3=[1,2,"star"]，运用 max 函数，输出最长的列表。
 * max_len=max(len(L1), len(L2), len(L3))

8. L=["Car","Carl","Care","Coco","Bar"] ，执行sorted(L)进行排序 ，试着总结sorted 按什么规则对列表中字符串进行排序?
 * 先比较首字母，首字母相同再比较第二个，以此类推。

9. a=(2,3)，试着用 append 方法将 1 添加进 a 的末端，可以成功运行么?如果令 a=[2,3]或者 a="2,3"，能成功运行么?请分别解释原因。
 * 不可以，a是元组类型不可变，如果a是列表类型，可以加入新元素，字符串不可变，同样不能。

10. 设一个立方体的 length, width, height = 40, 40, 40，请写一条输出语句输出立方体的体积。(要求输出形式为:The volume is .)
 * print( "The volume is {}".format(length*width*height))

11. a=(2,3,1,4,5),b=2,3,1,4,5, a 和 b 表达的含义相同么?请输出 a 中的第一个元素，b 中最后一个元素，以及 b 的长度。
 * print( a[0], b[-1], len(b))

12. L=[1,2,3,4,1,4,5,6],请完成:1删除列表中的重复元素并输出一个集合;2将7 随机添加到集合中;3随机从集合中删除一个元素。
 * ①S=set(L); ②S.add(7)③S.pop()

13. 字典 elements = {"hydrogen": 1, "helium": 2, "carbon": 6}中，哪些是键?哪些是值?键的类型可以有哪些?请输出“carbon”对应的值。
 * "hydrogen"等是键，1,2,6是值，键可以为任何不可变类型，print(elements["carbon"])

14. cube:length:40，width:40，height:40。请创建一个字典，包括 cube 的所有信息，并输出 cube 的 width 值。
 * cube={"length":40, "width":40, "height":40},  print(cube["width"])

15. cube:length:40，width:40，height:40, 请创建一个字典，包括 cube 的所有信息，并向字典中添加条目“color”和对应值"red"。
 * cube={"length":40, "width":40, "height":40}, cube["color"]="red"

16. 将字典变为两个元素一一对应的列表，一个只含有关键字，另一个只含有值。 如:{'a': 1, 'b': 2}变为['a', 'b'], [1, 2]
 * dict={'a':1,'b':2}, dict.keys(),dict.values()

17. my_set={1,2,4}可以从中取出第二个值吗？为什么？
 * 不可以取出，集合元素具有无序性
 
18. my_list={1,2,3,4,12,18}快速找出my_list中不重复的元素
 * set (my_list）

