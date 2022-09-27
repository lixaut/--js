
## 知识点

### 1. 数据类型

1. 6种不同的数据类型

    * String
    * Number
    * Boolean
    * Object
    * Function
    * Symbol

2. 3种对象类型

    * Object
    * Date
    * Array

3. 2个不包含任何值的数据类型

    * Null
    * Undefined

4. 注意

    * NaN的数据类型是Number
    * null的数据类型是Object
    * 可以通过constructor属性类判断`arr.constructor.toString().indexOf('Array') > -1`

5. 类型转化

    * 数字、日期、布尔 转字符串：

        1. String(eg)
        2. eg.toString()

    * 字符转数字：

        1. Number(eg)
        2. parseInt(eg)
        3. + 运算符

    * 布尔、日期 转数字：

        1. Number(eg)

    * 自动转换类型：

        1. 5 + null = 5
        2. '5' + null = '5null'
        3. '5' + 1 = '51'
        4. '5' - 1 = 4

### 2. 