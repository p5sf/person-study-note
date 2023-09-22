---
date: 2022-08-30
title: "IDEA基础配置"
category:
  - 后端开发
  - 工具
tag:
  - 后端开发
  - 工具
  - IDEA
---



## 一、基础配置

### 忽略大小写提示

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210424130821308.png?)

### 自动导入所有包

<img src="https://s2.loli.net/2022/04/16/XDchCIU1Py2biB4.png"/>



### 设置显示多行tabs

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210424130957697.png?)



### 设置默认字体、大小、行间距

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210424131219733.png?)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210424131523592.png?)

### 隐藏IDEA文件

> 可以避免IDEA默认的配置文件上传到Git上

<img src='https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162152466.png'>

### 忽略Git提交文件

> 在本地创建一个.gitignore

```
# IntelliJ project files
.idea
*.iml
out
gen

# compile
/target/
target/
.class
/dist

# logs
log/

# Mac 
.DS_Store
```



### 设置项目文件编码

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210424132808380.png?)

### 添加类注释

```java
/**
 * @author jitwxs
 * @date ${YEAR}年${MONTH}月${DAY}日 ${TIME}
 */
```

![图片](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162156438.webp)



### 启动idea不自动打开项目

![img](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162156115.png)

###  关闭Intellij IDEA自动更新

![关闭Intellij IDEA自动更新](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162156935.png)

### maven配置

![img](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157506.webp)





### 自动生成serialVersionUID

![Snipaste_2021-08-16_21-50-37.png](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157805.png)

![img](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157682.png)



### 目录定位

![idea目录定位](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157720.png)![目录定位](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157211.png)



快速定位当前文件在项目的位置

可以通过 `Alt + F1 + 1` 快捷键来定位当前文件所在 Project 组件窗口中的位置

![idea定位](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157657.png)

在编辑区域使用 Alt + F1 + 1 快捷键，效果如下

![idea定位一](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157806.png)

勾选`Autoscroll from Source`设置，可以使Project窗口自动定位到当前编辑区所打开的文件

![idea定位编辑区](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157202.png)





### 连接数据库

![1397676-20180914135750615-1050365771](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157769.png)

下载驱动并进一步配置

![](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157283.png)

填写数据库账户信息，用户名，Host填写为localhost，端口Port为3306，Password填写用户名对应的密码即可，Database可以填写想连接的数据库名，点击Test Connection按钮，如果显示成功Successful，说明连接成功

![](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162157404.png)



## 二、常用快捷键

默认快捷键方式：Windows 版本：IDEA 2021.1.3

#### 光标跳转

| 快捷键                   | 光标跳转                                        |
| ------------------------ | :---------------------------------------------- |
| Ctrl + G                 | 在当前文件跳转到指定行                          |
| Ctrl + End，Hoem         | 跳到文件头/尾                                   |
| Ctrl + [  Ctrl + ]       | 移动光标到当前所在代码的花括号开始位置/结束位置 |
| F3，Shfit+F3             | 在查找模式下，定位到下一个匹配处,上一个匹配处   |
| Ctrl + Delete            | 删除光标后面的单词或是中文句                    |
| CTRL + ALT +👈            | 返回上一次操作位置                              |
| CTRL +Shift +  Backspace | 退回到上一次修改的地方                          |

#### 文件操作

| 快捷键                     | 文件定位跳转                                       |
| -------------------------- | -------------------------------------------------- |
| 双击SHIFT                  | 在项⽬的所有⽬录查找⽂件                           |
| Ctrl + E                   | 显示最近打开的文件记录列表                         |
| ALT+SHIFT+C                | 查找最近项目操作的⽂件的变化                       |
| Ctrl + N、Ctrl + Shift + N | 根据名/类名查找类文件、通过文件名打开文件/目录     |
| Ctrl + F、Ctrl + Shift + F | 在当前文件进行文本查找、查找整个项目或指定目录内文 |
| Alt + 左方向键             | 按左方向切换当前已打开的文件视图                   |
| Ctrl+Tab                   | 切换标签页                                         |
| Ctrl + F4                  | 关闭当前编辑文件                                   |

#### 格式美化

