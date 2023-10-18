##卸载

首先是卸载，很简单，和其他软件的卸载方式一样，只是有一点需要注意

把凭证管理器里的git凭据删除，因为你卸载git之后，如果以后再使用大概率会用新号，因此把这个旧号删掉才能用新号。

方法：

1.WIN+R,输入control打开控制面板

2.把控制面板的查看方式改为小图标(右上角附近)

3.在第三列的中间位置找到凭据管理器

4.在Windows凭据里找到git凭据删除

5.如果没有找到可以不删

可参考[git报错：remote: Access denied 拒绝访问 fatal: unable to access ‘ https:/ /gitee. cohe requested URL 403 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/412244884)

##安装

卸载完成后就可以安装新的git了，地址[Git - Downloads](https://git-scm.com/download)

淘宝的镜像[CNPM Binaries Mirror (npmmirror.com)](https://registry.npmmirror.com/binary.html?path=git-for-windows/)

安装也很简单，基本不需要改动什么，点next就行了。

安装完成后可以在cmd中使用"git --version"命令查看安装的git版本

##参考

[git 简明指南 (runoob.com)](https://www.runoob.com/manual/git-guide/)

[Git的安装与使用教程（超详细！！！）_git.exe安装教程-CSDN博客](http://t.csdnimg.cn/ZdaVN)

[Git安装与卸载_git卸载重装-CSDN博客](http://t.csdnimg.cn/hQagr)
