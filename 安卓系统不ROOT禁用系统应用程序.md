# 安卓系统不ROOT禁用系统应用程序



> 前期准备：
>
> * 打开手机开发者模式，打开USB调试
> * 电脑安装ABD工具，打开CMD，CD进入ABD目录，输入"abd shell" 即可进入

在shell界面，输入：

```shell
pm disable-user "包名"
# 包名查找方式：打开手机设置、应用、详情即可查看
```