| 快捷键                 | 代码格式美化                                              |
| ---------------------- | --------------------------------------------------------- |
| Ctrl + +/-             | 展开这行代码/折叠代码                                     |
| Ctrl + Shift +/-       | 展开所有代码/折叠所有代码                                 |
| Ctrl+Alt+=             | 递归展开代码                                              |
| Ctrl+Alt+L             | 格式化代码                                                |
| Ctrl+Alt+I             | 自动缩进行                                                |
| Ctrl + Shift + U       | 对选中的代码进行大/小写轮流转换                           |
| Ctrl+Alt+O、ALT+回⻋   | 优化import                                                |
| CTRL+SHIFT+SPACE       | ⾃动补全代码                                              |
| Alt + Shift + 后方向键 | 移动光标所在行的代码向下移动                              |
| Ctrl + D               | 复制光标所在行或复制选择内容,并把复制内容插入光标位置下面 |
| Ctrl + X，Ctrl + Y     | 剪切光标所在行或剪切复制选择内容                          |
| Ctrl + Delete          | 删除光标后面的单词或是中文句                              |
| Ctrl + Shift + V       | 弹出缓存的剪贴板                                          |
| CTRL +Shift + 👆👇：     | 光标放在方法上，移动方法                                  |
| Alt + Shift + I        | 查看项目当前文件                                          |

#### 窗口操作

