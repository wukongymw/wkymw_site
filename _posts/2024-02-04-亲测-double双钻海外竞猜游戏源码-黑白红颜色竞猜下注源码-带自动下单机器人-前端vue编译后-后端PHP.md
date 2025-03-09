# 【亲测】double双钻海外竞猜游戏源码/黑白红颜色竞猜下注源码/带自动下单机器人/前端vue编译后+后端PHP

本套程序已经过悟空源码技术人员测试，如需搭建请直接联系客服：[@wukongymw](http://t.me/wukongymw)
**解压密码：timibbs.net**

源码说明

double双钻海外竞猜游戏源码/黑白红颜色竞猜下注源码/带自动下单机器人/前端vue编译后+后端PHP

测试反馈

测试环境：Linux系统CentOS7.6、宝塔、PHP7.3、MySQL5.6，根目录public，伪静态参考下面，开启ssl证书
语言：葡萄牙语
单语言，前端vue编译后的，只是提供研究，不建议直接运营
我也没玩懂这个玩意，所以只是看了一下功能，没有进行游戏（搞不懂）
数据库修改：根目录下面 .env 第23、24、25行
后端域名修改：根目录下面 .env 第5行
前端域名修改：/public/static/js 下面的 index.32b86ddf.js ，打开搜索 double.timibbs.vip 替换为自己的后端域名
前端修改：修改默认文档 index.html 为第一个， index.php 改成第二个 ，或者前端直接访问 后台域名/index.html
伪静态设置
location / {
try\_files $uri $uri/ /index.php?$query\_string;
}
location ~\* ^/ws {
access\_log off;
proxy\_pass http://localhost:2350;
proxy\_set\_header X-Real-IP $remote\_addr;
proxy\_set\_header Host $host;
proxy\_set\_header X-Forwarded-For $proxy\_add\_x\_forwarded\_for;
# WebSocket support (nginx 1.4)
proxy\_http\_version 1.1;
proxy\_set\_header Upgrade $http\_upgrade;
proxy\_set\_header Connection "upgrade";
}
计划任务：
开始游戏
php artisan game:start
未处理订单自动拒绝
php artisan withdrawBack
Workerman
php artisan workman start --d
前端测试账号：timibbs.net@gmail.com
密码：123456
后台：/timibbs
账号：timibbs
密码：timibbs.net

截图展示

[![](https://wukongymw.com/wp-content/uploads/2024/02/aa5d53a38a52f91.png)](https://wukongymw.com/wp-content/uploads/2024/02/aa5d53a38a52f91.png)[![](https://wukongymw.com/wp-content/uploads/2024/02/f32ec48bfff32dd.png)](https://wukongymw.com/wp-content/uploads/2024/02/f32ec48bfff32dd.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/d9a676d0a549d80.png)](https://wukongymw.com/wp-content/uploads/2024/02/d9a676d0a549d80.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/c1f0e0288e8b9af.png)](https://wukongymw.com/wp-content/uploads/2024/02/c1f0e0288e8b9af.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/52b2dfb4ba75505.png)](https://wukongymw.com/wp-content/uploads/2024/02/52b2dfb4ba75505.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/8a3c5b3e0b52cf1.png)](https://wukongymw.com/wp-content/uploads/2024/02/8a3c5b3e0b52cf1.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/dd898c5eba104ed.png)](https://wukongymw.com/wp-content/uploads/2024/02/dd898c5eba104ed.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/f53581b23d2017d.png)](https://wukongymw.com/wp-content/uploads/2024/02/f53581b23d2017d.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/498aaf1519304cd.png)](https://wukongymw.com/wp-content/uploads/2024/02/498aaf1519304cd.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/93d508247701e44.png)](https://wukongymw.com/wp-content/uploads/2024/02/93d508247701e44.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/812c8892902c418.png)](https://wukongymw.com/wp-content/uploads/2024/02/812c8892902c418.png)
[![](https://wukongymw.com/wp-content/uploads/2024/02/c4896bdf28ef1a0.png)](https://wukongymw.com/wp-content/uploads/2024/02/c4896bdf28ef1a0.png)