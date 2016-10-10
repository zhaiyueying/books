
# 快捷键
`Ctrl+/ 或 Ctrl+Shift+/` 注释（// 或者/*…*/ ）
`Ctrl+X 或 Ctrl+Y` 删除一行
`Shift+F6` 重构-重命名
`Alt+~`vcs操作

​	`Alt+~ 7`关闭重启前的本地历史纪录

`Ctrl+E`最近打开的文件

`Ctrl+Shift+R`工程内查找文件名

`Ctrl+Alt+Shift+N`通过字符快速查找位置

`Ctrl+F`文件内查找

​	`Ctrl+K`查找下一个

​	`Ctrl+Shift+K`查找下一个
`选中文本，按Ctrl+Shift+F7` 高亮显示所有该文本，按Esc高亮消失。
`Ctrl+B或Ctrl+鼠标左键单击` 快速打开光标处的类或方法

双击`Shift`全局搜索

### 界面操作

`Ctrl+F4`关闭当前代码选项卡

`Alt+←/→`切换代码选项卡

`Alt+[0~9]`快速拆合功能界面模块

`Alt+Shift+F`将当前文件加入收藏夹
`Ctrl+F12`显示当前文件的结构

### 代码编辑

`Alt+Shift+↑`选中单词/选中当前块

`Alt+Insert`新建一个文件或其他

`Ctrl+Alt+L`/`Ctrl+Shift+F`格式化代码

`Shift+Enter`重新开始一行（无论光标在哪个位置）

### 导航

`Esc`进入代码编辑区域

`Alt+F1`查找代码在其他界面模块的位置，颇为有用

`Ctrl+G`查找引用

`Ctrl+L`撞到指定行

`Ctrl+]/[`光标到代码块的前面或后面

`Ctrl+Shift+up/down`上一个/下一个方法

### 编辑器

`Ctrl+Alt+S`打开配置窗口

`Ctrl+Shift+A`快速查找并使用编辑器所有功能

## 文件模版变量
- `${PACKAGE_NAME}` name of the package in which the new file is created
- `${USER}` current user system login name
- `${DATE}` current system date
- `${TIME}` current system time
- `${YEAR}` current year
- `${MONTH}` current month
- `${MONTH_NAME_SHORT}` first 3 letters of the current month name. Example: Jan, Feb, etc.
- `${MONTH_NAME_FULL}` full name of the current month. Example: January, February, etc.
- `${DAY}` current day of the month
- `${HOUR}` current hour
- `${MINUTE}`	current minute
- `${PROJECT_NAME}` the name of the current project

## 文件模版
```html
/**
 * ${NAME}
 * ${NOTE}
 * @Author: ${USER}
 * @Date: ${DATE}
 * @Time: ${TIME}
 * Created with JetBrains WebStorm.
 */
<script>
    import HeaderComponent from './components/header.vue'
    import OtherComponent from './components/other.vue'
    export default{
        name:'',
        props:[],
        data(){
            return{
                msg:'hello vue'
            }
        },
        components:{
            'other-component':OtherComponent,
            HeaderComponent,
        },
        watch:{},
        methods:{}
    }
</script>
<template>
    <div>
        <header-component/>
        <div>this is template body</div>
        <other-component/>
    </div>
</template>
<style>
    body{
        background-color:#ff0000;
    }
</style>
```


[webstorm11--常见配置](http://www.jianshu.com/p/10f5f0055715)
[IntelliJ IDEA 常用设置讲解](http://wiki.jikexueyuan.com/project/intellij-idea-tutorial/settings-introduce-1.html)



[1]:https://www.jetbrains.com/help/idea/2016.1/symbols.html
[2]:http://my.oschina.net/maomi/blog/137807
[3]:http://helloweb.wang/jingyan~jiqiao/491.html
[4]:http://velocity.apache.org/engine/devel/user-guide.html
