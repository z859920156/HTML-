# HTML5语法与基础标签
## 一、认识HTML5骨架
### 1.认识HTML5骨架结构
![1](https://user-images.githubusercontent.com/97715724/153823341-eb487412-3d16-4037-b0b1-232cf0b8d8ab.jpg)

### 1-1.文档类型声明DTD
- HTML文件第一行必须是DTD（Document Type Definition ,文档类型声明）
- 不写DTD会引发浏览器的一些兼容问题。
- 不同版本的HTML有不同的DTD写法.
![2](https://user-images.githubusercontent.com/97715724/153823892-7fda3d10-1529-4898-aeea-6ff98346562e.png)

### 1-2.W3C(万维网联合会）
- **W3C(万维网联合会)是万维网的主要国际标准组织，负责制定web标准，主要是HTML和CSS。

### 2.认识<html></html>标签对
![2](https://user-images.githubusercontent.com/97715724/153823757-da032c1d-9268-4392-8a2c-785501ec0168.jpg)
![3](https://user-images.githubusercontent.com/97715724/153823789-1e229b17-2692-489e-8248-3e559c987894.JPG)

### 3.认识字符集
#### 3-1.字符集出现的位置
![3](https://user-images.githubusercontent.com/97715724/153825616-befd2ea1-d256-47f0-adbc-eea2306fa392.PNG)
![Snipaste_2022-02-14_16-22-04](https://user-images.githubusercontent.com/97715724/153826464-1735c736-293a-4536-9f99-035c0b4cdacf.jpg)
#### 3-2.字符集的区别(UTF-8和gb2312)
![4](https://user-images.githubusercontent.com/97715724/153826763-280bfdb8-4f6e-4185-aa6a-c51f46352be4.PNG)
- 无论使用哪种字符集，一定要在vscode编译器中将文件也设置为相同字符集，否则会出现乱码，然后更改meta属性。
- gbk占用的内存少，推荐使用如果只有英文和中文，但不支持live server插件

### 4.title、关键词及页面描述
#### 4-1.title设置出现的位置
#### 4-2.title的用途
- title标签用来设置网页的标题，文字会显示在浏览器的标签栏上。
#### 4-3.网页关键词和页面的描述
- 合理设置网页的网页的关键词和页面描述,也是SEO的重要手段
- **SEO(Search Engine Optimization,搜索引擎优化)** 利用搜索引擎的规则提高网站在有关搜索引擎内的自然排名,让网站在搜索引擎的结果中内占据领先地位,获得品牌收益
- 使用meta标签设置网页关键词和描述,name属性非常关键,用来设置meta的具体功能 **（Keywords关键词   content内容 Description页面描述）**
![6](https://user-images.githubusercontent.com/97715724/153862051-5bc52d70-bb26-4b61-b8cc-4d084980fd18.PNG)
## 二、认识标签
### 1.什么是标签
- HTML叫做“超文本标记语言”，超文本标记语言就是标签，这些标签有不同的功能
#### 1-1.标签对
- 标签通常成对出现，称作标签对，不同的标签可以给文字设置不同的“语义”
![4](https://user-images.githubusercontent.com/97715724/153862168-097c2d82-557d-4c69-99db-03b593e9bff2.JPG)
#### 1-2.单标签
- 有的标签不是成对儿的,而是只有起始标签,称为单标签
![5](https://user-images.githubusercontent.com/97715724/153862267-c3669d73-597e-4e07-9591-d281dcb0143a.JPG)
- **在HTML4代，单标签必须写一个结尾的反斜杠，HTML5中不需要写反斜杠**
![6](https://user-images.githubusercontent.com/97715724/153862333-e5e43545-9f63-4d67-bfd3-c645e4dfee2a.JPG)
### 2.标题和段落标签
#### 2-1 h系列标题标签
- h系列标签表示“标题”语义,**h是 headline的意思**
![7](https://user-images.githubusercontent.com/97715724/153862431-b71e493c-6025-4e81-be73-be67bdb86446.JPG)
- 搜索引擎非常看重<h1</h1>标签的内容,应该将重点内容放到< h1 >标签中,比如网页的logo等
- h1标签一般只能放置一个,否则会被搜索引擎视为作弊,但实际开发中,也会出现多个h1标签的情况,只是不推荐


