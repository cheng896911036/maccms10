## 苹果cms-v10  引用地址 https://github.com/magicblack/maccms10

苹果CMS程序是一套采用PHP+MYSQL环境下运行的完善而强大的快速建站系统。经过近多年的开发经验和技术积累，苹果CMS程序已逐步走向成熟，在易用性和功能上已经成为同行中的佼佼者。程序体积小->优化程序代码，运行速度快->高效的缓存处理，只要普通的虚拟主机就可以完美搭建起来，建站成本非常低。仿MVC模板分离，内置标签，自定义函数标签接口，强大的自定义采集功能，只要你会HTML就可以轻松做出个性化的网站。 程序易用性和功能上一直以来都积极采纳广大站长提出的各种好的建议，迅速响应各种紧急问题，我们的服务理念贯穿其中，保证每一位站长每一个环节都可以从容应对。v10采用tp5.x内核进行开发，扩展了模板处理引擎，将后台程序与html模板简单的分离出来，让设计人员与程序人员最大限度的发挥自己的优势而互不干扰，大大加快了项目有序、快速的完成。即使您是第一次接触，也会在最短的时间内熟练掌握它的使用方法。后台管理模块，一目了然，操作简单，绝对不会让您眼花缭乱。

Apple CMS program is a set of PHP and MYSQL environment operating in a perfect and powerful fast station system. After nearly years of development experience and technology accumulation, Apple CMS program has gradually matured, in ease of use and functionality has become the leader in peers. The program size is small - > optimizer code, running fast - > efficient caching processing, as long as the ordinary virtual host can be perfectly built, the cost of building a station is very low. Imitation MVC template separation, built-in tags, custom function label interface, powerful custom acquisition function, as long as you will HTML can easily make personalized website. Program ease of use and function has been actively adopted by the vast number of station director put forward a variety of good suggestions, quickly respond to a variety of urgent issues, our service concept throughout it, to ensure that every station director every link can be calmly coped with. v10 using the tp5.x kernel for development, extended the template processing engine, the background program and html template simple separation, so that designers and programmers to maximize their advantages without interference, greatly speed up the project orderly and fast completion. Even if you are in first contact, you will master how to use it in the shortest possible time. Back-office management module, at a glance, easy to operate, will never dazzle you.
## 免责声明

本程序仅供内部学习和交流使用，没有内置任何数据，请在遵守当地法律的前提下使用本站程序，对用户在使用过程中的自行维护的信息内容本站不负任何责任！

This program is for internal learning and communication use only, there is no built-in data, please comply with local laws under the premise of using the site program, the user in the process of self-maintenance of the information content of this site is not responsible!
## maccms10-tvbox-api  引用地址 https://github.com/feg545/maccms10-tvbox-api
TVBOX默认可以对接苹果CMS v10的接口，但是不支持过滤。 这个项目用来增加一个支持过滤的tvbox接口。

安装方法
下载Tvbox.php，上传到maccms10/application/api/controller/目录

浏览器地址栏访问：http://<maccms10地址>/api.php/tvbox 如果显示出json数据就表示安装成功。然后在TVBOX里面配置相应的接口即可。

主要功能：

只示一级分类
在分类上按遥控器OK键，弹出过滤窗口，添加了各种过滤功能
不过滤时可以设置默认过滤条件，在苹果CMS后台系统->网站参数->预留参数->自定义参数填写：
tvbox_default_year$$$2023
tvbox_default_area$$$中国
过滤功能展示
屏幕截图
