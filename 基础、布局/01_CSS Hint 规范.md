- CSS开发规范
  1、不要使用多个class选择元素,如：a.foo.boo,这个在ie6以下是不能正确解析的
  2、移除空的css规则，如：a{}
  3、正确使用显示属性,如：display:inline不要和width,height,float,margin,padding同时使用，因为使用也无效，display:inline-block不要和float同时使用
  4、避免过多的浮动，当浮动次数超过十次时，会显示警告
  5、避免使用过多的字号，当字号声明超过十种时，显示警告
  6、避免使用过多的web字体，当超过5次时，显示警告
  7、避免使用 id 作为样式选择器
  8、标题元素只定义一次
  9、使用 width:100% 时要小心
  10、属性值为0时不要写单位，如：border:0;
  11、各浏览器专属的css属性要有规范，如：.foot{-moz-border-radius:5px;border-radius:5px}
  12、避免使用看起来像正则表达式的CSS3选择器
  13、遵守盒模型规则
  14、尽量不使用!important,通过添加和使用类名，如.hidden