# python速度优化

* 用set替代求list的<u>交、并、差</u>集：

  ```
  print list(set(list_a).intersection((set(b)))
  
  print list(set(list_a).union((set(b)))
  
  print list(set(list_a).difference((set(b)))	
  ```

* 基本操作（判断，变量互换）：

  ```
  a,b =  b ,a
  while 1 #"while True" better
  if a==True #"if a is True" better
  
  ```

* 连接字符串

  使用` (" ?").join([substring_1,substring_1,substring_1])`

  

* 利用map,reduce,filter替代for循环

  

* 处理大量数据使，尽可能使用不可变数据类型如tuple而不是list

  

* 使用生成器



​                                       