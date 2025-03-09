# 【亲测】KUBI多语言交易所源码/合约交易+秒合约交易+币币交易+质押生息+币币交易机器人+平台币k线走势控制/前端vue编译后+后端PHP

本套程序已经过悟空源码技术人员测试，如需搭建请直接联系客服：[@wukongymw](http://t.me/wukongymw)
**解压密码：timibbs.net**

源码说明

KUBI多语言交易所源码/合约交易+秒合约交易+币币交易+质押生息+币币交易机器人+平台币k线走势控制/前端vue编译后+后端PHP

测试反馈

测试环境：Linux系统CentOS7.6、宝塔面板、Nginx、PHP7.2、MySQL5.6，根目录public，伪静态laravel5，开启ssl证书
语言：看图
wap+pc的前端，很遗憾都是编译后的，要是有源码的话就有价值了，后端laravel5框架
亲测k线结算功能正常，合约交易都是完整的，基本上所有功能都测试了一遍，暂时没有遇到问题
有质押生息功能、还可以发行平台币，控制平台币k线走势，币币交易也有机器人
整个目录全局搜索 jys110.timibbs.vip 替换为自己的域名，数据库里面也要替换域名
数据库修改：.env 里面的 timibbs\_jys110
跨域：/proxy/proxy.js 将 jys110.timibbs.vip 替换为自己的域名，也可以不用管，这是跨域才用得到的
安装php扩展 fileinfo opcache redis imagemagick imap intl xsl Swoole4并且禁用所有函数
部署好之后先清除程序缓存
cd /www/wwwroot/jys110.timibbs.vip
php artisan config:cache
jys110.timibbs.vip是你自己的程序目录
nginx站点配置反向代理：
location ~/(wss|socket.io) {
# 此处改为 socket.io 后端的 ip 和端⼝即可
proxy\_pass http://127.0.0.1:2000;
proxy\_set\_header Upgrade $http\_upgrade;
proxy\_set\_header Connection "upgrade";
proxy\_http\_version 1.1;
proxy\_set\_header X-Forwarded-For $proxy\_add\_x\_forwarded\_for;
proxy\_set\_header Host $host;
}
宝塔要放行所有端口哦！
环境部署教程和计划任务在压缩包里面，就不写出来了
前端wap：https://jys110.timibbs.vip/mobile
前端pc：https://jys110.timibbs.vip/app
测试账号：timibbs
密码：123456
后台：https://jys110.timibbs.vip/timibbs
账号：timibbs
密码：timibbs.net

截图展示

[![](https://wukongymw.com/wp-content/uploads/2024/05/f9e3499c2b92f40.png)](https://wukongymw.com/wp-content/uploads/2024/05/f9e3499c2b92f40.png)[![](https://wukongymw.com/wp-content/uploads/2024/05/d2c495cfa97cfe7.png)](https://wukongymw.com/wp-content/uploads/2024/05/d2c495cfa97cfe7.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/0ebb8e8917ee5d8.png)](https://wukongymw.com/wp-content/uploads/2024/05/0ebb8e8917ee5d8.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/3b93d9a5171cfa2.png)](https://wukongymw.com/wp-content/uploads/2024/05/3b93d9a5171cfa2.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/c19f14ebb544f4f.png)](https://wukongymw.com/wp-content/uploads/2024/05/c19f14ebb544f4f.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/c2fddc44c57637b.png)](https://wukongymw.com/wp-content/uploads/2024/05/c2fddc44c57637b.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/912d9f1ba0b7096.png)](https://wukongymw.com/wp-content/uploads/2024/05/912d9f1ba0b7096.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/8b6d06ee055c51c.png)](https://wukongymw.com/wp-content/uploads/2024/05/8b6d06ee055c51c.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/68e92f8fc891d34.png)](https://wukongymw.com/wp-content/uploads/2024/05/68e92f8fc891d34.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/bdf92dc52d1396d.png)](https://wukongymw.com/wp-content/uploads/2024/05/bdf92dc52d1396d.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/f19fb6c1fe40319.png)](https://wukongymw.com/wp-content/uploads/2024/05/f19fb6c1fe40319.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/507e4ef24b93f03.png)](https://wukongymw.com/wp-content/uploads/2024/05/507e4ef24b93f03.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/4a2d10dc9f334c6.png)](https://wukongymw.com/wp-content/uploads/2024/05/4a2d10dc9f334c6.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/98dbd240a290ab7.png)](https://wukongymw.com/wp-content/uploads/2024/05/98dbd240a290ab7.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/1da9b6d63ee612c.png)](https://wukongymw.com/wp-content/uploads/2024/05/1da9b6d63ee612c.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/c0f9b529baea5b1.png)](https://wukongymw.com/wp-content/uploads/2024/05/c0f9b529baea5b1.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/cf3eb1508e6e87d.png)](https://wukongymw.com/wp-content/uploads/2024/05/cf3eb1508e6e87d.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/1eb152d783c2f92.png)](https://wukongymw.com/wp-content/uploads/2024/05/1eb152d783c2f92.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/d7835580b75ff98.png)](https://wukongymw.com/wp-content/uploads/2024/05/d7835580b75ff98.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/5f6a3d677412a9d.png)](https://wukongymw.com/wp-content/uploads/2024/05/5f6a3d677412a9d.png)
[![](https://wukongymw.com/wp-content/uploads/2024/05/d398ba199c93a75.png)](https://wukongymw.com/wp-content/uploads/2024/05/d398ba199c93a75.png)