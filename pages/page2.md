### js中的数据类型

    5种简单数据类型：Undefined、Null、Boolean、Number、String
    1种复杂数据类型：Object

#### typeof操作符
    typeof('string') === 'string'
    typeof(1) === 'number'
    typeof(false) === 'boolean'
    typeof(undefined) === 'undefined'
    typeof(null) === 'object'
    typeof {} === 'object'
    typeof(() => {}) === 'function'
    typeof function(){} === 'function'

#### Undefined类型

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;只声明未初始化值的变量默认未undefined，对于尚未声明的变量只能执行typeof操作

    var a;
    console.log(a)                   // "undefined"
    console.log(typeof b)            // "undefined"
    console.log(b)                   // "Uncaught ReferenceError: b is not defined"

##### Number类型

* 八进制：第一位必须是0，然后是八进制数字序列（0～7）
* 十六进制：前两位必须是0x后跟任何十六进制数字（0～9，A～F）