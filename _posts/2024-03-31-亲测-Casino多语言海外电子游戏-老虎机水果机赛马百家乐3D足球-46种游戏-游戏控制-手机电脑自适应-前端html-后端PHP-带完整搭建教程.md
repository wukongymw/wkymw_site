# 【亲测】Casino多语言海外电子游戏/老虎机水果机赛马百家乐3D足球/46种游戏+游戏控制+手机电脑自适应/前端html+后端PHP/带完整搭建教程

本套程序已经过悟空源码技术人员测试，如需搭建请直接联系客服：[@wukongymw](http://t.me/wukongymw)
**解压密码：timibbs.net**

源码说明

Casino多语言海外电子游戏/老虎机水果机赛马百家乐3D足球/46种游戏+游戏控制+手机电脑自适应/前端html+后端PHP/带完整搭建教程

测试反馈

测试环境：Linux系统CentOS7.6、宝塔、PHP5.6、MySQL5.6，根目录选择 /app/webroot ，伪静态看下面，开启ssl证书
语言：10种，自己看图
PHP需要安装redis扩展，安装之后重启PHP使其生效
测试时发现的问题：
1.前端live这里会报错，可能是没有内容
2.有个别游戏进不去，这个不影响，删掉这个游戏就行
3.后台登陆的时候，直接登陆不行会报500，需要先登陆前端，然后直接输入后台网址就ojbk
数据库修改：/app/Config/database.php ， 将 timibbs\_casino 改为自己的
根目录选择 /app/webroot ，记得是webroot这个目录
伪静态：
if (!-e $request\_filename){
rewrite ^(.\*)$ /index.php?s=$1 last; break;
}
原来的数据库有1个G，清除了没有用的日志和记录，代码也优化了一下
游戏种类不是很多，前端都是canvas画布，后端是PHP，全开源的，可以做成接口模式
后门有几个，已经清理掉了，拿去运营的话还是建议从头到尾优化一遍，看样子是全部都能控制的，可以看最后一张截图
文件夹里面有自带的pdf说明，全英文，用处不是太大，计划任务的话参考这个：install and configure.pdf
前端：https://casino.wukongymw.com/
测试账号：timibbs
密码：admin1
后台：https://casino.wukongymw.com/amdin
账号：timibbs
密码：admin1
登陆后台时记得看我刚才说的问题3

截图展示

[![](https://wukongymw.com/wp-content/uploads/2024/04/70173dd75f059ed.png)](https://wukongymw.com/wp-content/uploads/2024/04/70173dd75f059ed.png)

[![](https://wukongymw.com/wp-content/uploads/2024/04/eccf3e5376f235a.png)](https://wukongymw.com/wp-content/uploads/2024/04/eccf3e5376f235a.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/806d8819e107156.png)](https://wukongymw.com/wp-content/uploads/2024/04/806d8819e107156.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/19bf0a64e22809f.png)](https://wukongymw.com/wp-content/uploads/2024/04/19bf0a64e22809f.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/26562c3dd3d6d69.png)](https://wukongymw.com/wp-content/uploads/2024/04/26562c3dd3d6d69.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/d8e1f706447b238.png)](https://wukongymw.com/wp-content/uploads/2024/04/d8e1f706447b238.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/e52a593379121d4.png)](https://wukongymw.com/wp-content/uploads/2024/04/e52a593379121d4.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/4949362ae668781.png)](https://wukongymw.com/wp-content/uploads/2024/04/4949362ae668781.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/818612d36ef5fc4.png)](https://wukongymw.com/wp-content/uploads/2024/04/818612d36ef5fc4.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/3221288dd193916.png)](https://wukongymw.com/wp-content/uploads/2024/04/3221288dd193916.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/9a95eec9ebd2ac2.png)](https://wukongymw.com/wp-content/uploads/2024/04/9a95eec9ebd2ac2.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/2805bf88bbd9f1a.png)](https://wukongymw.com/wp-content/uploads/2024/04/2805bf88bbd9f1a.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/d8b985d1a34eaf9.png)](https://wukongymw.com/wp-content/uploads/2024/04/d8b985d1a34eaf9.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/d31251cb6265ad1.png)](https://wukongymw.com/wp-content/uploads/2024/04/d31251cb6265ad1.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/d2cac9a66008587.png)](https://wukongymw.com/wp-content/uploads/2024/04/d2cac9a66008587.png)
[![](https://wukongymw.com/wp-content/uploads/2024/04/27c4957780e8e67.png)](https://wukongymw.com/wp-content/uploads/2024/04/27c4957780e8e67.png)