| 快捷键   | 窗口菜单操作               |
| -------- | -------------------------- |
| ESC      | 从工具窗口进入代码文件窗口 |
| Alt + F1 | 弹出所有弹出层并进行选择   |
| F12      | 回到前一个工具窗口         |
| Alt + `  | 弹出版本控制菜单           |

#### 重构代码

| 快捷键           | 重构代码                                                    |
| ---------------- | ----------------------------------------------------------- |
| Shift + F6       | 重命名                                                      |
| Ctrl + H         | 显⽰当前类结构图                                            |
| Ctrl+Alt+T       | 将选中的代码使用if、while、try/catch等包装                  |
| Ctrl + Shift + T | 对当前类生成单元测试类                                      |
| Alt+Insert       | 在类上产生构造方法、getter/setter等方法，在目录上创建新文件 |
| Ctrl + O         | 选择可重写的方法                                            |
| Ctrl + I         | 选择可继承的方法                                            |
| Ctrl+Shift+F6    | 更改数据类型                                                |
| Ctrl + P         | 方法参数提示显示                                            |

#### 调试代码

| 快捷键              | 调试运行                           |
| ------------------- | ---------------------------------- |
| (ctrl)+Shift+F9/F10 | 选择 Debug/Run                     |
| (Ctrl)+Shift+F8     | 查看断点                           |
| (shift)+F7          | 步⼊                               |
| (shift)+alt+F8      | debug时选中查看值                  |
| Alt+Shift+F7        | 强制步⼊                           |
| Alt+F10             | 定位到断点                         |
| F9                  | 恢复程序                           |
| F2                  | 跳转到下一个高亮错误 或 警告位置   |
| Ctrl + F1           | 在光标所在的错误代码出显示错误信息 |
| Shift + F2          | 跳转到上一个高亮错误 或 警告位置   |

书签功能

1. F11 打标签
2. Shift + F11 弹出书签显示层
3. Ctrl + num 跳转到num
4. CTRL +Shift + num 打num 标签



## 三、常用插件

插件官网：https://plugins.jetbrains.com/

####  代码生成类

- Codota ——代码智能提示，显示方法的常见用法
- Lombok ——简化代码插件最新IDEA版本为DeLombok
- GenerateAllSetter ———一键生成Set和Get
- SequenceDiagram ——自动生成序列图插件
- MyBatisCodeHelperPro ——根据数据库表生成 Java entity、dao、mapper、service、controller 等代码
- Easy Code  根据数据库表生成 Java entity、dao、mapper、service、controller 等代码
- Convert YAML and Properties File Yml和Yaml文件互相转换
- .gitignore —— 生成不同语言的版本控制忽略文件
- Javadoc  快速生成 Javadoc 文档
- GsonFormatPlus：将`JSON`字符串自动转换成`Java`实体类。
- Properties to YAML Converter：将配置文件一键转换成YAML 文件

#### **代码规范类**

- Alibaba Java Code Guidelines ——阿里巴巴Java代码规范插件
- CheckStyle ——代码格式插件
- SonarLint ——优化代码
- FindBugs-IDEA  找出代码中潜藏的 Bug

####  **逼格插件类**

- Background Image Plus 设置代码背景图片
- Grep Console 自定义设置控制台输出颜色
- Material Theme UI 主题样式修改
- activate-power-mode 打字特效
- RainBow ——显示彩虹括号
- Code Screenshots：代码截图工具

####  **扩展增强类**

- Chinese Language Pack 翻译成中文
- Translation ——必备翻译插件
- Maven Helper ——项目依赖版本冲突查看
- JRebel ——代码热部署
- Mybatis Log Plugin SQL日志
- JUnitGenerator ——单元测试生成工具
- Gitee 码云插件
- Key Promoter X ——展示快捷键
- Statistic 代码统计
- CodeStream：协同代码

#### **前端插件**

- Vue.js ——开发Vue项目必备插件
- px2rem ------rem和px单位转换
- Vant ---自动补全Vant



热部署插件JRebel：https://www.cnblogs.com/flyrock/archive/2019/09/23/11574617.html

破解MyBatisCodeHelper-Pro插件https://zhile.io/2019/04/23/mybatis-code-helper-pro-crack.html

不能加载插件https://blog.csdn.net/chenchunlin526/article/details/85339082

关闭多余插件：https://blog.csdn.net/tutian2000/article/details/80074643

## 四、代码阅读

### 快速搜索URL接口

<img src='https://img-blog.csdnimg.cn/20210901111427623.jpg?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5Lqm56KO5rWB5bm0,size_20,color_FFFFFF,t_70,g_se,x_16'>

### 查看方法调用树

查看方法调用树： <kbd>Ctrl</kbd> +<kbd>Alt</kbd> + <kbd>H</kbd>

<img src='https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/97456064fe5847b4b4e257381795019c~tplv-k3u1fbpfcp-zoom-in-crop-mark:1304:0:0:0.awebp'>



### 查看类关系图

查看类关系图：<kbd>Shift</kbd> + <kbd>Ctrl</kbd> + <kbd>U </kbd>

<img src='https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/7cb5dd469234448099d416b1001c3232~tplv-k3u1fbpfcp-zoom-in-crop-mark:1304:0:0:0.awebp'>



### 查看类的继承树

查看类的继承树：<kbd>Ctrl</kbd> + <kbd>H</kbd> 

<img src='https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/1d12bc3221a84750be9856cfd5a84af1~tplv-k3u1fbpfcp-zoom-in-crop-mark:1304:0:0:0.awebp'>



### 查看类结构

<kbd>Altl</kbd> + <kbd>7</kbd> :显示当前类的所有成员方法、属性

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200430143327749.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM4MDM5NDM3,size_16,color_FFFFFF,t_70)



### 断点的使用



![Snipaste_2021-01-16_13-02-55.png](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201470.png)

| 图标 | 说明                                                         |
| ---- | ------------------------------------------------------------ |
| 1    | (Alt+F10)                                                    |
| 2    | (F8)步过日方,一行一行往下走,不会进入方法内部                 |
| 3    | (F7)步入.进入方法内部(不会进入官方类库的方法)                |
| 4    | (Alt+Shift+F7)强制步入,进入任何方法包括官方类库的方法        |
| 5    | Shift+F8)步出,从步入的方法内退出到方法调用处,此时方法已经执行完成,只是还没有完成赋值 |
| 6    | 回退断点，回退到上一次方法执行处                             |
| 7    | Alt+F9运行到光标处,可以将鼠标定位到查看的那一行,不需要重新打断点 |
| 8    | Alt+F8计算表达式 设置变量计算表达式和改变变量的值去调试各种情况 |

![Snipaste_2021-02-26_10-33-32.png](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201163.png)

![Snipaste_2021-02-26_10-31-32.png](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201927.png)

条件断点调试

![](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201059.png)

多线程断点调试

![](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201335.png)

![](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201441.png)

异常断点

添加异常类型（例如空指针异常，当出现空指针时，自动进入断点模式）

![img](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201707.png)

### 远程调试

不推荐线上调试，一般测试时调试

IDEA中的远程管理工具SSH使用．配置远程终端的地址和密码.然后选择Tools ->Start SSH Session 即可启动远程终端、

1）远程连接

![Snipaste_2021-01-16_00-23-08.png](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201959.png)

![Snipaste_2021-01-16_23-12-43.png](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201492.png)

远程调试

![Snipaste_2021-01-17_23-56-46.png](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201259.png)

注意要保持JVM通信

![Snipaste_2021-01-16_00-33-24.png](https://java-note-pic.oss-cn-beijing.aliyuncs.com/java/202204162201665.png)

```shell
JAVA_OPTS="$JAVA_OPTS -agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=5005"
```

用于远程debug的代码必须与远程部署的代码完全一致，不能发生任何的修改，否则打上的断点将无法命中，另外5005端口放行。


