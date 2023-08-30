# 
20230830 
- （稍微用一段中文）
- 单周周三上课，机自335B，郭老师（中文授课）
- 三个实验报告
- （再次介绍发展史）

1. Lua语言（机器人）
2. python发展史
3. python语法
4. 输入输出的语法（巴拉巴拉）
5. 转义字符之反斜杠 \
6. Data type(?)数据类型
    - 数值：int float（等）
    - 字符串（String）的索引和切片
    - 列表(List)支持混合数据类型（数字、字符、字典、集合）
        - 列表是中括号，可以做索引和切片
        - operations: `len`/`append`/`delete`/...
        - `extend`/...
    - 元组(Tuple) 
        - 小括号，一定义就不能改变
        - 可切片
    - 字典(Dictionary)
        - 一个字典元素就是一个键值对(key/value)；key是关键字，value是关键字对应取值（与指针似乎有相似之处？）
        - 表示映射关系的数据结构
        - key不可重复，value可重复
        - 字典可以嵌套
        - 语法：打印字典、访问字典中的元素、查询字符是否在字典内in运算符、遍历（用for循环）、更新字典、合并字典(dic.update)、删除元素(`.pop()`、`.clear()`)
        - 字典里的元素是无序的
    - 集合(set)
        - 集合(set)&不可变集合(forzenset)
        - 元素无序
7. 函数(Fuction)
    - 叫“包”
    - 许多的内置函数，使用方便（用到再查）合理使用`help()`
    - 用户自定义函数
        - `def FuctionName`
        - 函数名、参数、返回值
        - 调用函数
        - 多元赋值，得多个返回值(很难不想起MIMO系统，现代控制所要处理的复杂玩意)
    - 变量的作用域
        - 全局变量(Global Variable)：函数体外
        - 局部变量(Local Variable)：函数内
    - 参数的传递:
        - 按值传递（形参&实参单独存储）.内部函数改变形参时,实参的值不会改变.
        - 列表/字典内会改变实参的值.
        - 参数的默认值
8. 模块和包(Module & Package) 
    - Module
        - python文件.(.py)
    - Package(范畴大于模块)(可以有子包)
    - 导入模块/包/库
        - 导入整个包:`import numpy as np` 
        - 导入包中指定模块或子包:`from numpy import *`
        -  创建自定义模块:常用函数打包放在同一个.py文件里,命名为"mymodule.py"
        -  调用自定义模块:`import mymodule as mm`
    - 系统函数(System Module)
    - 平台模块(Platform Module)
9. 类(Class)
    - Definition of Class:相同属性方法的一组对象的描述
    - 对象(Object):类中一个具体实例
    - 属性(Attribute):