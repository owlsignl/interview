# interview
1.Doctype作用？严格模式与混杂模式如何区分？它们有何意义?
答：Doctype作用：Doctype告诉浏览器解析器以哪种文档模式解析这个文档，主要影响CSS内容的呈现，在某些情况下会影响到javascript的解释执行。
区分：严格模式也称标准模式，是指浏览器按照W3C标准解析代码，混杂模式是浏览器用自己的方式解析代码。浏览器使用哪种模式与网页中的DTD直接相关。如果文档包含严格的DOCTYPE，以严格模式执行，url多以strict.dtd结尾。包含过渡DTD和URI的DOCTYPE，也以严格模式呈现，没有URL的DTD以混杂模式呈现。没有DTD或格式不正确的按照混杂模式呈现。
意义：标准模式是以该浏览器支持的最高标准解析网页，开发者能够使用最新的标准，混杂模式模拟老式浏览器的行为以防止站点无法工作。
2.html5为什么只需要写<!Doctype html>?
答：html5不是基于SGML的，不需要对DTD进行引用，但是需要Doctype来规范浏览器行为。HTML4.0.1是基于SGML，需要引用SGML来告知浏览器该文档的文档类型。
3.行内元素有哪些？块级元素有哪些？ 空(void)元素有那些？
4.页面导入样式时，使用link和@import有什么区别？
5.介绍一下你对浏览器内核的理解？
6.常见的浏览器内核有哪些？
7.html5有哪些新特性、移除了那些元素？如何处理HTML5新标签的浏览器兼容问题？如何区分 HTML 和 HTML5？
8.简述一下你对HTML语义化的理解？
9.HTML5的离线储存怎么使用，工作原理能不能解释一下？
10.浏览器是怎么对HTML5的离线储存资源进行管理和加载的呢？
11.请描述一下 cookies，sessionStorage 和 localStorage 的区别？
12.iframe有那些缺点？
13.Label的作用是什么？是怎么用的？（加 for 或 包裹）
14.HTML5的form如何关闭自动完成功能？
15.如何实现浏览器内多个标签页之间的通信? (阿里)
16.webSocket如何兼容低浏览器？(阿里)
17.页面可见性（Page Visibility）API 可以有哪些用途？
18.如何在页面上实现一个圆形的可点击区域？
19.实现不使用 border 画出1px高的线，在不同浏览器的Quirksmode和CSSCompat模式下都能保持同一效果
20.网页验证码是干嘛的，是为了解决什么安全问题？
21.tite与h1的区别、b与strong的区别、i与em的区别？
22.介绍一下标准的CSS的盒子模型？与低版本IE的盒子模型有什么不同的？
23.CSS选择符有哪些？哪些属性可以继承？
24.CSS优先级算法如何计算？
25.CSS3新增伪类有那些？
26.如何居中div？如何居中一个浮动元素？如何让绝对定位的div居中？
27.display有哪些值？说明他们的作用。
28.position的值relative和absolute定位原点是？
29.CSS3有哪些新特性？
30.请解释一下CSS3的Flexbox（弹性盒布局模型）,以及适用场景？
31.用纯CSS创建一个三角形的原理是什么？
32.一个满屏 品 字布局 如何设计?
33.常见兼容性问题？
34.li与li之间有看不见的空白间隔是什么原因引起的？有什么解决办法？
35.经常遇到的浏览器的兼容性有哪些？原因，解决方法是什么，常用hack的技巧 ？
36.为什么要初始化CSS样式。
37.absolute的containing block计算方式跟正常流有什么不同？
38.CSS里的visibility属性有个collapse属性值是干嘛用的？在不同浏览器下以后什么区别？
39.position跟display、margin collapse、overflow、float这些特性相互叠加后会怎么样？
40.对BFC规范(块级格式化上下文：block formatting context)的理解？
41.CSS权重优先级是如何计算的？
42.请解释一下为什么会出现浮动和什么时候需要清除浮动？清除浮动的方式。
43.移动端的布局用过媒体查询吗？
44.使用 CSS 预处理器吗？喜欢那个？
45.CSS优化、提高性能的方法有哪些？
46.浏览器是怎样解析CSS选择器的？
47.在网页中的应该使用奇数还是偶数的字体？为什么呢？
48.margin和padding分别适合什么场景使用？
49.抽离样式模块怎么写，说出思路，有无实践经验？[阿里航旅的面试题]
50.元素竖向的百分比设定是相对于容器的高度吗？
51.全屏滚动的原理是什么？用到了CSS的那些属性？
52.什么是响应式设计？响应式设计的基本原理是什么？如何兼容低版本的IE？
53.视差滚动效果，如何给每页做不同的动画？（回到顶部，向下滑动要再次出现，和只出现一次分别怎么做？）
54.::before 和 :after中双冒号和单冒号 有什么区别？解释一下这2个伪元素的作用。
55.如何修改chrome记住密码后自动填充表单的黄色背景 ？
56.你对line-height是如何理解的？
57.设置元素浮动后，该元素的display值是多少？（自动变成display:block）
58.怎么让Chrome支持小于12px 的文字？
59.让页面里的字体变清晰，变细用CSS怎么做？（-webkit-font-smoothing: antialiased;）
60.font-style属性可以让它赋值为“oblique” oblique是什么意思？
61.position:fixed;在android下无效怎么处理？
62.如果需要手动写动画，你认为最小时间间隔是多久，为什么？（阿里）
63.display:inline-block 什么时候会显示间隙？(携程)
64.overflow: scroll时不能平滑滚动的问题怎么处理？
65.有一个高度自适应的div，里面有两个div，一个高度100px，希望另一个填满剩下的高度。
66.png、jpg、gif 这些图片格式解释一下，分别什么时候用。有没有了解过webp？
67.什么是Cookie 隔离？（或者说：请求资源的时候不要让它带cookie怎么做）
68.style标签写在body后与body前有什么区别？
Js	
69.介绍JavaScript的基本数据类型。
70.说说写JavaScript的基本规范？
71.JavaScript原型，原型链 ? 有什么特点？
72.avaScript有几种类型的值？（堆：原始数据类型和 栈：引用数据类型），你能画一下他们的内存图吗？
73.Javascript如何实现继承？
74.Javascript创建对象的几种方式？
75.Javascript作用链域?
76.谈谈This对象的理解。
77.eval是做什么的？
78.什么是window对象? 什么是document对象?
79.null，undefined的区别？
80.写一个通用的事件侦听器函数(机试题)。
81.[“1”, “2”, “3”].map(parseInt) 答案是多少？
82.关于事件，IE与火狐的事件机制有什么区别？ 如何阻止冒泡？
83.什么是闭包（closure），为什么要用它？
84.javascript 代码中的”use strict”;是什么意思 ? 使用它区别是什么？
85.如何判断一个对象是否属于某个类？
86.new操作符具体干了什么呢?
87.用原生JavaScript的实现过什么功能吗？
88.Javascript中，有一个函数，执行时对象查找时，永远不会去查找原型，这个函数是？
89.对JSON的了解？
90.[].forEach.call($$("*"),function(a){ a.style.outline="1px solid #"+(~~(Math.random()*(1<<24))).toString(16) }) 能解释一下这段代码的意思吗？
91.js延迟加载的方式有哪些？
92.Ajax 是什么? 如何创建一个Ajax？
93.同步和异步的区别?
94.如何解决跨域问题?
95.页面编码和被请求的资源编码如果不一致如何处理？
96.模块化开发怎么做？
97.AMD（Modules/Asynchronous-Definition）、CMD（Common Module Definition）规范区别？
98.requireJS的核心原理是什么？（如何动态加载的？如何避免多次加载的？如何 缓存的？）
99.让你自己设计实现一个requireJS，你会怎么做？
100.谈一谈你对ECMAScript6的了解？
101.ECMAScript6 怎么写class么，为什么会出现class这种东西?
102.异步加载的方式有哪些？
103.documen.write和 innerHTML的区别?
104.DOM操作——怎样添加、移除、移动、复制、创建和查找节点?
105..call() 和 .apply() 的含义和区别？
106.数组和对象有哪些原生方法，列举一下？
107.JS 怎么实现一个类。怎么实例化这个类
108.JavaScript中的作用域与变量声明提升？
109.如何编写高性能的Javascript？
110.那些操作会造成内存泄漏？
111.JQuery的源码看过吗？能不能简单概况一下它的实现原理？
112.jQuery.fn的init方法返回的this指的是什么对象？为什么要返回this？
113.jquery中如何将数组转化为json字符串，然后再转化回来？
114.jQuery 的属性拷贝(extend)的实现原理是什么，如何实现深拷贝？
115.jquery.extend 与 jquery.fn.extend的区别？
116.jQuery 的队列是如何实现的？队列可以用在哪些地方？
117.谈一下Jquery中的bind(),live(),delegate(),on()的区别？
118.JQuery一个对象可以同时绑定多个事件，这是如何实现的？
119.是否知道自定义事件。jQuery里的fire函数是什么意思，什么时候用？
120.jQuery 是通过哪个方法和 Sizzle 选择器结合的？（jQuery.fn.find()进入Sizzle）
121.针对 jQuery性能的优化方法？
122.Jquery与jQuery UI有啥区别？
123.jquery 中如何将数组转化为json字符串，然后再转化回来？
124.jQuery和Zepto的区别？各自的使用场景？
125.针对 jQuery 的优化方法？
126.Zepto的点透问题如何解决？
127.jQueryUI如何自定义组件?
128.需求：实现一个页面操作不会整页刷新的网站，并且能在浏览器前进、后退时正确响应。给出你的技术实现方案？
129.如何判断当前脚本运行在浏览器还是node环境中？（阿里）
130.移动端最小触控区域是多大？
131.jQuery 的 slideUp动画 ，如果目标元素是被外部事件驱动, 当鼠标快速地连续触发外部元素事件, 动画会滞后的反复执行，该如何处理呢?
132.把 Script 标签 放在页面的最底部的body封闭之前 和封闭之后有什么区别？浏览器会如何解析它们？
133.移动端的点击事件的有延迟，时间是多久，为什么会有？ 怎么解决这个延时？（click 有 300ms 延迟,为了实现safari的双击事件的设计，浏览器要知道你是不是要双击操作。）
134.知道各种JS框架(Angular, Backbone, Ember, React, Meteor, Knockout…)么? 能讲出他们各自的优点和缺点么?
135.Underscore 对哪些 JS 原生对象进行了扩展以及提供了哪些好用的函数方法？
136.解释JavaScript中的作用域与变量声明提升？
137.那些操作会造成内存泄漏？
138.Node.js的适用场景？
139.(如果会用node)知道route, middleware, cluster, nodemon, pm2, server-side rendering么?
140.什么是“前端路由”?什么时候适合使用“前端路由”? “前端路由”有哪些优点和缺点?
141.知道什么是webkit么? 知道怎么用浏览器的各种工具来调试和debug代码么?
142.如何测试前端代码么? 知道BDD, TDD, Unit Test么? 知道怎么测试你的前端工程么(mocha, sinon, jasmin, qUnit..)?
143.前端templating(Mustache, underscore, handlebars)是干嘛的, 怎么用?
144.简述一下 Handlebars 的基本用法？
145.简述一下 Handlerbars 的对模板的基本处理流程， 如何编译的？如何缓存的？
146.用js实现千位分隔符?(来源：前端农民工，提示：正则+replace)
147.检测浏览器版本版本有哪些方式？
148.我们给一个dom同时绑定两个点击事件，一个用捕获，一个用冒泡，你来说下会执行几次事件，然后会先执行冒泡还是捕获
149.你遇到过比较难的技术问题是？你是如何解决的？
150.设计模式 知道什么是singleton, factory, strategy, decrator么?
151.常使用的库有哪些？常用的前端开发工具？开发过什么应用或组件？
152.页面重构怎么操作？
153.列举IE与其他浏览器不一样的特性？
154.99%的网站都需要被重构是那本书上写的？
155.什么叫优雅降级和渐进增强？
156.是否了解公钥加密和私钥加密。
157.WEB应用从服务器主动推送Data到客户端有那些方式？
158.对Node的优点和缺点提出了自己的看法？
159.你有用过哪些前端性能优化的方法？
160.http状态码有那些？分别代表是什么意思？
161.一个页面从输入 URL 到页面加载显示完成，这个过程中都发生了什么？（流程说的越详细越好）
162.部分地区用户反应网站很卡，请问有哪些可能性的原因，以及解决方法？
163.从打开app到刷新出内容，整个过程中都发生了什么，如果感觉慢，怎么定位问题，怎么解决?
164.除了前端以外还了解什么其它技术么？你最最厉害的技能是什么？
165.你用的得心应手用的熟练地编辑器&开发环境是什么样子？
166.对前端界面工程师这个职位是怎么样理解的？它的前景会怎么样？
167.你怎么看待Web App 、hybrid App、Native App？
168.你移动端前端开发的理解？（和 Web 前端开发的主要区别是什么？）
169.平时如何管理你的项目？
170.说说最近最流行的一些东西吧？常去哪些网站？
171.如何设计突发大规模并发架构？
172.是否了解开源的工具 bower、npm、yeoman、grunt、gulp，一个 npm 的包里的 package.json 具备的必要的字段都有哪些？（名称、版本号，依赖）
173.每个模块的代码结构都应该比较简单，且每个模块之间的关系也应该非常清晰，随着功能和迭代次数越来越多，你会如何去保持这个状态的？
174.Git知道branch, diff, merge么?
175.知道什么是SEO并且怎么优化么? 知道各种meta data的含义么?
176.移动端（Android IOS）怎么做好用户体验?
177.简单描述一下你做过的移动APP项目研发流程？
178.你认为怎样才是全端工程师（Full Stack developer）？
179.
180.你有自己的技术博客吗，用了哪些技术？
181.对前端安全有什么看法？
182.是否了解Web注入攻击，说下原理，最常见的两种攻击（XSS 和 CSRF）了解到什么程度
183.最近在学什么？能谈谈你未来3，5年给自己的规划吗？
184.
