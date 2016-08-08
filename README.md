## JSHint 配置项说明
<p>JSHint是一个javascript代码分析检测工具，不仅可以帮助我们检测到js代码错误和潜在问题，也能帮助我们规范代码开发。</p>

{
  /*
   * 是否阻止位运算符的使用 位运算符在js中用的比较少 默认为true
   */
  "bitwise" : true,
  /*
   * 是否要求变量都使用驼峰命名 
   */
  "camelcase": false,
  /* 
   * 是否要求 for/while/if 带花括号
   */
  "curly": true,
  /*
   是否强制使用严格等号
   */
  "eqeqeq": false,
  /*
   for-in 语句是否要求过滤原型链上的对象
   */
   "forin": true,
  /*
   是否要求以strict 模式检查，该选项要求文件有 "use strict"
   */
   "strict": false,
   /*
    是否阻止修改或扩展基本对象(Array,Date)等的原型链
    */
   "freeze": true,
   /*
    是否要求自执行的方法使用括号括起
    */
    "immed": true,
    /*
     指定缩进大小为2个空格
     */
    "indent": 2,
    /*
     要求变量在使用前声明
     */
     "latedef": true,
   /*
    要求构造函数大写
    */
    "newcap": true,
    /*
     不允许使用 arguments.callee 和 arguments.caller
    */
    "noarg": true,
    /*
     不允许空的代码块，默认关闭
    */
    "noempty": false,
    /*
     阻止直接使用new 调用构造函数的语句(不赋值对象)
     // ok
     var a = new Animal();
     // wain
     new Animal();
    */
    "nonew": true,
    /*
     提示未定义的变量
     */
    "undef": true,
    /*
     对代码中使用的 debugger 语句默认给出警告
     */
     "debug": true,
     /* 
      提示未使用的变量
      */
      "unused": true
}