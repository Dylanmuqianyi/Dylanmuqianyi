### uni-trans/www-trans

<div align="center">
  <img alt="Baidu-trans Logo" width="120" height="120" src="./images/trans.png">
  <h1>Baidu-trans</h1>
  <span><a href="./README.EN.md">English</a> | 中文</span>
</div>

#### 介绍

```js
这是一个基于百度翻译自动化翻译的JavaScript程序;
```

#### 使用说明

```js
使用方法：
1. 注册百度翻译开发者账号，并获取appid和密钥
2. 配置好翻译对象和翻译文件路径，配置好想要翻译成什么语言，根据百度翻译文档配置好翻译文件格式，eg：it、en、zh
3. 在html文件中填写appid和key，并运行程序(vscode最好安装liveserver插件打开html文件)
4. 在浏览器中点击开始翻译下载
5. 翻译完成后会自动下载相应的目标翻译文件(js文件名 eg：en.js)
```

#### 简述

```js
自动读取en.js中想要翻译的字段，并自动生成对应的翻译文件
自动遍历翻译文件对象，批量翻译，自动下载
```

### 两种不同的文件格式的读取

```js
1. uni-trans 方式是模块化开发时，每个语言文件夹代表一种语言，里面是每一个模块的语言js文件
2. www-trans 方式是将所有的同一种语言的内容放在一个js文件里面，每个文件代表一种语言

```

### 翻译审查工具

```js
// diff.html
用于开发时检查两个翻译文件字段名是否存在纰漏;
```

### 百度翻译 api

1. [翻译 api](https://fanyi-api.baidu.com/api/trans/vip/translate)
2. [翻译文档](https://api.fanyi.baidu.com/doc/21)
3. [翻译 api 测试](https://fanyi-api.baidu.com/api/trans/product/index)

### 其他 api 推荐

[deepl 翻译 api](https://www.deepl.com/zh/products/api)

### 注意事项

- 亚洲国家为了翻译更加准确，使用中文去翻译
- 其他地区用英文翻译更加准确
