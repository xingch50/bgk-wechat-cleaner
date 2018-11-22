硬广植入：本人自己搭建了个git代码托管服务器，各位大佬可以在我的git服务器里建立免费的私有库，也可以作为备用代码储存点，毕竟github总是会出问题的，本git服务器架设在华为云的广州节点上，git代码托管地址如下：
http://gayhub.fun (ps.本人不是基佬)

---

# 项目简介
本项目是我使用了wxpy和调用了百度ai开发平台接口实现的微信文字图片审核系统





# 安装与使用方法

### 最简单的方法

1. 把wx.py文件下载下来，确保你的py环境装了python3.5以上
2. 打开命令行界面，运行python wx.py命令
3. 正常肯定会报错，因为大多数人会缺少一些py包，你看报错信息缺哪个包pip install哪个就是了
4. 之后你的命令行界面就会显示出二维码，用你的微信号扫码登陆即可，此时你的微信就会变成智能ai

### 注意事项

- 因为上面你们是直接用的我的源码，所以百度ai开放平台api用的是我自己的api key，而一些应用的api key只能每天有限定次数，所以我希望你们自己去申请自己的api key
- 由于腾讯政策，只有老微信号才能登陆网页微信，所以这只有老微信号号才能使用，新微信号无法使用这个服务


# 项目的功能和相关依赖介绍
- 微信控制： wxpy
- 审查检测： 百度ai开放平台
