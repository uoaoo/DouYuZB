##学习使用github

* github的readme.md文件使用`markdown`语法编写
* git clone + 链接获取github项目
* Xcode提交上Github在菜单上Commit
* git c\

##获取App图片资源
* 使用PP助手下载ipa包
* 大部分资源放在Assets.car文件中
    * 方法一：在github上搜索cartool把Assets.car文件复制到其他文件夹，然后在cartool工程中点击Edit scheme，然后点击Arguments，然后在Arguments Passed on Launch中点+号，然后把Assets.car文件拖入形成目录，再点+号，把导出的目录也拖入进去
    * 方法二：使用iOS images Extractor解压Assets.car
##项目的基本设置
* 设置icon等
    *  删除Lauch Screen File中的内容
    *  点击Launch Images Source，选择Assent
