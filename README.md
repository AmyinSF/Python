# Python

http://www.runoob.com/python3/python3-basic-syntax.html

http://crossincode.com/course/lesson_list/

标识符
</br>第一个字符必须是字母表中字母或下划线 _ 。
</br>标识符的其他的部分由字母、数字和下划线组成。
</br>标识符对大小写敏感。

字符任何时候都要用引号。
</br>注释#写在前面。
</br>Python 通常是一行写完一条语句，但如果语句很长，我们可以使用反斜杠(\)来实现多行语句;在 [], {}, 或 () 中的多行语句，不需要使用反斜杠(\)

python中数字有四种类型：整数、布尔型、浮点数和复数。
</br>
int (整数), 如 1, 只有一种整数类型 int，表示为长整型，没有 python2 中的 Long。
</br>bool (布尔), 如 True。
</br>float (浮点数), 如 1.23、3E-2
</br>complex (复数), 如 1 + 2j、 1.1 + 2.2j

\n是换行 \t是空一个Tab的距离

字符串(String)

python中单引号和双引号使用完全相同。

使用三引号('''或""")可以指定一个多行字符串。

转义符 '\'

反斜杠可以用来转义，使用r可以让反斜杠不发生转义。。 如 r"this is a line with \n" 则\n会显示，并不是换行。

按字面意义级联字符串，如"this " "is " "string"会被自动转换为this is string。

字符串可以用 + 运算符连接在一起，用 * 运算符重复。

Python 中的字符串有两种索引方式，从左往右以 0 开始，从右往左以 -1 开始。

Python中的字符串不能改变。

Python 没有单独的字符类型，一个字符就是长度为 1 的字符串。

字符串的截取的语法格式如下：变量[头下标:尾下标]
