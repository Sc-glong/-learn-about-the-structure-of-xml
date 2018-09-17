  # 1. 初识xml
    学习记录。
  ## 1.1 什么是可扩展标记语言
   * 旨在传输数据，而不是显示数据
   * 标签没有预定义，需要自定义标签
   * 自我描述性
  ## 1.2 可扩展标记语言和超文本标记语言的区别
   * 可扩展标记语言传输数据，焦点是传输和存储数据，而超文本标记语言显示数据，焦点是数据的展示。
   * 可扩展标记语言是对超文本标记语言的的补充。
  ## 1.3 用途广泛
    xml是各种应用程序之间传输数据的常用的工具。
  ## 语法
 ``` <?xml version="1.0" encoding="UTF-8"?>
<recipe type="dessert">
<recipename cuisine="american" servings="1">Ice Cream Sundae</recipename>
<ingredlist>
<listitem><quantity units="cups">0.5</quantity>
<itemdescription>vanilla ice cream</itemdescription></listitem>
<listitem><quantity units="tablespoons">3</quantity>
<itemdescription>chocolate syrup or chocolate fudge</itemdescription></listitem>
<listitem><quantity units="tablespoons">1</quantity>
<itemdescription>nuts</itemdescription></listitem>
<listitem><quantity units="each">1</quantity>
<itemdescription>cherry</itemdescription></listitem>
</ingredlist>
<variations>
<option>Replace nuts with raisins.</option>
<option>Use chocolate ice cream instead of vanilla ice cream.</option>
</variations>
<preptime>5 minutes</preptime>
</recipe>
```
