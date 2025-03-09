# 【亲测】Turkey Global全开源9语言交易所源码/币币交易+合约交易+秒合约交易+C2C交易+新币认购+理财/前端uniapp纯源码+后端php

本套程序已经过悟空源码技术人员测试，如需搭建请直接联系客服：[@wukongymw](http://t.me/wukongymw)
**解压密码：wukongymw.com**

源码说明

Turkey Global全开源9语言交易所源码/币币交易+合约交易+秒合约交易+C2C交易+新币认购+理财/前端uniapp纯源码+后端php

测试反馈

测试环境：Linux系统CentOS7.6、宝塔面板、Nginx、PHP7.3、MySQL5.7，运行目录public，伪静态thinkphp，开启SSL
语言：9种，看图
这一套是和别人换的，看了他运行记录时间都是有k线行情的，但是我这边搭建出来没有k线，websocket有问题，启动之后有行情数据，不会实时跳动，需要的可以拿去修复，修好了卖个几千U都不是问题
前后端全开源，前端uniapp纯源码，后端是fastadmin框架，计划任务也是用宝塔的监控插件，很方便
手机端没有k线，pc端有实时k线，但是pc里面k线的行情图有报错，不排除文件丢失的情况
程序自带了在线客服的插件，我启动了workerman也没用，没时间继续研究了
带有C2C交易功能，其他网站都是卖2000U的，现在就免费给你们研究了吧，如果修复后能发一份给我的话就更好了
数据库修改：application/database.php 里面将 wukong\_jys2 改成你自己的，或者你自己设置账号密码都为 wukong\_jys2 即可
前端修改：里面批量搜索 jys2.wkym.cc 替换为自己的后端api域名
其他修改事项：
1、application/config.php 修改前端后端域名
2、addons/btpanel/config.php 修改宝塔api密钥跟地址
3、application/api/controller/Cron.php 修改网址和网站目录
4、数据库里面有图片域名可能也得改一下，还有后端尽量批量搜索换成自己的域名
5、根目录有2个文件存放ssl证书的，把里面内容换成自己域名的ssl证书
6、后台在插件管理里面打开Linux监控的插件，在宝塔打开api功能修改key填写服务器的ip:端口
首次搭建成功后一定要先访问一次：https://jys2.wkym.cc/api/cron/run
jys2.wkym.cc是你后端的域名
前端：https://jys2.wkym.cc
测试账号：wukongymw
密码：123456
后台：https://jys2.wkym.cc/wukongymw.php
账号：admin
密码：wukongymw.com

截图展示

前端H5

[![](https://wukongymw.com/wp-content/uploads/2025/03/ec99809fb3c70b5.png)](https://wukongymw.com/wp-content/uploads/2025/03/ec99809fb3c70b5.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/4dfd823167f238a.png)](https://wukongymw.com/wp-content/uploads/2025/03/4dfd823167f238a.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/807a324c0dbb033.png)](https://wukongymw.com/wp-content/uploads/2025/03/807a324c0dbb033.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/fc7826f879bdafc.png)](https://wukongymw.com/wp-content/uploads/2025/03/fc7826f879bdafc.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/862055bd8cf62f3.png)](https://wukongymw.com/wp-content/uploads/2025/03/862055bd8cf62f3.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/c45c60da217dc61.png)](https://wukongymw.com/wp-content/uploads/2025/03/c45c60da217dc61.png)

前端PC

[![](https://wukongymw.com/wp-content/uploads/2025/03/cdc0e460e041e93.png)](https://wukongymw.com/wp-content/uploads/2025/03/cdc0e460e041e93.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/e8bf916076032cf.png)](https://wukongymw.com/wp-content/uploads/2025/03/e8bf916076032cf.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/716a351f8279825.png)](https://wukongymw.com/wp-content/uploads/2025/03/716a351f8279825.png)

后台

[![](https://wukongymw.com/wp-content/uploads/2025/03/44aedffd30467cc.png)](https://wukongymw.com/wp-content/uploads/2025/03/44aedffd30467cc.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/a349f98335f1643.png)](https://wukongymw.com/wp-content/uploads/2025/03/a349f98335f1643.png)
[![](https://wukongymw.com/wp-content/uploads/2025/03/44d5b9e99b2c06c.png)](https://wukongymw.com/wp-content/uploads/2025/03/44d5b9e99b2c06c.png)