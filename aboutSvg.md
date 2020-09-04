##### 什么是SVG

- 可缩放矢量图形，是一个[W3C](https://baike.baidu.com/item/W3C)的推荐标准
- 基于XML语言、完全支持DOM，采用文本来描述矢量图形

##### SVG的优点

- SVG 图像可被搜索、索引、脚本化或压缩
- 具有跨平台性和可扩展性，具有交互性和动态性
- SVG图像可在任何的分辨率下被高质量地打印，换句话说，SVG图像质量不因缩放而下降
- 文本传输，尺寸小、速度快

##### Java中使用Batik库对SVG的操纵

###### Batik简介

官网地址：https://xmlgraphics.apache.org/batik/

官网简介：
```
Batik is a Java-based toolkit for applications or applets that want to use images in the Scalable Vector Graphics (SVG) format for various purposes, such as display, generation or manipulation.

The project’s ambition is to give developers a set of core modules that can be used together or individually to support specific SVG solutions. Examples of modules are the SVG Parser, the SVG Generator and the SVG DOM. Another ambition for the Batik project is to make it highly extensible —for example, Batik allows the developer to handle custom SVG elements. Even though the goal of the project is to provide a set of core modules, one of the deliverables is a full fledged SVG browser implementation which validates the various modules and their inter-operability.
```
百度百科：

Batik是使用[svg](https://baike.baidu.com/item/svg)格式图片来实现各种功能的应用程序以及Applet提供的一个基于java的工具包。

通过Batik,你可以在[JAVA](https://baike.baidu.com/item/JAVA)可以使用的地方操作[SVG](https://baike.baidu.com/item/SVG)文档，您还可以在你的应用程序使用Batik模块来生成 ， 处理和[转码](https://baike.baidu.com/item/转码)SVG图像。Batik很容易让基于Java的应用程序或小程序来处理SVG内容。

###### Batik能做些什么

- 查看SVG文件内容
- 转换SVG图像为光栅图(比如JPEG、PNG等)
- 生成SVG文件内容

