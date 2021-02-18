<div align="center">
   <img width="160" src="doc/mirai.png" alt="logo"></br>

   <img width="95" src="doc/mirai.svg" alt="title">

----

mirai 是一个在全平台下运行，提供 QQ Android 协议支持的高效率机器人库

这个项目的名字来源于
<p><a href = "http://www.kyotoanimation.co.jp/">京都动画</a>作品<a href = "https://zh.moegirl.org.cn/zh-hans/%E5%A2%83%E7%95%8C%E7%9A%84%E5%BD%BC%E6%96%B9">《境界的彼方》</a>的<a href = "https://zh.moegirl.org.cn/zh-hans/%E6%A0%97%E5%B1%B1%E6%9C%AA%E6%9D%A5">栗山未来(Kuriyama <b>mirai</b>)</a></p>
<p><a href = "https://www.crypton.co.jp/">CRYPTON</a>以<a href = "https://www.crypton.co.jp/miku_eng">初音未来</a>为代表的创作与活动<a href = "https://magicalmirai.com/2019/index_en.html">(Magical <b>mirai</b>)</a></p>
图标以及形象由画师<a href = "https://github.com/DazeCake">DazeCake</a>绘制
</div>

# mirai-setu

一个使用[loliconAPI](https://api.lolicon.app/#/setu) 的[mirai-console](https://github.com/mamoe/mirai-console) 的色图插件

# 声明
本插件为开发学习用，请勿用于非法用途。部分搜索的图片可能会引发不适，甚至导致账号封禁以及群封禁，请谨慎使用。作者本人不承担任何责任。

本插件遵循mirai软件AGPLv3协议开源，不参与一切商业活动。

由于作者学业压力较大，不能保证插件的及时更新以及bug修复。

## 使用说明
1. 环境配置
   - 插件兼容mirai-console2.0及以上版本。
   - mirai-console需要java环境，建议使用java11以及以上的版本运行。
2. 插件下载
   - 前往本项目的[releases](https://github.com/meaningtree/mirai-setu/releases)下载插件
3. 插件运行
   - 将本放入mirai-console的plugins的文件夹然后运行mirai-console。
4. 关于lollicon的注意事项
   -
   lolicon是一个公开的setu库的APi，此API不属于本人，如果此API出现问题，恕我无力解决。图片获取是从i.pixiv.cat反向代理得到的，可以不使用科学上网获取，但是国内网络获取比较慢，获取卡顿和失败是正常情况。如果有条件的话可以使用科学上网进行加速，或者部署到没有限制的服务器上。
   - lolicon的APIKEy申请需要到Telegram上申请，需要使用科学上网，请自备工具。

## 注意事项

1.插件更新版本之后配置文件不会出现新的配置信息，请删除配置文件让插件重新生成即可。

2.已知在使用缩略图（默认方法）发送图片的时候，图片在pc端无法显示，而且手机端无法直接转发图片，修改为发送原图可以解决此问题。

3.图片发送模式群主和管理员以及bot管理员（在配置文件中可以增加）都可以使用指令修改。

## 指令

指令可以参考指令配置文件，指令可以在配置文件进行修改

## 配置文件

配置文件可以配置代理一些配置，参考注释配置

