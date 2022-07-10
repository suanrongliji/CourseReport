<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript & TypeScript 学习总结</title>
</head>

<body>
    <h1>JavaScript & TypeScript 学习总结</h1>
    <h2>简介</h2>
    <div>
        JavaScript是目前web开发中不可缺少的脚本语言，js不需要编译即可运行，运行在客户端，需要通过浏览器来解析执行JavaScript代码。
    </div>
    <h3>js组成部分</h3>
    <ul>
        <li>（1）核心（ECMAScript）：这一部分主要是js的基本语法。</li>
        <li>（2）BOM：Brower Object Model（浏览器对象模型），主要是获取浏览器信息或操作浏览器的，例如：浏览器的前进与后退、浏览器弹出提示框、浏览器地址栏输入网址跳转等操作等。</li>
        <li>（3）DOM：Document Object
            Model（文档对象模型），此处的文档暂且理解为html，html加载到浏览器的内存中，可以使用js的DOM技术对内存中的html节点进行修改，用户从浏览器看到的是js动态修改后的页面。（增删改查）</li>
    </ul>
    <h2>作用</h2>
    <div>
        JavaScript 被用来改进设计、验证表单、检测浏览器、创建cookies，等等。JavaScript 是因特网上最流行的脚本语言，并且可在所有主要的浏览器中运行，比如：Internet
        Explorer、Maxthon、Mozilla、Firefox、Netscape、Chrome和 Opera等。
    </div>
    <h3>数据类型</h3>
    <ul>
        <li>数值型：number（凡是数字都是数值型，不区分整数和小数）</li>
        <li>字符串：string（凡是引号包裹起来的内容全部都是字符串）</li>
        <li>布尔：boolean（true、false）</li>
        <li>对象类型：object（特殊取值null）</li>
        <li>未定义型：undefined</li>
    </ul>
    <div>
        js是弱类型语言，不重视类型的定义，但js会根据为变量赋值的情况自定判断该变量是何种类型
    </div>
    <h3>关系运算符</h3>
    <div>
        >		>=		<		<=  	!=		
        ==	等于（只比较内容）	===	恒等于（比较内容的同时还要比较数据类型）
        注意：关系运算符返回的结果只有两个：true / false
    </div>
    <h3>逻辑运算符</h3>
    <div>
        &&	 	与		true&&false		====>false<br>
        || 		或		true||false			====>true<br>
        ！ 		非		!true				====>false<br>
        false（理解）：false,  0,  null,  undefined <br>
        true（理解）：true, 非0,  非null,  非undefined<br>
    </div>
    <h3>分支语句</h3>
    <div>
        if,switch和Java中的一样
    </div>
    <h3>循环结构</h3>
    <div>
        while(循环条件){循环体;}<br>
        do{循环体;}while(循环条件);<br>
        for(循环变量赋初值；循环条件；循环变量增值){循环语句;}<br>
    </div>
    <h3>自定义函数</h3>
    <div>
        函数是命名的独立的语句段，这个语句段可以被当作一个整体来引用和执行：<br>
        function 函数名(形式参数){函数体}<br>
        调用函数：函数名(实际参数);<br>
    </div>
</body>

</html>
