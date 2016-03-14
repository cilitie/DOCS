#关于Xcode的Injection插件的安装及使用

通过Alcatraz统筹管理（http://alcatraz.io/）

安装后重启Xcode，在Product菜单中多了两项（Injection Plugin、 Inject Source）

Product -> Injection Plugin -> Patch Project for Injection，插件会在main.m中插入一段代码 import进头文件

在原来正在运行的工程基础上保存文件，然后Ctl+= 不必重启即可直接测试运行效果

可以修改button的点击事件，ctl+= 运行injection更新，重新点击执行的为新的事件

可以调整实时运行参数。
