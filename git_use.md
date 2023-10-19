## git操作简单来说其实就三步

1. git add xx
   
   把文件添加到暂存区
   
   * git add -A . 添加所有改变的文件 
   
   * git add . 添加新文件和编辑过的文件，但不包括删除的文件
   
   * git add -u 表示添加编辑和删除的文件，但不包括新添加的文件

2. git commit -m "注释"

3. git push origin master
   
   ![](C:\Users\hap1y\AppData\Roaming\marktext\images\2023-10-19-16-06-14-image.png)

## 其他操作

git status 可以查看状态

git reflog 可以查看版本号

git reset --hard xx 可以设置到某个版本

* git reset --hard HEAD^ 可以回退到上一个版本(几个^代表几个版本)

git restore -- xx 可以撤销对于xx文件的修改



## 参考

[Git——从 Git 中的仓库中删除文件 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/465863655)


