# Typora简易教程

## 常用操作快捷键

``Ctrl + 0``到 ``Ctrl + 3``一级~四级标题

``Ctrl + B`` 加粗，**加粗**测试

``Ctrl + I`` 斜体，*斜体*测试

``Ctrl + U``下划线，<u>下划线</u>测试

``Shift + Alt +5``删除线，~~删除线~~测试

``Shift + Ctrl + Tab上边那个键 ``行内代码块，`行内代码块`测试

`Ctrl + K`超链接， [超链接](https://www.baidu.com)测试

`Ctrl + T`插入表格，支持拖拽移动，网页端表格转换

| 姓名 |  学号   | 成绩 |
| :--: | :-----: | :--: |
| 张三 | Java001 |  76  |
| 李四 | Java002 |  99  |

`Ctrl + Shift + Q` 引用：

> Maven项目对象模型(POM)，可以通过一小段描述信息来管理项目的构建，报告和文档的软件项目管理工具。

`Ctrl + Z` 返回上一步操作

`Tab` 调整缩进

`Ctrl + Shift + I` 图片

<img src="4175162_180626364155_2.jpg" style="zoom:100%;" />



## 部分配置需要自行在配置文件中开启

`Ctrl + Shift + M`公式块
$$
X^2 + Y^2 = Z^2
$$


**```**  代码块

```java

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```



无序列表

```
- 一级列表
Tab切换二级三级列表
Shift + Tab 切换回去
```

- Java基础
- 计算机基础知识
  - 操作系统
  - 数据结构与算法
  - 数据库
    - MySQL
    - Redis

有序列表

- 1. Java
  2. Python



多选框  \- [ ] 

- [x] tomcat
- [ ] servlet



注解功能：

```
[^1]与[^1]:
```

​	参考文献：

1. 创建独立的Spring[^1]应用程序

2. 嵌入的Tomcat[^2]，无需部署WAR文件

3. 简化Maven[^3]配置

4. 自动配置Spring
5. 提供生产就绪型功能，如指标，健康检查和外部配置

6. 绝对没有代码生成和对XML[^4]没有要求配置

[^1]: spring框架是由于软件开发的复杂性而创建的轻量级控制反转（IoC）和面向切面（AOP）的容器框架。
[^2]: Maven项目对象模型(POM)，可以通过一小段描述信息来管理项目的构建，报告和文档的软件项目管理工具。
[^3]: Tomcat 服务器是一个免费的开放源代码的Web 应用服务器，属于轻量级应用服务器。
[^4]:XML，中文为可扩展标记语言。



上标下标：

```
上标X^2^
下标H~2~O
```

X^2^

H~2~O



高亮：

```
==Javascipt==
```

==Javascipt==



注释：

```
<!--只会在本文档显示，不会在导出显示-->
```

<!--只会在本文档显示，不会在导出显示-->



分割线

```
---
```

---



指示上下文：

```
:up
```

:arrow_up:



目录生成

```
[toc]
```

[toc]

## Markdown 扩展功能

HTML 原生支持

Latex 公式支持

流程图支持： 内置Flowchart，Sequence，Mermaid引擎，支持多种流程图：时序图，甘特图，流程图



流程图(Flowchart) :point_right:代码块选择flow

```flow

```

流程图(Mermaid) :point_right:代码块选择Mermaid

```Mermaid

```

时序图(Sequence) :point_right:代码块选择Sequence

```sequence

```

甘特图(Mermaid)



## 主题更换

1. 文件​中打开偏好设置/外观/获取主题
2. 将下载的文件夹和css文件放入主题文件夹
3. 重启Typora







