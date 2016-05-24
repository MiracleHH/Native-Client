# 弹幕派 v1.3.0

![Logo](http://7xr64j.com1.z0.glb.clouddn.com//danmu/logo.png)

## 介绍

习惯了在Acfun、Bilibili等网站上看视频时发弹幕与他人一起分享、吐槽？无论是上课还是开会，不必死气沉沉，真正地让所有人都能参与到讨论中！弹幕派(Danmaku Pie)，为你的演示提供弹幕功能。

### 下载地址
[GitHub下载](https://github.com/Project-Danmu/Native-Client/releases)

[七牛云存储](http://7xr64j.com1.z0.glb.clouddn.com/danmu/release/Danmaku%20v1.3.0.zip)

[百度云](http://pan.baidu.com/s/1c17zLgk)

## 优点

* **为你的演示提供弹幕。**所有参与者现在都可以发表自己的意见，更可以用于提问环节。
* **提供自定义功能。**可以定义弹幕的字体样式、数量和滚动速度。
* **随时可以暂停。**你可以在正式演讲时暂停播放，然后在提问环节继续。
* **不需要任何提前准备。**只需要在微信平台注册，然后在客户端上登录，即可开始，不超过3分钟。
* **本地存储配置，无需安装。**您可以提前定义好弹幕的字体样式、滚动速度等参数，然后随身携带程序即可，无需安装。\*

	\* 需要 .net Framework 4.0 运行环境。

## 功能

* 弹幕功能
* 暂停与恢复
* 设置弹幕样式
* 将设置存储至本地
* 显示房间号
* 登录功能

## 使用说明

### 运行要求

需要 .net Framework 4.0 运行环境，在 Windows 8/8.1/10 上可以直接运行。Windows XP/Vista/7 用户请先安装 [.net Framework 4.0] (https://www.microsoft.com/zh-cn/download/details.aspx?id=17718)运行环境后运行。

### 登录

进入我们的[官方网站](http://danmu.zhengzi.me)进行注册和建立房间，在本地客户端使用您注册的账号和密码进行登录即可。听众们可以通过我们的公众号发送弹幕，您可以将鼠标指针放在`查看二维码`上显示二维码，用微信“扫一扫”功能扫描二维码进入我们的公众号。您还可以在官方网站上管理弹幕。

![登录界面](http://7xr64j.com1.z0.glb.clouddn.com/danmu/intro/Login.png)

### 使用

登录成功后，弹幕派即开始工作。您可以在托盘图标上点击右键选择`暂停`以暂停弹幕的滚动。双击托盘图标即可使其最小化至系统托盘处。点击`显示房间号`会在您的屏幕中央显示您注册的账号所在的房间号，屏幕上显示的弹幕即您当前所在房间里的弹幕，与会者通过在公众号中加入房间即可发送弹幕到屏幕上显示。
您还可以点击`通过弹幕显示房间号`和`显示公众号二维码`让您的听众进入您建立的房间。

![右键菜单](http://7xr64j.com1.z0.glb.clouddn.com/danmu/intro/Menu.png)

### 设置

目前提供的设置项有字体、颜色、大小、样式（加粗和倾斜）、屏幕上弹幕数量、弹幕获取速度以及弹幕滚动速度。您还可以将字体和颜色设置为随机。需要您注意的是，当您打开`设置`时，您需要重新设置弹幕颜色。
您的当前设置会保存到程序目录的`setting.ini`文件中，不推荐您改动`setting.ini`文件。如果在启动时程序提示`配置文件错误`，您可以删除`setting.ini`，在下一次启动时程序会自动以默认设置生成一个新的配置文件。

![设置界面](http://7xr64j.com1.z0.glb.clouddn.com/danmu/intro/setting.png)

## 版本说明

如果您在使用过程中遇到问题，欢迎反馈到 [thesharing@163.com](mailto:thesharing@163.com?subject=弹幕派意见反馈)。

### v 1.3.0 更新

* 对登录界面进行修改，现在登录时会有Loading图可以看了
* 删除了自动生成弹幕的“展示模式”的代码
* 优化了性能
* 降低了两条弹幕重合在一起的情况出现的概率
* 修改了设置界面

### v 1.2.1 更新

* 增加了新菜单项——“展示模式”
* 将房间号显示在弹幕中
* 在演示时显示二维码

### v 1.2.0 更新

* 增加多显示器支持
* 现在可以查看房间号了
* 增加全局快捷键
* 增加了帮助窗口，重新制作了关于窗口
* 重新制作Logo
* 修复了一个Bug
* 新增了IDisaposible接口以优化内存占用

### v 1.1.1 更新

* 新增弹幕随机字体颜色和随机字体样式功能
* 性能优化

### v 1.0.0 beta 更新

* 已经与Web-Client连接起来了~ 现在可以下载Release体验一下。扫描二维码，进入我们的公众号，用您的微信即可注册。

### 未完成部分

* 自动更新
* 日志
* 对话框
* 不文明语言过滤功能
* 调整弹幕位置
* 通过微信远程控制显示/隐藏
