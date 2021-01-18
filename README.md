# easytrader
安装教程：
一、官网下载python

       官网地址：https://www.python.org/downloads/windows/

       python版本：python-3.7.3-amd64

二、安装python

        网上有教程，这个不累述了。

        记得建好环境变量。

三、检查python安装是否成功

        1、cmd

        2、pip list

        3、python

        4、print('hello python')

四、python正常后，安装EasyTrader需要的包

         1、cmd

         2、pip install pypiwin32

         3、pip install pywinauto

         4、pip install numpy

         5、pip install pandas

         6、pip install scikit-learn

         7、pip install pillow

         8、pip install scipy

         8、pip install pytesseract

五、以上包都安装成功后，安装EasyTrader

         9、pip install easytrader

六、修改自己证券账户的地址

       Python37\Lib\site-packages\easytrader\config\client.py
       
[![Package](https://img.shields.io/pypi/v/easytrader.svg)](https://pypi.python.org/pypi/easytrader)
[![Travis](https://img.shields.io/travis/shidenggui/easytrader.svg)](https://travis-ci.org/shidenggui/easytrader)
[![License](https://img.shields.io/github/license/shidenggui/easytrader.svg)](https://github.com/shidenggui/easytrader/blob/master/LICENSE)

* 进行自动的程序化股票交易
* 支持跟踪 `joinquant`, `ricequant` 的模拟交易
* 支持跟踪 雪球组合 调仓
* 支持通用的同花顺客户端模拟操作
* 实现自动登录
* 支持通过 webserver 远程操作客户端
* 支持命令行调用，方便其他语言适配
* 基于 Python3.6, Win。注: Linux 仅支持雪球


### 微信群以及公众号

欢迎大家扫码关注公众号「食灯鬼」，一起交流。进群可通过菜单加我好友，备注量化。

![公众号二维码](https://gitee.com/shidenggui/assets/raw/master/uPic/mp-qr.png)

若二维码因 Github 网络无法打开，请点击[公众号二维码](https://gitee.com/shidenggui/assets/raw/master/uPic/mp-qr.png)直接打开图片。

### Author

**easytrader** © [shidenggui](https://github.com/shidenggui), Released under the [MIT](./LICENSE) License.<br>

> Blog [@shidenggui](https://shidenggui.com) · Weibo [@食灯鬼](https://www.weibo.com/u/1651274491) · Twitter [@shidenggui](https://twitter.com/shidenggui)

### 相关

[获取新浪免费实时行情的类库: easyquotation](https://github.com/shidenggui/easyquotation)

[简单的股票量化交易框架 使用 easytrader 和 easyquotation](https://github.com/shidenggui/easyquant)


### 支持券商

* 海通客户端(海通网上交易系统独立委托)
* 华泰客户端(网上交易系统（专业版Ⅱ）)
* 国金客户端(全能行证券交易终端PC版)
* 其他券商通用同花顺客户端(需要手动登陆)


### 模拟交易

* 雪球组合 by @[haogefeifei](https://github.com/haogefeifei)（[说明](doc/xueqiu.md)）

### 使用文档

[中文文档](http://easytrader.readthedocs.io/zh/master/)


### 作者其他作品
* [大数据网络小说推荐系统 - 推书君](https://www.tuishujun.com)
* [中文独立个人博客导航 - bloghub.fun](https://bloghub.fun)
